![alt text](https://github.com/sahil0094/Online-News-Popularity/blob/master/mashable1.jpg?raw=true)
# Online-News-Popularity
With the expansion of the Internet, more and more people enjoy reading and sharing online news articles. The number of shares under a news article indicates how popular the news is.  Our data comes from Mashable, a well-known online news website. We implemented different learning algorithms on the dataset, ranging from various classification technique like Logistic Regression, Decision Tree ,Random Forest & other Tree Boosted Models. Their performances are recorded and compared. Feature selection methods are used to improve performance and reduce features. LightGBM Forest turns out to be the best model for prediction, and it can achieve an auc score of 73.4% with optimal parameters.

# Objective:
We will provide recommendations to increase popularity of any article by tweaking some of the charateristics like number of words, number of images  of the article.Our work can help online news companies to improve news popularity before publishing it.

# File Descriptions:
<ul>
<li>Online News Popularity_continuous.ipynb- Taking target as discrete variable and performed count based regressions.
<li>Online_News_Popularity_Binary.ipynb- Converting target into two classes and performed binary classification
<li>Online_News_Popularity_Multiclass.ipynb- Checking possibilty of multiple classes using clustering techniques.
<li>Sample analysis.ipynb- Web scrapped one article using beautiful soup and calculated all column values for that particular article using NLP
<li>Univariate_Analysis.html- Univariate analysis using Pandas profiling library
<li>Webapp.zip -Web app made in flask to demonstrate working of model 
<li>Fnal_report.pdf - Final report describing the whole process used for the project
  
# Final Model Predictions
![alt text](https://github.com/sahil0094/Online-News-Popularity/blob/master/Images/Score.png?raw=true)

# Feature Importance (XGBOOST)
![alt text](https://github.com/sahil0094/Online-News-Popularity/blob/master/Images/Feature_imp.png?raw=true)

# Recommendations
<li>Restrict article word length to 2500 words
<li>Number of embedded links should be in range 0-25
<li>Number of images should be in range 0-10. Lesser the better
<li>Number of videos should be between 0-5. Lesser the better
<li>References to older articles which have high popularity
<li>Publish articles on weekend
<li>Focusing more on Entertainment or Lifestyle articles can get you popularity

