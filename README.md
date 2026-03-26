# 🎬 Movie Recommender System

## 📌 Project Overview
This project is a simple Movie Recommender System built using Python and Machine Learning concepts.  
It suggests movies similar to the one entered by the user based on content similarity.

---

## 🚀 Features
- Recommend movies based on user input  
- Uses movie metadata like genres, keywords, cast, and crew  
- Simple and interactive command-line interface  
- Fast and efficient recommendations  

---

## 🧠 How It Works
- The system uses **content-based filtering**  
- Movie features are combined into a single "tag"  
- Text data is converted into vectors  
- Cosine similarity is used to find similar movies  

---

## 📂 Dataset
This project uses the TMDB 5000 Movie Dataset.

🔗 Download from Kaggle:  
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata  

Download these files:
- `tmdb_5000_movies.csv`  
- `tmdb_5000_credits.csv`  

Place them in the same folder as `main.py`.

---

## ⚙️ Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/movie-recommender-system.git

```
2. Navigate to project folder:
```bash
cd movie-recommender-system

```
3. Install dependencies:
```bash
pip install pandas numpy scikit-learn
```
4. Run the project:
```bash
python main.py
```
## 🎯 Example Usage

```bash
Enter a movie name: Avatar

Titan A.E.
Small Soldiers
Independence Day
Ender's Game
Aliens vs Predator: Requiem
```
---

## 📚 Technologies Used
-Python
-Pandas
-NumPy
-Scikit-learn

---

## 🙌 Author
**Aanya Yadav**

---

## 🌟 Future Improvements
- Add a web interface (Streamlit)
- Improve recommendation accuracy
- Add posters and ratings

---
