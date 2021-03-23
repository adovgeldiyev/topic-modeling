![alt text](https://github.com/adovgeldiyev/topic-modeling/blob/main/images/sentiment.png?raw=true)
## Sentiment Analysis with Supervised learning, topic modeling with K-means and LDA
### Contents:</br>
#### 1. Data Preprocessing Phase
Cleaning with removing columns, adding new ones to get length of tweet</br>
Case Conversion: All words are converted either into lower case</br>
Stop words removal</br>
Punctuation Removal</br>
Spelling Correction</br>

#### 2. Sentiment Analysis
calculate polarity level of tweets</br>
create word cloud</br>
calculate term frequency and inverse document frequency</br>

#### 3. Classification</br>
create target variable from sentiment scores</br>
calculate term frequency</br>
Perform Logistic regression , LinearSVC, XGBoost to predict sentiment scores (3 target labels)</br>

#### 4. Clustering</br>
Implement KMeans clustering</br>
reduce components</br>
perform Gaussian Mixture</br>
get top features for each cluster</br>

#### 5. Topic Modeling with LDA</br>
Vectorize documents</br>
compute n-grams</br>
visualize number of topics</br>

Social media has become a huge part in our daily lives. It creates a connection between people and the outside world. Social media helps us to display our lives in a private, easy, and self-directed manner. People are more reliant on posts and tweets shared on social media sites such as Twitter, Instagram, and Facebook. Sentiment analysis is one of the most common research topics in the field of natural language processing nowadays, it is text mining that recognizes and extracts subjective information from source content, allowing a company to better understand the social sentiment of its brand, product, or service by analyzing online conversations (1). COVID-19, a form of coronavirus that first appeared in Wuhan, China at the end of 2019, has become one of the most widely discussed and distributed diseases in the world.</br>
![alt text](https://github.com/adovgeldiyev/topic-modeling/blob/main/images/wc.png?raw=true)
This paper deals with an extensive analysis of the sentiments emoted through the tweets since the beginning of 2020 pertaining to the novel COVID-19 using python programming language. While one dataset contains only coronavirus related tweets that have been published during the time span between March 2020 to September 2020, the other dataset contains tweets between April 2020 and May 2009. Sentiments of the tweets have been labeled and WordCloud is presented for every sentiment. Later, different topics were generated from COVID-19 tweets and visualized using pyLDAvis.</br>
The motivation of the paper lies in identifying whether a user-generated text expresses positive, negative, or neutral opinion and in classifying text data based on their topics. Supervised learning applied to classify the polarity level of tweets. To be precise Linear support vector classifier achieved 81% of accuracy on COVID-19 related tweets. Other than the above, this paper proposes topic modeling with Latent Dirichlet Allocation for multi-gram words and visualization tool for selected topics.
The paper is organized as follows: section II provides the literature review. The proposed system is introduced in section III, and finally conclusion and future work are presented in section IV.
