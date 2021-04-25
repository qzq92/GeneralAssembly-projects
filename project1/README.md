### Project 1: SAT & ACT Analysis
---
In this first Data Science project from the General Assembly curriculum, I examined trends in both SAT and ACT participation rates as well as aggregate scores from 2017 and 2018 across all the US states. 
The aim for this project is to identify possible trends in the data using various data exploration and analysis with outside research to identify factors resulting in influencing participation rates across various states and subsequently make recommendations in increasing SAT participation rate based on a state of my choice, which is California.

### Issues with provided data
---
- The column names for ACT 2017 and 2018 are different with the exception of state.
- An additional "National" state entry was found in ACT 2017 dataset but not ACT 2018.
- Irregular values were in the Science and Composite columns of ACT 2017 dataset, likewise for the Math column in SAT 2017 dataset.

### Summary of Findings & Recommendations
---
In general, high participation rates in one test usually means low participation rates in the other. ACT is still widely sought after examination compared to SAT with 29 states having higher participation for ACT in 2017 and 27 states in 2018. Participation rate for states are 100% for specific type of exam when there are laws and regulations that mandates the need for taking the exam. The test scores for 2017 cohort and 2018 are largely similar across all subjects for each test.

Taking into consideration of the various US state populations with focus in increasing SAT participation rate with no existing state laws mandating high school juniors to take SAT, I would choose the state of California for consideration as it is the most populous state.

It was noted that there are no laws mandating the need for SAT exam participation for high school juniors in California. To increase participation amongst graduating seniors, the College Board may recommend the California State Board of Education (CSBE) to adopt SAT exam inline with other states which have done so and remove California High School Proficiency Examination (CHSPE) to provide SAT takers an opportunity to apply for universities not just within California but also other states.
The CSBE may consider recommending the governor to legislate SAT exam as a compulsory state exam to be passed prior to getting high school diploma.

Furthermore, SAT exam is cheaper as it costs 52 USD compared to CHSPE which costs 162 USD. By selecting this populous state, more resources could be devoted which could be enjoyed by large number of people due to large population resulting in efficient utilisation of provided resources. 


### Data Dictionary
---

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|SAT/ACT|US States participating in SAT/ACT exam for 2017,2018| 
|**act17_pptn**|*float*|ACT|US State participation rate in ACT exam for 2017|
|**act17_english**|*float*|ACT|US State average ACT score for English subject for 2017|
|**act17_math**|*float*|ACT|US State average ACT score for Math subject for 2017|
|**act17_reading**|*float*|ACT|US State average ACT score for Reading subject for 2017|
|**act17_science**|*float*|ACT|US State average ACT score for Science subject for 2017|
|**act17_composite**|*float*|ACT|US State average ACT Composite score for 2017 (Composite = Average of English, Math, Reading and Science subjects' scores)|
|**act18_pptn**|*float*|ACT|US State participation rate in ACT exam for 2018|
|**act18_composite**|*float*|ACT|US State average ACT Composite score for 2018 (Composite = Average of English, Math, Reading and Science subjects' scores)|
|**act18_english**|*float*|ACT|US State average ACT score for English subject for 2018|
|**act18_math**|*float*|ACT|US State average ACT score for Math subject for 2018|
|**act18_reading**|*float*|ACT|US State average ACT score for Reading subject for 2018|
|**act18_science**|*float*|ACT|US State average ACT score for Science subject for 2018|
|**sat17_pptn**|*float*|SAT|US State Participation rate in SAT exam for 2017| 
|**sat17_ebrw**|*float*|SAT|US State average SAT score for Evidence-Based Reading and Writing subject for 2017| 
|**sat17_math**|*float*|SAT|US State average SAT score for Math subject for 2017| 
|**sat17_total**|*float*|SAT|US State average total SAT score for 2017 (Total = Evidence-Based Reading and Writing + Math subjects' scores)|
|**sat18_pptn**|*float*|SAT|US State Participation rate in SAT exam for 2018| 
|**sat18_ebrw**|*float*|SAT|US State average SAT score for Evidence-Based Reading and Writing subject for 2018| 
|**sat18_math**|*float*|SAT|US State average SAT score for Math subject for 2018| 
|**sat18_total**|*float*|SAT|US State average total SAT score for 2018 (Total = Evidence-Based Reading and Writing + Math subjects' scores)|
