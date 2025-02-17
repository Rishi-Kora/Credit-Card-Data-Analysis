# Credit-Card-Data-Analysis
Exploratory Data Analysis of Credit Customers Dataset<br>
In this repository, I have taken the Credit Card Customers data from kaggle and I have done: <br>

1. Data Loading and Initial Exploration:
Loading the dataset from a CSV file located in Google Drive.
Displaying initial dataset information using df.info() and descriptive statistics using df.describe().<br>

2. Data Cleaning and Preprocessing:
Checking for missing values in each column using df.isnull().sum().
Removing duplicate entries to ensure data integrity using df.drop_duplicates().
Standardizing numerical features using StandardScaler and MinMaxScaler for better model performance and comparability.<br>

3. Outlier Detection:
Detecting outliers using the Interquartile Range (IQR) method.
Calculating Z-scores to identify outliers based on standard deviations from the mean.<br>

4. Data Visualization:
Creating box plots using plotly.express to visualize the distribution of numerical features and identify potential outliers.
Generating histograms for each numerical feature to visualize their distributions and identify skewness or other patterns.<br>

Feel free to download the code and data.
