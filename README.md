# Chestnut Ridge Customer Segmentation – Marketing Analytics with R

##  Project Overview
This project is based on a **University of Exeter Marketing Analytics case study**.  
The task was to help **Chestnut Ridge**, a long-established U.S. apparel and lifestyle retailer, understand its **different customer segments**. The company offers a wide range of products across multiple channels and can no longer rely on a one-size-fits-all marketing strategy.  

As a marketing analyst, the goal was to:
- Identify **distinct customer segments** using survey and demographic data.
- Develop **segment profiles** based on attitudes (store attribute importance) and demographics (income, age).
- Recommend **targeting strategies** for the most attractive segments.

---

## Tools & Techniques
- **Language**: R  
- **Techniques**:  
  - Data cleaning & descriptive analysis  
  - Z-score standardization  
  - Distance calculation (Euclidean)  
  - Hierarchical clustering (Ward’s method)  
  - K-means clustering  
  - Cluster profiling & visualization  
  - GE Matrix for target segment evaluation  

---

##  Process
1. **Data Preparation**  
   - Imported `retailer.csv` dataset with 200 customer responses.  
   - Standardized store attribute ratings (1–10 scale).  

2. **Exploratory Analysis**  
   - Descriptive statistics of variables (income, age, attribute importance).  
   - Normalization to ensure comparability.  

3. **Clustering**  
   - Applied **hierarchical clustering** (Ward.D2) to visualize customer groups.  
   - Tested both **3-cluster and 4-cluster solutions** with k-means.  
   - Validated solutions with **NbClust** for optimal cluster number.  

4. **Segmentation & Profiling**  
   - Created cluster profiles showing attribute preferences, income, and age.  
   - Assigned descriptive names to segments (e.g., *Price-Conscious Families*, *Quality Seekers*).  

5. **Strategic Recommendations**  
   - Used the **GE Matrix** to select the most attractive customer segment(s) for Chestnut Ridge.  

---

## Outcomes
- Identified clear customer segments with unique needs and priorities.  
- Provided **data-driven marketing strategies** tailored to each group.  
- Showcased how **cluster analysis** supports managerial decision-making.  

---

## What I Learned
- How to implement **hierarchical and k-means clustering in R**.  
- The importance of **data standardization** for distance-based clustering.  
- How to **interpret and profile clusters** for actionable marketing insights.  
- How to bridge **quantitative analysis** with **business strategy**.  

---
## Files

- **Chestnut.Rmd:**
An R Markdown file containing the full analysis, code, outputs, and commentary. Knit this file to view the complete report.

- **Case Study Chestnut.docx:**  
Business-focused case study summary, including:
    - Target segment evaluation and selection (GE Matrix results)
    - Key insights from the cluster analysis
    - Strategic recommendations for Chestnut Ridge’s marketing approach  
  This document is ideal for stakeholders seeking actionable insights and business implications.

- **retailer.csv:**  
  The original dataset with 200 customer responses, including demographic and survey information. Used for all analysis and modeling in this project.

