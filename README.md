# Student Marks Analysis with Pandas

A **Python project using Pandas** to analyze and manipulate student marks data. This project demonstrates **data loading, analysis, grouping, and CSV operations** using Pandas.

---

## 📝 Project Overview

This project performs the following tasks:

1. **Load student marks data** from `Student_Marks.csv`.
2. **Display initial data** to inspect the dataset.
3. **Identify top scores** based on the number of courses.
4. **Calculate average and total marks** for each student.
5. **Save updated data** to `students_updated.csv`.
6. **Group students** into:
   - Group A: Students with 8 or more courses  
   - Group B: Students with less than 8 courses
7. **Save groups to separate CSV files** (`group_a.csv` and `group_b.csv`).
8. **Merge groups back** into a single DataFrame and save as `merged_students.csv`.

---

## 🛠️ Technology Used

- **Python**
- **Pandas**

---

## 📂 Dataset

The project uses `Student_Marks.csv`, which contains columns like:

| Column Name      | Description                           |
|-----------------|---------------------------------------|
| Student          | Name of the student                   |
| number_courses   | Number of courses taken by the student|
| time_study       | Hours of study                         |
| Marks            | Marks obtained in exams                |

After analysis, the dataset includes additional columns:

| Column Name | Description                |
|------------|----------------------------|
| Average    | Average of courses, study, and marks |
| Total      | Sum of courses, study, and marks     |

---
👤 Author
Kavibharathi G
Passionate about Python programming and data analytics.
