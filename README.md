# 📊 Student Performance Analysis Using Exploratory Data Analysis

## 📌 Overview
This project applies **Exploratory Data Analysis (EDA)** to the [Student Performance Dataset](https://www.kaggle.com/datasets/devansodariya/student-performance-data).  
The central focus is to investigate how **study time** and **attendance (absences)** relate to students’ final performance (`G3`).  
The analysis is implemented in a **Jupyter Notebook** using Python’s data science ecosystem, with emphasis on **NumPy demonstrations, Pandas exploration, and meaningful visualisations**.

---

## 🎯 Analytical Question
**How do study time and attendance relate to students' final performance?**

---

## 🎯 Objectives
- Understand the dataset’s structure and data quality.  
- Explore relationships between study-related variables (`studytime`, `absences`) and final grades (`G3`).  
- Demonstrate NumPy array operations, broadcasting, aggregation, and indexing.  
- Communicate findings through clear visualisations and concise explanations.  
- Provide reproducible analysis in a well-documented Jupyter Notebook.

---

## 🛠️ Tools & Libraries
- **[NumPy](ca://s?q=Role_of_NumPy_in_EDA)** – Efficient numerical computation, vectorization, broadcasting.  
- **[Pandas](ca://s?q=Role_of_Pandas_in_EDA)** – Data loading, cleaning, tabular exploration.  
- **[Matplotlib](ca://s?q=Role_of_Matplotlib_in_EDA)** – Foundational plotting library.  
- **[Seaborn](ca://s?q=Role_of_Seaborn_in_EDA)** – High-level statistical visualisations.  
- **[Plotly](ca://s?q=Role_of_Plotly_in_EDA)** – Interactive plots (optional).

---

## 📂 Dataset Details
- **Source:** Kaggle – [Student Performance Dataset](https://www.kaggle.com/datasets/devansodariya/student-performance-data)  
- **Rows:** ~650  
- **Columns:** 33  
- **Key Variables:**  
  - `studytime` – Weekly study time (categorical).  
  - `absences` – Number of school absences.  
  - `G1`, `G2`, `G3` – Grades (first, second, final).  
  - Demographic and family-related attributes (`sex`, `age`, `Medu`, `Fedu`, etc.).

---

## 📑 Notebook Structure
1. **Project Title & Analytical Question**  
2. **Objective**  
3. **Dataset Source & Description**  
4. **Task 1 – Data Understanding**  
5. **Task 2 – Data Exploration**  
6. **Task 3 – NumPy Demonstrations**  
7. **Task 4 – Advanced NumPy for EDA**  
8. **Task 5 – Visualisations**  
   - Numerical variable (`G3` distribution).  
   - Categorical variable (`sex`, `parental education`).  
   - Relationship (`studytime` vs `G3`, `absences` vs `G3`).  
9. **Task 6 – Communication & Findings**  
   - Key patterns.  
   - Answer to analytical question.  
   - Observations vs assumptions.  
   - Limitations.  
   - Follow-up analyses.  
   - Conclusion.

---

## 📊 Key Findings
- **Study time ↑ → Final grades ↑** (positive correlation).  
- **Absences ↑ → Final grades ↓** (negative correlation).  
- Behavioral factors (study habits, attendance) are stronger predictors of performance than demographic attributes.  

---

## ⚠️ Limitations
- Dataset is context-specific and may not generalize globally.  
- Study time is self-reported; absences are raw counts.  
- Other influential factors (teaching quality, motivation, peer influence) are not included.  

---

## 🔮 Future Work
- Explore **interaction effects** between study time and absences.  
- Compare early grades (`G1`, `G2`) with final grade (`G3`).  
- Investigate lifestyle factors (`Dalc`, `Walc`) alongside attendance.  

---

## ✅ Conclusion
The analysis demonstrates that **study time and attendance strongly relate to student performance**.  
Students who study more and attend regularly tend to achieve higher grades.  
While causation cannot be claimed, the evidence highlights the importance of consistent study habits and attendance in academic success.  

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/arushi04khanna/student-performance-eda.git
