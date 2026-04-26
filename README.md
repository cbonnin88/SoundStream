# Strategic Growth & Behavioral Analytics for SoundStream

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD7F32?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📌 Project Overview
This project serves as a comprehensive **Product Management (PM) Case Study** focused on user retention, feature prioritization, and growth strategy for a music streaming platform. Using a dataset of **50,000 users**, I performed a deep dive into behavioral patterns to identify high-value segments and validate product hypotheses.

### The Problem
In a competitive streaming market, "growth" isn't just about new signups—it's about **retention** and **monetization**. This project aims to answer:
1. Which features correlate most strongly with long-term retention?
2. How do behavioral segments differ in their usage of the product?
3. Is our "Premium" offering providing a statistically significant improvement in user satisfaction?

---

## 🛠️ Tech Stack & Methodology
* **Data Processing:** `Polars` (Chosen for high-performance lazy evaluation and speed over Pandas).
* **Visualization:** `Plotly` (Interactive business intelligence charts).
* **Statistical Analysis:** `SciPy` (A/B testing and T-tests).
* **Machine Learning:** `Scikit-learn` (K-Means Clustering for behavioral segmentation).
* **Environment:** Google Colab.

---

## 📂 Project Structure

### Phase 1-3: Product Analytics & Visualization
**Focus:** Data integrity, North Star metrics, and roadmap prioritization.
* **Data Cleaning:** Handling schema types and validating date ranges.
* **Cohort Analysis:** Tracking retention rates by signup month to monitor "leaky bucket" issues.
* **Roadmap Analysis:** Analyzing 50,000+ "Desired Future Feature" entries to quantify market demand.
* **Forecasting:** Using 3-month moving averages to project user acquisition trends.


**Cohort Analysis**
<img width="1724" height="525" alt="Cohort Analysis" src="https://github.com/user-attachments/assets/6d2a1f49-4d74-493f-8fd7-863ffe29b887" />

**User Acquisition**
<img width="1724" height="525" alt="User Acquisition" src="https://github.com/user-attachments/assets/de93adfd-3449-4f4c-a74c-c5ea4dae6bdb" />

**Most Desired Features**
<img width="1724" height="525" alt="Desired Features" src="https://github.com/user-attachments/assets/620d36c2-bede-42b2-aba7-ef72a8bab2f3" />

**Engagement Correlation**
<img width="1724" height="525" alt="Cohort HeatMap" src="https://github.com/user-attachments/assets/9c496e63-9fea-43c1-a8af-72f54c177a6f" />





### Phase 4: Behavioral Segmentation (Machine Learning)
**Focus:** Moving beyond demographics to behavioral personas.
* Implemented **K-Means Clustering** to categorize users based on listening hours, skip rates, and playlist creation.
* **Outcome:** Identified 4 distinct personas (e.g., "Active Curators" vs. "Passive Listeners") to help the marketing team with targeted messaging.

**3D Cluster**
  <img width="1724" height="525" alt="3D Cluster Plot" src="https://github.com/user-attachments/assets/c2a9cad6-4792-4e5e-b8a1-c02f394158ca" />


### Phase 5: A/B Test Evaluation
**Focus:** Technical rigor and hypothesis testing.
* Compared **Music Suggestion Ratings** between Free and Premium tiers.
* **Outcome:** Performed an Independent T-Test to calculate P-values, ensuring that product changes are driven by statistical significance rather than noise.


**A/B Testing**
<img width="1724" height="525" alt="A:B Testing" src="https://github.com/user-attachments/assets/8426724b-ead9-47fc-bbba-31f7d20f0392" />

---

## 📊 Key Business Insights
* **The "Aha! Moment":** Users who create more than **5 playlists** in their first month show a 25% higher retention rate.
* **Roadmap Priority:** "Mood-based Auto Playlists" emerged as the #1 requested feature, outperforming "Concert Alerts" by 15%.
* **Statistically Significant Lift:** Premium users report a significantly higher satisfaction rating (p < 0.05), validating the value proposition of the paid tier.



---

## 🚀 How to Use
1.  Upload the `spotify_user_behavior_realistic_50000_rows.csv` to your Google Colab environment.
2.  Run the notebooks in order: `Analysis.ipynb` -> `ML_Segmentation.ipynb` -> `AB_Testing.ipynb`.
3.  Install dependencies:
    ```bash
    pip install polars plotly scikit-learn scipy
    ```

## 📬 Contact
**Christopher Bonnin** *Product Manager: Data and Analytics:*  [My LinkedIn profile](https://www.linkedin.com/in/christopher-bonnin-a08a95197/)
