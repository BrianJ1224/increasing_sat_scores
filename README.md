
# How can we increase SAT participation in Lousianna?
#### Author: Brian Jankowitz
[Medium](https://medium.com/@JankowitzB) | [LinkedIn](https://www.linkedin.com/in/brian-jankowitz/)

#### [Project Presentation](presentation.pptx)
#### [Jupyter Notebook](/code/project_notebook.ipynb)


### Problem Statement

The SAT and ACT are two big standardized tests that are given in
the United States. These exams are used for entrance into college.
In this documentation, Lousiana was studied for 2017 and 2018.

In Lousiana, the participation rate for the SAT is very low compared to the SAT in 2017 and 2018. Colorado was similiar although in 2018 the opposite occured.Data was analized to see why Colorado had an incraase in students taking the SAT. In addition, reseach was done to see why this happened.


### Executive Summary

Four data sets were provided:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)

These data sets give the average SAT and ACT scores by state, as well as participation rates. This data is for 2017 and 2018.

The source for the 2017 SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the 2017 ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows).


The source for the 2017 SAT data [here](https://reports.collegeboard.org/sat-suite-program-results/state-results), and the source for the  2018 ACT state-by-state mean composite scores and participation rates data [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .

These four files are comppiled and are located in the data folder.

Data Dictionary listed below

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state_sat_2017|object|SAT|Place of test
|participation_sat_2017|int|SAT|Percentage of people who took test
|evidence-based reading and writing_sat_2017|int|SAT|English score
|math_sat_2017|int|SAT|Math Score
|total_sat_2017|int|SAT|Total score
|state_act_2017|object|ACT|Place of test
|participation_act_2017|int|ACT|Percentage of people who took test
|english_act_2017|float|ACT|English score
|math_sat_2017|float|ACT|Math score
|reading_act_2017|float|ACT|Reading score
|science_act_2017|float|ACT|Science score
|composite_act_2017|float|ACT|Total score
|state_sat_2018|object|SAT|Place of test
|participation_sat_2018|int|SAT|Percentage of people who took test
|evidence-based reading and writing_sat_2018|int|SAT|English score
|math_sat_2018|int|SAT|Math Score
|total_sat_2018|int|SAT|Total score
|state_act_2018|object|ACT|Place of test
|participation_act_2018|int|ACT|Percentage of people who took test
|english_act_2018|float|ACT|English score
|math_sat_2018|float|ACT|Math score
|reading_act_2018|float|ACT|Reading score
|science_act_2018|float|ACT|Science score
|composite_act_2018|float|ACT|Total score


|State|SAT 2017|SAT 2018|ACT 2017|ACT 2018|
|---|---|---|---|---|
|Louisiana|4%|4%|100%|100%|
|Colorado|11%|100%|100%|30%|
|National|39%|45%|66%|62%

### Primary Findings

For Louisiana, the participation rate of the SAT was 4% and the participiation rate of the ACT was 100% in 2017 and 2018.

Colorado had a participation rate of the SAT was 11% followed by 100%. For the participation rate of the ACT was 100% followed by 30%.

Lousiana is not at the average participation rate for the SAT. The average for SAT in 2017 and 2018 which is 39% and 45% and ACT which is 66% and 62%. The SAT is about 35% and 41% below the national average.

Colorado was looked at to see why they were able to go from a state with the ACT having a higher participation rate to the SAT having a higher participation rate. This was because a testing reform legislation fought. After, a bidding process that took place and the SAT won. For the first time since 2001, juniors in high school were given the SAT instead of the ACT in 2017.

### Conclusion

The ACT tends to have more test takers in the central part of the United States unlike the SAT where it is very popular on the east and west coat. This could be due to smaller universities in the midwest than on the coasts. However, Lousiana has a lower percentage of students taking the SAT than ACT because the state uses the ACT for high school testing.

### Recommendations

College Board, the organization that adminsters the SAT, can talk with the Lousiana government to try and get them to change to the SAT. College Board can lobby and enter a bidding battle with the ACT.



### Sources
- https://www.edweek.org/ew/articles/2017/05/24/in-race-for-test-takers-act-outscores-sat--for.html
- https://www.studypoint.com/ed/sat-and-act-test/
- https://www.kaptest.com/sat/sat-vs-acthttps://www.denverpost.com/2017/03/06/colorado-juniors-sat-college-exam/
- https://www.testive.com/colorado-sat-change-2017/
