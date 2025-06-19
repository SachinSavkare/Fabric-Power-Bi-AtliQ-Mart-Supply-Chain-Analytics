# AtliQ Mart Supply Chain Performance Analysis (Mar–Aug 2022)

> A Microsoft Fabric Mini Project analyzing end-to-end supply chain KPIs  
> Developed during the **Codebasics Data Analytics Bootcamp**  
> **By:** Sachin Savkare

🔗 **Live Power BI Dashboard:**  
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzVmNmQ0MGUtNGJlMC00MzE1LTk2YjQtOWMzNGQ4NzAxNmJlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 🏢 About AtliQ Mart

**AtliQ Mart** is a fast-growing FMCG manufacturer based in Gujarat, India, operating across **Surat, Ahmedabad, and Vadodara**, with plans to scale into other Tier 1 cities.

However, some major clients chose not to renew contracts due to:
- Delayed deliveries  
- Incomplete order fulfilment

To address these issues, the **supply chain team initiated a performance analysis project** using Microsoft Fabric tools and Power BI to track and improve service-level KPIs.

---

## ❓ Problem Statement

AtliQ Mart's key clients reported service issues impacting long-term relationships.  
The company lacked visibility into:
- On-time delivery trends  
- Order fulfilment accuracy  
- Location-wise and store-wise performance gaps  

**Goal:** Monitor and improve:
- **OT %** (On-Time Delivery)  
- **IF %** (In-Full Delivery)  
- **OTIF %** (On-Time In-Full Delivery)

---

## 👨‍💻 Role & Tools

**My Role:** Data Analyst – Supply Chain Analytics  
Responsibilities:
- Design KPIs and create insights  
- Build an interactive dashboard using Microsoft Fabric + Power BI  
- Recommend improvements for logistics, inventory, and vendor coordination  

**Tools Used:**
- Microsoft Fabric (Lakehouse, Dataflow)  
- Power BI  
- Power Query  
- SQL  
- Excel  

---

## 📊 Dashboard Sections & Key Insights

> *Each section includes an uploaded visual + extracted insights below.*

---

### 📌 1. Orders

![Alt text](https://github.com/SachinSavkare/Fabric-Power-Bi-AtliQ-Mart-Supply-Chain-Analytics/blob/main/Orders%201.JPG)

**Key Observations:**
- **Total Orders:** 31.73K  
- **OT Orders:** 18.73K  
- **IF Orders:** 16.75K  
- **OTIF Orders:** 9208  
- Top volume stores: **Lotus Mart** (11.2%) & **Acclaim Stores** (11.1%)  
- Surat leads OT % (61.21%), Vadodara lowest IF % (51.56%)  

**Recommendations:**
- Prioritize underperforming cities like Vadodara  
- Audit top stores for improvement potential  
- Establish weekly monitoring with city-level dashboards  
- Segment delays by product, vendor, and location

---

### 📌 2. Service Level Analysis

![Alt text](https://github.com/SachinSavkare/Fabric-Power-Bi-AtliQ-Mart-Supply-Chain-Analytics/blob/main/Service%20Level%20Analysis%202.JPG)

**Key Insights:**
- Only 4–5 stores are close to OTIF target (65.91%)  
- **Elite Mart:** Strong OT, poor IF → stockouts  
- **Vijay Stores:** Great OT, low IF → reliability issues  
- Scatter plot highlights top performers vs critical underperformers  

**Recommendations:**
- Benchmark from stores like **Propel Mart** & **Chiptec**  
- Create SOPs for top stores  
- Segment action plans  
- Pilot AI-driven delivery routing  
- Add SKU-level stock alerts & buffer stock planning  

---

### 📌 3. Metric Performance Over Time

![Alt text](https://github.com/SachinSavkare/Fabric-Power-Bi-AtliQ-Mart-Supply-Chain-Analytics/blob/main/Metric%20Performance%20Over%20Time%203.png)

#### OT % – Target = 86.09%  
- Performance mostly between 54–67%  
- High in May (67.63%) but not consistent  

#### IF % – Target = 76.51%  
- Mostly between 44–60%, except for spikes in June & August  

#### OTIF % – Target = ~65.91%  
- Stays between 25–35% with a brief spike in June  

#### LIFR % – Target = 75%+  
- Average around 65–70%, dipped to 59% in June  

#### VoFR % – Excellent!  
- Maintains >95.5% across all months  

**Strategic Summary:**
- **Volume is not the issue** – it’s timing & item-level accuracy  
- Surat is consistently better → use as benchmark  
- Focus on improving OTIF through cross-functional strategies  

---

### 📌 4. Order Lines

![Alt text](https://github.com/SachinSavkare/Fabric-Power-Bi-AtliQ-Mart-Supply-Chain-Analytics/blob/main/Order%20Lines%204.JPG)

**Summary (Mar–Aug 2022):**
- **Total Order Lines:** 57.10K  
- **Fully Filled:** 37.66K  
- **LIFR %:** 65.96%  
- **VOFR %:** 96.59%  

**Observations:**
- **Coolblue:** Lowest LIFR (52%)  
- **Vijay & Acclaim Stores:** High volume, poor fulfilment  
- **Propel Mart & Chiptec:** Top performers (76% LIFR)  

**Recommendations:**
- Replicate top store processes  
- Improve pick & pack practices  
- Focus on line-level issues despite strong overall volume performance  

---

### 📌 5. Line Lead Time Analysis

![Alt text](https://github.com/SachinSavkare/Fabric-Power-Bi-AtliQ-Mart-Supply-Chain-Analytics/blob/main/Products%205.JPG)

**Category Insights:**
- **Dairy**: Best on-time rates, but needs cold-chain optimization  
- **Beverages**: Slight early deliveries  
- **Food**: Slightly late deliveries  

**City-wise:**
- Consistent 65% on-time across cities  
- Ahmedabad leads early delivery  
- Coolblue shows late shipments → logistics issue  

**Recommendations:**
- Standardize dispatch timelines  
- Introduce inventory automation at low-performing stores  
- Share best practices from Propel & Chiptec  
- Target 70–75% LIFR at minimum for all stores  

---

### 📌 6. Product-Level Performance

![Alt text](

**Key Takeaways:**
- **Dairy**: Strong VOFR (>96%) but low LIFR (63–67%)  
- **Food**: AM Biscuits 750 strong, 250 SKU weak → inventory mismatch  
- **Beverages**: Stable overall; **AM Tea 500** best alignment  

**Recommendations:**
- Communicate supplier reliability using VOFR  
- Focus internally to improve LIFR  
- Visualize VOFR vs LIFR gap per SKU to identify root causes  

---

## ✅ Final Outcome

With this dashboard and analysis, AtliQ Mart’s supply chain team can now:
- Continuously monitor OT, IF, and OTIF metrics  
- Identify inefficiencies across stores and categories  
- Leverage strong vendor performance (high VOFR)  
- Develop focused improvement plans by store, product, and location  
- Improve fulfillment & customer trust — avoiding further contract loss  

---

## 📈 Dashboard Snapshot

🔗 **[Click here to view the live dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzVmNmQ0MGUtNGJlMC00MzE1LTk2YjQtOWMzNGQ4NzAxNmJlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---

## 🙌 Special Thanks

Big shoutout to the **Codebasics team**, mentors **@Hemanand Vadivel** and **@Dhaval Patel** for designing a practical, industry-relevant learning experience.
