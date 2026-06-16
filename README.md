# IPL Win Probability Predictor

A Machine Learning-powered web application that predicts the winning probability of IPL teams during a live cricket match. By analyzing match conditions such as current score, target, overs remaining, wickets in hand and run rate, the model provides real time win probability estimates for both teams.

<img width="962" height="807" alt="image" src="https://github.com/user-attachments/assets/c71e739a-99ef-4aef-ba63-86515310dc6e" />

## Features

* Predicts win probability during an ongoing IPL match
* Interactive and easy-to-use web interface
* Real-time probability updates based on match inputs
* Trained on historical IPL match data
* Data preprocessing and feature engineering pipeline
* Machine Learning model built using Scikit-learn
* Deployed using Streamlit

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

## How It Works

The model takes match-related inputs such as:

* Batting Team
* Bowling Team
* Host City
* Target Score
* Current Score
* Overs Completed
* Wickets Fallen

Using these inputs, it calculates derived features like:

* Runs Left
* Balls Left
* Wickets Remaining
* Current Run Rate (CRR)
* Required Run Rate (RRR)

The trained Machine Learning model then predicts the winning probability of both teams.

## Project Structure

```text
IPL-Win-Probability-Predictor/
│
├── app.py
├── pipe.pkl
├── teams.pkl
├── dataset/
├── notebooks/
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ipl-win-probability-predictor.git
```

2. Navigate to the project directory:

```bash
cd ipl-win-probability-predictor
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
streamlit run app.py
```


