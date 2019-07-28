# Project-Amazon-fine-food-reviews-usin-KNNClassification
<html>
<h3>Objective:</h3>
<p>Given a text review, determine the sentiment of the review whether its positive or negative.</p>

<p>Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews.</p>
<p>Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(BOW, tfidf, Word2Vec). </p>

<h3>About Dataset</h3>
<p>The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.</p>
<ol>
<ul>Number of reviews: 568,454</ul>
<ul>Number of users: 256,059</ul>
<ul>Number of products: 74,258</ul>
<ul>Timespan: Oct 1999 - Oct 2012</ul>
<ul>Number of Attributes/Columns in data: 10</ul>
</ol>

<h3>Attribute Information:</h3>

<p>Id</p>
<p>ProductId - unique identifier for the product</p>
<p>UserId - unqiue identifier for the user</p>
<p>ProfileName</p>
<p>HelpfulnessNumerator - number of users who found the review helpful</p>
<p>HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not</p>
<p>Score - rating between 1 and 5</p>
<p>Time - timestamp for the review</p>
<p>Summary - brief summary of the review</p>
<p>Text - text of the review</p>




<h2>1. Amazon Food Reviews EDA, NLP, Text Preprocessing. </h2>
<ol>
<li>Defined Problem Statement</li>
<li>Performed Exploratory Data Analysis(EDA) on Amazon Fine Food Reviews Dataset Distplots, Histograms, etc.</li>
<li>Performed Data Cleaning & Data Preprocessing by removing unneccesary and duplicates rows and for text reviews removed html tags, punctuations, Stopwords and Stemmed the words using Porter Stemmer</li>
<li>Documented the concepts clearly</li>
<li>The cleaned data (EDA) in .sqlite can be found:https://github.com/iamrawindra/EDA-Amazon-Fine-Food-Reviews-Analysis.</li>

</ol>



<h2>2. KNN Classifier</h2>
<p>1.Applied K-Nearest Neighbour on Different Featurization of Data viz. BOW(uni-gram), tfidf, Avg-Word2Vec and tf-idf-Word2Vec.</p>
<p>2.Evaluated the test data on various performance metrics like accuracy.</p>
<h4>Conclusions:</h4>
<ol>
<ul>KNN is a very slow Algorithm takes very long time to train.</ul>
<ul>Best Accuracy is achieved by Avg Word2Vec Featurization which is of 85.87%.</ul>
<ul>Overall KNN was not that good for this dataset.</ul>
</html>
