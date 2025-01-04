# Manufacturing Line Productivity Analysis  

## 📋 **Table of Contents**  
1. [Background and Overview](#background-and-overview)  
2. [Executive Summary](#executive-summary)  
3. [Insights Deep Dive](#insights-deep-dive)  
4. [Recommendations](#recommendations)  
5. [Caveats and Assumptions](#caveats-and-assumptions)  
6. [Tools Used](#tools-used)  
7. [Data Source](#data-source)  

---

## Background and Overview  

In a soda bottling production line, there have been a few issues resulting in decreased efficiency and output over a span of five days. The documented data includes information on operators, products, start and end times, and downtime factors for each batch.  

This project thoroughly analyzes the data to uncover critical insights that can help remediate and alleviate inefficiencies in the manufacturer’s production process.  

We will do so by answering the following questions:

- What's the current line efficiency? (total time / min time)
- Are any operators underperforming?
- What are the leading factors for downtime?
- Do any operators struggle with particular types of operator error?

---

## Executive Summary  

The analysis of the soda bottling production line reveals critical inefficiencies stemming from both operator errors and equipment-related issues. Machine failures and inventory shortages are the primary contributors to downtime, significantly impacting production line efficiency.  

By addressing controllable factors such as machine failures, inventory shortages, and operator errors, the production line's efficiency can realistically improve from **67% to 80%**, representing a **20% increase**. While human errors are not fully addressed in this analysis, areas and individuals requiring improvement have been identified for future development.  

This approach ensures the target is both realistic and achievable while addressing key inefficiencies within management’s control.  

---

## Insights Deep Dive  

- **What’s the current line efficiency?**  
   - The production line efficiency currently stands at **67%**. If identified inefficiencies are resolved, the efficiency could rise to **80%**, marking a substantial improvement.  

- **Are any operators underperforming?**  
   - Operator Dennis frequently struggles with **machine adjustments**, especially on September 2nd.  
   - Operator Mac faces consistent challenges during **batch changes**, particularly in 3 out of 5 recorded instances.  

- **What are the leading factors for downtime?**  
   - **Machine adjustment (12 occurrences):** 332 minutes of downtime.  
   - **Machine failures (11 occurrences):** 254 minutes lost.  
   - **Inventory shortages (9 occurrences):** 225 minutes of downtime.  
   - **Batch changes (5 occurrences):** 160 minutes of delays.  
   - **Batch coding errors (6 occurrences):** 145 minutes of wasted time.  

- **Do any operators struggle with particular types of operator error?**  
   - Dennis struggles significantly with machine adjustments.  
   - Mac shows the highest frequency of errors during batch changes.  

---

## Recommendations  

1. **Resolve Machine Failures and Inventory Shortages:**  
   - Investigate root causes and implement preventive maintenance protocols.  
   - Optimize inventory management to reduce interruptions.  

2. **Implement Targeted Operator Training:**  
   - Focus on machine adjustment techniques, particularly for Dennis.  
   - Provide specialized training for Mac on batch changes and coding processes.  
   - Conduct skill development workshops to ensure all operators are better equipped.  

3. **Monitor and Continuously Improve Processes:**  
   - Establish KPIs to track downtime factors and operator performance.  
   - Conduct regular audits to ensure sustained improvement.  

---

## Caveats and Assumptions  

- The analysis is based on a data sample spanning only five days, which may not capture all downtime factors.  
- Unrecorded downtime could result in incomplete insights.  
- Operator assessments are based on recorded data, which might not fully reflect typical performance.  
- Efficiency improvements assume effective resolution of controllable issues.  
- External factors like supply chain disruptions are not accounted for in this analysis.  

---

## **Tools Used**  
- **Excel**: XLOOKUP, pivot tables, and charts for data analysis and visualization.  

---

## **Data Source**  
The dataset used for this project was provided by **Maven Analytics**. You can explore their comprehensive library of datasets and resources here: [Maven Analytics](https://www.mavenanalytics.io/data-playground).  
