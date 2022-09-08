<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Project 1: Standardized Test Analysis
---
## Problem Statement
---
One of tutor school is planning to open new school after the covid-19 pandemic. Tutor school hires data scientist for analyze the ACT/SAT data. Since this is the first phase of the project, tutor school require data about SAT/ACT as much as possible. The purpose of the analysis is acquiring the information about SAT/ACT in 2017 - 2019 and student.

## Data Dictionary
---
The 6 datasets using in this project are ACT2017, ACT2018, ACT2019, SAT2017, SAT2018 and SAT2019. All of the features in the dataset display in table below.

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT2017/ACT2018/ACT2019/SAT2017/SAT2018/SAT2019|Identify the state.|
|participation|float|ACT2017/ACT2018/ACT2019/SAT2017/SAT2018/SAT2019|The fraction of participation to the SAT/ACT test.|
|english|float|ACT2017|Average score of English subject for each state.|
|math|float/int|ACT2017/SAT2017/SAT2018/SAT2019|Average score of Math subject for each state.|
|reading|float|ACT2017|Average score of reading part for each state.|
|science|float|ACT2017|Average score of Science subject for each state.|
|composite|float|ACT2017/ACT2018/ACT2019|Average score of all parts for each state.|
|ebrw|int|ACT2017/SAT2017/SAT2018/SAT2019|Average score of evidence-based reading and writing part for each state.|
|total|int|ACT2017/SAT2017/SAT2018/SAT2019|Average total SAT score for each state.|

## Brief summary of analysis
---
**The analysis in this project contain 4 section**
1. High participation rate of ACT and SAT in US
2. Compare score between high participation rate and the other state
3. High participation rate for both ACT and SAT
4. Relation between score for each subject in ACT/SAT

**The goal for each section :** 
- Part 1, 3 : Analysis the state in US for locate the tutor school (state with 100% participation rate).
- Part 2 : Analysis the performance of student.
- Part 4 : Analysis the correlation between each subject in ACT and SAT.

## Conclusions and Recommendations
---
**Conclusion**
1. The state, that have high participation rate either SAT or ACT, trend to have low participation rate for the other test. 
2. For ACT/SAT 2017 - 2019, The state with 100% participation trend to have lower score than other state with lower participation rate.
3. The student in state, that have both participation rate of ACT and SAT greater than 50%, is slightly above student in state that have 100% participation rate .
4. Mean of ACT and SAT doesn't change that much in year 2017 - 2019.
5. Std ACT/SAT score of the student in state, have 100% participation rate, is lower over year.
6. The student that have high score trend to have high score in all subject.

**Recommendation**
1. Recommendations tutor school location
    - From data exploration part1 and part2 : There are 19 states and 4 states that have 100% participation rate of ACT and SAT respectively.
    - From data exploration part3 : There are 5 states that have both participation rate of ACT and SAT greater than 50%.
2. Recommendations for the next phase
    - If possible : Collecting data in the specific state in the recommend location and analysis the data in the state for more information.
    - Analysis about the state that require ACT/SAT and find more opportunity for locate the tutor school location.
