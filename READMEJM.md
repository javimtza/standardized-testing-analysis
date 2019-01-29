# Project 1: SAT & ACT Analysis
### Javier Martinez Abrego Cantu

---

## Executive Summary


### Contents:
- [Problem Statement](#Problem-Statement)
- [Data Dictionary](#2018-Data-Import-and-Cleaning)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

---


## Problem Statement
In 2016, College Board changed the fortmat of the SAT. Major changes were done to the scoring system of the test, as well as its contents.
Some of the changes included a change in score range from 600-2400 (previous) to 400-1600 (new) as well as joining the reading and writing section and removing penalties for incorrect answers. Because 2016 marked a pivot year in the College Board’s SAT test, I will be using the 2017/18 SAT & ACT Scores and Participation rates for states in the US to single out a state in which the College Board can focus to better improve SAT participation rates.

---

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|2017 National ACT Scores|State for which average scores are measured| 
|act_participation_17|float|2017 National ACT Scores|Participation for corresponding state (in percent, 100 means 100%)| 
|act_english_17|float|2017 National ACT Scores|Average score for the English section for the corresponding state (out of 36) | 
|act_reading_17|float|2017 National ACT Scores|Average score for the Reading section for the corresponding state (out of 36)|
|act_science_17|float|2017 National ACT Scores|Average score for the Science section for the corresponding state (out of 36)| 
|act_math_17|float|2017 National ACT Scores|Average score for the Math section for the corresponding state (out of 36)| 
|act_composite_18|float|2017 National ACT Scores|Average composite score for the corresponding state (out of 36)| 
|act_participation_18|float|2018 National ACT Scores|Participation for corresponding state (in percent, 100 means 100%)| 
|act_english_18|float|2018 National ACT Scores|Average score for the English section for the corresponding state (out of 36) | 
|act_reading_18|float|2018 National ACT Scores|Average score for the Reading section for the corresponding state (out of 36)|
|act_science_18|float|2018 National ACT Scores|Average score for the Science section for the corresponding state (out of 36)| 
|act_math_18|float|2018 National ACT Scores|Average score for the Math section for the corresponding state (out of 36)| 
|act_composite_18|float|2018 National ACT Scores|Average composite score for the corresponding state (out of 36)| 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|sat_participation_17|float|2017 National SAT Scores|Participation for corresponding state (in percent, 100 means 100%)| 
|sat_math_17|float|2017 National SAT Scores|Average score for the Math section for the corresponding state (out of 800)| 
|sat_evidence-based reading and writing_17|float|2017 National SAT Scores|Average score for the Evidence Based reading and writing section for the corresponding state (out of 800)| 
|act_composite_17|float|2017 National ACT Scores|Average composite score for the corresponding state (out of 1600)| 
|sat_participation_18|float|2018 National SAT Scores|Participation for corresponding state (in percent, 100 means 100%)| 
|sat_math_18|float|2018 National SAT Scores|Average score for the Math section for the corresponding state (out of 800)| 
|sat_evidence-based reading and writing_18|float|2018 National SAT Scores|Average score for the Evidence Based reading and writing section for the corresponding state (out of 800)| 
|act_composite_18|float|2018 National ACT Scores|Average composite score for the corresponding state (out of 1600)| 

---

## Conclusions and Recomendations
Based on my exploration of the 2017/18 SAT and ACT data I can say for certain that participation rates between SAT and ACT are negativley correlated, meaning that if one state tends to have high SAT participation, then it probably will have low ACT participation and vice versa. This negative corrolation can also be seen by participation of a given test (SAT or ACT) and its scores (both total/composite and by subject). This correlation is due to the fact that we have selection bias in the data, meaning that since some states require one of the tests to graduate therefore giving that test close to (if not) 100% participation while the other test has low participation. Because the non-required test is only taken by a fraction of the students, the average scores for low participation tests tend to be higher, since students who will take the test will be students who strive for better scores. 

My recommendation would be to not compare average SAT scores to ACT scores because of the selection bias that is caused by participation rates around states. However, is possible to compare states with other states that have similar participation in a given test. My recommendation to the College Board would be to focus on Oregon in order to improve their participation rate. While there are certainly other states that have less SAT participation, those states tend to already have high ACT participation due to policies in place. Therefore we should focus on states that do not have a ACT requirement and try to sway those states into becoming a state that requires the SAT test; in this case, Oregon.