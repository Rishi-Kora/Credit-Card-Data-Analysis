# Credit-Card-Data-Analysis
Exploratory Data Analysis of Credit Customers Dataset<br>
In this repository, I have taken the Credit Card Customers data from kaggle and I have done: <br>

1. Data Loading and Initial Exploration:<br>
Loading the dataset from a CSV file located in Google Drive.<br>
Displaying initial dataset information using df.info() and descriptive statistics using df.describe().<br>

2. Data Cleaning and Preprocessing:<br>
Checking for missing values in each column using df.isnull().sum().<br>
Removing duplicate entries to ensure data integrity using df.drop_duplicates().<br>
Standardizing numerical features using StandardScaler and MinMaxScaler for better model performance and comparability.<br>

3. Outlier Detection:<br>
Detecting outliers using the Interquartile Range (IQR) method.<br>
Calculating Z-scores to identify outliers based on standard deviations from the mean.<br>

4. Data Visualization:<br>
Creating box plots using plotly.express to visualize the distribution of numerical features and identify potential outliers.<br>
Generating histograms for each numerical feature to visualize their distributions and identify skewness or other patterns.<br>

Feel free to download the code and data.
