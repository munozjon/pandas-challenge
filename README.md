# pandas-challenge

## Module 4 Challenge

For this assignment, I analyzed and interpreted the information about a school district's standardized test results using Jupyter Notebook. The notebook, PyCitySchools, is located in the PyCitySchools folder of the repository. I was provided with two CSV files, one that contained information for each school in the district, and the other that contained information, including test results, for each student at each school in the district. With this data, I completed an in-depth analysis of the overall district, as well as each school's performance, using functions in the Pandas library.

## District Overall Summary

This district contains 15 'charter' and 'district' high schools, with a total of 39,170 students across all schools. The total budget allocated for all the schools was $24,649,428.00. For the district, the average test scores for math and reading were about 78.99 and 81.88, respectively. While roughly 74.98% and 85.81% of students passed the math and reading exams each, only about 65.17% of students overall passed both exams.

## Analysis and Conclusions

### Trends in School Type

Further analysis for each school reveals interesting trends in the data. To begin, the data reveals that the top 5 schools in Overall Passing Percentage all come from charter schools. The implication here would suggest that these types of schools employ better resources for students to pass their exams. Overall, about 90.43% students from charter schools passed both the math and reading exams. By contrast, the bottom 5 schools in Overall Passing Percentage are all district schools. In general, only about 53.67% of students from district schools passed both the math and reading exams.

Another notable observation is that the top 5 charter schools have a noticably smaller student body than the bottom 5 district schools. This is potentially due to the more rigorous enrollment process for the charter schools compared to district schools, which are generally more accessible. This trend is further emphasized when looking at the overall scores based on the size of all of the schools. The larger schools with 2000 to 5000 students had, cumulatively, only about 58.29% of its students pass both the math and reading exams. Conversely, small (less than 1000) and medium (1000 to 2000) schools had about 89.88% and 90.62% of their students pass both exams, respectively. This further emphasizes the point that the charter schools generally produce better test scores from students than the district schools.

### Trends in School Budget

Moving forward, analyzing the schools by their total budget and per capita budget reveals key trends in school performance. When looking at per capita spending, schools that spend less than 585 dollars per student see about 90.37% of their students pass both the math and reading exams, with average math score of about 83.46 and reading score of about 93.46. By contrast, the schools who spent between 645 and 680 dollars per student saw only about 53.53% of their students pass both exams. This generally coincides with the idea that schools with larger student bodies tend to score lower on their exam scores and see fewer of their students pass both exams; to that end, the schools with the least amount of spending per student charter schools, while the schools spending the most per student are district schools.

### Trends by Grade and Exam

Finally, we can identify some other key trends found from the data. As previously mentioned, overall, students recorded better scores on the reading exam than the math exam. We can see that, on average, each grade performs very similarly on each exam. This can signify a level of consistency found across all the schools, where despite each grade level becoming more difficult, students are generally seeing the same level of success throughout their time in high school. Despite this, there is still room for improvement, as found with the generally lower math scores found across all of the schools.

### Conclusion

Overall, the district has many things they can work to improve on across all 15 of their schools. Based on the trends in school types and size, there is reasonably sufficient evidence to suggest that the larger schools should work to provide more adequate studying resources to their students to work towards improving their scores. When taking into accounts the trends found in the budgets, the priority should likely be reallocating costs towards these efforts. Finally, all schools should look to see how they can improve their students' math scores.