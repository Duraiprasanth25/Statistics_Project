# Statistics_Project

# Atliqo Bank Project: Credit Card Launch Target Market Analysis

## Executive Summary
The Atliqo Bank project aims to identify and analyze the target market for launching a new credit card. The primary focus is on an untapped market segment, specifically customers aged 18-25, and validating assumptions using statistical analysis. This project involves data cleaning, exploratory data analysis, statistical testing, and A/B testing to derive actionable insights for targeted marketing.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Project Phases](#project-phases)
   - [Phase 1: Data Collection, Cleaning, and Analysis](#phase-1-data-collection-cleaning-and-analysis)
   - [Phase 2: Statistical Analysis and Hypothesis Testing](#phase-2-statistical-analysis-and-hypothesis-testing)
3. [Outcomes](#outcomes)
4. [Tools & Technologies Used](#tools--technologies-used)
5. [How to Use This Project](#how-to-use-this-project)
6. [Future Work](#future-work)
7. [Contributors](#contributors)
8. [License](#license)

---

## Project Phases

### Phase 1: Data Collection, Cleaning, and Analysis

#### **Datasets Used**
- `customer.csv`
- `credit_profiles.csv`
- `transaction.csv`

#### **Key Tasks**

##### **Data Cleaning**
- Processed **50,000 entries**, handling null values, duplicates, and outliers.
- Ensured data consistency and integrity for accurate analysis.

##### **Exploratory Data Analysis (EDA)**
- Conducted descriptive statistics and visualizations to understand customer behavior.
- Identified key patterns and trends in the dataset.

##### **Data Visualization**
- Visualized **customer demographics, credit profiles, and transaction patterns**.
- Used **Matplotlib** and **Seaborn** for insightful graphical representations.

##### **Feature Engineering**
- Created new features to better define the target market segment.

📌 **[View Phase 1 Notebook](https://github.com/Duraiprasanth25/Statistics_Project/blob/main/Notebooks/phase_1_atliqo_bank.ipynb)**

#### **Insights**
- Customers aged **18-25** account for **26%** of the customer base.
- Average annual income of this group is **less than $50,000**.
- Limited credit history leading to lower credit scores and credit limits.
- Credit card usage is **relatively low** in this group.
- **Top shopping categories:**
  - Electronics
  - Fashion & Apparel
  - Beauty & Personal Care

---

### Phase 2: Statistical Analysis and Hypothesis Testing

#### **Key Tasks**

##### **Statistical Measures**
- Performed **Z-tests** to validate hypotheses regarding the target market.

##### **Hypothesis Testing**
- Used the **statsmodels** library’s `ztest` function for statistical testing.

##### **A/B Testing**
- Compared performance of **old credit card (control group)** vs **new credit card (test group)**.

📌 **[View Phase 2 Notebook](https://github.com/Duraiprasanth25/Statistics_Project/blob/main/Notebooks/phase_2_atliqo_bank.ipynb)**

#### **Results**
- **Z-score**: 2.74
- **P-value**: 0.0030
- **Significance Level**: 5%
- **Z-critical**: 1.644
- **Conclusion**: Since the **Z-score (2.74) exceeds the Z-critical value (1.644)**, and the **p-value (0.0030) is less than 0.05**, the test results are statistically significant, indicating that the new credit card outperforms the old credit card.

#### **Final Insights**
- Validated the hypothesis that the **18-25 age group represents an untapped market** for credit card usage.
- Confirmed **statistically significant differences** in transaction patterns and income levels compared to other groups.

---

## Outcomes
- **Identified an untapped market segment** (age 18-25) with potential for **targeted credit card marketing**.
- **Validated assumptions** through **robust statistical analysis**.
- Provided **actionable insights** for **product design and marketing strategies**.

---

## Tools & Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn, statsmodels, scipy)
- **Jupyter Notebook** for analysis and visualization
- **SQL** for querying datasets
- **Statistical methods** (Z-tests, A/B testing)

---

## How to Use This Project
1. Clone the repository.
2. Install the required dependencies using:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scipy
   ```
3. Load the dataset and execute the Jupyter Notebook for analysis.

---

## Future Work
- Explore **machine learning models** for predicting customer credit card usage.
- Develop **personalized marketing strategies** based on behavioral insights.
- Enhance feature engineering for **better segmentation and targeting**.

---

## License
This project is licensed under the **MIT License**.


