Data Analysis and Preprocessing Summary
This project involved performing Exploratory Data Analysis (EDA) and data preprocessing on a dataset containing Netflix TV shows and movies. The steps taken are as follows:

Data Loading: The dataset was loaded from the provided CSV file (/content/Netflix TV Shows and Movies.csv) into a pandas DataFrame for analysis.
Initial Data Exploration: The structure of the dataset was examined, including displaying the first few rows, checking data types, and reviewing descriptive statistics to understand the data's characteristics.
Missing Value Handling: Missing values in the description, age_certification, and imdb_votes columns were identified and imputed using the mode of each respective column.
Outlier Detection and Imputation: Outliers in the numerical columns (runtime, imdb_score, and imdb_votes) were visualized using box plots and identified using the Interquartile Range (IQR) method. These outliers were then imputed with the median value of each column.
Data Visualization: Various visualizations were created using seaborn to gain better insights into the data:
Count plots were generated to show the distribution of categorical variables (type and age_certification).
Box plots were used to explore the relationship between imdb_score and categorical variables (type and age_certification).
A line plot was created to visualize the trend of releases over time for both movies and TV shows.
A correlation heatmap was generated for the numerical columns (runtime, imdb_score, and imdb_votes) to show their pairwise correlations.
Cleaned Data Output: The preprocessed and cleaned DataFrame was saved to a new CSV file named cleaned_netflix_data.csv for further use or analysis.
These steps have resulted in a cleaned dataset that is ready for subsequent analysis, modeling, or visualization tasks.
