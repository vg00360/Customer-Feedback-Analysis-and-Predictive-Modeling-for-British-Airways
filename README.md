# Customer-Feedback-Analysis-and-Predictive-Modeling-for-British-Airways
This repository contains two tasks completed as part of a data science project, involving customer feedback analysis and predictive modeling to enhance customer acquisition and satisfaction.

## Task 1: Scrape and Analyze Customer Feedback

### Objective:
Scrape and analyze customer feedback reviews for British Airways from the Skytrax website to uncover insights related to customer experiences, sentiment, and key topics.

### Approach:
1. **Data Collection**:
   - Utilized Python web scraping techniques to extract customer reviews from Skytrax specifically about British Airways.
   - Stored the data in a structured format for further analysis.
   - If you navigate to this link: [https://www.airlinequality.com/airline-reviews/british-airways] you will see this data. Now, we can use Python and BeautifulSoup to collect all the links to the reviews and then to collect the text data on each of the individual review links.

2. **Data Cleaning**:
   - Preprocessed and cleaned the review data, removing irrelevant information and handling missing values.
   - Applied text preprocessing steps like removing stopwords, special characters, and converting text to lowercase.

3. **Sentiment Analysis**:
   - Performed sentiment analysis to classify customer reviews into positive, negative, or neutral categories.
   - Leveraged pre-trained model TextBlob for sentiment classification.

4. **Topic Modeling**:
   - Used Latent Dirichlet Allocation (LDA) for topic modeling to identify key themes in customer reviews.
   - Extracted meaningful insights related to common customer sentiments and feedback.

5. **Visualization**:
   - Analyzed sentiment distribution across reviews and topics using bar charts and other graphical tools.

### Tools Used:
- Python (BeautifulSoup, pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook
- TextBlob for Sentiment Analysis
- LDA for Topic Modeling

## Task 2: Build Predictive Model for Customer Bookings

### Objective:
From customer booking data, train a predictive model to forecast whether a customer will make a booking, and evaluate the model’s performance.

### Approach:
1. **Data Exploration and Preprocessing**:
   - Explored the provided dataset to understand its structure, key features, and summary statistics.
   - Handled missing data, outliers, and performed feature engineering to create new relevant variables that could improve model performance.

2. **Modeling**:
   - Trained a Random Forest Classifier to predict whether a customer will make a booking based on the available featur

3. **Findings Presentation**:
   - Created visualizations to clearly communicate the results and model interpretation.

### Tools Used:
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook

## Conclusion:
This project demonstrates the use of data science techniques to analyze customer feedback and predict customer behavior. By leveraging data scraping, text analysis, and machine learning, insights are provided to British Airways to enhance customer satisfaction and proactively target potential bookings.
