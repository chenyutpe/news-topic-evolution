# An Observation on Topic Evolution of News with Word Clouds

By collecting the words used in news media through the time, we try to observe the topic evolution.

## Overview
In this repository, we scrap the data from [***Today's Paper - The New York Times***](https://www.nytimes.com/section/todayspaper), and make word clouds to observe the result.

You can either use our code to do all the job, or use your own data and make the word clouds.

We seperate the data from the front page and others, analysis the differences as well.

*P.S. News before 2006/04/01 is unavailable*

## Usage

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chenyutpe/news-topic-evolution/blob/main/scrapping_and_wordclouds.ipynb)

We provide 2 main settings for you to adjust (you can find them at the top of the notebook)

- Start and End date of the news to collect
- Time Scale to group the data by

Run All, or Run from the Data Exploration block if you have prepared the data.

## Future Plans

- Add more news websites to choose from
- More analysis on the data
- Useful applications
- Fix the problem that some special words will be split by the word cloud