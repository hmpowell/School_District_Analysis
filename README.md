# School_District_Analysis

## Overview of the school district analysis

The goal of this project was to look at school performance within a district and present it to a school board. With the information, about performance based on budget, size, and type of school, they will be able to make decisions about future funding within the district and how it impacts math and reading scores.


## Results

- How is the district summary affected?

The school district summary was not impacted very much by the removal of the ninth grader scores from Thomas High School. The average reading score was not affected, and the average math score only decreased by 0.1. The percentage passing math was decreased by 0.2%, and the percentage passing reading decreased by 0.1%. The overall passing percentage decreased by 0.3%. None of these were very significant overall.

Before removal of scores:

![This is a picture showing the district summary before scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/mod_district_summary.png)

After removal of scores:

![This is a picture showing the district summary after scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/challenge_district_summary.png)


- How is the school summary affected?

Again, the difference was miniscule. Obviously, the only school impacted was by removing scores was Thomas High School, and it was only changed in the scores. Because the total number of students and the budget remained the same, the per student budget also remained constant. The scores only impacted the summary slightly.

Before removal of scores:

![This is a picture showing the school summary before scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/mod_school_summary.png)

After removal of scores:

![This is a picture showing the school summary after scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/challenge_school_summary.png)


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Since the scores only changed the averages and percentages slightly, Thomas High School's position within the top 5 schools was not changed. It remained in the second spot with or without the ninth grade scores. It moved closer to the third spot, but did not drop.

Before removal of scores:

![This is a picture showing the top schools before scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/top_schools_mod.png)

After removal of scores:

![This is a picture showing the top schools after scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/top_schools_challenge.png)


- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
When the math and reading scores are broken up by school, it does not affect anything, as Thomas High School 9th grad was the only one that was changed. The remaining schools retain the same averages per grade, and the other grades remain exactly the same. Upon further calculation, the averages for the total ninth grade math and reading scores dropped slightly, with the overall ninth grade math average dropping by 0.2 and the overall ninth grade reading average dropping by 0.8. Once again, this does not change anything significantly, but is referenced only for notation here.

Before removal of scores:

![This is a picture showing the ninth grade reading and math averages before scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/mod_overall_ninth_averages.png)

After removal of scores:

![This is a picture showing the ninth grade reading and math averages after scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/challenge_overall_ninth_averages.png)


  - Scores by school spending
Thomas High School was within the $630-644 per student spending bucket, so that would be the only range that had a difference; however, the difference was so small that when the data frame was formatted to be rounded, it remained exactly the same. Prior to formatting, there were only very small differences is the decimal points.

Before removal of scores:

![This is a picture showing the scores grouped by school spending before scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/mod_school_spending.png)

After removal of scores:

![This is a picture showing the scores grouped by school spending after scores were removed](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/challenge_school_spending.png)


  - Scores by school size
Thomas High School was located in the "Medium" bucket, so that would be the only size that had a change; however, once again, the difference was so small that when the data frame was formatted to include rounded numbers, it remained exactly the same.

Both before and after the removal of scores:

![This is a picture showing the scores grouped by school size](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/challenge_and_mod_school_size.png)


  - Scores by school type
Thomas High school is a "Charter" school, so that is the only type of school that would be affected by a change in scores; however, the change was, again, so small that the averages and percentages remained the same when formatted to include rounding.

Both before and after removal of scores:

![This is a picture showing the scores grouped by school type](https://github.com/hmpowell/School_District_Analysis/blob/main/Resources/mod_and_challenge_school_type.png)


## Summary

To summarize the results from the removal of all scores in the ninth grade at Thomas High School: the change was so small that the results were not altered in a significant way. The change in scores barely altered the math and reading scores in the entire ninth grade, scores grouped by school spending, scores grouped by school size, or scores grouped by school type. In presenting this to the school board, it would be obvious that excluding the ninth grade from Thomas High does not change the results of their analysis and their decision-making can continue as planned.
