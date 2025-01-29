# 🎮 Steam Game Data Visualization

## 📊 Overview
This Tableau dashboard analyzes Steam game data to uncover **pricing trends, playtime insights, and publisher influence on ratings**.  
The dataset includes thousands of games with details on **price, average playtime, game type (multiplayer/single-player), and publisher**.

🔗 **[Tableau Public Link]** (Add link if you upload it there)

---

## 🔍 Key Insights & Findings

### 🎯 **1. Do More Expensive Games Get Played More?**
- The **scatter plot (Price vs. Playtime)** shows that **price has minimal impact on playtime**.
- Most high-playtime games **cost under $30**, proving that **cheaper games often provide just as much (or more) playtime**.
- Some **outliers** exist where high-cost games have very little playtime, suggesting **poor value for money**.

### 🎮 **2. Multiplayer vs. Single-Player Games – Which Are Played More?**
- The **pie chart** shows that **single-player games dominate** Steam’s library (~83% of games).
- However, **multiplayer games have significantly higher average playtime** due to replayability.
- Single-player games tend to have a **shorter playtime lifecycle**, whereas multiplayer games keep players engaged for longer.

### 🏷 **3. Price Distribution on Steam**
- Most games are **priced between $0 and $20**, with a **huge spike in free-to-play games**.
- The **pricing histogram** confirms that premium-priced games ($40+) are rare.

### 🏢 **4. How Do Publishers Influence Ratings?**
- A **bubble chart** highlights **top publishers** like **Valve, Bethesda, and Facepunch Studios**.
- Some publishers have **higher negative ratings**, possibly due to bad launches or microtransaction-heavy games.

---

## 📂 Files in This Repository
- **`steam-games-dashboard.twbx`** → Tableau Packaged Workbook (Open in Tableau)
- **`README.md`** → This file (Project Overview)
- **`data.csv`** (Optional) → Raw dataset used for analysis  

---

## 🚀 How to Use This Project
1. **Download the `steam-games-dashboard.twbx` file**.
2. Open it in **Tableau (Desktop or Public Edition)**.
3. Interact with the visualizations to explore trends in Steam game data.

---

## 🎯 Future Improvements and Projects
- Add **more filters** (e.g., by genre or release year).
- Connect to **live Steam API data** for real-time updates.
