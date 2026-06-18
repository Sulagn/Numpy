# 📊 Student Performance Analyzer using NumPy

A beginner-friendly NumPy project that demonstrates the three most important concepts in numerical computing:

✅ Arrays  
✅ Broadcasting  
✅ Dot Product

Using a simple student grading system, this project calculates weighted scores, rankings, grades, and class statistics.

---

## 🚀 What You'll Learn

### 1. NumPy Arrays

Store student marks in a structured matrix.

```python
marks = np.array([
    [85, 78, 92],
    [70, 88, 80],
    [90, 95, 85],
    [60, 72, 75],
    [88, 84, 91]
])
```

---

### 2. Broadcasting

Add bonus marks to every student without using loops.

```python
bonus = np.array([5, 3, 2])

updated_marks = marks + bonus
```

#### Before

| Student | Math | Physics | CS |
|----------|------|----------|----|
| 1 | 85 | 78 | 92 |
| 2 | 70 | 88 | 80 |

#### Bonus

| Math | Physics | CS |
|--------|--------|----|
| +5 | +3 | +2 |

#### After Broadcasting

| Student | Math | Physics | CS |
|----------|------|----------|----|
| 1 | 90 | 81 | 94 |
| 2 | 75 | 91 | 82 |

---

### 3. Dot Product

Calculate weighted scores.

```python
weights = np.array([0.4, 0.3, 0.3])

final_scores = np.dot(updated_marks, weights)
```

#### Example

```text
[90, 81, 94]
·
[0.4, 0.3, 0.3]

=
90×0.4 + 81×0.3 + 94×0.3

=
88.5
```

---

## 📂 Project Structure

```text
student-performance-analyzer/
│
├── student_analyzer.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/student-performance-analyzer.git
```

Move into the project folder:

```bash
cd student-performance-analyzer
```

Install NumPy:

```bash
pip install numpy
```

---

## ▶️ Run the Project

```bash
python student_analyzer.py
```

---

## 📈 Features

- Student marks storage using NumPy arrays
- Bonus marks using broadcasting
- Weighted score calculation using dot products
- Student ranking system
- Grade assignment
- Subject-wise averages
- Class statistics
- Topper detection

---

## 🧠 NumPy Concepts Used

| Concept | Implementation |
|----------|----------|
| Arrays | `np.array()` |
| Broadcasting | `marks + bonus` |
| Dot Product | `np.dot()` |
| Mean | `np.mean()` |
| Sum | `np.sum()` |
| Maximum | `np.max()` |
| Standard Deviation | `np.std()` |
| Ranking | `np.argsort()` |
| Topper Detection | `np.argmax()` |

---

## 🎯 Sample Output

```text
Subject-wise Average:
Math Average      : 83.60
Physics Average   : 86.40
CS Average        : 86.60

Topper Information
------------------
Student Number: 3
Score: 93.50

Class Ranking
-------------
Rank 1: Student 3 (Score = 93.50)
Rank 2: Student 5 (Score = 91.20)
Rank 3: Student 1 (Score = 88.50)
Rank 4: Student 2 (Score = 81.90)
Rank 5: Student 4 (Score = 71.60)
```

---

## 🎓 Learning Outcomes

After completing this project, you'll understand:

- How NumPy stores data in multidimensional arrays
- How broadcasting removes the need for loops
- How dot products are used for weighted calculations
- How to perform statistical analysis using NumPy
- How ranking systems work using `argsort()` and `argmax()`

---

## 🔥 Challenge Extensions

Try adding:

- Student names instead of IDs
- More subjects
- CSV file input
- Data visualization using Matplotlib
- Grade distribution charts
- Pass/Fail prediction
- GPA Calculator

---

## 💡 Why This Project?

This project is intentionally small but covers the core operations used in:

- Data Science
- Machine Learning
- Deep Learning
- Scientific Computing
- Financial Analytics

If you understand every line of this project, you'll have a solid foundation in NumPy's most important features.

---

### ⭐ If you found this project helpful, consider giving the repository a star!
