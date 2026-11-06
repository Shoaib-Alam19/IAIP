# IAIP - Intern Alpha Internship Projects

Data Analytics Internship (Oct - Nov 2026) | Intern Alpha

## Task 1: IPL Matches Analysis (2008-2024)

### Objective
IPL ke 1095 matches ke data ko clean karke analyze karna aur teams, toss, venues aur players ke bare me insights nikalna.

### Dataset
Kaggle: IPL Complete Dataset (2008-2024), `matches.csv`

### Tools Used
Python, pandas, matplotlib, seaborn, SQLite, Google Colab

### What I Did
1. Data load karke explore kiya (1095 rows, 20 columns)
2. Cleaning: date ko datetime me badla, season labels ke bajaye date se `year` banaya, purani/nayi team names ko standardize kiya (jaise Delhi Daredevils -> Delhi Capitals), missing values handle ki
3. 7 charts banaye (matches per year, team wins, toss impact, toss decision trend, chase vs defend, Player of the Match, venues)
4. SQL queries (SQLite) chalayi: top teams, season-wise toss impact, top venues

### Key Insights
- Mumbai Indians ne sabse zyada matches jeete (___ wins), uske baad Chennai Super Kings aur Kolkata Knight Riders
- Toss jeetne wali team ne sirf **50.8%** matches jeete, matlab toss ka impact bahut kam hai
- Chase karne wali team **54.1%** matches jeeti, pehle batting karne wali **45.9%**
- 2016 ke baad zyadatar teams toss jeetke fielding choose karti hain
- AB de Villiers (25) aur CH Gayle (22) ko sabse zyada Player of the Match awards mile
- 2011-13 aur 2022 ke baad matches zyada hue kyunki teams ki sankhya badhi

### Files
- `IPL_Matches_Analysis.ipynb` - poora analysis notebook
- `matches.csv` - dataset

### Author
Md Shoaib Alam
