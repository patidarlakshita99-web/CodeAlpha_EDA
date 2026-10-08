# CodeAlpha EDA — Book Dataset

Exploratory Data Analysis (EDA) of a book dataset collected from a publicly accessible website.

## Objective

The objective of this project is to explore the dataset, identify trends and patterns, test assumptions using statistics and visualization, and detect potential data-quality issues.

## Dataset

* **Records:** 1,000 books
* **Original variables:** 6
* **Source:** Books to Scrape
* **Main information:** Book title, price, rating, availability, category, and product URL

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* VS Code
* Git & GitHub

## Analysis Performed

The following EDA steps were performed:

1. Explored the dataset structure and data types.
2. Checked dataset dimensions and column names.
3. Checked for missing values.
4. Checked for duplicate records.
5. Checked URL uniqueness.
6. Analyzed book-rating distribution.
7. Analyzed category distribution.
8. Calculated descriptive statistics for book prices.
9. Compared average prices across ratings.
10. Calculated Spearman correlation between rating and price.
11. Compared average prices across categories.
12. Detected potential price outliers using the IQR method.
13. Investigated potential data-quality issues.
14. Created visualizations to identify trends and patterns.

## Key Findings

* The dataset contains 1,000 books.
* No missing values were found.
* No duplicate records were found.
* All 1,000 product URLs are unique.
* All books were listed as "In stock".
* The average book price is approximately **£35.07**.
* The median book price is approximately **£35.98**.
* There are **50 book categories**.
* "Default" is the most common category.
* No price outliers were detected using the IQR method.
* The Spearman correlation between rating and price is approximately **0.0292**, indicating an extremely weak relationship.
* The hypothesis that higher-rated books are generally more expensive is therefore **not supported**.
* The category **"Add a comment"** appears in 67 records (6.7%) and was identified as a potential data-quality issue.
* Some categories contain very few books, so their average prices should be interpreted cautiously.

## Project Structure

```text
CodeAlpha_EDA
│
├── data
│   └── books_dataset.csv
│
├── notebooks
│   └── eda.ipynb
│
├── README.md
│
└── .gitignore
```

## Conclusion

The EDA provides an overview of book prices, ratings, categories, and availability in the dataset. Statistical analysis and visualization show that book rating has almost no relationship with price. The analysis also identified the "Add a comment" category as a potential data-quality issue that should be investigated before further analysis.
