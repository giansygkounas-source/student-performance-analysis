# Student Performance Analysis

Exploratory data analysis of the [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) dataset (1,000 students, 8 columns) using pandas and matplotlib.

## Questions
- Which gender has the better average score?
- Which subject has the best performance?
- Do students who completed test preparation score higher?
- What percentage of students score above 80?
- Which group of students has the lowest performance?

## Key findings
1. **Gender:** Female students have a higher overall average. Male students lead in math, while female students lead in reading and writing.
2. **Subjects:** Reading has the highest average (69.2), followed by writing (68.1) and math (66.1).
3. **Test preparation:** Students who completed the course score higher in all three subjects, with the biggest gap in writing. This shows correlation, not causation.
4. **Scores above 80:** Reading 23.5%, writing 20.8%, math 17.6%, overall average 19.4%.
5. **Lowest-performing groups:** Students whose parents completed only high school (63.1 average) and students with free/reduced lunch (62.2). The lowest combined group is free/reduced lunch with no test preparation.

## Tools
Python, pandas, matplotlib, Jupyter Notebook, uv

## How to run
```bash
uv sync
uv run jupyter notebook
```
Download `StudentsPerformance.csv` from Kaggle and place it in the project folder, then open `student_analysis.ipynb`.