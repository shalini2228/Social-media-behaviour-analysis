# Social-media-behaviour-analysis

# Twitter Behavior Analysis Project

## Table of Contents
- [Description](#description)
- [Aim](#aim)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description
This project aims to analyze social media behavior on Twitter by examining tweets related to the hashtag **#DataScience**. The analysis is performed using R and leverages the `rtweet` package for accessing Twitter data and the `tidyverse` for data manipulation and summarization. The project provides insights into user engagement, such as the number of tweets, average favorites, and average retweets per user.

## Aim
The goal of this project is to develop a program that accurately fetches and analyzes Twitter data to understand user engagement related to the #DataScience hashtag, assisting in identifying trends and key influencers in the Twitter community.

## Features
- Fetch tweets containing the hashtag #DataScience.
- Clean and preprocess the fetched data.
- Summarize user engagement statistics, including:
  - Total tweet count per user.
  - Average number of favorites per tweet.
  - Average number of retweets per tweet.

## Technologies Used
- **Programming Language**: R
- **Libraries**: `rtweet`, `tidyverse`

## Installation
1. Ensure you have R installed on your system.
2. Install the required libraries by running the following commands in your R environment:
    ```R
    install.packages("rtweet")
    install.packages("tidyverse")
    ```

## Usage
1. Set up your Twitter API credentials by replacing placeholders in the authentication section of the code.
2. Run the R script to fetch and analyze tweets:
   ```R
   source("path/to/your_script.R")
3.View the results printed in the console as a summary table showing user engagement statistics.

Results
The analysis results in a summary table displaying:

Usernames (screen_name)
Total tweet count for each user
Average favorites per tweet
Average retweets per tweet

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Inspired by various data science and social media analysis projects.
Special thanks to the contributors and mentors for their guidanc
