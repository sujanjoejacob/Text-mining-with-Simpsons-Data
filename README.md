# Text-mining-with-Simpsons-Data
This dataset contains the characters, locations, episode details, and script lines for approximately 600 Simpsons episodes, dating back to 1989.

1 Introduction
This dataset contains the characters, locations, episode details, and script lines for approximately 600 Simpsons episodes, dating back to 1989.

2 Ten Most Active Characters
We want to find out which characters have spoken the most in the episodes. Here the top Ten are being displayed.

3 Next Ten Most Active Characters
Here the next 10 active characters are being displayed. Their ranking is from the 11th position to the 20th position.

4 Top Twenty most Common Words
We examine the Top Twenty Most Common words and show them in a bar graph.

4.1 WordCloud of the Common Words
A word cloud is a graphical representation of frequently used words in the Normalized text.

5 Parts of Speech
We use the Parts of Speech dataset to have a glimpse of the different Parts of Speech available.

6 TF-IDF
TF-IDF computes a weight which represents the importance of a term inside a document.

6.1 The Math
TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document)
IDF(t) = log_e(Total number of documents / Number of documents with term t in it).
Value = TF * IDF

6.2 Twenty Most Important words for the Twenty Most Active Characters
Here using TF-IDF , we investigate the Twenty Most Important words for the Twenty Most Active Characters.

6.3 Marge Important Words
We investigate here the most important words spoken by Marge.The conversations of Marge with the word homie is provided below. We observe that all of it is addressed to her husband Homer .

6.4.1 Word focus - “Midge”

7 Relationship among words
Til now, we have explored the most important words for a character. Now, we will explore the relationship between words.

7.1 Dont word network graph

8 Sentiment Analysis

8.1 Postive Characters and Not so Positive Characters
We will use the AFINN sentiment lexicon, which provides numeric positivity scores for each word, and visualize it with a bar plot.We limit the sentiment analysis to the Top 20 characters who have spoken the most in the episodes.

8.2 Postive and Not So Postive Words

8.3 Postive and Not So Postive Script Lines

9 Topic Modelling

10 Location of Characters

10.1 Homers Location

10.2 Marge’s Location

10.3 Bart’s Location

10.4 Lisa’s Location

11 Homer Simpson

11.1 Word Cloud

11.2 Postive and Not So Postive Words of Homer Simpson

11.3 Sentiment Analysis based on location

12 Best and the Worst Episodes

12.1 Best Episode
###### [1] 0.8309179 is the sentiment score for the Best Episode

12.2 Worst Episode
###### [1] 0.4871795 is the sentiment score for the Worst Episode

12.3 Positive and Not So Positive Characters of the Best Episode

12.4 Positive and Not So Positive Characters of the Worst Episode

12.5 Postive and Not So Postive Words of Best Episode

12.6 Postive and Not So Postive Words of Worst Episode

13 Modelling with XGBoost
We try to predict whether the ScriptLines are spoken by Homer or not
We do Cross Validation using Caret package.

Inspiration and credit for gathering the data goes to Todd Schneider: https://github.com/toddwschneider/flim-springfield
