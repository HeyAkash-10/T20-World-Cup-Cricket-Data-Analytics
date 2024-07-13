# T20 World Cup Cricket Data Analytics

## Project Overview

* This project aims to identify the top player for a T20 cricket team based on various
parameters relevant to their roles in the team. The data for this analysis was scraped
from ESPNcricinfo with a Brightdata website tool, cleaned, and transformed using pandas,
and then visualized using Power BI.

* Used the resulting Power BI dashboard to select players for various categories(Openers,
Middle Order, Finishers, Lower Order, and Fast Bowlers) for choosing the top 11 players
to play in the match.

## The selected roles and their corresponding parameters are as follows:

### Openers
- Batting Average >= 30
- Strike Rate >= 140
- Inning Batted > 3
- Boundary % >= 50
- Batting Position < 4

### Middle Order
- Batting Average >= 40
- Strike Rate >= 125
- Inning Batted > 3
- Average Balls Faced >= 20
- Batting Position > 2

### Finishers
- Batting Average > 25
- Strike Rate >= 130
- Inning Batted > 3
- Average Balls Faced > 12
- Batting Position > 4

  ### All Rounders
- Batting Average > 15
- Strike Rate >= 140
- Inning Batted > 2
- Batting Position > 4
- Innings Bowled > 2
- Bowling Economy <= 7
- Bowling Strike Rate <= 20

  ### Fast Bowlers
- Innings Bowled > 4
- Bowling Economy <= 7
- Bowling Strike Rate <= 16
- Bowling Style: Fast
- Bowling Average <= 20
- Dot Ball % >= 40


