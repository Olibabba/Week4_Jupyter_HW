# Week4_Jupyter_HW

## Overview

After completing an analysis for the school district, evidence was found of academic dishonesty. As such the district has requested another analysis which excludes the ninth grade of Thomas High School, in order to get a view into the scores without the suspected academic dishonesty.

## Results

#### How is the district summary affected?

Overall the removal of Thomas High Schools(THS) ninth graders had only a modest impact on the school districts. For perspective, THS ninth graders make up 461 out of 39,170 total students in the district.

![School District Summary](https://github.com/Olibabba/Week4_Jupyter_HW/blob/main/resources/district_summary.png)

The new district summary, shown above, revealed the following changes
    
- Avg math score: -.1
- Avg reading score: no change
- % Passing math: no change
- % Passing reading: no change
- % Passing overall: no change


#### How is the school summary affected?

We begin to see the impact of removing THS ninth graders when we look at THS alone. It should be noted that the summary numbers have been adjusted to account for the removal of the ninth graders.

![Per School Summary](https://github.com/Olibabba/Week4_Jupyter_HW/blob/main/resources/per_school_summary.png)

The new Per School Summary, shown above, revealed the following changes to THS
- Avg math score: -.06
- Avg reading score: +.05
- % Passing math: -.09%
- % Passing reading: -.29%
- % Passing overall: -.31%

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Even with the drop in THS's overall scores, they remained in the number two top performing spot compared to the other schools.

![Top Five Performing Schools](https://github.com/Olibabba/Week4_Jupyter_HW/blob/main/resources/top_5_perf.png)


#### How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade

The changes here are really straight forward. Both dataframes have a nan under THS's ninth grade column

- Scores by school spending

The changes to THS showed here in the $630 - $645 spending per student range, but were small enough not to show after rounding the scores and percentages

![Scores By Spending](https://github.com/Olibabba/Week4_Jupyter_HW/blob/main/resources/scores_by_spending.png)

- Scores by school size

The changes to THS showed here in the Medium (1000-1999) range, but were small enough not to show after rounding the scores and percentages.

![Scores by Size](https://github.com/Olibabba/Week4_Jupyter_HW/blob/main/resources/scores_by_size.png)

- Scores by school type

The changes to THS showed here in the charter group, but were small enough not to show after rounding the scores and percentages.

![Scores by Type](https://github.com/Olibabba/Week4_Jupyter_HW/blob/main/resources/scores_by_type.png)    

## Summary

The primary changes from replacing the THS ninth grade scores with "nan" can be seen in the decrease in scores in the district summary and per school summary.

There was one very tiny increase in the avg reading score of THS. 

These changes could only be seen when the numbers were left unformated, so these and any other changes are minute enough that they are not shown once scores and percentages are rounded.

Though I am perplexed that the avg math score of the entire district showed a change of -.1, but once I took smaller sample sizes the change could not be seen.

But that analysis is not within the scope of this analysis. And so I recommend that you hire my company to take a deep dive into the numbers to get to the bottom of this.