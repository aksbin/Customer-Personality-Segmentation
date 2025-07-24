# Retail Customer Personality Segmentation with Machine Learning

## Business Context
Understanding customer personality and behavior is pivotal for businesses to enhance customer satisfaction and increase revenue. Segmentation based on a customer's personality, demographics, and purchasing behavior allows companies to create tailored marketing campaigns, improve customer retention, and optimize product offerings.  

A leading retail company with a rapidly growing customer base seeks to gain deeper insights into their customers' profiles. The company recognizes that understanding customer personalities, lifestyles, and purchasing habits can unlock significant opportunities for personalizing marketing strategies and creating loyalty programs. These insights can help address critical business challenges, such as improving the effectiveness of marketing campaigns, identifying high-value customer groups, and fostering long-term relationships with customers.  

With the competition intensifying in the retail space, moving away from generic strategies to more targeted and personalized approaches is essential for sustaining a competitive edge.  

## Objective
In an effort to optimize marketing efficiency and enhance customer experience, the company has embarked on a mission to identify distinct customer segments. By understanding the characteristics, preferences, and behaviors of each group, the company aims to:  
1. Develop personalized marketing campaigns to increase conversion rates.  
2. Create effective retention strategies for high-value customers.  
3. Optimize resource allocation, such as inventory management, pricing strategies, and store layouts.  


## Cluster Plot and Key Findings

After preprocessing and dimensionality reduction (PCA), we applied the KMeans algorithm and identified 2 optimal customer clusters using the elbow method.

<img width="607" height="475" alt="image" src="https://github.com/user-attachments/assets/889fe30a-70f9-4396-9b90-9333315dc6ac" />


## Cluster Profiling by Standardized Features

This bar chart shows the standardized average values of key features across the two clusters. The contrast in spending, demographics, and channel engagement makes the segmentation actionable from a business perspective.

<img width="1434" height="702" alt="image" src="https://github.com/user-attachments/assets/f18e00d0-118e-41da-908e-9f077e1104bb" />


##### **Observations:**

Cluster 0:
- Higher Income, fewer children
- Strong spend on premium categories
- Highly active across all channels - (store, web, catalog)
- Above average catalog and web purchases

*These are the premium high engagment customers*
______________
Cluster 1:
- Lower income, more children
- Below average spending across all product categories
- Less active overall, despite slightly higher web visits
- Minimal catalog and store interaction


*These are the budget-conscious lower-engagement customers and have more kids*

## **Business Recommendations**

---

### Cluster 0: Premium High Engagement Customers

**Profile:**  
High income individuals with fewer children, exhibiting high engagement across all purchasing channels and above average spending, especially on premium products like meat, wine, and gold.

**Strategic Recommendations:**

- **Loyalty Program:** Introduce a tiered loyalty program that rewards continued engagement with perks such as early access to new products, premium bundle discounts, or exclusive offers.
- **Exclusive Catalog Drops:** Leverage their strong response to catalogs by launching limited edition campaigns or seasonal collections through this channel.
- **Premium Bundling:** Offer high-margin curated bundles (e.g., gourmet meat and wine pairings) tailored to their purchasing behavior.
- **Personalized Touchpoints:** Implement "surprise and delight" strategies like personalized thank-you notes, birthday discounts, or tailored product suggestions.
- **Retention Monitoring:** Track engagement levels and proactively re-engage users showing signs of reduced activity (e.g., fewer catalog orders or web visits).

>  *These are your high-value customers. Your primary goal should be retention and upsell through premium, personalized experiences.*

---

### Cluster 1: Budget-Conscious, Low Engagement Customers

**Profile:**  
Lower-income households with more children, primarily interacting through the website. They show lower overall spend and limited engagement with store or catalog channels.

**Strategic Recommendations:**

- **Value Bundles:** Introduce family-friendly bundles and budget-conscious product packs that appeal to households with tighter budgets.
- **Digital First Engagement:** Focus marketing efforts on digital channels (email, mobile push) instead of catalogs. This aligns with their behavior and keeps costs low.
- **Website Optimization:** Simplify the user experience, especially on mobile. Highlight value deals and bundles directly on the homepage or cart page.
- **Discounts:** Offer simple, well-timed discounts to encourage purchases, especially during cart abandonment or on high-traffic pages.
- **Referral Program:** Launch a “refer-a-friend” program with incentives, this segment is likely to respond well to small, high-perceived-value rewards.

> *Focus on increasing engagement through affordability, convenience, and family-oriented messaging. Efficiency and scalability matter here.*

---



