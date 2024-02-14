# NBA Data Modelling Project

Full Narrative: https://marcelcastrolima.github.io/nba_data_1.html 

This project analyzes the influence of various NBA statistics on regular-season success. Utilizing the insights gleaned from a dialogue with the large language model, Gemini, a multivariate linear regression model was constructed using data retrieved from the NBA's public statistics API via Python. Feature engineering techniques were employed to preprocess and refine the acquired data. The model aims to predict a team's winning percentage based on the identified key statistical parameters. By interpreting the model's results and conducting an evaluation, the project intends to assess the effectiveness of the parameters suggested by Gemini in determining a team's regular season performance.

As a source for this project, I used data acquired from the NBA API Python package available at https://github.com/swar/nba_api, which provides several endpoints for NBA statistics of various sorts. The stats suggested by Gemini as good predictors of a successful regular season are summarized below.

## Offensive Efficiency

Points per game: Scoring consistently at a high-level wins games. Top contenders typically average over 110 points per game.

Field goal percentage: Converting shots efficiently maximizes opportunities. Look for teams shooting above 45% overall and 35% from three-point range.

Assist-to-turnover ratio: Moving the ball and taking care of it reduces wasted possessions and creates better scoring chances. Aim for ratios above 2.0.

## Defensive Prowess

Points allowed per game: Limiting the opponent's scoring keeps you in contention. Strong teams hold opponents below 105 points per game.

Rebounds per game: Controlling the boards limits second-chance opportunities and fuels transition offense. Look for teams grabbing over 50 rebounds per game.

## Balance and Depth

Scoring distribution: Multiple players contributing offensively prevents opponents from focusing on single-stop strategies. Balanced teams have at least 3 players averaging double-digit points.

Bench production: A reliable bench unit can provide scoring, defensive intensity, and rest for starters. Top teams see significant contributions from their reserves.

## Intangibles

Home court advantage: Winning at home is crucial for playoff seeding and momentum. Strong teams typically boast a winning home record.
