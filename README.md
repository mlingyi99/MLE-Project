📊 Data Exploration & Customer Profiling
RFM analysis is a marketing technique used to segment customers based on three key metrics: Recency, Frequency, and Monetary value. It helps businesses understand customer behavior and identify their most valuable customers. By analyzing these metrics, businesses can tailor marketing strategies and personalize offers to improve customer engagement and retention. 

Approach Overview:
  1. RFM Analysis
     Recency (R): Days since the user’s last transaction.
     Frequency (F): Number of transactions per period.
     Monetary (M): Total spend during a specified timeframe.
  2. Customer Segmentation
     Segment users based on their R, F, and M scores to uncover distinct behavioral groups (e.g., “loyal,” “at-risk,” “big spenders”).
  3. CLV / LTV Modeling
     Customer Lifetime Value (CLV or LTV): Predict future spending using historical RFM and revenue data.
     Goal: Estimate how much new users are likely to spend in the next 1–2 years.

Dataset
  Nearly one year of transaction records, including date, customer ID, and purchase amounts.

🚀 Pipeline Workflow
    1.Compute RFM scores from transaction data.
    2.Group customers into portrait segments using clustering (e.g., K‑means).
    3.Model Customer Lifetime Value:
        Aggregate historical RFM to predict future monetary contributions.
        Answer: “Based on past behavior, how much will new users spend in the next 12–24 months?”
🔍 Why This Matters
    1.Enables targeted marketing by identifying high-value or at-risk segments.
    2.Informs budgeting and acquisition strategies by estimating future revenue from new users.
    3.Provides a data-driven foundation for improving customer loyalty and retention.
