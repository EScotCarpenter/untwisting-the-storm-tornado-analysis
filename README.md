# Untwisting the Storm: Tornado Analysis

## Introduction
This project explores the Tornadoes dataset from TidyTuesday derived from data provided by NOAA (2024) which gives detailed information about reported tornadoes in the United States between 1950 to 2022. Before the exploration of the dataset begins, a review of literature will provide a brief overview of tornadogenesis, and the history of how tornadoes are estimated and categorized into different scores on a scale based on the amount of damage done to the area of the tornado’s occurrence. The literature will also provide insight into the physical locations and the time of day that tornadoes occur. The exploration of the dataset will check the assumptions made in the review of literature and provide statistically significant results to back up those assumptions. Once the assumptions have been verified, an examination of the dataset will provide insights on locations and time of day that high F/EF-scale tornadoes occur. 

The code can be examined inside the [RMD file](Tornadoes.qmd), and the finished product can be viewed through the [rendered HTML](https://escotcarpenter.github.io/untwisting-the-storm-tornado-analysis/UntwistingTheStorm.html).

## Abstract
Changes in categorization methods have led researchers to often exclude data for tornadoes before 1973, when modern scales were introduced. How have implementations of, and changes to, categorization scales impacted how tornadoes are classified? Are current research findings regarding the timing and location of tornadoes in the United States accurate? ANOVA and Tukey HSD tests provided statistically significant results which verify that there are distinct eras in tornado classification and these eras should be examined separately. Research findings on regions prone to tornadoes were verified and the timing of high-scale (F/EF2+) tornados were examined. Of all F/EF2+ tornadoes that occurred in Tornado Alley, 71% of them occurred at night and of all F/EF2+ tornadoes that occurred in Dixie Alley, 53% occurred at night. These findings can lead to further research into the occurences of the most dangerous tornadoes and which measures should be taken to mitigate risk to human life.

## Acknowledgements
[NOAA](https://www.spc.noaa.gov/wcm/#data})

[TidyTuesday](https://github.com/rfordatascience/tidytuesday)
