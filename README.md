# Quantium-Virtual-Internship-Task-1
Overview This project replicates the Quantium Data Analytics Virtual Internship Task 1 using Python. The goal is to analyze chip purchases, clean the dataset, explore trends, and generate actionable insights for customer segmentation.
 Steps Followed
1. Data Cleaning
- Converted DATE column from Excel integers to proper calendar dates.
- Removed salsa products (focus only on chips).
- Filtered out outlier customers (200‑pack transactions).
- Extracted PACK_SIZE and BRAND features.
- Standardized brand names for consistency.
2. Exploratory Data Analysis (EDA)
- Pack size distribution → 175g packs dominate.
- Top brands → Doritos, Smiths, Twisties lead.
- Sales over time → Seasonal spikes in December.
3. Merge with Customer Data
- Joined transactions with QVI_purchase_behaviour on LYLTY_CARD_NBR.
- Added LIFESTAGE and PREMIUM_CUSTOMER segments.
4. Segment Analysis
- Sales by segment → Mainstream Young Singles/Couples and Budget Older Families drive the most sales.
- Units per customer → Some segments buy more packs per trip.
- Average price per unit → Premium customers pay less per unit (larger packs).
5. Statistical Testing
- Ran Welch’s t‑test comparing Premium vs Mainstream customers.
- Result: Premium customers significantly pay less per unit (p‑value ≈ 0).

 Insights
- 175g packs are the most popular size.
- Doritos and Smiths dominate brand preference.
- December sales spike shows strong holiday demand.
- Mainstream Young Singles/Couples are a high‑value segment.
- Premium customers prefer larger packs, lowering their per‑unit spend.

 Recommendations
- Target promotions at Mainstream Young Singles/Couples.
- Stock larger packs for Premium customers.
- Plan inventory around December spikes.
- Push Doritos and Smiths in mainstream channels, while offering variety packs for Premium customers.

 Tech Stack
- Python: pandas, seaborn, matplotlib, scipy
- Data: QVI transaction + customer purchase behaviour datasets


