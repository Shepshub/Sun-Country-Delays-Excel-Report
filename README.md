# Sun Country Delays
## Background and Overview
In this project, we focus on the analysis of flight delay data from Sun Country Airlines for the months of August and September 2024. Airlines face significant operational challenges due to delays, which can result in increased operational costs, customer dissatisfaction, and logistical complexities. The goal of this project is to identify key factors contributing to delays, assess their operational impact, and provide actionable insights to improve performance.

Flight delays are classified into controllable and uncontrollable categories. While some delays, like weather-related or late-arriving aircraft, are outside the airline's control, others stem from operational inefficiencies such as maintenance issues, crew scheduling problems, or ground operations delays. This analysis aims to uncover trends in controllable delays to help Sun Country Airlines better allocate resources, streamline operations, and ultimately reduce the occurrence of these preventable delays.

Goals of the Project:
- Delay Identification and Trends: Analyze delay trends across multiple dimensions, such as aircraft, arrival airports, delay codes, and managers on duty (MOD), to pinpoint recurring issues.
- Operational Impact Assessment: Examine the operational impact of delays on airline performance, focusing on metrics such as Total Delay Time, On-Time Performance (OTP), and Total Delayed Flights.
- Insights and Recommendations: Provide key insights and recommend actionable steps to reduce delays and improve operational efficiency, potentially leading to better on-time performance and overall service quality.

This project uses a combination of Excel and data visualization techniques to present a comprehensive dashboard that tracks delay performance and offers a breakdown of controllable delays. By leveraging this analysis, Sun Country Airlines can focus on data-driven improvements to enhance operational reliability.

## Data Structure & Initial Checks
This project uses flight delay data from Sun Country Airlines, spanning August and September 2024. Below is an overview of the key tables and their corresponding columns and data types:

### Data Considerations:
Multiple Delay Codes: Some flights may have multiple rows in the Delays sheet if they experienced more than one reason for delay. Each delay reason is captured in separate rows, along with the corresponding total delay time and code.

Controllable vs. Uncontrollable Delays: Delay codes and subcodes help differentiate between delays that the airline could control (e.g., crew issues) versus uncontrollable factors (e.g., weather or inbound delays).
