# Customer Segmentation
**Data Mining Course | Data Science MSc's**

Welcome to the repository for the ABCDEats customer segmentation project. Acting as data analysts for ABCDEats, the goal is to leverage three months of customer data to develop targeted marketing strategies that improve retention and foster stronger engagement. 

By categorizing the customer base into distinct segments based on their behaviors and preferences, this data-driven approach aims to enhance the company’s understanding of its audience, enabling more personalized services and strategic marketing decisions.

---

## Repository Structure

This repository is divided into two main sections representing the project's key delivery phases.

### Part 1: Exploratory Data Analysis (EDA)
**Notebooks used for the first delivery**

This phase establishes the foundation of our project through an in-depth exploration of the raw dataset. 
* **Data Cleaning:** Resolved missing values, duplicates, outliers, and data inconsistencies.
* **Descriptive Analysis:** Uncovered initial data distributions and basic statistics.
* **Pattern & Anomaly Detection:** Identified key trends and flagged irregular data points.
* **Relationship Mapping:** Analyzed correlations and relationships between variables.
* **Feature Engineering:** Created new meaningful variables to improve model performance in later stages.

### Part 2: Clustering Approach & Profiling
**Notebooks used for the second delivery**

Following feature selection, we split the dataset into two distinct analytical perspectives: **Customer Behavior** and **Customer Preference**.

* **Model Testing:** Experimented with various clustering algorithms on both perspectives, including:
  * K-Means
  * Hierarchical Clustering
  * Self-Organizing Maps (SOMs)
  * DBSCAN
  * Mean-Shift
  * Gaussian Mixture Model (GMM)
* **Model Selection:** Based on $R^2$ scores, **SOMs** were selected as the optimal model for both the behavior and preference segments.
* **Final Merging & Profiling:** Merged the results of the two SOMs perspectives using Hierarchical Clustering. This resulted in **4 distinct customer groups**, which were then heavily profiled to extract actionable marketing insights.

---

## Models & Techniques Used
* Exploratory Data Analysis & Feature Engineering
* Self-Organizing Maps (SOMs)
* Hierarchical Clustering
* K-Means, DBSCAN, Mean-Shift, GMM (Evaluated)
* R-squared ($R^2$) Evaluation Metric
