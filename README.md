# chess-data-analysis
exploratory data analysis on a chess dataset
# ♟️ Chess Games Data Analysis

A beginner-friendly data analysis project using real chess match data from [Lichess.org](https://lichess.org).  
Analyzed using Python, Pandas, Matplotlib, and Seaborn.

---

## 📂 Dataset

- Source: [Kaggle - Lichess Games](https://www.kaggle.com/datasets/datasnaek/chess)
- Format: CSV
- Total rows: ~20,058 games

---

## 🛠 Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

---

🎯 Objective

To identify key factors that influence the outcome of chess games using data analysis techniques.

---

## 📊 Key Insights

  **Average Turns Per Game:**  
   Most games lasted around 60 moves. The distribution of game lengths peaks around 50–60 turns.

   **Player Ratings Distribution:**  
   Player Elo ratings were centered near **1500**, with nearly identical curves for both white and black players.
 
  **Maximum Ratings:**  
   Highest recorded white rating: ~2700  
   Highest recorded black rating: ~2723  
   No rating bias observed.

  **White Advantage:**
   White wins slightly more games than Black, indicating a measurable first-move advantage.

   **Impact of Rating Difference:**
    Win probability strongly depends on rating difference. Players with higher ratings consistently outperform lower-rated opponents, with even moderate rating gaps significantly increasing winning chances.

   **Opening Analysis:**
    Among the most frequently played openings, win rates vary noticeably, suggesting that opening choice impacts performance. It is noticed that openings like the scandinavian defense , scotch game give a higher win rate for the players

   **Game Length vs Outcome:**
    Shorter games are more likely to result in decisive outcomes, indicating that early mistakes play a major role in determining results.
    
---

## 📈 Visualizations

- Histogram of game lengths  
- KDE plots comparing white vs black player ratings  
- Bar chart comparing maximum ratings
- Win rate comparison (White vs Black)
- Win probability vs rating difference
- Top 10 most played openings with high win rate
- Game length distribution by game outcome 

![Game Length Plot](https://github.com/AnirudhGhatty/chess-data-analysis/blob/main/Screenshot%202025-07-16%20163553.png)
![White vs Black player ratings](https://github.com/AnirudhGhatty/chess-data-analysis/blob/main/Screenshot%202025-07-16%20164427.png)
![Maximum ratings , white vs black](https://github.com/AnirudhGhatty/chess-data-analysis/blob/main/Screenshot%202025-07-16%20164822.png)


---

## 🧠 Skills I Practiced

Data cleaning and preprocessing using Pandas
Exploratory Data Analysis (EDA)
Data visualization and interpretation
Extracting meaningful insights from structured data
Analytical thinking and pattern recognition

