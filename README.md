# Mobile-Phone-Price-prediction-System
The provided Python code is a web scraping and machine learning project that extracts information about mobile phones from Flipkart's website, performs data cleaning and exploratory data analysis (EDA), and then builds a linear regression model to predict the price of a mobile phone based on its specifications.

Here is a step-by-step overview of what the code does:

1. Import necessary libraries: The code starts by importing required Python libraries such as requests, BeautifulSoup, pandas, numpy, seaborn, matplotlib, and scikit-learn.

2. Web scraping: The code uses web scraping techniques to extract information about mobile phones from the Flipkart website. It navigates through multiple pages of mobile phone listings and extracts details like product name, price, total price, offers, ratings, and descriptions for each mobile phone. The data is then stored in a DataFrame.

3. Data Cleaning: The code performs data cleaning by handling missing values, dropping duplicate rows, and extracting relevant information from the description column, such as RAM and ROM size, product brand, and product color.

4. Exploratory Data Analysis (EDA): The code uses seaborn and matplotlib libraries to create various visualizations, such as bar plots, count plots, pair plots, and histograms, to analyze the distribution and relationships between different features of the mobile phones.

5. Machine Learning Modelling: The code prepares the data for machine learning by converting categorical variables into numerical using one-hot encoding. It then splits the data into training and testing sets, creates a linear regression model, and fits it on the training data. Finally, it evaluates the model's performance on the testing data using the R-squared score.

6. User Input and Prediction: After building the linear regression model, the user is prompted to enter specifications of a mobile phone, such as RAM size, ROM size, product brand, and rating. Based on this input, the code predicts the suggested price of the mobile phone using the trained regression model.

7. Recommended Phone: The code then suggests mobile phones that match the user's budget and specifications.

Overall, this project combines web scraping, data cleaning, exploratory data analysis, and machine learning techniques to help users make informed decisions when buying a mobile phone within their budget and desired specifications.
