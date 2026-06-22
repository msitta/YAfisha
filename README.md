# 📈 Marketing Optimization - Y.Afisha (LTV, CAC, and ROI)

## 📋 About the Project
This project consists of data analysis for **Y.Afisha**, a fictitious company, aiming to optimize marketing investments. The main focus was analyzing server logs and order history to understand user behavior and the profitability of advertising campaigns.

The challenge was to answer the crucial question: **"Are the marketing investments paying off?"**

## 🎯 Business Objectives
The board needed to understand the efficiency of each acquisition channel. Therefore, the project focused on:
* Calculating product metrics (**DAU, WAU, MAU**, and Sticky Factor).
* Analyzing the sales funnel and conversion time.
* Calculating the **LTV (Lifetime Value)** by cohorts.
* Calculating the **CAC (Customer Acquisition Cost)** by source.
* Determining the **ROI (Return on Investment)** to indicate where to allocate the budget.

## 🛠️ Technologies Used
* **Python 3**
* **Pandas & Numpy:** Data manipulation and cleaning.
* **Matplotlib & Seaborn:** Data visualization (Heatmaps, Bar Charts).
* **Jupyter Notebook:** Development environment.

## 📊 Key Findings (Insights)

### 1. Device Analysis 📱 vs 💻
We identified that although mobile devices (**Touch**) generate a high volume of visits, the actual conversion mostly happens on **Desktop**.
* **Action:** Maintain mobile campaigns for awareness, but focus conversion on Desktop.

### 2. The Source 3 "Trap" 📉
**Source 3** received the majority of the marketing budget. However, the ROI analysis revealed it is inefficient: it has a high CAC and brings in customers with a low LTV.
* **Impact:** Operational loss on this source.

### 3. The Opportunities (Sources 1 and 2) 🚀
* **Source 1:** Showed the best overall ROI. It is the "Star" source.
* **Source 2:** Although it has a high customer acquisition cost (CAC), it brings "Premium" customers who spend much more over time, justifying the investment.

## 💡 Conclusion and Strategic Recommendation
Based on the data analysis, the final recommendation for the marketing team is to execute a **budget reallocation**:

1.  Immediately **cut** investment in **Source 3** (inefficient).
2.  **Reinvest** the saved budget into **Sources 1 and 2**, which proved to be profitable.
3.  Monitor **Sources 5, 9, and 10**, which show low cost and scaling potential.

> *"The suggested strategy is to stop 'buying expensive visits' on Source 3 and start 'investing in profitable customers' on Sources 1 and 2."*

---
**Author:** Marco
[My LinkedIn](https://www.linkedin.com/in/marcositta) | [My E-mail](mailto:msitta@gmail.com)