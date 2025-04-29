
# 🏏 IPL Win Predictor

This is a Machine Learning-powered **IPL Win Predictor** that forecasts the chances of winning for both teams during a live T20 match, based on current match stats such as score, overs, wickets, and more.

## 📌 Project Description

The app uses historical IPL data and a trained machine learning pipeline to predict the winning probabilities of the two competing teams, given the following inputs:

- **Batting Team** (e.g., Chennai Super Kings)
- **Bowling Team** (e.g., Gujarat Titans)
- **City** (e.g., Bangalore)
- **Target Runs** (e.g., 200)
- **Current Score** (e.g., 120)
- **Overs Completed** (e.g., 10)
- **Wickets Out** (e.g., 3)

Using this data, the app calculates:
- Runs Left
- Balls Left
- Remaining Wickets
- Current Run Rate
- Required Run Rate

Then, it predicts the win probability of each team.

## 🧪 Example Output

**Input:**
- Batting Team: *Chennai Super Kings*
- Bowling Team: *Gujarat Titans*
- City: *Bangalore*
- Target: *200*
- Current Score: *120*
- Overs Completed: *10*
- Wickets Out: *3*

**Derived Metrics:**
- Runs Left: 80  
- Balls Left: 60  
- Remaining Wickets: 7  
- Current Run Rate: 12.0  
- Required Run Rate: 8.0  

**Predicted Result:**
- ✅ Chennai Super Kings: **86%**
- ❌ Gujarat Titans: **14%**

---

## 🚀 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit (for frontend deployment)
- Pickle (for saving ML model)

---

## 📁 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Luqman-Ahmaad/ipl-analysis
   cd ipl-analysis

🔗 Live Demo

Try the app here: [IPL Win Predictor Live Demo](https://ipl-match-win-prediction.streamlit.app/)
