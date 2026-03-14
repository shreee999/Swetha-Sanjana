# Swetha-Sanjana
Objective 1 — The Love-Hate Divide (Easy)
Goal:
Identify games that are universally loved vs. games that divide opinion.
Measure “community agreement” — e.g., a game might have lots of reviews but split between positive and negative.
What we do:
Analyze the Positive vs Negative reviews.
Calculate a review balance metric (e.g., ratio of positive to total reviews).
Visualize with scatter plots or bar charts showing games with high/low consensus.
Insight:
Tells us which games are genuinely successful (adored) vs. just popular (many reviews but divided opinion).

Objective 2 — The Value Proposition (Easy)
Goal:
Investigate the relationship between Price and player satisfaction/playtime.
Find games that are best or worst deals for players.
What we do:
Filter numeric columns: Price, Positive, User score, Peak CCU.
Calculate a Value Index (Positive reviews per $ or playtime per $).
Visualize Price vs Satisfaction scatter plots.
Highlight top 10 best deals and worst deals using bar charts.
Insight:
Shows which games give the most “bang for your buck” and which overpromise for their price.

Objective 3 — The Market Paradox (Medium)
Goal:
Map extremes:
Games that punch above their weight (high satisfaction vs low price or low hype).
Games that underperform despite high price or hype.
What we do:
Combine metrics like Price, User Score, Positive Reviews, Value Index.
Identify extremes using scatter plots or outlier detection.
Highlight games in each quadrant: “Overperformers” vs “Underperformers”.
Insight:
Advises players where to spend their money.
Highlights hidden gems and cautionary tales.

Objective 4 — The Evolution Question (Medium)
Goal:
Study how player satisfaction changes over time and across genres.
Look for a “golden age” or trends in gaming quality.
What we do:
Convert Release Date → Release Year.
Aggregate average Positive Reviews or User Scores by year & genre.
Visualize trends with line plots or heatmaps over time.
Insight:
Reveals whether games are getting better/worse, or just different.
Shows which genres have consistently high or low satisfaction.

Objective 5 — The Satisfaction Equation (Hard)
Goal:
Build a predictive model to understand what drives positive reviews.
Identify which features (price, achievements, DLCs, ratings) influence satisfaction the most.
What we do:
Select numeric predictors like Price, Reviews, Achievements, User Score.
Handle missing values and scale features.
Train a Random Forest Regressor to predict Positive reviews.
Evaluate with R² and MSE, visualize feature importance, and plot actual vs predicted.
Insight:
Shows which factors truly matter for player satisfaction.
Reveals limits of data — some aspects of “fun” or “community love” cannot be quantified.

Objective 6 — The Market Landscape (Hard)
Goal:
Discover natural clusters or segments in the Steam ecosystem.
Understand how games are positioned: casual vs hardcore, high budget vs indie, niche vs mainstream.
What we do:
Use features like Price, Reviews, Peak CCU, Positive, Negative.
Scale features and apply K-Means or PCA for clustering.
Visualize clusters using scatter plots or 2D projections.
Insights:
Reveals market structure and player behavior patterns.
Helps developers or marketers understand competition and positioning
Label clusters meaningfully (e.g., “Indie Gems”, “Blockbuster Hits”, “Free-to-Play Niche”).
Insight:
