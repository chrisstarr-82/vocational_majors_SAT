# Vocational Fields and SAT Scores

## Overview

This was the first project for the DSI boot camp. For this project, we were given some datasets and a detailed walkthrough of steps to take for data analysis. However, I chose the topic.

I included it in this github to show that I am interested in economic justice and development issues, because there is a good data visualization on the bottom of the notebook, because I think I wrote some decent code for the project, and because it demonstrates the approach to data analysis that I learned at DSI.

## Problem Statement

I am working for a four year college that serves students who are focused on training in applied fields. The college is filling a need for students trained in these fields, but many of the applicants to the college are not academically inclined. Board members have asked if the college should still evaluate SAT scores as part of the application process, or if they should focus on other things instead.

## Background

The SAT is a standardized test that many colleges and universities in the United States require for their admissions process. This score is used along with other materials to determine whether or not a potential student will be accepted to the university. The SAT has two sections of the test: Evidence-Based Reading and Writing and Math. SAT tests are popular among students, but colleges have found less value in them over time.

Most four-year colleges use admissions tests as part of the admissions process, but they are not as important as other materials. The SAT could be used for determining academic readiness, placing students in the right classes, or identifying needs for academic support. 


**References**

https://www.theatlantic.com/ideas/archive/2020/09/even-coronavirus-cant-kill-sat-and-act/616360/
https://bigfuture.collegeboard.org/get-in/testing/8-things-to-know-about-how-colleges-use-admission-tests

---

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|sat_state_2017, sat_state_2018, sat_state_2019|US State|
|intended_college_major|object|sat_major_2019|Major that a student declares when taking the test|
|major_test_takers|int64|sat_major_2019|Number of test takers that declared a certain major|
|major_percent|float64|sat_major_2019|Percent of test takers that declared a certain major|
|major_total|int64|sat_major_2019|Overall SAT score in the majors data|
|major_english|int64|sat_major_2019|English, Reading, Writing score in the majors data
|major_math|int64|sat_major_2019|Math score in the majors data|
|math_2017|float64|sat_state_2017|Math score in the 2017 state data|
|math_2018|int64|sat_state_2018|Math score in the 2018 state data|
|participation_2017, participation_2018, participation_2019|float64|sat_state_2017, sat_state_2018, sat_state_2019|State SAT participation percent data|
|english_2017, english_2018, english_2019|int64|sat_state_2017, sat_state_2018, sat_state_2019|State SAT English, Reading, Writing scores|
|total_2017, total_2018, total_2019|int64|sat_state_2017, sat_state_2018, sat_state_2019|State SAT math scores|


## Conclusions

- There is an uneven distribution of test takers by major. The popularity of the SAT for vocational applicants should be evaluated for the specific college
- The lowest relative scores are for vocational majors. Requiring the SAT is not recommended for a school focused on the student population the college is focused on, but it can be used for other purposes, like planning coursework for individual students.



