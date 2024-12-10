## Customer Behavior Analysis and Segmentation

### Overview
This project analyzes customer data and segments it into different groups based on factors such as income, age, spending behavior, family size, and work experience. The goal is to help businesses understand customer behavior and effectively target the right customer segments.

### Project Structure
- *Data Preprocessing*: The raw customer data is cleaned and processed, handling missing values and extracting key features.
- *Feature Engineering*: New features are created, such as income group, age group, spending behavior, etc.
- *Data Analysis*: The data is analyzed, and insights are derived using various visualizations.
- *Clustering*: K-Means clustering is used to group customers based on their characteristics.

### Questions Solved through Visualizations
1. *What is the Gender Distribution of Customers?*
   - Gender distribution is visualized using a pie chart to understand the proportion of male and female customers.

2. *What is the Spending Behavior Across Age Groups?*
   - A bar plot shows the average spending behavior (spending score) across different age groups.

3. *What is the Income Distribution Across Age Groups?*
   - A boxplot visualizes the income distribution across various age groups, helping identify patterns.

4. *What is the Spending Behavior Across Family Size Groups?*
   - A boxplot compares spending behavior across different family size groups.

5. *Which Profession Spends the Most?*
   - A bar plot shows the average spending score for each profession.

6. *Which Cluster (Segment) has the Highest Average Spending Score?*
   - Using K-Means clustering, this analysis visualizes the spending score across different customer clusters.

7. *Is there a Relationship Between Income and Spending Score?*
   - A scatter plot visualizes the relationship between income and spending score, with clusters color-coded for better understanding.

8. *What is the Distribution of Customers Across Clusters?*
   - A count plot shows the distribution of customers in each cluster, highlighting the segment sizes.

9. *What is the Income and Spending Behavior for Each Cluster?*
   - A bar plot compares the average income and spending score for each cluster.

10. *What is the Distribution of Work Experience Across Clusters?*
   - A count plot shows how work experience is distributed across different clusters.

### Installation
To run this project, you need to install the following:
- Python 3.11.7
- Required libraries: pandas, seaborn, matplotlib, scikit-learn

You can install these libraries using pip:
bash
pip install pandas seaborn matplotlib scikit-learn


### Key Insights
- *Customer Segmentation*: Using K-Means clustering, customers are segmented based on their income, age, spending score, and family size.
- *Visualization*: Seaborn and matplotlib are used to visualize the data, making it easier to understand customer behavior and segmentation.
- *Analysis*: This analysis helps businesses better understand their customers and improve marketing strategies.

---
