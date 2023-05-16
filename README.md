# Capstone-Exploratory-Analysis

Capstone Project: Initial Report and Exploratory Data Analysis (EDA)

#### Executive summary

Valence is a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry). Can the target outcome, for negative or positive valence, be predicted via the features in music? This question is important because music recommendation systems are important to particular clinical populations in persons that consider music highly important.  For example, persons with dementia may benefit from positive memories that music evokes. If musical features can predict positive valence, for instance, these features can be used to recommend music that may benefit quality of life for an individual.

Regarding this data set, I first examined, cleaned, and prepared the data for further analysis. Next, I performed L1 Regularization in Logistic Regression. The resulting top feature was Danceability. Finally, I compared simple models for Logistic Regression, KNN, and Decision Trees.  The optimal model was the Decision Tree model, and I also searched optimal parameters for the Decision Tree Model. Next steps are to categorize the outcome variable, Valence, into four classes rather than two classes. More models can then be compared via accuracy scores.

#### Rationale
This question is important because music recommendation systems are important to particular clinical populations in persons that consider music highly important.  For example, persons with dementia may benefit from positive memories that music evokes. If musical features can predict positive valence, for instance, these features can be used to recommend music that may benefit quality of life for an individual.

#### Research Question
Is It Possible to Predict Valence From Musical Features, Thereby Enhancing Music Recommendation Systems?

#### Data Sources
I obtained the data set from Kaggle.com, with the web page entitled, "Music Recommendation System using Spotify Dataset".
https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/notebook#Music-Over-Time

#### Methodology
Regarding this data set, I first examined, cleaned, and prepared the data for further analysis. Next, I performed L1 Regularization in Logistic Regression. The resulting top feature was Danceability. Finally, I compared simple models for Logistic Regression, KNN, and Decision Trees.  

#### Results

My research found the optimal model was the Decision Tree model, and I also found optimal hyperparameters for the Decision Tree Model.

#### Next steps
Next steps are to categorize the outcome variable, Valence, into four classes (levels) rather than two classes. More models can then be compared via accuracy scores.

#### Outline of project

- Predicting musical valence using musical features
- L1 regularization for Logistic Regression
- Comparing Logistic Regression, KNN, and Decision Tree Models
- Optimizing hyperparameters for best performing model (Decision Tree)

- Link to notebook: https://github.com/ChristineNoelle/Capstone-Exploratory-Analysis/blob/a3a9a5f2c07bdf1a229fa8d240877b1b19369940/Capstone%20Exploratory%20Data%20Analysis.ipynb)

- Link to data set: https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/input
##### Contact and Further Information: Christine – noellecmr@yahoo.com
