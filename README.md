# US States Education Performance

### Overview

Our first module in DSI covers:
- Basic statistics and probability
- Many Python programming concepts
- Programmatically interacting with files and directories
- Visualizations
- EDA
- Working with Jupyter notebooks for development and reporting

You might wonder if you're ready to start doing data science. While you still have **tons** to learn, there are many aspects of the data science process that you're ready to tackle. Project 1 aims to allow you to practice and demonstrate these skills.

For our first project, we're going to take a look at aggregate SAT and ACT scores and participation rates in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to address our problem statement.

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.

### Problem Statement

Education is one of the most important factor for every country in the world. To develop human well-being, well educated citizen can provide security of society, also sustainable economic.

US spends a lot of money for primary and secondary schools but how can the investment of education be measured over the country.

Therefore, the project aims to measure education performance and public spending on education by using standardized tests, SAT and ACT, over US states.

---

### Datasets

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|object|ACT/SAT 2017-2019|Year of recording| 
|state|object|ACT/SAT 2017-2019|US state| 
|sat_participation|float|SAT 2017-2019|SAT participation rate| 
|sat_eng|float|SAT 2017-2019|SAT evidence-based reading and writing scores| 
|sat_math|float|SAT 2017-2019|SAT Math scores| 
|sat_total|float|SAT 2017-2019|SAT total scores| 
|act_participation|float|ACT 2017-2019|ACT participation rate| 
|act_composite|float|ACT 2017-2019|ACT average scores| 
|act_eng|float|ACT 2017|ACT English scores| 
|act_math|float|ACT 2017|ACT Math scores| 
|act_reading|float|ACT 2017|ACT Reading scores| 
|act_science|float|ACT 2017|ACT Science scores| 
|perpupil_spending|float|Census 2017-2019|Per pupil school public spending| 
|combine_participation|float|Calculation|Combination of SAT and ACT participation rate| 
|sat_total_normal|float|Calculation|Percentage of SAT total scores| 
|sat_weight|float|Calculation|Weight for SAT/ACT index| 
|act_total_normal|float|Calculation|Percentage of ACT total scores| 
|act_weight|float|Calculation|Weight for SAT/ACT index| 
|combine_total_normal_weighted|float|Calculation|Weighted SAT/ACT index| 
|combine_total_normal|float|Calculation|Un-weighted SAT/ACT index| 
|spending_2019_group|Object|Calculation|Group of 2019 education spending and SAT/ACT index| 

---

### Conclusions and Recommendations

According to the project results, public educational spending related to education level (SAT/ACT index).  
But some states are found to spend large money with lower education level achieved that are Minnesota, Hawaii, Ohio, North Dakota, and Wyoming.
These states should be investigated to find reasons that prevent the states perform well after spend a large money.

---

