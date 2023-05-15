# School_District_Analysis
## Purpose of Analysis
The main purpose of this project was to review the performance of high schools in a given school district, based on the math and reading scores of their students on standardized tests. Two separate CSVs, one recording information about the various high schools, and another about all of the high school students in the district, were reviewed, cleaned, and then combined prior to being subject to various analyses.
The initial analysis consisted of a per-school overview of student population, budget, per-student budget, average math & reading scores, and percentage of students with passing grades. This was also accompanied by a rating of the top-five and bottom-five performing schools, determined by the overall passing percentage of students at these schools.
## Results
### District Summary Affect:
The challenge consisted of the removal of some information as the scenario presented was that evidence of academic dishonesty necessitated the voiding of test scores for all 9th grade students at Thomas High School. Thomas High School has 461 9th graders and the affected scores were under math, reading, and the overall score. The orignal district data shows slightly higher grades than after the changes took place. For example, the average reading score was 81.88% and the % passing math was 74.98%. After changing the data the results revealed very similar scores. For example, the altered data average reading score was 81.86 and the % passing math was 74.76%. When rounded to whole numbers, the results would still be the same compared to the previous district score.
### School Summary Affect:
The original overall school passing rate was 91% which seemed suspiciously high. After removing the 9th grade students math and reading scores, the new overal passing percent became 65.07%. This is a significant difference.
### Replacing grades relative to other schools
The original analysis had Thomas High School ranked second in the district, which seemed suspicious. After altering the data, the new results show Thomas High School to be 8th in the district.
#### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade: In the original analysis Thomas High School had a 83.6 math average and 83.7 reading average for 9th graders. The test scores were then replaced with nan which show the other grades, 10th, 11th, 12th as doing slightly better than before
![Screen Shot 2022-08-10 at 10 54 43 PM](https://user-images.githubusercontent.com/106174279/184066996-d1cb76eb-1656-4ef3-a2f0-71d33e213c64.png)

- Scores by school spending: Not much changed when comparing the spending range, as shown below.
Original:
![Screen Shot 2022-08-10 at 10 56 17 PM](https://user-images.githubusercontent.com/106174279/184067140-04c87faf-6f93-4d59-a987-9b11c4d0ac98.png)
Updated:
![Screen Shot 2022-08-10 at 10 56 23 PM](https://user-images.githubusercontent.com/106174279/184067155-faaec9da-00ee-42fd-95a1-9b7580218b5e.png)

- Scores by school size: Thomas High School is a medium sized school and no significant change took place.
- Scores by school type: Thomas High School is a charter school and no significnat change took place
## Summary
### Four changes that took place
1. In reports, the 9th grade reading and math data averages have been nullified and are completely unusable since they were tainted with the cheating.
2. Overall passing rate at THS saw a significant change as it went from 91% to 65%
3. Campus math and reading averages had minor shifts
4. THS went from 2nd to 8th in the district of 15 schools
