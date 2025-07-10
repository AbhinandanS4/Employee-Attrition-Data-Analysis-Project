# Employee-Attrition-Data-Analysis-Project

This repository contains a complete end-to-end analysis of employee attrition using data analysis and visualization techniques in both **Python** and **Power BI**. The project explores patterns in employee data, tests hypotheses, and provides visually intuitive dashboards for decision-making.

---

## 📂 Project Structure

| File Name | Description |
|-----------|-------------|
| `Attrition_rate.ipynb` | Jupyter notebook performing data cleaning, feature engineering, exploratory data analysis (EDA), and hypothesis testing using `scipy` (independent sample t-tests). |
| `Cleaned_Employee_Data.xlsx` | Processed dataset used for Power BI dashboard creation. |
| `employee_attrition_dashboard.pbix` | Power BI file containing both simplistic and modern dashboard views for employee attrition insights. |
| `employee_attrition_dashboard.jpg` | Preview of the Power BI dashboards. |
| `employee_attrition_dashboard.pdf.jpg` | Alternate visual preview (PDF exported and converted to image). |
| `README.md` | Project overview and documentation (this file). |

---

## 📊 Dashboards

Two Power BI dashboards were designed:
- **Simplistic Dashboard**: Offers clear, beginner-friendly insights.
- **Modern Dashboard**: Uses advanced visuals and layout for professional-grade storytelling.

They display:
- Attrition by department, age, gender, and job role
- Key KPIs such as attrition rate and average tenure
- Visual trends in performance, education, and job satisfaction

---

## 🧠 Analysis & Hypothesis Testing

The Python notebook includes:
- **Data Cleaning & Feature Engineering**: Handling missing values, encoding, and creating derived features.
- **Boxplots & Histograms**: For visualizing distributions and spotting outliers or trends.
- **Hypothesis Testing**: Independent sample t-tests (using `scipy`) to explore differences in variables such as:
  - Job satisfaction vs attrition
  - Distance from home vs attrition
  - Monthly income vs attrition

---

## 🛠️ Tools & Libraries

- `Pandas`, `NumPy` – Data preprocessing
- `Matplotlib`, `Seaborn` – Visualization
- `scipy.stats` – Hypothesis testing
- **Power BI** – Dashboard creation and storytelling

---

## 📌 Conclusion

This project provides both technical and visual insights into the causes of employee attrition. It combines statistical testing with intuitive dashboarding to empower HR teams and decision-makers with actionable insights.

---

## 📸 Preview

![Dashboard Preview](employee_attrition_dashboard.pdf.jpg)

---

## 🔗 Dataset

The dataset used is included in the repository as `Cleaned_Employee_Data.xlsx`. If you're interested in the raw data source, please reach out.

---

## 📥 Getting Started

To run the notebook:
1. Clone the repository
2. Install required libraries with `pip install -r requirements.txt` (create one if needed)
3. Open `Attrition_rate.ipynb` in Jupyter or VS Code

To view the dashboards:
- Open the `.pbix` file using Power BI Desktop

---

## 🤝 Contributing

Suggestions, feedback, and improvements are welcome. Feel free to open issues or submit pull requests.

---

## 📃 License

This project is for educational purposes only and does not include sensitive or proprietary data.
