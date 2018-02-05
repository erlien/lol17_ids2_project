# lol17_ids2_project
Course Project: Predicting NBA teams performance using Social Media attributes

What is the question you hope to answer?
How many wins will each NBA team have this season (2017-2018) and do they correlate with social media attributes (followers, activities, pageviews, etc.)?

What data are you planning to use to answer that question?
* Social Media data from 2016-2017: https://www.kaggle.com/noahgift/social-power-nba/data
- nba_2017_player_wikipedia.csv -- wikipedia pageviews
- nba_2017_real_plus_minus.csv -- NBA players stats
- nba_2017_twitter_players.csv -- twitter stats: retweets and favorites ## missing followers, tweets...

* Boxscores and games data for 2016-2017 season and beginning part of 2017-2018 for checking: https://www.kaggle.com/pablote/nba-enhanced-stats/data
- 2016-17_playerBoxScore.csv -- Player box score for 2016-2017
- 2016-17_standings.csv	-- Final standings for 2016-2017 season
- 2016-17_teamBoxScore.csv -- Team box score for 2016-2017
- 2017-18_playerBoxScore.csv -- Player box score for 2017-2018 until 2/2/2018
- 2017-18_standings.csv	-- Standings for 2017-2018 as of 2/2/2018
- 2017-18_teamBoxScore.csv -- Team box score for 2017-2018 until 2/2/2018

What do you know about the data you're using so far?
- Social Media:
  retweets: # of retweets of player's Twitter account
  favorites: # of favorites of player's Twitter account
  pageviews: # of page views of player's Wikipedia page
- Games data:
  Plus/Minus: box score-based metric for evaluating basketball players' quality and contribution to the team.
  Wins: # of wins in the season, out of 82 games

Why did you choose this topic?
I am an avid NBA fan!
Aside from a few predicatable outcomes such as the top teams in each conference, the fight for the last spots in the playoffs are always fun and exciting to follow. With blockbuster trades, offseason signings and drafts, I would like to explore how much individual players can affect the performance of their teams. Specifically their star power, with the rising use and influence of social media, measured here by followers, activities, pageviews, etc., and if there is any correlation between these factors and their teams' win/loss record.

Assumptions:
* I am starting this with the very general assumption that better players would accumulate more followers, have more social media activities and pageviews, etc. when compared to less skilled players.
* Also assuming that better players contributes more to their teams' wins.
* Assuming we are at the start of 2017-2018 season, so I can check how valid the predictions are against the games already played this season.
