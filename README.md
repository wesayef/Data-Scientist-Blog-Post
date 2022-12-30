# Data-Scientist-Blog-Post
Stack Overflow 2019 Survey Analysis - Data Scientist Nanodegree Project

## Overview

This project was done as part of Udacity's [Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025) coursework. In it, I explore the 2019 [Stack Overflow Developer Survey](https://insights.stackoverflow.com/survey), with the goal of getting some insight into the preferences of people who work with software - personal, work-wise, and educational.

To that end, I base my analysis on three specific questions:

*How does company size influence the job satisfaction of developers?*

*Does the age of developers influence which programming languages they know or want to learn?*

*Do people in different countries learn about software development in different ways?*



You can find the blog post related to these observations [here](https://medium.com/@wasayf88/data-analysis-of-stack-overflow-developer-survey-2019-ab56f8d2274f).

## Requirements

The CSV table used in this project may be downloaded [here](https://insights.stackoverflow.com/survey), in the link 'Download Full Data Set (CSV) under the '2019' header.

## Files

The full data exploration is contained in the notebook Stack-Overflow-Survey-Analysis.ipynb. This is carried out according to the CRISP-DM process and the data science process - gather, assess, clean, analyze, model, and visualize. Markdown cells and comments are used to clarify all the steps and answer the questions I pose to the dataset. The remaining files in this repository are:


## Libraries & Technologies Used

* Python
* Jupyter Notebook
* Libraries: matplotlib, numpy, pandas, seaborn, scipy.stats

## Results

The analysis turned up a lot of interesting findings, which are expanded on in this [Medium blog post](). The major takeaways are:

1. Self-employed developers and ones working in groups of 2-9 people report the highest relative rates of satisfaction, but the largest proportion of survey respondents who report being either 'slightly satisfied' or 'very satisfied' with their jobs work in mid-sized organizations of either 20-99 or 100-499 people.

2. Programming language use and desirability definitely vary with age. To use just a few examples, the youngest respondents are more inclined to use HTML than JavaScript, and want to learn Python more than they want to learn JavaScript. And the use and desirability of C++ and C is more pronounced the younger the respondents are.

3. The country of respondents has a subtle but noticeable impact on the way they pursue informal programming education. For example, people in the United States, United Kingdom and Germany are more likely to teach themselves new skills with no direction. Brazilians are most likely to learn from online part-time courses. And Indian respondents are most likely to participate in online coding competitions.

## Acknowledgements

My thanks, once again, to Stack Overflow and Stack Exchange, Inc. for making their yearly  developer survey public at https://insights.stackoverflow.com/survey.
