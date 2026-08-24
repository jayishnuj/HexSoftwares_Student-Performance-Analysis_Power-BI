# HexSoftwares_Student-Performance-Analysis_Power-BI

Interactive Power BI dashboards analyzing Mathematics performance across G1 , G2 , and G3 grades using demographic , academic , family and social factors

# Data Source

https://archive.ics.uci.edu/dataset/320/student+performance

# The feature variables in this dataset are :-

1. **school** — Student's school (binary: `GP` - Gabriel Pereira or `MS` - Mousinho da Silveira)

2. **sex** — Student's sex (binary: `F` - female or `M` - male)

3. **age** — Student's age (numeric: 15 to 22)

4. **address** — Student's home address type (binary: `U` - urban or `R` - rural)

5. **famsize** — Family size (binary: `LE3` - less than or equal to 3 or `GT3` - greater than 3)

6. **Pstatus** — Parent's cohabitation status (binary: `T` - living together or `A` - apart)

7. **Medu** — Mother's education (numeric: `0` - none, `1` - primary education, `2` - 5th to 9th grade, `3` - secondary education, `4` - higher education)

8. **Fedu** — Father's education (numeric: `0` - none, `1` - primary education, `2` - 5th to 9th grade, `3` - secondary education, `4` - higher education)

9. **Mjob** — Mother's job (nominal: teacher, health care related, civil services, at home, or other)

10. **Fjob** — Father's job (nominal: teacher, health care related, civil services, at home, or other)

11. **reason** — Reason for choosing the school (nominal: close to home, school reputation, course preference, or other)

12. **guardian** — Student's guardian (nominal: mother, father, or other)

13. **traveltime** — Home-to-school travel time (numeric: `1` - <15 min, `2` - 15–30 min, `3` - 30 min–1 hour, `4` - >1 hour)

14. **studytime** — Weekly study time (numeric: `1` - <2 hours, `2` - 2–5 hours, `3` - 5–10 hours, `4` - >10 hours)

15. **failures** — Number of past class failures (numeric)

16. **schoolsup** — Extra educational support (binary: yes or no)

17. **famsup** — Family educational support (binary: yes or no)

18. **paid** — Extra paid classes within the course subject (binary: yes or no)

19. **activities** — Extra-curricular activities (binary: yes or no)

20. **nursery** — Attended nursery school (binary: yes or no)

21. **higher** — Wants to pursue higher education (binary: yes or no)

22. **internet** — Internet access at home (binary: yes or no)

23. **romantic** — Currently in a romantic relationship (binary: yes or no)

24. **famrel** — Quality of family relationships (numeric: `1` - very bad to `5` - excellent)

25. **freetime** — Free time after school (numeric: `1` - very low to `5` - very high)

26. **goout** — Going out with friends (numeric: `1` - very low to `5` - very high)

27. **Dalc** — Workday alcohol consumption (numeric: `1` - very low to `5` - very high)

28. **Walc** — Weekend alcohol consumption (numeric: `1` - very low to `5` - very high)

29. **health** — Current health status (numeric: `1` - very bad to `5` - very good)

30. **absences** — Number of school absences (numeric: 0 to 93)                                                                                         

# The target variables are :-

31. **G1** - first period grade (numeric: from 0 to 20)
 
32. **G2** - second period grade (numeric: from 0 to 20)
 
33. **G3** - final grade (numeric: from 0 to 20) 

# Project :-

This Power BI project analyzes the academic performance of students in Mathematics across three stages of assessment: Grade 1 (G1), Grade 2 (G2), and Final Grade (G3).
The dashboard is organized into three dedicated pages:
- Grade 1 Dashboard – analyzes students' first-period Mathematics performance.
- Grade 2 Dashboard – analyzes second-period performance.
- Final Grade Dashboard – focuses on students' final Mathematics grades.

# What the dashboard analyzes :-

The project goes beyond simply displaying grades. It examines how academic performance relates to several student, family, educational, and lifestyle factors.
The dashboards include:
- Average, maximum, and minimum grades for each assessment period.
- Student count across different categories.
- Performance comparison based on internet access and gender.
- Relationship between study time and family educational support.
- Comparison of study time with urban/rural residence.
- Influence of free time and aspirations for higher education on performance.
- Relationship between family relationship quality and family size.
- Student performance based on participation in extracurricular activities.
- Distribution of students according to health condition.
- Analysis of the reason for choosing the school.
- A matrix examining Mathematics performance in relation to father's and mother's education levels.
- A school slicer allowing the dashboard to be filtered by school.
