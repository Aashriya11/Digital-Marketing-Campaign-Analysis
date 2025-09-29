# Digital-Marketing-Campaign-Analysis
**✨ Turning Campaign Chaos into Clarity ✨**

This dashboard analyzes digital marketing campaigns, providing insights on performance, reach, engagement, conversions, and ROI. It helps identify high-performing campaigns, audience trends, and regional effectiveness, enabling data-driven decisions to optimize marketing strategies.

---

## 1. Introduction

The project analyzes digital marketing campaigns to evaluate performance, audience reach, and overall effectiveness. Using campaign data, two interactive dashboards were developed to provide actionable insights.

**Dashboard 1** : Lead Generation Analysis
Focuses on leads generated, conversion rates, and cost-effectiveness.

**Dashboard 2** : Region-Based Analysis
Provides geographical insights into campaign performance, enabling targeted improvements.

These dashboards transform raw campaign data into clear visual insights, empowering stakeholders to optimize marketing investments and maximize ROI.

![image alt](https://github.com/Aashriya11/Digital-Marketing-Campaign-Analysis/blob/b6892cf8cc35e40e7c9a8dc0df5730468647488b/Dashboard.png)

---

## 2. Data Pre-processing Process 
To ensure accuracy and consistency in the Digital Marketing Data Analysis project, the 
following preprocessing steps were carried out: 
 
#### 1. Handling Missing Values – 
All blanks in numerical columns (such as impressions, clicks, 
conversions, and costs) were replaced with 0, preventing errors in calculations and ensuring 
reliable aggregations. 

#### 2. Data Modelling – 
Separate dimension tables (e.g., Campaign, Date, Region, and Channel) 
were prepared to provide descriptive attributes, while a central fact table was created to 
store key performance metrics. This star-schema model allowed efficient data organization, 
better relationships, and faster dashboard performance. 

---

## 3. Data Analysis

### Dashboard 1 Insights: Lead Generation Analysis

**Overall KPIs**

* Campaign Reach: **1,139K**
* Impressions: **2,124K**
* Leads Generated: **6K**
* Total Campaigns: **22**


#### 1. Cost per Result by Month

* Highest CPR: **August – ₹1,648**
* Lowest CPR: **September – ₹23**

**According to Delivery Status (Highest CPR month):**

* Active Campaigns: September (₹23)
* Not Delivering Campaigns: August (₹1,648)


#### 2. Amount Spent (INR) vs Count of Results

* Highest amount spent: **April – ₹25K**
* Lowest CPR spend: **September – ₹1K**
* Highest result count: **August – 120 results**
* Lowest result count: **September – 7 results**

**According to Delivery Status:**

* Highest Amount Spent:

  * Active: September (₹669)
  * Not Delivering: April (₹25,685.37)

* Highest Result Count:

  * Active: September (7)
  * Not Delivering: August (120)


#### 3. Top 5 Campaigns by Results

| S.No | Campaign Name                                    | Total Results |
| ---- | ------------------------------------------------ | ------------- |
| 1    | GBC-Aramco-Leads-11-April-2025                   | 840           |
| 2    | New-Lead-Gen-Campaign-Apparel-Group-12-June-2025 | 586           |
| 3    | Lead-Gen-Campaign-For-FIJI-Job                   | 569           |
| 4    | New Leads campaign                               | 552           |
| 5    | New-Lead-Gen-Campaign-Riyad-30-Aug-2025          | 543           |

> The **GBC-Aramco-Leads-11-April-2025** campaign generated the highest results (840) among all 22 campaigns.


#### 4. Bottom 5 Campaigns by Results

| S.No | Campaign Name                                          | Total Results |
| ---- | ------------------------------------------------------ | ------------- |
| 1    | New Engagement campaign                                | 0             |
| 2    | New-Lead-Gen-Germany-Male-Nurse-05-Aug-2025            | 24            |
| 3    | New-Lead-Gen-Campaign-Female-Nurse-30-Aug-2025         | 31            |
| 4    | Lead-Gen-Campaign-for-Kitchen-Supervisor               | 43            |
| 5    | Lead-Gen-Campaign-Zoomalian-Sales-Executive-2-Sep-2025 | 51            |

> The **New Engagement Campaign** performed the worst, generating 0 results.


#### 5. CPC vs Cost per Result (CPR) Analysis

* **Best Performance (June–July):**

  * CPC: ₹36–112
  * CPR: ₹95–19

* **Worst Performance (September):**

  * CPC: ₹12
  * CPR: ₹1,648

**Insight:** September campaigns had the lowest CPC but the highest CPR, meaning clicks were cheap but failed to convert effectively.


### Dashboard 2 Insights: Region-Based Analysis

#### 1. Campaign Reach by Region (Map View)

* Campaigns covered multiple regions in India.
* **Top performing states:** Uttarakhand, Maharashtra, Uttar Pradesh, Delhi, Himachal Pradesh.


#### 2. Cost per Result by Region

| Region           | CPR (₹) |
| ---------------- | ------- |
| West Bengal      | 103.56  |
| Karnataka        | 155.23  |
| Delhi            | 370.19  |
| Haryana          | 398.83  |
| Himachal Pradesh | 439.21  |
| Uttarakhand      | 515.37  |

* Lowest CPR: **West Bengal** and **Karnataka** (cost-effective).
* Highest CPR: **Uttarakhand** and **Himachal Pradesh** (costly).
* Mid-range: **Delhi** and **Haryana**.


#### 3. Top 5 Results by Region

| Region        | Results |
| ------------- | ------- |
| Uttarakhand   | 1.9K    |
| Maharashtra   | 1.1K    |
| Uttar Pradesh | 0.7K    |
| Delhi         | 0.6K    |
| Himachal Pr.  | 0.3K    |

**Insight:** Uttarakhand delivered the most results (1.9K) but with high CPR, indicating strong reach but expensive conversions.


#### 4. Impressions, Reach & Results by Region

* **Uttarakhand**: Impressions – 1,073.

---

## 4. Conclusion 
This project analyzed campaign performance using two dashboards: **Lead Generation Analysis** 
and **Region-Based Analysis**. 

From the **Lead Generation Analysis dashboard**, it was observed that campaign costs and 
performance varied significantly across months. Notably, **September recorded the highest 
Cost per Result (₹1,648)**, while months like **June (₹95)** and **July (₹112)** achieved lower 
acquisition costs with better efficiency. This highlights the importance of consistent cost 
monitoring and budget optimization to avoid spikes in campaign expenses. 

The **Region-Based Analysis dashboard** revealed that campaigns had a wide geographical 
reach across India, with **Uttarakhand (1.9K results)** and **Maharashtra (1.1K results)** 
contributing the most leads. However, the cost efficiency varied: **West Bengal (₹103.56)** and 
**Karnataka (₹155.23)** achieved the lowest Cost per Result, whereas **Uttarakhand (₹515.37)** 
and **Himachal Pradesh (₹439.21)** were comparatively costlier. This shows that while some 
regions generate higher volumes of results, they may not always be cost-effective. 

Overall, the findings emphasize that campaign success depends on both **time-based 
performance tracking** and **region-wise efficiency analysis**. For sustainable growth, businesses 
should adopt a **dual optimization strategy**—controlling monthly fluctuations in cost while also 
allocating budgets toward regions with the best cost-to-result ratios.

---

## 5. Future Scope

* Predictive campaign planning for cost optimization.
* Region-wise budget reallocation for efficiency.
* Advanced segmentation (age, device, interest).
* A/B testing across regions.
* Real-time anomaly detection in costs and results.
* Conversion quality and engagement tracking.

---

## 🙏 Acknowledgment
Grateful to NovaNectar Services Pvt. Ltd. for the opportunity to work on this project.
Special thanks to Mr. Suryadeep Das for mentorship and guidance.

Tools used: Power BI, Microsoft Excel, Power Query.

---

## 🔗 Connect
Feel free to connect for collaboration, reviews, or suggestions to enhance this project further.
