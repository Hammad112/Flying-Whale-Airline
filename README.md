# Flying Whale Case Study: Power BI

Welcome to Flying Whale's Power BI Visualization Case Study! Today, we'll weave magic, turning raw data into captivating Power BI Visualizations. Let's soar!


## Why Power BI?
Power BI isn't just a tool—it's a game-changer. With its intuitive interface, robust features, and seamless integration capabilities, Power BI empowers you to explore data in ways you never thought possible. Whether you're a beginner or a seasoned pro, this assignment will equip you with the skills and confidence to unleash your creativity and make data come to life.

## About the Dataset

This dataset comprises two CSV files:

1. **Customer Flight Activity**
   - **Loyalty Number**: Unique identifier for loyalty program members.
   - **Year**: Year of flight activity.
   - **Month**: Month of flight activity.
   - **Flight with Companions**: Number of flights taken with companions.
   - **Total Flight**: Total number of flights taken.
   - **Distance**: Distance traveled in flights.
   - **Points Accumulated**: Loyalty points accumulated.
   - **Points Redeemed**: Loyalty points redeemed.
   - **Dollar Cost Points Redeemed**: Dollar value of loyalty points redeemed.

2. **Customer Loyalty Activity**
   - **Loyalty Number**: Unique identifier for loyalty program members.
   - **Country**: Country of residence.
   - **Province**: Province/state of residence.
   - **City**: City of residence.
   - **Postal Code**: Postal code of residence.
   - **Gender**: Gender of the member.
   - **Education**: Level of education.
   - **Salary**: Income level.
   - **Marital Status**: Marital status of the member.
   - **Loyalty Card**: Type of loyalty card held.
   - **CLV**: Customer Lifetime Value.
   - **Enrollment Type**: Type of enrollment in the loyalty program.
   - **Enrollment Year**: Year of enrollment in the loyalty program.
   - **Enrollment Month**: Month of enrollment in the loyalty program.
   - **Cancellation Year**: Year of cancellation (if applicable).
   - **Cancellation Month**: Month of cancellation (if applicable).

This dataset provides comprehensive insights into customer flight and loyalty activities, enabling analysis of travel patterns, loyalty program effectiveness, and customer demographics.

# Power BI Visualization Tips:

This Power BI project aims to address three key business scenarios:

## 1. Flight Activity Analysis:

- Analyze monthly and yearly flight booking patterns.
  - **Tips:**
    - Ensure proper naming and sorting of months.
  - Explore the correlation between flight distances and loyalty points accumulated.
    - Include a trend line and a max line.
  - Assess the impact of companion bookings on loyalty points redeemed.
    - Determine the number of companions where members are redeeming the most points.

## 2. Loyalty Segmentation:

- Segment customers based on loyalty card status.
  - Show the total number of flights by Loyalty Card across months.
  - Analyze the demographics and behaviors of customers.
    - Depict the number of loyalty members by marital status.
    - Show flights booked by loyalty card and broken up by gender.
    - Show median distance traveled by different loyalty card tiers.
  - Utilize the Narrative visual to auto-generate insights. Ensure to remove irrelevant insights.
  - Identify trends in Customer Lifetime Value (CLV) across loyalty segments.
    - Answer: Which credit card tier on average has customers with the highest Customer Lifetime Value?

## 3. Enrollment and Cancellation Trends:

- Analyze the reasons and patterns behind membership cancellations.
  - **Tips:**
    - Create a table Customer Loyalty Cancellation for loyalty members that have canceled.
    - Create two new columns in the new table: Enrollment Duration (e.g., 2 years 1 month) and Enrollment Duration (Months) (e.g., 25).
    - Create two new columns in Customer Loyalty History table: Enrollment Duration (Till Date) and Enrollment Duration (Till Date) Months. These columns should count the time a member has been enrolled till today or till they canceled, whichever comes first.
  - Provide information for the average duration of enrollment among canceled members by province. Which province sees members canceling the fastest? (Bonus: Depict this information on a map)
  - Determine the most popular months for cancellations.
  - Analyze cancellations by education and marital status. Which demographic is canceling the most?
  - Identify which loyalty card members have the lowest enrollment duration among cancellations.
- Recommend strategies for improving enrollment and retention.

This structured approach outlines the key tasks and objectives for each business scenario, providing a clear roadmap for data analysis and visualization in Power BI.

## Feedback and Contributions
We welcome feedback, suggestions, and contributions from the community. If you have any ideas for improving this repository or would like to contribute your own content, please don't hesitate to open an issue or submit a pull request.
