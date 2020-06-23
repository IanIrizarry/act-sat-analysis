# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Executive Summary

As part of the College Board Participation Improvement task force, our team was responsible for tracking statewide participation and providing a recommendation for where money might best be spent to improve SAT participation rates. Our goal is to work to increase the participation rate in the state of Illinois.

In this report, we are going to do the following:

1. Take a look at aggregate SAT and ACT scores and participation rates from each state in the United States
2. Seek to identify trends in the data
3. Combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states.

### Background

The SAT has been known as a long time leader in standardized testing. The rival standardized test, the ACT, has gained traction as a viable test to take for those interested in persuing a college education. 

### Problem Statement

Before looking at the data, our task force wanted to answer the question:

    What influences participation rates, generally, and what influences a change in preference from one test to the other.

### Main Point

#### Rates in Illinois flipped dramatically from ACT prioritization to SAT

The first finding is that the participation rates in Illinois, for the SAT, were extremely low in 2017. However, despite the low participation rate in that year, in 2018, the rate increased drammatically to 99%. I found an explanation for this flip in my outside research. According to the Chicago Tribune, the ACT has dominated the market share of Illinois standardized testing for nearly two decades. However, in 2016, the state decided to run a bid to determine which standardize test would be provded in the state. That same year, the state awarded the bid to the Collage Board's SAT.

#### Delay in participation improvement

The second finding is that, although the College Board was awarded the bid, participation rates remained low until 2018. What that tells me is that preferences for the ACT remained strong until 2018. Additionally, state funding towards the SAT may have caused an obstacle. For 2 years in a row, the state struggled to form a state budget between 2015 and 2017.

#### Participation rates are largely influenced by state involvement

Finally, an analysis of the states with the highest and lowest participation rates revealed that many of the states either required SAT/ACT testing in highschool or provided funding for one test over the other. This state influence has a signficant impact on participation rates.

### Recommendations

1. We should identify the states that play a role in standardized testing. This includes:
    - states that mandate testing
    - states that pay for testing; and
    - states that bid for testing
2. Based on the delay between the Illinois decision to support SAT testing and the increase in the SAT participation, we can speculate that testing preference may have an influence on decision making. Therefore, we should develop a brand message that demonstrates why states, schools, parents, and students should choose to take the SAT over the ACT.
3. Finally, the third recommendation would be to target the branding message at states that require ACT testing over another.

---

### Datasets

#### Provided Data

For this project, you'll have four provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

---

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|Object|ACT or SAT|The state in which the testing took place||
a_participation_17|Float|ACT|The percentage of students who recorded that specific state as their testing state for the 2017 ACT|
a_english_17|Float|ACT|The ACT english Score (1-36)|
a_math_17|Float|ACT|The ACT math Score (1-36)|
a_reading_17|Float|ACT|The ACT reading Score (1-36)|
a_science_17|Float|ACT|The ACT science Score (1-36)|
a_composite_17|Float|ACT|The ACT composite Score (1-36)|
s_participation_17|Float|SAT| The percentage of students who recorded that specific state as their testing state for the 2017 SAT|
s_rw_17|Int|SAT|The SAT writing Score (200-800)|
s_math_17|Int|SAT|The SAT math Score (200-800)|
s_total_17|Int|SAT|The SAT total Score (200-800)|
