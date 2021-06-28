# PyCitySchools
## Background
Given two data sets: [schools_complete.csv](https://github.com/rflammia-py/pandas-challenge/blob/main/PyCitySchools/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/rflammia-py/pandas-challenge/blob/main/PyCitySchools/Resources/students_complete.csv), I used python pandas to import and merge the aggregate data and displayed them in data frames. I completed the project in Jupyter Notebook and can viewed in my [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/rflammia-py/pandas-challenge/blob/main/PyCitySchools/PyCitySchools_starter.ipynb).


## Observable Trends

- When looking at all schools, the averages between subjects vary. 
    
        The overall passing rate for reading: 85.805463
        The overall passing rate for math: 74.980853
    
  - So quickly, it is shown that a greater emphasis on mathmatical education is needed. 

- When comparing the top performing schools to the bottom performing schools (by overall percent passing), the common denominator was not budget or budget per student. It was school type 
    
        The top five performing schools were all Charter
        The bottom five performing schools were all District
        
        Overall % Passing Rate for District Schools: 53.672208
        Overall % Passing Rate for Charter Schools: 90.432244

- The more spending per student, the worse the schools for each subject were
- When looking at reading scores by grade, only schools with high averages have improvement from 9th to 12th grade. The bottom performing schools reading scores by grade:
               
        Rodriguez High School District: 80.993, 80.629, 80.864, 80.376
        Figueroa High School District: 81.198, 81.408, 80.640, 81.384
        Huang High School District: 81.290, 81.512, 81.417, 80.305
        Hernandez High School District: 80.866, 80.660, 81.396, 80.857
        Johnson High School	District: 81.260, 80.773, 80.616, 81.227
  
    - **All of these bottom schools scores actually _decrease_ throughout the grades**, except Figueroa High School District. The bottom performing schools reading scores decreased by an average of **-0.291** from 9th grade to 12th grade. 
- Now looking at the reading scores by grade for the top performing schools:
               
        Cabrera High School: 83.676, 84.253, 83.788, 84.287
        Thomas High School: 83.728, 84.254, 83.585, 83.831
        Griffin High School: 83.369, 83.706, 84.288, 84.013
        Wilson High School: 83.939, 84.021, 83.764, 84.317
        Pena High School: 83.807, 83.612, 84.335, 84.591
  
    - **All of these top schools reading scores _increase_ throughout the grades**. The top performing schools reading scores increased by an average of **+0.504** from 9th grade to 12th grade. 
 
- And the size of the school has a strong correlation on student success. The overall passing rate goes from aroun 90% to 58% when it reaches a school size of about 2000 or more. 
  - School boards and public officials should be mindful of school population size more than budget when considering the childrens success. As school sizes rise, it negatively impacts a students achievements.
