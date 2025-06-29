📱 Google Play Store Apps Rating Prediction
📌 Project Overview
A full-cycle data science project that performs data cleaning, exploratory data analysis (EDA), SQL querying, and machine learning modeling to predict app ratings based on features like installs, reviews, size, and price.

📦 About the Dataset
Source: Kaggle – Google Play Store Apps Dataset

Contains metadata for 10,000+ apps including:

App name, Category, Rating, Reviews, Size, Installs, Type, Price

Content Rating, Genres, Last Updated, Current Version, Android Version

🛠️ Tools & Technologies Used
Languages: Python, SQL

Libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn

IDE: Jupyter Notebook / VS Code

Model: Random Forest Regressor

Visualization: Seaborn, Matplotlib, Plotly

Database: PostgreSQL (for SQL analysis)

🧹 Data Preprocessing
Handled missing values (dropna, fillna)

Removed duplicate rows

Converted string formats to numeric:

Reviews, Installs, Size, Price

Encoded categorical features using LabelEncoder

📊 Exploratory Data Analysis (EDA)
Distribution of App Ratings

Top 10 Categories by App Count

Free vs Paid Apps Distribution

Correlation Between Reviews and Ratings

Price Analysis of Paid Apps

Price vs Rating

Distribution of Content Ratings

Content Rating vs App Rating

Top 10 Genres by Total Installs

🤖 Machine Learning Model
Model Used: Random Forest Regressor

Features Used: Category, Reviews, Size, Installs, Type, Price, Genres, Content Rating

Train/Test Split: 70/30

Evaluation Metrics:

Mean Squared Error (MSE)

R-squared Score (R²)

📈 Results
Achieved a reliable prediction model for app ratings.

Identified key drivers of app ratings such as review count, genre, and content rating.

🏁 Conclusion
This project demonstrates a complete data science pipeline from raw data to actionable insights and machine learning predictions. It provides a powerful foundation for app developers and marketers to understand market trends and optimize their product.


Author:
Sri Abhirami J.L
