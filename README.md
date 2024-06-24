# pandas-challenge
module 4 challenge

## Report
This dataset included both school data and student data related to the type of school, the school's budget, number of students, and student specific data like name, student ID, reading scores and math scores. In this analysis, we looked at the test scores by different breakouts including school, school type,  school size, and grade level.

### Key Findings
- Charter schools are outperforming public schools despite having smaller per student budgets.
- Public schools, especially those with large student populations, have students that are stuggling with more with math and reading.

### Overview of Schools in the District
- There are 7 schools are public schools and 8 are charter schools within the district.
- Public schools have larger total budgets and student populations compared to charter schools.
- Public schools generally have a larger per student budgets than charter schools.
- Charter schools have a higher percent of their student population that are passing both math and reading.
#### District Summary
![district summary table](https://github.com/megan-oconnor/pandas-challenge/assets/147878655/c8b76170-a7eb-4c82-ae09-84375932757f)

#### School Summary
![school summary table](https://github.com/megan-oconnor/pandas-challenge/assets/147878655/96214d24-859e-4ca5-9b4d-0d7b615e532c)

#### Math & Reading Scores
The highest performing schools were charter schools, while the lowest performing schools were public schools. 
- The top perfoming school is Cabrera High School where 91% of the students are passing. They also have the 2nd lowest per student budget at $582 a student.
- The lowest performing school is Rodrigues High School where just under 53% of the students are passing.

When looking at the scores for both math and reading by school and grade level, scores generally look consistent at the schools. This means no one grade level at a school is doing significantly better than the other grades; if the test scores in 9th grade are 81, then the scores for 10th, 11th, and 12th grade are approximately 81 as well.
![avg scores by budget table](https://github.com/megan-oconnor/pandas-challenge/assets/147878655/ed24a6b5-eb9a-4efb-926e-9756f741d475)

We also created spending ranges for the per student budget and looked at the average test scores and pass rates for these ranges. We found that schools with larger per student budgets had lower scores and pass rates.
![avg scores by budget table](https://github.com/megan-oconnor/pandas-challenge/assets/147878655/5568299e-b4bc-4e7c-8627-70fcd586b101)

The schools were grouped into 3 categories related to their school size and then we calculated their average test results and passing rates. We found that schools with less than 2000 students had better test results and passing percentages. 
![avg scores by school size table](https://github.com/megan-oconnor/pandas-challenge/assets/147878655/06e5f807-2516-45cc-ae80-d1d93e6bd456)

Lastly, we looked at the scores and pass rates by school types. We found that charter schools had higher scores and pass rates than public schools.
![avg scores by school type table](https://github.com/megan-oconnor/pandas-challenge/assets/147878655/1eeb1f43-b2c2-4b43-adfd-4e57b95111bc)


## Resources
Code File: [main.ipynb](https://github.com/megan-oconnor/pandas-challenge/blob/main/PyCitySchools/main.ipynb) contains analysis of the dataset, contained in the [PyCitySchools](https://github.com/megan-oconnor/pandas-challenge/tree/main/PyCitySchools) folder
Datasets: 2 datasets for school data and student data, both in the [Resources](https://github.com/megan-oconnor/pandas-challenge/tree/main/PyCitySchools/Resources) folder
Images: contain screenshots of the datatables from the analysis, all located in the [Images](https://github.com/megan-oconnor/pandas-challenge/tree/main/Images) folder
