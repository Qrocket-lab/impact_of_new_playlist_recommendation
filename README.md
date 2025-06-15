# impact_of_new_playlist_recommendation
Findings from a Controlled Experiment on Spotify Data

# 🎧 A/B Testing: Spotify Playlist Recommendation Algorithm

This project evaluates the effectiveness of a new playlist recommendation algorithm introduced by Spotify. Using A/B testing methodology, we analyze user engagement—measured by "Duration Played"—between users who received the new recommendation engine (Target group) and those who did not (Control group).

---

## 📌 Project Objective

To determine whether the new recommendation algorithm increases user engagement time on Spotify.

---

## 🧪 A/B Testing Overview

- **Control Group**: Users with the existing recommendation system
- **Target Group**: Users with the new algorithm
- **Key Metric**: `Duration Played` (in seconds)

We use statistical tests (Shapiro-Wilk, Levene's, Welch’s t-test) to assess:
- Data distribution (normality)
- Variance equality
- Mean differences between the groups

---

## 🗂️ Repository Structure
ab-testing-spotify/
│
├── README.md                
├── requirements.txt         
├── impact_of_new_playlist_recommendation.py      
└── spotify_ab_test.csv      
 

---

## 📊 Key Results

| Group     | Mean Duration Played (sec) |
|-----------|----------------------------|
| Control   | 120.07                     |
| Target    | 159.91                     |

- **P-value** (Welch’s t-test) = 0.000
- **Conclusion**: There is a statistically significant increase in engagement for the Target group.

---

## 📈 Visual Highlights

![Group Count Plot](images/duration_barplot.png)

---

## ⚙️ Tech Stack

- Python
- Pandas
- Seaborn & Matplotlib
- Scipy (for statistical tests)
- Google Colab

---

## 📎 Dataset

[Spotify A/B Test CSV](https://docs.google.com/spreadsheets/d/e/2PACX-1vTQeu7yHoA0tdMZbxzaYcY_F_5oL-4GwFYgo5p2PtycUbYOmD7YFajiFWzXaQxf1w/pub?gid=2014393006&single=true&output=csv)

---

## 🧠 Learnings

- Reinforced A/B testing logic: control vs variant group evaluation
- Gained hands-on experience with statistical hypothesis testing
- Interpreted real-world engagement metrics in a business context

---

## 🧑‍💻 Author

**Qodri Muhamad**  
*Aspiring Business Intelligence Analyst | Economics Graduate*  
[LinkedIn]([#](https://www.linkedin.com/in/qodri-muhamad/)) • [GitHub](https://github.com/Qrocket-lab) • [Portfolio](https://feline-coal-d92.notion.site/Q-s-Portfolio-2025-20e1dc8bddcd80e5bc51f37a0b8539d1?source=copy_link)

---

## 📬 Feedback & Contributions

Feel free to open issues or submit pull requests. Feedback is welcome!
