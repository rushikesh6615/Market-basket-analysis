🛒 Market Basket Analysis using R
A data-driven project that uncovers hidden shopping patterns using Market Basket Analysis in R. By applying the Apriori algorithm, it identifies frequent item combinations and generates insightful association rules from transactional datasets. Perfect for understanding customer behavior, optimizing product placement, and boosting sales through targeted marketing.

📊 Features
📦 Reads transactional retail data

🔍 Applies the Apriori algorithm to find frequent itemsets

📈 Generates and visualizes association rules

📉 Measures rule strength using Support, Confidence, and Lift

🧠 Helps uncover buying patterns and product affinities

🛠️ Tech Stack
R – Programming language used

arules – For mining association rules

arulesViz – For rule visualization

RStudio – IDE used for development

🚀 How to Run the Project
1.Clone the repository:
git clone https://github.com/yourusername/market-basket-analysis.git
2.Open the mba_analysis.R file in RStudio.
3.Install required packages (if not already installed):
install.packages("arules")
install.packages("arulesViz")
4.Run the script:
source("mba_analysis.R")
5.Explore the rules and visualizations!

📈 Sample Output
Example Rule: {milk, bread} => {butter}

Metrics: Support = 0.07, Confidence = 0.63, Lift = 1.45

Visual outputs: Rule graphs, item frequency plots, matrix layouts

🧠 Use Cases
Retail product placement

Cross-selling strategies

E-commerce recommendation systems

Inventory optimization

