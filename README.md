# Customer-Segmentation-Retail-Marketing
Customer segmentation project on retail marketing data. It analyzes customer demographics, purchase recency, spending behavior across multiple categories, and engagement activity to uncover distinct customer groups and provide actionable insights for targeted marketing.

# 📌 Project Overview
Customer segmentation is a key application of data analytics in marketing. By grouping customers based on their demographics, spending patterns, and engagement behavior, businesses can design more personalized and effective strategies.
In this project, we apply K-Means clustering to a retail marketing dataset to uncover distinct customer segments. The dataset includes:
- Demographics: Income, family details, education, marital status
- Recency: How recently a customer made a purchase
- Spending Behavior: Purchases across multiple categories (wine, meat, fruits, fish, sweets, gold)
- Engagement: Web, catalog, and in-store purchase activity

#  🎯 Objectives
- Identify distinct customer segments based on demographics, spending, and engagement.
- Recognize high-value customers for loyalty programs.
- Detect inactive or budget-restricted customers.
- Enable businesses to design targeted marketing campaigns.

# 🛠️ Project Workflow
1. Data Collection – Retail marketing dataset with customer demographics, income, recency, and product spendings.
2. Data Cleaning & Preprocessing – Handle missing values, scale numerical features, and encode categorical variables.
3. Exploratory Data Analysis (EDA) – Study customer behavior through univariate and bivariate analysis.
4. Feature Selection – Select relevant features like income, recency, and product categories for clustering.
5. Clustering (K-Means) – Group customers into meaningful segments.
6. Cluster Evaluation – Validate optimal clusters using silhouette score.
7. Cluster Profiling – Interpret clusters based on demographics, spending, and channels.
8. Visualization – Generate plots (boxplots, heatmaps, bar charts) for insights.
9. Insights & Strategy – Summarize findings and translate them into business recommendations.

# 🔑 Key Insights
- Income – Clear differentiation across clusters; premium segments spend significantly more across categories.
- Recency – High-value customers shop more frequently and recently compared to low-spending groups.
- Spending Behavior – Distinct product preferences:
  - Some clusters spend heavily on wines and luxury items.
  - Others are low or selective spenders, focusing on essentials.
 - Purchase Channels – Variations across web, catalog, and in-store purchases highlight preferred engagement modes.
 - Demographics (Education, Marital Status) – Subtle influence; some segments show stronger associations with higher education and family status.

# 📊 Results & Insights
- Cluster 0: Low-income, inactive shoppers
- Cluster 1: High-income, high-value loyalists
- Cluster 2: Middle-income, selective buyers
- Cluster 3: Upper-middle-class, balanced shoppers
🔹 These insights enable data-driven marketing strategies, such as:
- Rewarding loyal high-spenders
- Re-engaging inactive customers
- Offering personalized campaigns based on product preferences

# 💼 Business Recommendations
- Reward High-Value Loyalists – Create premium loyalty programs with exclusive offers to retain top spenders.
- Re-Engage Low Spenders – Target budget-conscious clusters with personalized discounts, bundles, and entry-level products.
- Cross-Sell & Upsell – Introduce balanced buyers and selective shoppers to complementary products (e.g., wine + gourmet foods).
- Channel Optimization – Focus digital campaigns on web-active customers and catalog promotions for traditional buyers.
- Personalization by Demographics – Leverage education and family insights to design tailored campaigns.

# ⚙️ Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Modeling: K-Means Clustering
- Visualization: Heatmaps, Boxplots, Bar Charts, Cluster Profiles

# 📈 Business Impact
By applying customer segmentation, businesses can:
- Improve customer engagement with segment-based marketing.
- Boost retention and loyalty among premium customers.
- Increase cross-sell/upsell opportunities by identifying product affinities.
- Optimize marketing ROI with data-driven campaign strategies.
- Build a foundation for personalized customer experiences across all channels.

# 📦 Dataset
The dataset is publicly available on Kaggle: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis
