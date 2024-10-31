# GitHub User Data in Delhi

- Collected GitHub profiles and repositories for users in Delhi with over 100 followers through GitHub API, processed for clean and structured storage.
- Found that JavaScript and Python were the most commonly used languages, highlighting these as trending in the Delhi tech community.
- Developers can gain more visibility by focusing on popular languages and maintaining active repositories with clear licenses.

## Overview
This project uses the GitHub REST API to gather and analyze data on GitHub users with high follower counts in Delhi. It provides insights into tech stacks, license preferences, and popular repositories.

## Data Files
- `users.csv`: Contains user information including bio, company, location, and follower count.
- `repositories.csv`: Lists public repositories of users with fields such as language, stargazer count, and license type.

## Usage
1. Clone this repository.
2. Load the CSV files for analysis, or inspect them directly to explore developer trends in Delhi.

### Analysis
This analysis offers a snapshot of technology preferences among top-followed GitHub users in Delhi, providing valuable insights for developers and recruiters.

##########Facts Found
1.Leader Strength Metric:

A unique metric we introduced, called leader strength (followers / (1 + following)), shows that users with a higher follower-to-following ratio tend to have better "influence" in terms of followers. Our analysis of the top 5 users by leader strength could indicate users who have a strong influence relative to their level of engagement with others.
Hireable Users’ Following Behavior:

2.On average, hireable users follow more people than non-hireable users. This could reflect a networking-oriented behavior, where hireable individuals actively engage with a wider audience or maintain a higher number of connections.
Programming Language Diversity in Repositories:

3.We observed a wide variety of programming languages across repositories, with some languages showing higher follower counts. This diversity highlights the range of expertise and potential collaboration opportunities within different language communities on GitHub.
Repository Features and Licensing:

A significant number of repositories have wikis and projects enabled, showing a trend toward more documentation and project management. 
