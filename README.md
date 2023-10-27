# Hotel_Bookings_Analysis
This analysis pertains to the Hotel Booking dataset sourced from Kaggle. The study was undertaken as an integral component of my training and development as a data analyst. The dataset is sourced from the publication 'Hotel Booking Demand Datasets' by Nuno Antonio, Ana Almeida, and Luis Nunes, featured in the 'Data in Brief' journal (Volume 22, February 2019) published by Elsevier [https://www.sciencedirect.com/science/article/pii/S2352340918315191].

This dataset comprises 119,390 entries for both a City Hotel and a Resort Hotel. Every entry signifies a hotel reservation made between July 1, 2015, and August 31, 2017, encompassing both successfully completed stays and those that were canceled.

Research objectives: Evaluate strategies to enhance revenue.


🔗 Data location: The data is stored as csv files available by Kaggle [https://www.kaggle.com/datasets/mojtaba142/hotel-booking].

💹 Data license: Data files © Original Authors

✔️ Data privacy: Personal identifying information is subjected to anonymization to ensure the protection of sensitive data (financial data, address etc.).

  ❗         Data credibility: 
                              
                              I. Reliable: The 119,390 entries is sizeable and can provide valuable insights

                              II. Original: Since the data is sourced from a third party, its originality is categorized as low.
                              
                              III. Comprehensive: The data set is highly comprehensive because it contains all critical information to make an informed decision with respect to research objectives.
                              
                              IV. Current: The data is not current as it covers the period between July 1, 2015, and August 31, 2017. 
                              
                              V. Cited: The data source is cited. 

Tools used for the analysis.
1. SQL server
2. Power BI
   

Overall, the data was complete, correct, relevant to the business objectives, and did not present any significant flaws.


🏨 Discovering the Story Behind the Numbers: 

I. The total number of transactions is 119.390, among which 66.45% were for City Hotel and 33.55% for the Resort Hotel. 
      
II. Transient customers make up the bulk of the total transactions for both hotels: 49.76% for City Hotel and 25.3% for the Resort Hotel.
      
III:  Approximately 40.69% of transactions are coming from Portugal. 
  
 IV.	The monthly transactions from January to August generally exhibit an ascending trend. However, there is an anomalous dip in June, where transactions decreased by approximately 7.22% compared to May, before resuming the upward trend.  In autumn, we observe a declining trend in transactions, with a notable exception in October, which shows a slight recovery after a dip in September. Specifically, after peaking at 13,877 in August, transactions decrease to 10,508 in September, rebound to 11,160 in October, and then sharply drop in November and December to under 7,000 each month.
     
  V.	In analyzing the relationship between transactions and lead time, a notable anomaly emerges in August: despite having the highest transaction count for summer, its lead time is the shortest at 121.14 days. Generally, from January to July, lead time exhibits a consistent upward trend. It peaks in July at 136.32 days, dips in August, slightly rebounds to 136.68 days in September, and then demonstrates a declining trajectory from October through December.

 VI.	In examining the interplay between Average Daily Rate (ADR) and Cancellation Rate, a distinct pattern emerges during the Spring and Summer months where ADRs are at their peak. Statistically, an inverse correlation is evident: as the ADR increases, there's a corresponding decrease in the cancellation rate. This suggests that higher room rates during these months are associated with a lower likelihood for bookings to be cancelled.

 VII.	Upon examining the relationship between lead time and cancellation rate, we observe a statistically significant difference between the two lead time groups. For bookings made within a lead time of 0-30 days, the cancellation rate is considerably higher at 81.44%. Conversely, for bookings with a lead time of greater than 30 days, the cancellation rate is substantially lower at 54.09%. This pattern is further emphasized when considering the Average Daily Rate (ADR). For the shorter lead time group (0-30 days), the ADR is notably higher at €103.26, compared to an ADR of €98.86 for the longer lead time group (>30 days). This suggests that bookings made closer to the check-in date not only have a higher likelihood of cancellation but also come with a premium rate.

VIII.	There's a notable spike in cancellations from Thursday through Saturday, indicating a trend towards the end of the workweek and the start of the weekend.

IX.	In a comprehensive examination of hotel booking dynamics, distinct patterns emerge: 

a.	🏩 Booking Segment Insights:

•	Online TA dominates both in terms of revenue and transaction count.

•	Offline TA/TO remains a substantial contributor.

•	Direct bookings account for over a tenth of all bookings, suggesting possible influence from loyalty incentives.

•	Groups showcase an interesting dynamic with high transaction volume but a lower corresponding revenue, pointing to potential differential pricing or discounted bookings.

b.💸 Monthly Revenue Dynamics:

•	August stands out as the revenue pinnacle.

•	A significant revenue contraction is evident transitioning from August to September.

•	December witnesses a commendable 12.5% revenue augmentation compared to November, despite its placement towards the year-end.

c.💡 Transaction vs. Revenue Discrepancy in October:

•	There's an upward trend in October's transactions by 6.2% from September.

•	Contrarily, October's revenue underperforms September's by a notable 19.35%, suggesting potential variations in the nature or value of bookings during this month. 

X.	Analyzing the stay patterns reveals distinguishing behaviors between Transient and Contract customers. Transient customers, while more numerous, generally exhibit a preference for shorter stays. Their sheer volume, combined with these brief durations, likely depresses their average stay duration. In contrast, Contract customers demonstrate a consistent inclination towards longer stays, suggesting their engagements or commitments at the hotel span a more extended period.

XI.	When examining the patterns of weekday versus weekend stays by customer type, a consistent trend emerges across all categories: stays during weekdays outnumber those during weekends. Notably, transient customers dominate both weekday and weekend stays, but they show a marked inclination towards weekdays.

XII.	Upon examining guest loyalty and booking trends segmented by customer type:

a.	Transient guests showcase a significant number of cancellations (6,650) yet still achieve a high completion rate with 14,648 bookings.

b.	Transient-Party guests tend to cancel more than they complete their bookings.

c.	Group guests display an impressive loyalty, with a high number of completed bookings against a backdrop of very few cancellations.

d.	In stark contrast, Contract guests have a pronounced tendency to cancel, with cancellations significantly outnumbering completed bookings.

e.	In terms of loyalty, from highest to lowest:

     I. Group Guests

    II. Transient Guests

    III. Transient-Party Guests

    IV. Contract Guests

XIII.	 From a customer experience perspective, 59.21% of Transient guests choose the Bed & Breakfast option, a trend also seen among guests traveling with children. Additionally, Transient customers are prominent in their special requests, especially in their frequent need for car parking.

💰 Recommendations: 

                I.	Targeted Marketing: Focusing on the Resort hotel is recommended due to the evident preference for City hotels in the dataset. Considering the dominance of Portuguese clients, geographically-targeted promotions can be a strategic approach to leverage this.
   

               II.	Engagement Strategies: Loyalty or reward programs can be critical in industries with high competition, such as hospitality. Given the notable cancellations amongst Transient customers, incentives might foster commitment.
  

              III.	Revenue Optimization: Adjusting the ADR based on cancellation rates and implementing weekday promotions are strategic decisions that can maximize revenue.
 

               IV.	August's Paradox: Offering last-minute deals is an excellent recommendation, capitalizing on the observed trend.
 

                V.	Segment-Specific Promotions: Tailoring offers for specific segments, especially high-revenue ones like Online TA, is likely to enhance overall revenue.
  

              VI.	Focus on Guest Experience: Considering the high cancellations among Contract and Transient-Party customers, enhancing their experience could lead to more loyalty and fewer cancellations.
 

             VII.	Service Expansion: Given the observed preference for Bed & Breakfast among various customer types, expanding or enhancing this service can capitalize on its popularity. Implementing a feedback mechanism is an excellent recommendation; understanding guest experiences can inform future decisions.


Power BI file is available under the link: https://drive.google.com/file/d/1_mQ7oJijFpoYmnxo8p4rC3lKnDfDh0j0/view?usp=drive_link 

