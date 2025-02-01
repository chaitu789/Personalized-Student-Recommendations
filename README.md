# Personalized-Student-Recommendations
This project analyzes quiz performance data to provide insights on strengths, weaknesses, and improvement trends. It fetches quiz data from online sources, processes the data, and generates detailed insights and recommendations.
Features

Fetches quiz data from online APIs

Processes historical quiz performance

Identifies weak and strong areas

Provides personalized recommendations for improvement

Analyzes speed vs. accuracy trends

Generates rule-based feedback for students

Setup Instructions

Prerequisites

Ensure you have the following installed:

Python 3.7+

Required Python libraries:

requests

matplotlib

seaborn

pandas

Install dependencies using:

pip install requests matplotlib seaborn pandas

Running the Analysis

Clone the repository:

git clone <repo-url>
cd <repo-folder>

Run the script:

python analyze_quiz.py

The script will fetch data from endpoints, process performance trends, and generate personalized recommendations.


Approach Description

1. Data Collection

The script fetches JSON data from three external endpoints:

Quiz Endpoint: Contains quiz metadata.

Current Quiz Submission: Holds data from the latest quiz attempt.

Historical Quiz Data: Stores past quiz results for trend analysis.

2. Data Processing & Insights

Performance Tracking: Extracts accuracy, score, duration, and topic-wise trends.

Weak & Strong Areas: Sorts topics by performance, identifying weak and strong subjects.

Trend Analysis: Examines improvement or decline in performance over time.

Time Analysis: Evaluates time spent per question and its impact on accuracy.

3. Personalized Recommendations

Topic-Specific Feedback: Suggests difficulty level changes based on performance.

Speed vs. Accuracy Analysis: Recommends pacing strategies to balance speed and accuracy.

Study Plan Adjustments: Provides targeted improvement strategies based on historical mistakes.

The goal is to help students identify areas for improvement, fine-tune their study approach, and maximize performance in NEET preparation.


Next Steps

Implement a visualization dashboard for performance trends.

Integrate machine learning for predictive performance insights.

Allow users to upload quiz data files for offline analysis.
