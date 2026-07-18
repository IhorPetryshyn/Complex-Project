# E-Commerce Customer & Sales Analytics Project

## 📊 Project Overview
This project focuses on analyzing e-commerce data (349,545 unique sessions over a 91-day period) to uncover insights regarding customer behavior, geographical distribution, website traffic efficiency, and subscription economics. The analysis includes comprehensive data preprocessing, statistical hypothesis testing (Shapiro-Wilk, Mann-Whitney U, Kruskal-Wallis, Chi-Square), and data visualization.

## 🔗 Interactive Dashboard
The exploratory data analysis is complemented by an interactive BI solution.
* **View the full dashboard here:** [Tableau Dashboard](https://public.tableau.com/app/profile/ihor.petryshyn/viz/Portfolio1_17817002319700/additionaldashboard?publish=yes)

---

## 🔑 Key Findings

### 1. Geography and Seasonality
* **Core Markets:** The Americas continent generates the highest overall revenue, with the USA occupying 7 out of the top 10 country-level sales spots.
* **Weekly Cycles:** Peak sales consistently occur on Tuesdays and Wednesdays, while a noticeable demand drop happens over weekends. This pattern is primarily driven by product category leaders: sofas, armchairs, and chairs.
* **Calendar Trends:** Revenue peaked significantly in December (due to the pre-Christmas shopping rush), followed by a prolonged sales slump in January.

### 2. Devices and Interfaces
* **Desktop Dominance:** Desktop devices generate ~60% of total revenue, mobile devices contribute 38%, and tablets account for just 2%.
* **Synchronized Patterns:** Sales dynamics on mobile and desktop devices mirror each other completely. Given that half of the total traffic comes from Chrome, Safari, and iPhone, optimizing mobile UX/UI is a top priority to lift smartphone conversion rates.

### 3. Marketing & Traffic Ecosystem
* **Primary Channels:** The bulk of e-commerce revenue comes from Organic Search (absolute leader in session volume), Paid Search (26.6% of revenue), and Direct visits (23.4%).
* **Channel Synergy:** A strong correlation ($r > 0.81$) was found between channels. Paid ads successfully stimulate Organic Search, which later converts into Direct traffic. 
* **Underperformer:** Social Search proved to be the least effective source for acquiring high-value users.

### 4. Subscription Economics (LTV vs. Quick Revenue)
* **Value of Subscribers:** Subscribed users generate significantly higher individual revenue (higher LTV and predictability) compared to unsubscribed ones. The top 5 countries by subscription count perfectly match the top 5 countries by revenue.
* **Strategic Balance:** Subscriptions share a moderate correlation with revenue ($r = 0.650$) and support long-term growth. Conversely, unsubscribed users are highly critical for driving immediate liquidity during major promotional events ($r = 0.918$).

---

## 💡 Strategic Recommendations

1. **Double Down on Search:** Maximize SEO support for Organic Search and optimize PPC bidding for Paid Search, as search traffic scales the platform.
2. **Mobile UX/UI Optimization:** Improve the checkout and browsing experience specifically for Safari/iPhone users to better monetize the 38% mobile traffic share.
3. **Smart Subscription Funnels:** Encourage users to subscribe immediately after their first purchase to extend LTV. Avoid putting aggressive subscription barriers for new guests to protect fast sales during holiday campaigns.
4. **Data-Driven Cross-Selling:** Bundle top-performing complementary categories (e.g., Sofas + Bookcases or Cabinets) since correlation analysis proves they are frequently bought together.

---

## 🛠️ Tech Stack & Methods Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, SciPy (stats), Matplotlib, Seaborn
* **Statistical Tests Applied:** 
  * *Shapiro-Wilk Test* (Distribution normality check)
  * *Mann-Whitney U Test* (Non-parametric comparison of two independent groups)
  * *Kruskal-Wallis Test* (Non-parametric multi-group comparison)
  * *Chi-Square Contingency Test* (Categorical proportion and conversion analysis)

##  [🔍Link to file created with SQL Query](https://drive.google.com/file/d/1qyQWUPAWv2BwibbUn_yXAD15o7Htn9YN/view?usp=sharing)
    

   
