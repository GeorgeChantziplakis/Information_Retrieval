# Information_Retrieval
Academic Project

For this project Selenium was used to crawl some information from Google Scholar in a BFS manner. A bot was created and crawl all our information for us to navigate between the pages and the papers of the different profiles.
After that, we created an inverted index for the information we saved in our database and implemented it in a simple python Search Engine. Libraries like Natural Language Tool Kit (nltk), Regular Expressions (re), PyDictionary, and more were employed for getting more accurate results for our search engine regardless of the structure of the query a user search for.
As the last part, we had to train a subject classification model that can identify papers (mostly descriptions) and classify them into the proper category (Business, Health, etc.). Using scikit-learn we trained a Multinomial Logistic Regression algorithm that gave us 83% accuracy, a Support Vector Machines giving us only 65%, and a Naïve Bayes model that was also the best one reaching an accuracy of 93%.
The dataset was created from scratch, combining various texts from Kaggle.
