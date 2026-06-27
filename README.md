# 📊 Student Performance Analysis using Pandas

A beginner-friendly **Python Data Analysis** project built using **Pandas** and **NumPy**. This project demonstrates essential data wrangling techniques such as data cleaning, feature engineering, grouping, merging datasets, and generating summary reports.

---

## 🚀 Features

- 📂 Load student performance data from a CSV file
- 🔍 Explore dataset structure and statistics
- 🧹 Handle missing values using `fillna()`
- 🗑️ Remove duplicate records
- 📊 Create new features:
  - Total Score
  - Average Score
  - Percentage
  - Grade
  - Pass/Fail Status
- 📈 Analyze student performance
- 👨‍🎓 Find top and bottom performers
- 📑 Perform `groupby()` analysis
- 🔗 Merge student attendance data
- 💾 Export cleaned dataset
- 📝 Generate a summary report

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy

---

## 📁 Project Structure

```
Student-Performance-Analysis/
│
├── StudentsPerformance.csv
├── student_attendance.csv
├── cleaned_students.csv
├── report.txt
├── student_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 📚 Concepts Covered

- DataFrame
- read_csv()
- head()
- tail()
- info()
- describe()
- isnull()
- fillna()
- duplicated()
- drop_duplicates()
- groupby()
- merge()
- Feature Engineering
- Data Analysis
- Exporting Data

---

## 📈 Analysis Performed

- Total number of students
- Male vs Female student count
- Average scores in each subject
- Highest scorer
- Lowest scorer
- Overall percentage
- Grade distribution
- Pass/Fail analysis
- Gender-wise average scores
- Lunch-wise performance
- Test preparation analysis
- Race/Ethnicity-wise performance
- Parent education-wise performance
- Attendance analysis

---

## 📊 Feature Engineering

The following new columns were created:

- Total Score
- Average Score
- Percentage
- Grade
- Result (Pass/Fail)

---

## 📄 Output Files

After running the notebook, the following files are generated:

- `student_attendance.csv`
- `cleaned_students.csv`
- `report.txt`

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Student-Performance-Analysis.git
```

### 2. Move into the project folder

```bash
cd Student-Performance-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open `student_analysis.ipynb` in Jupyter Notebook or VS Code and execute all cells.

---

## 📌 Learning Outcomes

By completing this project, you will learn:

- Data loading using Pandas
- Data cleaning techniques
- Handling missing values
- Feature engineering
- GroupBy operations
- Merging DataFrames
- Data analysis with Pandas
- Generating reports
- Exporting processed data

---

## 📷 Sample Output

- Student Performance Report
- Top 10 Students
- Bottom 10 Students
- Group-wise Performance Analysis
- Attendance Analysis

---

## 📄 License

This project is created for educational purposes and is free to use.

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
