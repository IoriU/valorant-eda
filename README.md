# Valorant Match Dataset Exploration and Insight
This project is an exploration of the Valorant match dataset, with the goal of finding insights into the game. The project includes two main components:

Exploration: This component focuses on discovering insights within the data.
Classification: This component classifies the agent used by each player in a game.
Regression: This component predicts the average ACS score for each team in a game.

## Results
The results of the project are as follows:
- Some agents have experienced increased or decreased popularity among players between major patch. These changes are likely due to buffs and nerfs that make some agents more powerful than others. Additionally, new characters are not guaranteed to be popular upon release.
- On average, duelist agents have higher ACS scores than other roles. This is also true on each map, where Raze as duelist having the highest average ACS score. This trend is likely attributed to how ACS is calculated in Valorant, taking into account both damage inflicted and kills. Given that duelist agents are specialized in these areas, this finding is not surprising.
- The most common winning team composition consists of two duelists, a sentinel, a controller, and an initiator. The most commonly used agents in winning teams include Jett and Sova.
- Classification: The classification model achieves a micro F1-score of 72%.
- Regression: The regression model achieves an R-squared of 0.91.

## Conclusion
This project showcases the utilization of pandas and machine learning to explore and extract insights from the Valorant match dataset. The classification and regression models developed in this project can be used to predict the agent used by each player in a game and the average ACS score for each team in a game.

## Further work
- Use new feature engineering to improve metric score.
- Develop new models, such as models to predict the winner of a game or the outcome of a round.
- Explore the use of clustering methods for data analysis.