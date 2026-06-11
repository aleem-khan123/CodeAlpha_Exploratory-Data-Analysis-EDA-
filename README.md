# Netflix Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

The objective of this project is to perform Exploratory Data Analysis (EDA) on a Netflix dataset to understand content distribution, identify trends, analyze ratings and genres, and extract meaningful insights through data-driven analysis.

The project demonstrates the complete data analysis workflow including data understanding, data cleaning, statistical analysis, visualization, and reporting.

---

## Project Objectives

* Understand the structure and characteristics of the dataset.
* Identify and handle missing values.
* Perform data cleaning and preprocessing.
* Conduct statistical analysis to uncover patterns and trends.
* Create meaningful visualizations for better understanding.
* Generate actionable insights and recommendations.

---

## Dataset Information

### Dataset Details

| Attribute      | Value                       |
| -------------- | --------------------------- |
| Total Records  | 200                         |
| Total Features | 12                          |
| Dataset Type   | Netflix Movies and TV Shows |
| Analysis Tool  | Python                      |

### Features Included

* show_id
* type
* title
* director
* cast
* country
* date_added
* release_year
* rating
* duration
* listed_in
* description

---

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* GitHub

---

## Data Cleaning Process

The following data quality issues were identified and addressed:

### Missing Values Before Cleaning

| Column   | Missing Values |
| -------- | -------------- |
| country  | 64             |
| director | 63             |
| cast     | 20             |

### Cleaning Actions Performed

* Handled missing values in country column.
* Replaced missing director values with "Unknown".
* Processed missing cast values.
* Verified dataset consistency.
* Checked duplicate records.

### Data Quality Results

* Duplicate Records Found: 0
* Missing Values After Cleaning: 0

The dataset was successfully cleaned and prepared for analysis.

---

## Exploratory Data Analysis

### Content Type Distribution

| Type     | Count | Percentage |
| -------- | ----- | ---------- |
| Movies   | 127   | 63.5%      |
| TV Shows | 73    | 36.5%      |

### Rating Distribution

Most Common Ratings:

| Rating | Count |
| ------ | ----- |
| TV-MA  | 50    |
| TV-14  | 34    |
| PG-13  | 28    |
| R      | 23    |
| TV-PG  | 22    |

### Release Year Analysis

* Earliest Release Year: 1961
* Latest Release Year: 2021
* Most Frequent Release Year: 2021 (78 titles)

### Top Director

| Director          | Count |
| ----------------- | ----- |
| Toshiya Shinohara | 4     |

### Top Country

| Country       | Titles |
| ------------- | ------ |
| United States | 50     |

### Top Genre

| Genre                                                    | Count |
| -------------------------------------------------------- | ----- |
| Action & Adventure, Anime Features, International Movies | 12    |

---

## Visualizations Included

The project contains the following visualizations:

1. Movies vs TV Shows Distribution
2. Top 10 Content Producing Countries
3. Content Ratings Distribution
4. Top 10 Genres
5. Release Year Trend

---

## Key Findings

* Movies represent the majority of content on Netflix, accounting for 63.5% of the dataset.
* The United States is the leading content-producing country.
* TV-MA is the most common content rating, indicating a strong focus on mature audiences.
* Action & Adventure and International content are among the most popular genres.
* Content production increased significantly in recent years, with 2021 showing the highest number of releases.
* Toshiya Shinohara is the most frequently appearing director in the dataset.

---

## Recommendations

* Continue investing in movie content due to its dominant presence.
* Expand content production partnerships across additional countries.
* Increase genre diversity to reach broader audience segments.
* Analyze audience engagement with TV-MA content to guide future content planning.
* Monitor emerging content trends for strategic decision-making.

---

## Repository Structure

```text
CodeAlpha_EDA
│
├── Netflix_Original.csv
├── Netflix_Cleaned.csv
├── Task-01(Code Alpha).ipynb
├── Task 1 Report.pdf
├── Movies vs TV Shows.png
├── Top 10 Content Producing Countries.png
├── Content Ratings Distribution.png
├── Top 10 Genres.png
├── Release Year Trend.png
└── README.md
```

---

## Conclusion

This project successfully applied Exploratory Data Analysis techniques to a Netflix dataset and transformed raw data into meaningful insights. Through data cleaning, statistical analysis, and visualization, important trends regarding content type, ratings, genres, directors, release years, and countries of production were identified.

The project highlights the importance of EDA in understanding datasets and supporting data-driven decision-making.

---

## Author

**Aleem Shoukat**

Data Analytics Intern | Aspiring Data Analyst | BS Computer Science Student

### Contact Information

Email: [aleemshoukat91@gmail.com](mailto:aleemshoukat91@gmail.com)

LinkedIn: https://www.linkedin.com/in/aleem-shoukat-9bb3b6356/

GitHub: Add your GitHub profile link here:https://github.com/aleem-khan123

