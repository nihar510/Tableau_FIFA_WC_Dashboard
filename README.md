# Tableau_FIFA_WC_Dashboard
This Tableau dashboard explores the complete history of the FIFA World Cup, from its first tournament in 1930 through the 2022 edition in Qatar. The visualization combines tournament data, top scorers, and historical records to tell the story of football's most prestigious event.

Source: FIFA & Football Complete Dataset (1930–2022) from Kaggle

Files Used:

1. fifa_world_cup_history.csv - 22 tournament editions with winners, runners-up, hosts, and goal statistics

2. fifa_world_cup_top_scorers.csv - Top scorers of each tournament, their data and goal counts for each tournament

https://www.kaggle.com/datasets/zkskhurram/fifa-and-football-complete-dataset-19302022?select=fifa_world_cup_history.csv

-22 World Cup tournaments

-2,720 total goals scored across 964 matches

-8 different nations have won the World Cup

-Data spans 92 years of football history (1930-2022)


**Questions I Was Interested In Answering:**
1. Which countries have won the most World Cup titles and runner-up finishes?
2. How has the tournament expanded in terms of participating teams over time?
3. Who are the all-time top goal scorers across World Cup history?
4. Which countries have hosted the World Cup?

**Steps Taken to Create the Analysis:**
- Connected and joined fifa_world_cup_history and fifa_world_cup_top_scorers tables by Year
- Created calculated fields to standardize country names (Germany/West Germany)
- Built filled map for host countries using geographic data
- Designed bar charts for winning countries, runner-up countries, and top goal scorers
- Created line chart to visualize tournament expansion trends
- Added text objects and KPI cards for trivia and key statistics
- Applied dashboard actions and filters for interactivity

**My Key Takeaways:**
- Only 8 nations have ever won the World Cup, with Brazil leading at 5 titles
-Germany holds the record for most finals appearances (8) and runner-up finishes (4)
-Tournament grew from 13 teams in 1930 to 32 teams by 1998, showing global expansion
-Miroslav Klose (Germany) remains the all-time top scorer with 16 goals across 4 tournaments
-Italy and Brazil are the only nations to win back-to-back World Cups
