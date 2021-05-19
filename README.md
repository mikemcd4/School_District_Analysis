# School District Analysis

## Overview

An analysis of 15 different school's math and reading scores based off grade level was conducted using Python in Jupyter Notebook. The purpose of this analysis was to visualize the overall success of each school, and to try and correlate spending allocations to performance. During the analysis, it was discovered that the 9th grade testing scores for Thomas High School were invalid, so a second analysis was performed that removed them from the overall analysis to keep the end result accurate.

## Results

![School_summary_2](https://user-images.githubusercontent.com/77767984/118750962-21c8ae00-b826-11eb-91d5-c5754c429a5e.png)

As seen from the screenshot above, the overall results for the district summary were not significantly effected by the removal of the 461 ninth graders at Thomas High School, due to the original total number of students in the district being 39,170.

The effect on the overall analysis may have been insignificant, but the effect it had on Thomas High School's individual statistics was quite noticeable. Pictured below is the first school summary, prior to the removal of the 9th Grades' invalid test scores.

![school_summary](https://user-images.githubusercontent.com/77767984/118751717-6d2f8c00-b827-11eb-9bd8-f8f9ef2d69b3.png)

Now, take a look at Thomas High School's summary after the 9th grade results are removed.

![school_summary_3](https://user-images.githubusercontent.com/77767984/118751834-a1a34800-b827-11eb-964b-8077e1af20d7.png)

It appears that the ninth grade results heavily impacted the school summary scores in a negative way, showing that many ninth graders did not meet the passing criteria of 70% or higher. 

Additionally, replacing the ninth graders' math and reading scores increased Thomas High School's overall performance, placing them in the number 2 spot for top five schools.

![school_summary_4](https://user-images.githubusercontent.com/77767984/118753196-11b2cd80-b82a-11eb-8e1d-5fd24517c357.png)

However, replacing the ninth-grade scores did not affect the math and reading scores by grade, due to them not affecting grade levels outside of its own.

Similarly, the school spending wasn't affected significantly. In terms of scores by school size, medium sized schools such as Thomas High School (1,635 students) would be slightly positvely affected, due to Thomas High's passing percentages increasing after replacing the ninth grade scores. With school types, we can infer that charter schools saw a slight increase in their overall passing percentages, due to Thomas High School being classified as a charter school.

## Summary

From our analysis, we can confirm the following 4 changes.

  1. The overall passing percentage for Thomas High School increased significantly when the ninth grade scores were removed
  2. The Reading Average had an increase from 83.85 to 83.90
  3. The passing percentages for the district as a whole saw an increase when the ninth graders were removed
  4. The Reading Percent Passed had a decrease from 97.31 to 97.02
