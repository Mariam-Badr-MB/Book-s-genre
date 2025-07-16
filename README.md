# 📚 Book Clustering Using NLP (Unsupervised Learning)

This project explores whether books can be grouped into hidden **micro-genres** based on the content of their descriptions.  
Using **unsupervised machine learning** (KMeans clustering), we analyze the similarity between book summaries and group them accordingly.

---

## 💡 Objective

Identify clusters of books with similar themes or topics (micro-genres) without using labeled genre data.

---

## 📊 Techniques Used

- **Natural Language Processing (NLP)** for text cleaning:
  - Lowercasing
  - Removing stopwords
  - Lemmatization
- **TF-IDF Vectorization** to convert text into numerical features
- **KMeans Clustering** to group books into clusters
- **PCA Visualization** to plot and explore the cluster structure
- **Silhouette Score** to evaluate cluster quality

---

## 🧠 Tools & Libraries

- Python
- `pandas`, `matplotlib`, `seaborn`
- `nltk` for text preprocessing
- `scikit-learn` for TF-IDF, clustering, PCA

---

## 📁 Dataset

The dataset contains over 6 million book entries. For this project:
- Only `title` and `summary` columns were used
- The dataset is sourced from [Hugging Face Datasets](https://huggingface.co/datasets/BrightData/Goodreads-Books/viewer/default/train?row=3&views%5B%5D=train).

---

## 📈 Project Workflow

1. **Data Loading**
2. **Text Cleaning** (lowercase, remove stopwords, lemmatize)
3. **Vectorization with TF-IDF**
4. **Clustering with KMeans**
5. **Cluster Evaluation using Silhouette Score**
6. **Visualization using PCA**
7. **Export clustered results to CSV**

---

## 🔍 Example Output

- Clustered books saved in: `clustered_books.csv`
- Each book is assigned to a micro-genre cluster
- Clusters visualized in 2D space using PCA

---

## 💾 Output Sample

| Title                         | genre |
|------------------------------|---------|
| The Secret Garden            | 2       |
| A Brief History of Time      | 0       |
| The Art of War               | 3       |

---


## 👩‍💻 Author

**Mariam Badr**  
Faculty of Computers & Artificial Intelligence, Cairo University
[GitHub](https://github.com/Mariam-Badr-MB) - [LinkedIn](https://www.linkedin.com/in/mariambadr13/)

---

## 📜 License

This project is for educational and learning purposes.
