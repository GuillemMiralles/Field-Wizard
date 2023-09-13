# Field Wizard: Predicting Positions and Formations for Success on the Soccer Field ⚽🧐🔥

**Author: Guillem Miralles**

## Abstract 📝

The project, titled "Field Wizard: Predicting Positions and Formations for Success on the Soccer Field", represents a comprehensive exploration of football player data and match-related information with a goal to uncover insights, patterns, and predictive models in the realm of professional football. The project comprises a series of Jupyter notebooks, each focusing on specific aspects of the analysis, ranging from exploratory data analysis (EDA) to predictive modeling of football-related phenomena. 

## 1. Introduction 📣

The world of professional football is driven by data, with every player, team, and match generating a treasure trove of information. In the era of data-driven decision-making, understanding and harnessing this wealth of data can lead to significant advantages in player scouting, team strategy development, and match outcome prediction. The project seeks to leverage advanced data analysis and machine learning techniques to explore diverse facets of football-related data.

## 2. Notebooks Overview 📚

The project comprises four distinct Jupyter notebooks, each addressing specific aspects of football data analysis and modeling:

1. **PlayerPositionEDA.ipynb:** This notebook dives into the world of football player positions, conducting an in-depth exploratory data analysis. It investigates the correlations between player positions and ratings across different seasons, aiming to provide insights into the evolving landscape of football player roles.

2. **PlayerPositionPrediction.ipynb:** Building upon the insights gained from the EDA, this notebook takes on the challenge of predicting player positions based on their attributes and performance. Machine learning models are employed to create predictive models that assist clubs, coaches, and analysts in understanding the most suitable positions for players.

3. **Formations_DataFrame.ipynb:** Football matches are not just about individual player performance but also about team formations. This notebook delves into match data and player statistics to unravel the influence of team formations on match outcomes. A new dataset, "MatchAndStats.csv," is created to facilitate comprehensive analysis.

4. **FormationsOptimization.ipynb:** Winning football formations can significantly impact match outcomes. This notebook ventures into the realm of predictive modeling to identify winning team formations based on historical performance data. The application of machine learning, including linear regression and Random Forest, empowers coaches and analysts with insights into successful formations.

5. **FormationsOptimization.ipynb:** The notebook orchestrates a symphony of data analysis and modeling to predict losing team formations in football matches. Armed with a dataset brimming with match, team, and player information, it ventures into the realm of machine learning to foresee the formations of the unfortunate teams.

For detailed explanations and results, please refer to the respective notebooks linked below.

## 3. Methodology 📙

The project employs a diverse set of techniques and tools, including data preprocessing, exploratory data analysis, eature engineering, machine learning modeling and deep learning. These techniques collectively form the foundation for gaining insights and building predictive models in the domain of professional football.

## 4. Results and Findings 🔮

The results of the project are distributed across the individual notebooks but collectively offer valuable insights:

- [PlayerPositionEDA.ipynb] reveals how player positions and ratings correlate, evolving over seasons.
- [PlayerPositionPrediction.ipynb] provides predictive models for player positions, aiding in player selection and strategy.
- [Formations_DataFrame.ipynb] introduces the "MatchAndStats.csv" dataset, enabling in-depth formation analysis.
- [FormationsOptimization.ipynb] identifies winning formations, facilitating informed decisions for coaches and analysts.

## 5. Conclusion 💭

The project represents a holistic endeavor to extract actionable insights from football data. By combining exploratory data analysis, predictive modeling, and formation analysis, it contributes to the growing body of knowledge in the field of sports analytics. The project's findings hold significant potential for enhancing player performance assessment, team strategy development, and match outcome prediction in professional football.

## 6. Future Directions ⏬

While the project has provided valuable insights, there are numerous avenues for future exploration. Future research could include:

- Incorporating real-time data to enhance predictive models.
- Exploring the impact of more features on match outcomes.
- Conducting player-specific performance analysis for individual player development.


# Detailed notebooks 🔎
---
## 📊 PlayerPositionEDA.ipynb

### 🚀 Introduction:
The Jupyter notebook "PlayerPositionEDA.ipynb" is your gateway to an exciting journey through Exploratory Data Analysis (EDA) in the realm of football player positions. Dive into this adventure powered by various Python libraries as we explore and visualize data related to player ratings and positions across different seasons. Our main goal? To unravel the intricate dance between player positions and ratings, tracing their evolution over time.

### 🎯 Objective:
Our compass points us towards the comprehensive analysis of football player data, aiming to unearth hidden patterns and relationships between player positions and ratings. Some specific goals include:

- Painting vivid portraits of the most common player positions.
- Navigating the player constellation through Principal Component Analysis (PCA).
- Unveiling the player ratings' metamorphosis across seasons.
- Charting the topography of overall player ratings across different positions.

### 🛠️ Techniques:
Our toolkit consists of a diverse set of data analysis techniques and tools, including:
- Crafting data narratives and orchestrating data movements with pandas.
- Illuminating insights through data visual symphonies performed by matplotlib and seaborn, rendering captivating charts, histograms, and enchanting box plots.
- Applying the magical wand of Principal Component Analysis (PCA) to shrink data dimensions and create visual clusters.
- Weaving the rich tapestry of descriptive statistics to understand the distribution of player ratings.
- Hints of machine learning magic, such as the enigmatic Random Forest and neural networks, may be lurking beyond the provided code, waiting to reveal their secrets elsewhere in the project.

### 📈 Results:
While there's no dedicated "Results" section, the analysis unfolds like a captivating story, with results woven into visualizations and charts. Expect to unearth patterns in player clustering through PCA techniques, witness the player ratings' evolution, and grasp the symphony of overall ratings orchestrated by player positions. These discoveries hold the keys to decisions in the realm of football, like player selection and performance evaluation over time.
---

## ⚽ PlayerPositionPrediction.ipynb

### 🌟 Introduction:
The notebook is your ticket to predicting football player positions using player statistics and FIFA data. We embark on a quest to predict player positions based on their characteristics and abilities, shedding light on decisions about team lineup and strategy for football clubs, coaches, and sports analysts.

### 🏆 Objective:
Our quest's ultimate goal? Forge a machine learning model that accurately predicts football player positions using their characteristics and statistics. In this epic journey, we also seek to unveil the essential traits that shape player positions.

### 🔧 Techniques:
Our journey involves several techniques and tools:

**Data Preparation:** We gather data from player statistics and FIFA datasets, forging an alliance between information, cleaning it, and transforming it into a suitable format.

**Exploratory Data Analysis (EDA):** We embark on a voyage through player statistics, crafting visual tales to understand the relationship between features and player positions.

**Machine Learning Models:** We wield the magic of machine learning, unleashing linear regression, Random Forest, and a neural network to predict player positions.

**Model Evaluation:** We measure our models' worth through the lenses of accuracy, F1 score, and the mystique of the confusion matrix.

**Creation of New Features:** In our quest, we craft new features from original statistics to empower our model's predictive prowess.

### 🚀 Results:
Our journey has led us through data's treacherous paths, including data cleaning and feature crafting. Along the way:

- We've summoned the spirits of machine learning models, with the neural network showing its promising potential.
- We've uncovered the elusive threshold for binary predictions, guided by the F1 score.
- We've deciphered the hieroglyphs of feature importance in predicting player positions.
- Our trained model has ventured beyond known horizons, predicting player positions not found in the FIFA database, expanding its predictive power.
---

## 📈 Formations_DataFrame.ipynb

### 🌐 Introduction:
This notebook delves into the world of football match data and player statistics to uncover the secrets of team formations and player performance. Prepare for a data-driven journey filled with preprocessing, feature engineering, and captivating visualizations.

### 🎯 Objective:
Our primary objective is twofold:

- Explore how team formations influence match outcomes through the analysis of football match data and player statistics.
- Forge a new dataset that harmoniously merges match results and player statistics, providing fertile ground for in-depth exploration.

### 🔨 Techniques:
Our arsenal includes a variety of techniques and processes:

**Data Cleaning:** We cleanse and prepare football match data and player statistics, ensuring data purity and quality.

**Data Transformation:** From converting match dates into seasons to the creation of new features, our transformation magic shapes data.

**Data Visualization:** Visualizations take center stage, featuring football field diagrams with player positions and insights that illuminate the path.

**Data Merging:** Datasets unite as we merge match results with player statistics, unveiling a richer dataset.

**Feature Engineering:** The crafting of columns to represent player formations and match winners adds depth to our analysis.

### 📊 Results:
The journey culminates in the creation of a new dataset christened "MatchAndStats.csv." This dataset beckons explorers to embark on further expeditions into the intricate relationship between team formations and match outcomes.
---

## ⚽ FormationsOptimization.ipynb
### 🌠 Introduction:

This project revolves around a Jupyter notebook dedicated to analyzing and predicting football team formations using statistical and performance data. The notebook deploys an array of machine learning techniques, including linear regression, Random Forest, and a neural network, to predict winning formations in football matches.

### 🎯 Objective:

Our grand objective is to craft a machine learning model that masterfully predicts winning team formations in football matches based on historical performance data. Coaches and sports analysts eagerly anticipate the unveiling of which formations hold the key to success in various game scenarios.

### 🔧 Techniques:

Our toolkit features the following techniques and steps:

**Data Loading:** Data is summoned from a CSV file containing a treasure trove of football match information and associated statistics.

**Data Preprocessing:** Data undergoes transformations, including one-hot encoding of team formations and feature scaling.

**Oversampling:** We address the imbalances in formation classes by venturing into oversampling the minority classes.

**Machine Learning Models:**

- *Linear Regression:* A stately model for predicting winning formations.
- *Random Forest:* A mystical forest of classification trees trained to predict winning formations.
- *Neural Network:* The birth of a deep neural network powered by TensorFlow and Keras for predictions.

**Model Evaluation:** Our models undergo rigorous evaluation, including deciphering confusion matrices, accuracy metrics, and the enchantment of the F1 score.

**Results Visualization:** Our journey concludes with the unveiling of results through captivating visuals, including the display of confusion matrix plots and the mystic curves of learning.

### 📈 Results:

Behold the fruits of our journey, where the models have been conjured to predict winning formations in football matches. The performance of these models is scrutinized using metrics such as accuracy and the F1 score. Visualizations, including the unveiling of the confusion matrix's secrets, offer a deeper understanding of how predictions align with actual formations.

In summary, this notebook embarks on a machine learning odyssey to tackle a football-related challenge, providing an evaluation of the models' ability to predict winning formations based on statistical and performance data.
---

## ⚽ Formation_Evaluation.ipynb

### 🎮 Introduction:

The notebook orchestrates a symphony of data analysis and modeling to predict losing team formations in football matches. Armed with a dataset brimming with match, team, and player information, it ventures into the realm of machine learning to foresee the formations of the unfortunate teams.

### 🏴‍☠️ Objective:

The primary objective is to predict the formations of losing teams in football matches. To achieve this, the notebook calls upon the arts of data preprocessing, feature creation, and machine learning modeling.

### 🔨 Techniques Utilized:

**Data Preprocessing:** The dataset is tamed, with match dates aligned to specific seasons and data cleaned to prepare it for analysis.

**Feature Creation:** A new dataset emerges, merging match and player information. It identifies the losers in matches and extracts relevant player features.

**One-Hot Encoding:** Formations of losing teams are encoded into binary features, creating an enchanting dataset.

**Machine Learning Modeling:** Models are summoned, from neural networks to the enigmatic Random Forest, trained to predict losing team formations based on player characteristics.

**Model Evaluation:** The models face their reckoning, evaluated using precision, F1 score, and the unveiling of the confusion matrix.

### 📊 Results:

The analysis births models with the power to predict losing team formations in football matches, guided by player characteristics. Visualizations, confusion matrices, and evaluation metrics present the models' performance, signifying their efficacy in the daunting task of predicting losing formations in the world of football.
