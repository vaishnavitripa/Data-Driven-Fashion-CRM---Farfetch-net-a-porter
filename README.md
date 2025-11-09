# ***Data-Driven Fashion CRM: Predicting Churn & Building Customer Retention Strategies***

## ***Project Overview***


*This project explores how luxury fashion e-commerce platforms like Farfetch and Net-a-Porter can predict and reduce customer churn using real product data, synthetic sales behavior, and sentiment analysis.
By integrating product-level insights (fabric, price, style) with customer engagement data, the project aims to help brands retain high-value customers and improve mid-range buyer conversion.*


## **🚀Business Problem**

Luxury fashion retailers face:
- High customer acquisition costs.
- Low repeat purchase rates.
- Frequent churn among “aspirational” mid-value buyers.


 *The challenge:*
Identify which factors — product characteristics, sentiment, or customer behavior — most strongly predict churn and how to act on them.

## **🧩 Objectives**

- Analyze product mix and pricing across major luxury brands.
- Segment customers using RFM (Recency, Frequency, Monetary) modeling.
- Predict churn based on sentiment, product engagement, and pricing behavior.
- Visualize insights in a Tableau CRM-style dashboard to guide business strategy.
  

## **🛠️ Tools & Technologies**


    - Category                   -            Tools 
    - Data Extraction            -            Python, BeautifulSoup, Selenium.
    - Data Analysis	             -            Pandas, NumPy, Scikit-learn.
    - Visualization	             -            Tableau, Matplotlib, Seaborn.
    - Data Management            -            Excel.
    - Reporting                  -            PowerPoint.


## **🗂️ Dataset**
1. Product Data (Real)

     Scraped from Farfetch & Net-a-Porter (FW25 collections).
  Attributes: brand, product category, price, fabric, print, color, and season.


3. Sales & Sentiment Data (Simulated)
   
    Simulated transactional and review data to represent purchase frequency, review sentiment, and churn behavior.



## **🔍 Exploratory Data Analysis (EDA)**

Key Insights:
  - Most luxury items are priced between $500–$2,000.
  - Knitwear and Dresses dominate this range — core seasonal categories.
  - Polyester & Cotton appear most often due to versatility and cost balance.
  - Solid prints outperform other styles, aligning with “quiet luxury” trends.


## **📈 Predictive Modeling**


🔹 RFM Segmentation

   High RFM scores: Runway & exclusive pieces (e.g., silk or leather) → loyal, low-churn customers.

   Low RFM scores: Older listings and low review count → risk of churn.
   
🔹 Churn Prototype Model

   Behavioral churn > brand-based churn.
   
   Mid-value customers (aspirational buyers) show highest churn risk.
   
   Prada & Miu Miu have strong sales but higher churn → price sensitivity and exploration patterns.
   
🔹 Sentiment Insights

   Positive sentiment drives retention more than brand prestige.
   
   Neutral or mixed reviews often precede churn → early signal for re-engagement.

## **💡 Business Impact**


    - Insight	                                  -        Business Value
    - Identify at-risk customer segments	      -        Enables early retention campaigns
    - Map churn probability to product types	  -        Guides assortment and pricing
    - Link sentiment to retention	              -        Supports personalized communication
    - Visual dashboards	                          -        Assist marketing teams with real-time insights
    
“By merging product intelligence with customer behavior analytics, this project bridges fashion creativity and data strategy — turning churn into an opportunity for stronger customer relationships.”

## **🖥️ Visualization**

Tableau Dashboard Includes:

  - Churn segmentation by price and sentiment
  - RFM heatmap by product category
  - Revenue-at-risk by brand.
    
      (Tableau Public link here - https://public.tableau.com/app/profile/vaishnavi.tripathi1427/vizzes)

 ## **🚀 Results Summary**
   - Identified mid-value customers as highest churn group.
   - Predicted churn risk with behavioral indicators (RFM + sentiment).
   - Developed actionable framework for retention & pricing optimization.
  
    
