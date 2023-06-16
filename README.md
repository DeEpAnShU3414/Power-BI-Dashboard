# Power-BI-Dashboard
Customer Feedback Dashboard - Power BI
Power BI is an essential and foundational tool for data modeling, and I want to share my learnings and the process behind building this dashboard.
I learned how to set up a survey using MS Forms or Google Forms and collect customer feedback just by sharing the feedback link or QR Code and how to design a highly visual dashboard just by using the feedback data to gain more insights without any manual data entry.
OBJECTIVE: The Hotel aimed to create a customer Analytics report to gain insights into their overall Net Promoter Scores (NPS). Net Promoter Score (NPS) is a management tool that can be used by a Hotel, a Restaurant, or a Company to gauge loyalty in customer relationships. The customer gives the company a recommendation score between 0-10 based on one's experience. Values between 0-6 are considered detractors, values between 7-8 as passives, and values between 9-10 as promoters.
Steps I followed for creating this dashboard:
DATA CLEANING: Importing the Excel Workbook and performing activities like applying filters, choosing columns, creating duplicate Query, and transforming the data into an easily readable format.
DATA PROCESSING: In this case, the data model was linked with the Unique customer ID column and there were multiple attributes and ratings linked to a single ID. I calculated the NPS score using the columns and measures. Here I used the unpivot option and then merged the query using the left outer join to LOOKUP the feedback category and rating scores. In the data modeling part, I have used One to Many relationships to create my data models and removed unnecessary auto-detected relationships. This helps in making the model fast and responsive.
DATA ANALYSIS: In the report view I have used multiple visuals including Tables, Matrix Charts, Donut charts, Gauge charts, and Stacked Bar charts. To enhance the functionality, I have added Cards and slicers to filter the required parameter for example to filter the visuals based on Gender, Purpose of Visit, NPS Score, NPS Category, Source Trend, Source of Information, Feedback, and Overall Rating.
INSIGHTS:
1.      Staff received the highest feedback 14.6K.
2.      Under Gender 56.3% were male and the rest were female.
3.      Business was the highest with 42.5% among the purpose of visit.
4.      Passives and Detractors were nearly the same around 500 whereas Promoters were the highest around 1000.
5.      Total NPS score was 9.75 / 10
6.      And the Overall Rating of the hotel was 3.60/ 5.00.
CONCLUSION TO IMPROVE NPS SCORE
To improve the NPS score and overall rating the hotel should focus more on bookings generated through business and booking for vacations. Especially Bookings from Organizations and hotel booking sites. More emphasis on improving the customer experience by upgrading the rooms, staff, and facilities provided by the restaurant.
