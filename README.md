# Sun Country Delays
## Background and Overview
This project is focused on analyzing flight delay data from Sun Country Airlines for August and September 2024. Airlines face significant operational challenges due to delays, which can result in increased operational costs, customer dissatisfaction, and logistical complexities. This project aims to identify key factors contributing to delays, assess their operational impact, and provide actionable insights to improve performance.

Flight delays are classified into controllable and uncontrollable categories. While some delays, like weather-related or late-arriving aircraft, are outside the airline's control, others stem from operational inefficiencies such as maintenance issues, crew scheduling problems, or ground operations delays. This analysis aims to uncover trends in controllable delays to help Sun Country Airlines better allocate resources, streamline operations, and ultimately reduce the occurrence of these preventable delays.

Goals of the Project:
- Operational Impact Assessment: Examine the operational impact of delays on airline performance, focusing on metrics such as On-Time Performance (OTP), Total Delay Time, Total Delayed Flights, Top Delay Codes, and Delay Time Distribution.
- Delay Identification and Trends: Analyze delay trends across multiple dimensions, such as aircraft, arrival airports, delay codes, and managers on duty (MOD), to pinpoint recurring issues.
- Insights and Recommendations: Provide key insights and recommend actionable steps to reduce delays and improve operational efficiency, potentially leading to better on-time performance and overall service quality.

This project uses a combination of Excel and data visualization techniques to present a comprehensive dashboard that tracks delay performance and offers a breakdown of controllable delays. Sun Country Airlines can leverage this analysis to focus on data-driven improvements to enhance operational reliability.

An interactive Excel dashboard can be downloaded [here](https://github.com/Shepshub/Sun-Country-Delays/raw/refs/heads/main/Sun%20Country%20Delays%20-%20Aug%20Sep.xlsx)

An interactive Power BI dashboard can be downloaded [here](https://github.com/Shepshub/Sun-Country-Delays/raw/refs/heads/main/Delays%20SEP%20&%20AUG.pbix)

The Excel dashboard is the primary dashboard for this project and all of its insights. The Power BI dashboard is a secondary optional dashboard to further explore and breakdown different delay trends across multiple dimensions.

## Data Structure & Initial Checks
This project uses flight delay data from Sun Country Airlines, spanning August and September 2024. Below is an overview of the key tables and their corresponding columns and data types:

![image](https://github.com/user-attachments/assets/28f88a22-d1cf-49a4-a131-1c7ec21437f5)

### Data Considerations:
Multiple Delay Codes: Some flights may have multiple rows in the Delays sheet if they experienced more than one reason for delay. Each delay reason is captured in separate rows, along with the corresponding total delay time and code.

Controllable vs. Uncontrollable Delays: Delay codes and subcodes help differentiate between delays that the airline could control (e.g., crew issues) versus uncontrollable factors (e.g., weather or inbound delays).

## Executive Summary
The analysis of Sun Country Airlines' delays, focusing on August and September 2024, provides valuable insights into operational efficiency and the impact of controllable delays on flight performance. This case study was built to identify trends in delay codes, highlight operational bottlenecks, and propose areas for improvement.

Key performance indicators (KPIs) were analyzed, including on-time performance, total delay time, and delay frequency. The study focuses on the relationship between different delay codes, aircraft types, arrival airports, and operational teams to better understand the root causes of controllable delays.

![image](https://github.com/user-attachments/assets/32e23b3a-885c-4ee4-99b4-1f77ffab6551)

1. On-Time Performance
   
     During August and September 2024, Sun Country Airlines' on-time performance (OTP) averaged 70%. The best-performing days they achieved OTPs of up to 100%, while the worst-performing days dropped to as low as 26%. The beginning and end of peak travel days (Thursday- Monday) have the worst OTP, with 70% of the bottom 10 OTP days occurring on Mondays and Thursdays. Over the last two months, OTP showed moderate daily fluctuations, but overall, there was an upward trend due to the lower number of flights in September.

3. Total Delayed Flights
   
    Across both months, 572 delayed flights were recorded, with a total delay time of 22,191 minutes, representing 30% of the total flights operated in this period (out of 1,897 scheduled flights). The most significant spike in delays occurred on August 5, 2024, with 39 delayed flights, primarily attributed to aircraft defects (Code 41), TSA congestion (Code 85A) and late arrivals (Code 93). There was a 41% decrease in the number of flights from August to September, resulting in 248 fewer delayed flights and an 11% increase in OTP.

5. Top Delay Code
   
     The top delay codes identified were responsible for the majority of the delays over the two months:

![image](https://github.com/user-attachments/assets/00fdbe30-f1af-48b8-a06c-4a4a0b43b0f5)

- Code 93: Aircraft location - Late arrival (167 occurrences)
- Code 41: Aircraft defects, including deferrals (90 occurrences)
- Code 46: Aircraft change for technical reasons (48 occurrences)
- Code 65: Flight deck crew special request or error (30 occurrences)
- Code 37: Catering, late delivery or loading (27 occurrences)
  
     These five delay codes were consistent across both individual months and, in total, accounted for 63% of all delays during August and September 2024. The most significant contributor was Code 93, which alone represented 29% of total delays. Combined, these top 5 delay codes generated 12,943 minutes of total delay time over the two months, with Code 93 and Code 46 being the primary drivers of delays.
  
  ![image](https://github.com/user-attachments/assets/2672935f-92ea-4510-acbb-210d2ffe32be)

     Along with having 2 of the top 5 delay codes, MX has, far and away, the most controllable delay codes over the two months, with 121 delays coded in August and 47 in September. This accounts for 31% of all controllable delays over the two months.

4. Delay Time Distribution
   
   ![image](https://github.com/user-attachments/assets/996d845b-96b3-4398-bc03-6e40348a5580)
   
     Delays during this period ranged widely, but 88% of all delay times were less than 60 minutes, and 72% were less than 30 minutes. A notable ten flights exceeded 4 hours, causing the issuance of compensation and having the most significant impact on both on-time performance and passenger satisfaction. 

## Recommendations
Based on the analysis of delays during August and September 2024, the following recommendations are proposed to improve on-time performance and reduce operational disruptions:

1. Focus on Minimizing Delays from Inbound Aircraft (Code 93)

     Delays caused by late arriving aircraft were the most frequent issue, accounting for 29% of all delays. **Implement more robust contingency plans for inbound aircraft. This could include optimizing turnaround times, better coordinating with ground services, pre-assigning backup aircraft, or swapping aircraft routes when inbound delays are anticipated to improve on-time performance.**

2. Enhance Aircraft Maintenance and Pre-flight Checks (Code 41 & 46)

     Aircraft defects and technical changes together accounted for nearly 30% of delays. Addressing these technical issues would target two of the top five causes of delays. **Strengthen pre-flight technical inspections and ensure better maintenance schedules, particularly for aircraft that frequently experience defects or technical issues.**
  
3. Streamline Processes for Flight Deck and Cabin Crew Requests (Codes 65 & 68)

     Delays from the flight deck and cabin crew special requests represent significant operational inefficiencies. **Clear communication protocols between crew members and ground services to prevent last-minute requests or changes. Further, additional training on flight readiness and on-time departures should be offered to above and below wings agents to anticipate and prevent these requests.**

4. Improve Catering and Ground Service Coordination (Code 37)

     Rationale: Delays related to late catering deliveries were in the top five and are highly preventable. **Implement real-time delivery tracking to get better data on exactly when flights are being catered. Based on this new information, integrate catering schedules more closely with flight plans. Review contracts and service level agreements with catering providers to enforce stricter deadlines if needed.**

5. Monitor and Report on Controllable Delays

     Controllable delays make up a significant portion of overall delays but can be mitigated with targeted interventions. **Set up regular reporting dashboards focused on controllable delay categories, enabling better performance monitoring over time. Provide these dashboards to management in each department. This will allow for earlier intervention and more proactive delay management.**
