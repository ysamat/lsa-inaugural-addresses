# 🗽 Latent Semantic Analysis of U.S. Presidential Inaugural Addresses

This project explores the evolving rhetoric of American presidents through **Latent Semantic Analysis (LSA)** of their inaugural addresses from **1789 to 2005**. All analysis is done in a single Jupyter notebook, from data collection to final visualization.

---

## 📘 Overview

Using Python tools like `BeautifulSoup`, `TfidfVectorizer`, and `NumPy`, this notebook:
- Scrapes and processes inaugural speeches from Project Gutenberg
- Builds a term-document matrix using TF-IDF
- Applies Singular Value Decomposition (SVD) for dimensionality reduction
- Performs Latent Semantic Analysis to uncover hidden rhetorical themes
- Visualizes presidential speeches in 2D semantic space

---

## 🧠 Methods Used

- **TF-IDF Vectorization**
- **Singular Value Decomposition (SVD)**
- **Latent Semantic Analysis (LSA)**
- **2D Visualization using Truncated SVD**
- **Theme interpretation via top word analysis**

---

## 📊 Key Themes Identified

Each theme is a latent dimension learned from the speeches. Here are the top 10:

Theme 1: Formal / Rhetorical Structure  
Theme 2: Foundational Government Principles  
Theme 3: Economic & Industrial Policy  
Theme 4: War, Peace, and Foreign Affairs  
Theme 5: Civil War & Religious Appeals  
Theme 6: Enlightenment & Early Republic  
Theme 7: Democracy, Union, and Slavery  
Theme 8: Revolution & National Identity  
Theme 9: Democratic Foundations (some noise)  
Theme 10: Monetary Rhetoric (some noise)  

---

## 🚀 How to Run

1. Download or clone this repository:
   ```bash
   git clone https://github.com/ysamat/lsa-inaugural-addresses.git
   cd lsa-inaugural-addresses
   ```

2. Open the notebook in Jupyter or Colab:
   - The notebook will fetch all data and run all code autonomously

3. All plots and summaries are generated directly in the notebook.

---

## 📚 Data Source

Speeches from [Project Gutenberg – Inaugural Addresses Collection](https://www.gutenberg.org/files/925/925-h/925-h.htm)

---

## 💡 Future Directions

- Add modern speeches (Obama, Trump, Biden)
- Compare themes by political party or historical era
- Track word/theme usage over time

---

## 🧙 Author

Developed by [@ysamat](https://github.com/ysamat)  
A solo notebook project with full-stack NLP + visualization

---

## 🏛️ License

MIT License — free to reuse and remix with credit.
