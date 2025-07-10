# Expedia Consumer Travel Insights

## Introduction

The modern travel industry operates in an increasingly complex digital ecosystem where consumers are bombarded with sponsored content across multiple touchpoints during their journey from inspiration to booking. This research project focuses on analyzing traveler behavior patterns, crafting data-driven insights, and developing effective marketing strategies that will enhance how Expedia's travel partners engage with customers throughout their decision-making process. By understanding the nuanced ways sponsored travel content influences consumer choices at different stages of the travel planning journey, we can optimize content strategy, improve conversion rates, and create more meaningful connections between travelers and travel providers. 

The insights generated from this analysis will enable Expedia's partners to deliver more targeted, relevant, and effective sponsored content that resonates with consumers' evolving needs and preferences in an increasingly competitive marketplace.

---

## 🧠 Project Goals

- Understand how age, spending, and platform usage shape travel decisions
- Discover natural traveler segments using **KMeans clustering** and **PCA**
- Inform **targeted content strategy** based on consumer behavior
- Demonstrate a full data-to-strategy pipeline for stakeholder engagement

---

##  🔍 Key Takeaways:

This project analyzes 1,000+ synthetic survey responses to uncover how different types of travelers interact with **sponsored travel content**, and what influences their booking decisions. Using unsupervised learning and data visualization, we uncover key **behavioral segments** and strategic insights for Expedia’s marketing partners.

- **Young Frequent Explorers** (18–24, TikTok-centric) respond to short-form content, budget deals, and influencer travel hacks.
- **Millennial Mid-Spenders** (25–34, Instagram) balance value and experience, prioritizing wellness, aesthetics, and social sharing.
- **Budget-Conscious Yearly Travelers** (35–44, YouTube) plan deliberately and prefer reviews and price-sensitive tools.
- **Luxury Traditionalists** (60+, Facebook) book less often but spend more, valuing premium experiences, trust, and simplicity.

---

## 🔍 Methods & Tools

| Step               | Description                                              |
|--------------------|----------------------------------------------------------|
| **Data Generation** | Survey data generated with demographic and behavioral realism |
| **Cleaning**        | Pandas, label encoding, one-hot encoding                 |
| **EDA**             | Seaborn, Plotly, and matplotlib for data exploration     |
| **Clustering**      | KMeans, silhouette score, elbow method, PCA visualization |
| **Visualization**   | PCA scatter, heatmaps, radar plots                       |
| **Storytelling**    | Markdown summaries + executive-ready segmentation        |

---

## 📊 Summary of Findings

After evaluating different clustering strategies, the analysis revealed **4 distinct traveler personas**:

### 1. Young Frequent Explorers
- Ages 18–24, high social media usage (TikTok/Instagram)
- Budget-conscious, frequent weekend travelers
- Trust UGC and influencer content over branded ads

### 2. Millennial Mid-Spenders
- Ages 25–34, heavy Instagram + YouTube users
- Balance value and quality, prefer wellness and boutique trips
- Open to sponsored content when it feels personal

### 3. Budget-Conscious Yearly Travelers
- Ages 35–44, use Facebook and travel blogs
- Spend less but travel thoughtfully, trust peer reviews
- Prefer curated lists and price breakdowns

### 4. Luxury Traditionalists
- Ages 60+, low social media usage, prefer Google/TripAdvisor
- High spenders (>$2500), value safety, simplicity, and premium service
- Respond better to editorial content and testimonials


## 📈 Strategic Value: These insights offer a clear framework for tailoring Expedia’s sponsored content strategy:

- Match platforms and formats to each cluster’s digital behavior
- Personalize messaging around trip frequency and price sensitivity
- Align influencer partnerships and visuals to segment-specific values

---

## 📈 Marketing Recommendations

- **Platform Matching**: Tailor ad spend by persona platform use (TikTok ≠ Facebook)
- **Content Personalization**: Use UGC for younger clusters, premium storytelling for older
- **Optimize Funnel**: Create different CTA strategies by persona
- **Sponsored Content Strategy**: Test influencer vs. editorial campaigns by segment

---

## 📎 Files

- Firstly conducted Consumer and Customer Insight Research in this document: [Research Analsysis.md](https://github.com/olidare/Data-Analytics---Expedia/blob/main/Documentation/research_analysis.md)
- Created a Survey to gather more insights from consumers: [Google Forms Survey](https://docs.google.com/forms/d/e/1FAIpQLSdJvahDkJbf2xOPi-oCNghbwcIBVSq11vwM4xECfdkjktkZcg/viewform)
- DataSet: [Expedia_Consumer_Survey_Responses.csv](https://github.com/olidare/Data-Analytics---Expedia/blob/main/Expedia_Consumer_Survey_Responses.csv)
- Full Exploratory Data Analysis with clustering and PCA: [EDA_Expedia.ipynb](https://github.com/olidare/Data-Analytics---Expedia/blob/main/EDA_Expedia.ipynb)
- Business-ready version of the findings - `Presentation.pdf` TBC

  
---

## 🚀 Future Work

- Further trend analysis on the rest of the DataSet.
- Implement the recommendations and monitor the impact.
- Expand segments with more detailed surveys to further information on demographics.
- Incorporate real engagement data, Web data from Expedia Website/ App (Click Through Rates, bookings)
- Deploy a Tableau dashboard for interactive persona exploration

---

