# Sentiment-analysis-on-amazon-reviews

This project showcases a comparative study between different machine learning models to perform sentiment analysis on the customer reviews of Amazon products in the Electronics category. The primary models we will look into for our analysis are Support Vector Machines, Naive Bayes Classifier, Random Forest Classifier, BERT Model, Stochastic Gradient Descent (SVM Linear) and Linear SVC models.

---

## Dataset Source
Amazon Product Reviews Dataset (2018 Updated Version)<br>
http://jmcauley.ucsd.edu/data/amazon/index_2014.html


## Running the project

The original dataset is huge and takes a lot of computational power to process. Here are some samples from the original dataset that can be used to execute the project. Make sure to download/save it to your drive, and change the URLs in the files accordingly.

- [Subset of the original dataset with 50k rows](https://drive.google.com/file/d/1EW-2ZiC2Df8PufsuNMPqIrdx6_zo29D1/view?usp=sharing)

### To run the project
Update the urls in the files and run following steps

- <b>Data cleaning</b>: Run `datacleaning.ipynb` with its dataset url pointing to the location where your dataset is stored. Modify the "CLEAN_URL" to the output file as well where the clean dataframe would be written into.
- <b>Exploratory data analysis</b>: Run `EDA.ipynb` with the url pointing to the cleaned version of the dataset from above to view the different visualisations from the dataset.
- <b>Model Building and training</b>: Inside the `models/` folder, run the `models.ipynb` to compare and train different models we build, like Support Vector Machines, Naive Bayes Classifier, Random Forest Classifier, Stochastic Gradient Descent (SVM Linear) etc, and view the accuracies and compare them. To run BERT model, run the `BERT.ipynb` with the url pointing to the cleaned dataset

