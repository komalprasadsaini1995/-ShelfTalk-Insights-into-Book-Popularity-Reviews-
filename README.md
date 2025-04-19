# -ShelfTalk-Insights-into-Book-Popularity-Reviews-
project of selftalk: insights into book popularity
📚 Book Ratings & Popularity Analysis
This project performs a comprehensive exploratory data analysis (EDA) and builds an interactive Power BI dashboard using a dataset of books. The goal is to uncover trends, understand rating behavior, and identify key insights related to authors, publishers, and book popularity.

📁 Dataset
The dataset (books.csv) includes the following key fields:

title – Book title

authors – Author(s) name

average_rating – Average user rating

ratings_count – Number of user ratings

text_reviews_count – Number of text reviews

num_pages – Number of pages

publisher – Publisher name

publication_date – Date of publication

🔍 Analysis Overview
1. Exploratory Data Analysis (EDA)
Distribution of average_rating, ratings_count, and num_pages

Correlation between num_pages and average_rating

Trends in publication_date

Visualization using histograms, box plots, and scatter plots

2. Rating & Popularity Analysis
Relationship between popularity (ratings_count) and average rating

Publisher-wise rating comparison

Trend of ratings over recent years

Correlation heatmaps and scatter plots

3. Trend Analysis
Average rating over the years

Most active publishing years

Ratings by decade using box plots

Time series line charts for publication trends

4. Author & Publisher Analysis
Top authors by average rating (minimum 3 books)

Box plots comparing publisher rating distributions

Analysis of author productivity vs. rating consistency

Scatter plots for deeper author-level insights

📊 Power BI Dashboard
An interactive Power BI dashboard was built to visualize:

Genre-wise ratings (if genre data available)

Top-rated books

Publisher performance

Publication & rating trends over time

Interactivity via slicers for year, publisher, and average_rating

📂 Project Structure
bash
Copy
Edit
├── data/
│   └── books.csv
├── notebooks/
│   └── books_analysis.ipynb
├── dashboard/
│   └── books_dashboard.pbix
├── README.md
🚀 How to Use
Python Environment
Run the Jupyter notebook to explore and analyze the dataset.

Power BI Dashboard
Open the .pbix file in Power BI Desktop to explore interactive visuals. You can also import the CSV to Power BI and follow the provided structure.

Extend the Project

Add genre classification

Predict book ratings using regression

Use NLP to analyze text reviews (if available)

📦 Requirements
Python (for EDA):

bash
Copy
Edit
pandas
matplotlib
seaborn
Power BI:

Power BI Desktop

✍️ Author
Created by [komal prasad saini]
Feel free to fork, extend, or reach out with suggestions!
