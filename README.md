Business Intelligence Case Study: FlyingWhale Airline


Background

FlyingWhale Airline, a prominent (fictional) international airline, is seeking to enhance its business intelligence capabilities by analyzing Customer Flight Activity and Customer Loyalty History. The airline is committed to optimizing customer experience, understanding travel patterns, and maximizing the effectiveness of its loyalty programs.


Data: You have access to two key datasets:

1. Customer Flight Activity:
   
• Loyalty Number: A unique identifier for each customer's loyalty account.
• Year and Month: Period details for analysis.
• Flights Booked: Number of flights booked by the member during the period.
• Flights with Companions: Number of flights booked with additional passengers.
• Total Flights: Combined total of Flights Booked and Flights with Companions.
• Distance: Flight distance traveled in kilometers during the period.
• Points Accumulated: Loyalty points earned in the period.
• Points Redeemed: Loyalty points redeemed during the period.
• Dollar Cost Points Redeemed: Dollar equivalent for points redeemed in Canadian Dollars (CDN).

2. Customer Loyalty History:
   
• Loyalty Number: A unique identifier for each customer's loyalty account.
• Demographics: Country, Province, City, Postal Code, Gender, Education, Salary, Marital Status.
• Loyalty Card: Current loyalty card status
• Customer Lifetime Value (CLV): Total invoice value for all flights ever booked by the member.
• Enrollment Details: Enrollment Type (Standard / 2018 Promotion), Enrollment Year, Enrollment Month.
• Cancellation Details: Cancellation Year and Month if applicable.


Business Scenarios:

1. Flight Activity Analysis:
   
• Analyze monthly and yearly flight booking patterns.
• Tips:
▪ Make sure months are named properly
▪ Make sure months are sorted properly

• Explore the correlation between flight distances and loyalty points accumulated.
• Include a trend line and a max line
• Assess the impact of companion bookings on loyalty points redeemed
• What is the number of companions where members are redeeming the most points?

2. Loyalty Segmentation:
   
• Segment customers based on loyalty card status.
• Show Total number of flights by Loyalty Card across months
• Analyze the demographics and behaviors of customers
• Depict Number of loyalty members by marital status
• Show flights booked by loyalty card and broken up by gender
• Show median distance travelled by different loyalty card tiers
• Use the Narrative visual to autogenerate insights. Make sure to remove insights that may not be useful.
• Identify trends in Customer Lifetime Value (CLV) across loyalty segments.
• Answer the question: Which credit card tier on average has customers with the highest Customer Lifetime Value?

4. Enrollment and Cancellation Trends:
   
• Analyze the reasons and patterns behind membership cancellations.
• Tips
▪ Create a table Customer Loyalty Cancellation for loyalty members that have cancelled.
▪ Create two new columns in the new table Enrollment Duration (e.g. 2 years 1 month) and Enrollment Duration (Months) (e.g. 25)
▪ Create two new columns in Customer Loyalty History table Enrollment Duration (Till Date) and Enrollment Duration (Till Date) Months
• These columns should count the time a member has been enrolled till today or till they cancelled whatever comes first

Answer the following:

▪ Provide information for average duration of enrollment among cancelled members by province.
Which province sees members cancelling the fastest? Bonus: Depict this information on a map
▪ Most popular months for cancellations
▪ Cancellations by education and marital status. Which demographic is cancelling the most?
▪ Which loyalty card members have the lowest enrollment duration among cancellations
• Recommend strategies for improving enrollment and retention.

Deliverables:

• Power BI Dashboards and Reports for the scenarios mentioned.
• A comprehensive presentation summarizing key findings and recommendations.
