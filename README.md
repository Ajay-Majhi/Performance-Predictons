# Performance-Predictons
# Our Prediction based on this datasets ,datasets contain some pattern :---
# Attributes for both student-mat.csv (Math course) and student-por.csv (Portuguese language course) datasets:
1 school - student's school (binary: "GP" - Gabriel Pereira or "MS" - Mousinho da Silveira)</br>
2 sex - student's sex (binary: "F" - female or "M" - male)</br>
3 age - student's age (numeric: from 15 to 22)</br>
4 address - student's home address type (binary: "U" - urban or "R" - rural)</br>
5 famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)</br>
6 Pstatus - parent's cohabitation status (binary: "T" - living together or "A" - apart)</br>
7 Medu - mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)</br>
8 Fedu - father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)</br>
9 Mjob - mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")</br>
10 Fjob - father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")</br>
11 reason - reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")</br>
12 guardian - student's guardian (nominal: "mother", "father" or "other")</br>
13 traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)</br>
14 studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)</br>
15 failures - number of past class failures (numeric: n if 1<=n<3, else 4)</br>
16 schoolsup - extra educational support (binary: yes or no)</br>
17 famsup - family educational support (binary: yes or no)</br>
18 paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)</br>
19 activities - extra-curricular activities (binary: yes or no)</br>
20 nursery - attended nursery school (binary: yes or no)</br></br>
21 higher - wants to take higher education (binary: yes or no)</br>
22 internet - Internet access at home (binary: yes or no)</br></br>
23 romantic - with a romantic relationship (binary: yes or no)</br>
24 famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)</br></br></br>
25 freetime - free time after school (numeric: from 1 - very low to 5 - very high)</br></br>
26 goout - going out with friends (numeric: from 1 - very low to 5 - very high)</br>
27 Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)</br>
28 Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)</br>
29 health - current health status (numeric: from 1 - very bad to 5 - very good)</br>
30 absences - number of school absences (numeric: from 0 to 93)</br>

# these grades are related with the course subject, Math or Portuguese:
31 G1 - first period grade (numeric: from 0 to 20)</br>
31 G2 - second period grade (numeric: from 0 to 20)</br>
32 G3 - final grade (numeric: from 0 to 20, output target)</br>

Additional note: there are several (382) students that belong to both datasets . </br>
These students can be identified by searching for identical attributes</br>
that characterize each student, as shown in the annexed R file.</br>
