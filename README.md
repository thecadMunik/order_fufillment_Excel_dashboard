# 📦 Data-Driven Excellence in Order Fulfillment: Excel Dashboard to Vanquish Backlogs
## 📌 Project Overview

Efficient order fulfillment is essential in logistics because delays can lead to backlogs, higher costs, and poor customer experience. This analysis focused on Streamline Logistics Solutions, where growing order backlogs and delivery delays were affecting operational efficiency.

Using Microsoft Excel, the dataset was cleaned, analyzed, and transformed into an interactive dashboard to track order status, delivery delays, driver performance, route efficiency, allocation rules, and customer feedback. The dashboard helped uncover key operational issues and provided insights that can support better decision-making, improved delivery performance, and reduced backlog.

🛠️ **Tools Used:** Microsoft Excel  


📁 **Dataset:** Order Fulfillment Dataset (1,500 rows, 14 columns)


## 🧠 Project Goal

The goal of this project is to help Streamline Logistics Solutions improve its order fulfillment process by using data to answer key operational questions.

I wanted to understand why order backlogs were increasing, what was driving delivery delays, how drivers, routes, vehicle types, and allocation rules were performing, and what actions the company could take to improve efficiency and customer satisfaction.

## 🏢 Business Problem

Streamline Logistics Solutions is a well-established logistics company known for dependable deliveries. However, the company began facing operational challenges that were affecting both performance and customer experience.

The main issues I identified were:

- Growing order backlogs
- Delayed deliveries
- Limited visibility into order progress
- Rising customer frustration
- Increasing operational costs due to overtime and expedited shipping

Because order fulfillment is central to logistics performance, solving these issues was important for improving customer satisfaction, protecting the company’s reputation, and reducing operational waste.

## 📂 About the Dataset

The dataset I worked with contained **1,500 records** and **14 columns**. It included important fields such as:

- Order ID
- Delivery Address
- Order Timestamp
- Order Status
- Driver ID
- Vehicle Info
- Current Location
- Delivery Time
- Delay Time
- Customer Feedback
- Delivery Zone
- Allocation Rules

This gave me enough information to analyze performance from different angles and build a dashboard that tells a clear operational story.

## 🧹 My Process

### 1. Data Understanding and Cleaning

I started by reviewing the dataset structure, checking the data types, and scanning for inconsistencies and missing values. I also looked at the date range and used Excel’s quick analysis features to get an initial feel for the data.

This stage helped me understand the quality of the dataset and prepare it properly before moving into analysis.

### 2. Preliminary Analysis

After cleaning the data, I moved into the first level of analysis by answering core business questions such as:

- How many orders are still in progress?
- What is the average delivery delay?
- Which delivery zones record the highest delay?
- What does customer feedback look like overall?
- How are orders distributed across allocation rules?

From this stage, I found that:

- **767 orders** were still in progress
- **733 orders** had been completed
- The **average delay time** was **14.51 minutes**
- Delay levels across zones were very close, suggesting a broader process issue
- Customer feedback was fairly balanced across positive, neutral, and negative responses
- Orders were almost evenly distributed across Expedited, Custom, and Standard allocation rules

This gave me a strong high-level view of the fulfillment process and showed that backlog and delay were already clear concerns.

### 3. Deep Dive Analysis

Next, I went deeper into the operational drivers behind the delays. I explored questions like:

- How does customer feedback compare with delay levels?
- Which drivers have the highest average delay?
- Which routes are the most problematic?
- Which vehicle types are associated with higher delays?
- How do allocation rules perform in terms of average delay?

To do this, I used Excel pivot tables, summary analysis, and charts to compare performance across categories.

This part of the project helped me move beyond just describing the problem and begin identifying where the real inefficiencies were happening.


## 📊 Dashboard Development

After completing the analysis, I designed an **interactive Excel dashboard** to present the findings in a clear and user-friendly way.

## 🔍 Key Insights 

### 1. High Backlog Indicates a Fulfillment Bottleneck
Out of **1,500 total orders**, **767 orders (51.1%)** were still in progress, while only **733 orders (48.9%)** had been completed.

This told me that the company is dealing with a serious backlog problem, likely caused by limited fulfillment capacity or inefficiencies in dispatch and delivery operations.

### 2. Delays Are Consistent and Systemic
The overall average delay was **14.51 minutes**, and the variation across cities and routes was relatively small.

This suggested to me that the delays were not random or isolated. Instead, they appear to be built into the current fulfillment process.

### 3. Expedited Allocation Is Not Performing as Expected
One of the most surprising findings was that **Expedited Rules** had the **highest average delay (15.03 mins)**, compared to:

- **Custom Rules:** 14.30 mins  
- **Standard Rules:** 14.23 mins  

This indicates that the expedited allocation method is underperforming and may not actually be helping priority deliveries move faster.

### 4. Driver Performance Varies Significantly
Some drivers stood out for having much higher delay times than the average, including:

- **D86:** 20.73 mins  
- **D44:** 19.33 mins  
- **D29:** 18.93 mins  

This showed me that driver-level performance differences are contributing to delivery inefficiencies and should not be ignored.

### 5. Certain Routes Are More Problematic
I found that **Route3** and **Route1** had the highest average delays, while **Route5** performed best.

This points to route-level bottlenecks that may be linked to traffic, route complexity, or poor route planning.

### 6. Vehicle Type Affects Delivery Efficiency
Among the vehicle types, **Bike C** recorded the highest delay, performing worse than both **Truck B** and **Van A**.

This suggests that vehicle assignment may not be aligned properly with delivery distance, order size, or operational needs.

### 7. Customer Feedback Is Not Entirely Driven by Delay
Customer feedback was distributed quite evenly:

- **Negative:** 35%
- **Neutral:** 33%
- **Positive:** 32%

Even though delays were present, customer sentiment did not lean overwhelmingly negative. This made me conclude that communication, visibility, and service quality may also play a major role in how customers rate their experience.

## 🖼️ Dashboard Preview
![Streamline Logistics Dashboard](https://github.com/thecadMunik/order_fufillment_Excel_dashboard/blob/main/Dashboard/strealinedashboard.png)

## 💡 Recommendations 

Based on the findings from my analysis and dashboard, I recommended the following:

### 1. Reduce the Backlog
The company should increase short-term fulfillment capacity through temporary staff or shift adjustments, while also improving dispatch and processing efficiency in the long term.

### 2. Review the Expedited Allocation System
Since expedited orders are actually showing the worst delay performance, the current rule logic should be reviewed and redesigned.

### 3. Monitor Driver Performance More Closely
I recommended implementing driver-level performance tracking so the company can identify underperformance early and provide training or route reassignment where needed.

### 4. Investigate High-Delay Routes
Routes with consistently high delays should be reviewed in more detail to understand whether traffic, route design, or distance is causing the problem.

### 5. Improve Vehicle Assignment
Vehicle selection should be better matched to delivery requirements. Bikes should be reserved for shorter and lighter deliveries, while vans and trucks should handle larger or longer-distance orders.

### 6. Introduce Real-Time Monitoring
The company would benefit from a more proactive monitoring system that tracks delays, backlog levels, and fulfillment status in real time.

### 7. Improve Customer Communication
Since feedback is not entirely explained by delay alone, I recommended improving order updates, delay notifications, and communication touchpoints to create a better customer experience.

## ✅ Final Conclusion

Through this project, I used **Microsoft Excel** not just for analysis, but as a full business intelligence tool to solve a real operational problem.

By cleaning the dataset, exploring the fulfillment process, performing deep-dive analysis, and building an interactive dashboard, I was able to uncover the major causes of backlog and delivery inefficiency at Streamline Logistics Solutions.

This project showed me how powerful Excel can be for operations analysis when data is structured properly and presented clearly. More importantly, it demonstrated how data-driven insights can help a business improve performance, reduce delays, and make better strategic decisions.

