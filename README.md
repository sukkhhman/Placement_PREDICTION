# Campus Placements Prediction Web App

## Introduction
The **Campus Placements Prediction Web App** is a tool designed to predict the likelihood of a student getting placed during campus placements. It analyzes various factors such as academic performance, work experience, and specialization to generate predictions. The app is trained on a dataset and can be easily modified to suit recruiters' needs.

## Features
- **Prediction:** Predicts the probability of a student getting placed during campus placements.
- **User-Friendly Interface:** An intuitive and easy-to-use interface built with Streamlit.
- **Data Visualization:** Provides insights and visual representations of the dataset used for predictions.
- **Customizable Model:** The underlying machine learning model can be fine-tuned based on available data.
- **Scalability:** Can be extended to handle a large number of users and data points.

## Description of Dataset
The dataset used for prediction contains the following features:

| Feature | Description |
|---------|-------------|
| `sl_no` | Unique anonymous ID for a student |
| `gender` | Gender of the student (Male/Female) |
| `ssc_p` | Percentage of marks in Secondary School Certificate (10th grade) |
| `ssc_b` | SSC Board (Binary: Central/Others) |
| `hsc_p` | Percentage of marks in Higher Secondary Certificate (12th grade) |
| `hsc_b` | HSC Board (Binary: Central/Others) |
| `hsc_s` | Stream in 12th grade (Science, Commerce, Arts) |
| `degree_p` | Percentage of marks secured in the undergraduate degree |
| `degree_t` | Type of undergraduate degree (Sci&Tech, Comm&Mgmt, Others) |
| `workex` | Prior work experience (Yes/No) |
| `etest_p` | Percentage of marks in the placement exam |
| `specialisation` | MBA Specialization (Mkt&HR, Mkt&Fin) |
| `mba_p` | Percentage of marks in MBA |
| `status` | Placement status (Placed/Not Placed) - **Target Variable** |
| `salary` | Annual salary package offered to placed students |

## How to Use the Web App
1. Open the **Streamlit** web app (link provided below).
2. Upload a CSV file containing student details **or** manually enter details in the sidebar.
3. Click the **Predict** button to get placement probability.
4. View the prediction results and any additional insights provided by the app.

## Installation & Running Locally
To run the app locally, follow these steps:

### **Prerequisites**
- Python 3.x installed
- Virtual environment (optional but recommended)

### **Steps to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/placement-prediction.git
   cd placement-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run placement_prediction/app.py
   ```
4. Open the provided **localhost** link in your browser.

## Data Source
The dataset used for training the model is available on [Kaggle Campus Placement Dataset](https://www.kaggle.com/competitions/ml-with-python-course-project/data).

## App Link
[Campus Placements Prediction App](#) *(Replace # with the actual deployed app link)*

## Note
- This project is intended for **educational and demonstration purposes only**.
- Predictions generated may not reflect actual placement trends or market conditions.
- Model performance can be improved with additional data and fine-tuning.

---
**Contributors:** Your Name *(Replace with actual names if multiple contributors)*

Feel free to contribute to this project by submitting a pull request!

---

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

