## Responsibilism
Codes associated with the Responsibilism project.

Zhang, J., Liao, T., Oishi, S. & Talhelm, T. Responsibilism Predicts Happiness Better Than Warm Fuzzy Collectivism: A Text Analysis of Reddit Posts Across U.S. States.

### Figure 1. Constructing a State-Level Collectivism Index Using Reddit Data
![alt text](workflow.jpeg)

## Code
The code contains the following parts which readers may run to reproduce our findings.
1. Train_Word2Vec.ipynb - Scrape each US states' subreddit using Convokit and train separate a separate Word2Vec model for each state.
2. Construct_Dimensions.ipynb - Construct state-level collectivism index.
3. Construct_Dataframe.ipynb - Link index to other state-level covariates.
4. Regression.ipynb - Test convergent validity of index and use index to predict state-level happiness.

## External Data & Packages
* Convokit - scrape subreddits.
* Gensim Word2vec (Rehurek & Sojka, 2011) - Train word embedding models
* roBERTa, VADER, Evaluative Lexicon (Rocklage et al., 2017) - Sentiment analysis on each state.
* Gallup Wellbeing Index - Convergent validity for sentiment scores.
* Vandello Cohen Collectivism Index (Vandello & Cohen, 1999) - Convergent validity for our collectivism index.

