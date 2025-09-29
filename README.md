# 🎬 IMDB Movies Dataset Analysis

## 📌 Project Overview  
This project provides a **cleaned version of the IMDB movies dataset** along with exploratory data analysis.  
The original dataset contained multiple genres in a single row. We **exploded genres** into individual rows, making it easier to analyze genre-level insights.  

The analysis includes:  
- Cleaning and preprocessing of raw movie data  
- Genre distribution and counts  
- Average ratings and revenues by genre  
- Visualization of **revenue vs. rating** by genre  

---

## 📂 Repository Contents  
- **movies_cleaned.csv** → Final cleaned dataset with exploded genres  
- **IMDB_MOVIE_DATA_ANALYSIS.ipynb** → Jupyter Notebook with full analysis + explanations  
- **analysis_script.py** → Python script version for Kaggle / automation  
- **README.md** → Project documentation (this file)  

---

## 📊 Dataset Highlights  
- **Rows (after explosion):** ~10,000+  
- **Unique genres:** 20  
- **Key columns:** `title`, `genres`, `vote_average`, `revenue`, `budget`, `release_year`  

---

## 🚀 How to Use  
1. Clone this repo:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```  
2. Install dependencies:  
   ```bash
   pip install pandas matplotlib
   ```  
3. Open the notebook:  
   ```bash
   jupyter notebook IMDB_MOVIE_DATA_ANALYSIS.ipynb
   ```  
4. Or run the script:  
   ```bash
   python analysis_script.py
   ```  

---

## 📈 Analysis Preview  
We explored:  
- **Most common genres**  
- **Highest-rated movies**  
- **Average revenue vs. ratings** (visualized with scatter plots)  

---

## 📜 License  
This dataset is provided for **educational and research purposes**.  
You are free to use it for learning, analysis, and building machine learning models.  
