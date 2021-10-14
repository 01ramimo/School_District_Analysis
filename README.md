# School_District_Analysis
PyCitySchools with Panda

**Overview 

The school board suspects academic dishonesty at Thomas High School (THS) and specifically amongst 9th graders in that school. Hence, the purpose for this analysis is to clean up (replace the data) the math and reading scores for the 9th graders at THS with NaN and then compare if any, the difference in average math and reading score, percent (%) passing math, reading and overall passing to the values before and after cleaning the data. While further evaluating those values against the scores by school spending, size, type etc. to help statistically validate and draw opinions that THS is underperforming as suspected.

**Results

**How is the district summary affected?

•	**Before Cleanup Observations:

The Average Math and reading score, % Passing Math and Reading as well as % Overall Passing were as follows respectively:
79.0 %, 82.0%, 75.0%, 86.0% and 65.1%

![district summary 1](https://user-images.githubusercontent.com/89875689/137234234-f37f4aaf-f0dc-4d5c-9640-f13f1e6bb36d.png)

•	**After Cleanup Observations:

The Average Math and reading score, % Passing Math and Reading as well as % Overall Passing were as follows respectively:
79.0%, 82.0%, 75.0%, 86.0% and 65.0%

![district summary 2](https://user-images.githubusercontent.com/89875689/137234332-2451ec80-91c3-4a2f-9e47-50666a888c60.png)

•	Hence, comparing both before and after there’s close to no change in the district summary data.

**How is the school summary affected?

•	Before Cleanup observations - Thomas High School ranked 2rd in place with a 91% Overall Passing.

![school summary 1](https://user-images.githubusercontent.com/89875689/137234632-9691c090-c9cc-479d-92fc-5b5f1def1670.png)

•	After Cleanup observations - Thomas High School ranked 8th in place with a 65% Overall Passing.

![school summary 2](https://user-images.githubusercontent.com/89875689/137234685-6fbe953c-39b9-4091-9749-dd437e619e58.png)


Evidently, there was a significant change in Thomas’s School percentage % Overall Passing which resulted to drop in its rank placing it from the 2rd to the 8th school on the list after the cleanup. This data could help statistically validate the board member’s suspicions about academic dishonesty as suspected at Thomas High School (THS).


o	**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 

As a result, data showed that Thomas High School’s performance drastically changed from ranking 2rd to 8th place in the list. Whereas the set of the High schools remained relatively at the same rank and % scores.

**Summary

o	**How does replacing the ninth-grade scores affect the following:

**Math and reading scores by grade 

Both Math and reading scores for Thomas High School reduced after the cleanup hence supporting that the 9th graders score were equivalent to failing.

**Scores by school spending 

The spending for Thomas High School was $638 falling at the range of $630-644. Removing the 9th grade scores resulted in a reduction to % passing math, % passing reading and % overall passing scores i.e., % passing math reduced from 73-67 %.

**Scores by school size 

The school size for Thomas High School was medium falling in the range of 1000 – 2000. Removing the 9th grade scores resulted in a reduction to % passing math, % passing reading and % overall passing scores i.e., the % passing math reduced from 94 -88 %.

**Scores by school type 

Thomas High School fell under the “Charter” bucket. Removing the 9th grade scores resulted in a reduction to % passing math, % passing reading and % overall passing scores i.e., the % passing math reduced from 94 -90 %.




