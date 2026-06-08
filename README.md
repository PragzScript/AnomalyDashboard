# Employee Talent Analytics & Workforce Intelligence

A Machine Learning-based HR Analytics project that helps organizations identify high-potential employees, predict promotion readiness, estimate future role fitment, and detect workforce anomalies using employee assessment data.

---

## 📌 Project Overview

This project analyzes employee competency and performance data to generate actionable talent insights for HR and leadership teams.

The notebook performs multiple analytics tasks:

* Employee Talent Segmentation
* Promotion Probability Prediction
* Future Readiness Prediction
* Competency Gap Analysis
* Workforce Anomaly Detection
* Dashboard Data Generation

The final output can be directly connected to visualization tools like **Tableau** or **Power BI** for executive dashboards.

---

## 🚀 Features

### 1. Talent Tier Classification

Employees are grouped into different talent segments using **K-Means Clustering** based on:

* Weighted Average Score
* Success Probability Score
* Future Role Fitment Score
* Competency Ratings

Example tiers:

* High Potential
* Emerging Talent
* Developing Talent

---

### 2. Promotion Probability Prediction

A **Random Forest Classifier** is trained to estimate the likelihood of employee promotion using various competency and performance metrics.

**Output Example:**

| Employee   | Promotion Probability |
| ---------- | --------------------- |
| John Doe   | 87.5%                 |
| Jane Smith | 63.2%                 |

---

### 3. Future Readiness Prediction

A **Linear Regression Model** predicts future readiness scores based on employee competencies.

The model estimates:

* Predicted Future Readiness %
* Readiness Prediction Gap

```
Readiness Gap =
Predicted Future Readiness
−
Current Future Role Fitment
```

This helps identify employees who are likely to grow rapidly.

---

### 4. Competency Gap Analysis

The notebook compares employee competencies against a benchmark score.

Competencies analyzed include:

* Business Acumen
* Communication
* Leading People
* Customer Focus
* Strategic Thinking
* Innovation
* Collaboration

The output highlights employees requiring targeted upskilling.

---

### 5. Workforce Anomaly Detection

An **Isolation Forest Algorithm** identifies unusual employee profiles that differ significantly from the overall workforce distribution.

Possible anomaly categories:

* Exceptionally High Performer
* Skill Mismatch
* Promotion Outlier
* Performance Risk

---

## 🛠 Technologies Used

| Technology   | Purpose                 |
| ------------ | ----------------------- |
| Python       | Core Programming        |
| Pandas       | Data Processing         |
| Scikit-learn | Machine Learning Models |
| Matplotlib   | Data Visualization      |
| OpenPyXL     | Excel File Handling     |
| Google Colab | Development Environment |

---

## 📂 Project Structure

```
ModelAnalysis.ipynb
│
├── Data Loading
├── Data Preprocessing
├── Talent Tier Clustering
├── Promotion Prediction Model
├── Future Readiness Prediction
├── Competency Gap Calculation
├── Anomaly Detection
├── Dashboard Dataset Creation
└── Excel Export
```

---

## 🤖 Machine Learning Models

| Task                        | Algorithm                |
| --------------------------- | ------------------------ |
| Talent Segmentation         | K-Means Clustering       |
| Promotion Prediction        | Random Forest Classifier |
| Future Readiness Prediction | Linear Regression        |
| Anomaly Detection           | Isolation Forest         |

---

## 📊 Generated Output Files

The notebook exports several Excel files:

| File                                 | Description                             |
| ------------------------------------ | --------------------------------------- |
| `talent_tiers_output.xlsx`           | Employee Talent Segmentation            |
| `employee_dashboard_data.xlsx`       | Dashboard-ready employee dataset        |
| `final_dashboard_data.xlsx`          | Enhanced HR analytics output            |
| `final_complete_dashboard_data.xlsx` | Complete workforce intelligence dataset |

---

## 📈 Dashboard Integration

The generated datasets can be used to build HR dashboards containing:

* Talent Distribution
* Promotion Readiness
* Competency Heatmaps
* Future Readiness Trends
* High-Potential Employee Identification
* Workforce Risk Analysis
* Employee Segmentation

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/employee-talent-analytics.git
cd employee-talent-analytics
```

Install dependencies:

```bash
pip install pandas scikit-learn matplotlib openpyxl
```

Run the notebook:

```bash
jupyter notebook ModelAnalysis.ipynb
```

---

## 📥 Input Dataset

The notebook expects an employee assessment dataset containing fields such as:

* Employee Name
* Current Role
* Weighted Average Score
* Success Probability Score
* Future Role Fitment %
* Competency Scores
* Performance Metrics

---

## 🎯 Business Impact

This project enables organizations to:

* Identify high-potential employees.
* Support succession planning.
* Optimize promotion decisions.
* Detect workforce risks early.
* Design personalized learning paths.
* Build data-driven HR strategies.

---

## 🔮 Future Enhancements

* XGBoost-based prediction models
* SHAP explainability for model interpretation
* Automated PDF HR reports
* Real-time dashboard integration
* Employee attrition prediction
* Recommendation engine for learning paths

---

## 👩‍💻 Author

**Pragya Jha**

Machine Learning | Data Science | HR Analytics

---

## 📜 License

This project is intended for educational and portfolio purposes. Feel free to use and modify it for learning and research.
