# Surgical-Delay-Dashboard
 Surgical Delay Insight Dashboard
Overview
The Surgical Delay Insight Dashboard is an interactive Tableau dashboard designed to analyze delays in surgical procedures across different roles and days of the week. The dashboard aims to uncover trends, peak delay times, and root causes contributing to surgical inefficiencies in a hospital setting.

Purpose
This dashboard provides operational insights to hospital administrators, clinicians, and healthcare analysts by:
Identifying which days and times experience the most surgical delays.
Pinpointing which healthcare professionals (surgeons, anaesthetists) are associated with frequent delays.
Highlighting the top contributing factors to delays (e.g., consent issues, late patient arrival).
Measuring delay trends to support scheduling, staffing, and decision-making improvements.

Dashboard Sections
1. Key Metrics Summary
Total Procedures: Number of all scheduled procedures (432)
Total Anaesthetists: Unique anaesthetists involved (68)
Total Surgeons: Unique surgeons involved (42)
Delayed Procedures: Number of procedures with delays (55)
Average Delay per Day: Mean delay time in minutes (326 mins)
Current Day Filter: Allows users to explore data specific to a chosen day (e.g., Monday)

2. Peak Surgical Delay Time
A heatmap showing hours of the day with the highest concentration of delays by weekday.
Darker shades indicate higher frequency of delays, helping to visualize bottlenecks.

3. Trend Delay by Day
A line chart showing daily delay trends from Monday to Sunday.
Useful for identifying which weekdays require operational attention.

4. Surgeon Delay per Day
A bar chart listing surgeons with the most frequent delays.
Helps monitor accountability and training needs.

5. Anaesthetist Delay per Day
Similar to the surgeon delay chart but focused on anaesthetists.

6. Top Contributors of Delay
A bar chart outlining reasons for delay such as:
Previous case overrun
Surgeon/anaesthetist delay
Emergency clearance
Consent issues
Late patient arrival
Equipment unavailability

Tools & Technologies
Tableau Public Desktop Edition

Data Source: Internal hospital dataset 

Analytical Techniques: Heatmaps, trend analysis, bar charts, and filters

Use Cases
Hospital administrators can optimize scheduling and staffing.
Clinical leadership can assess team performance and resource bottlenecks.
Healthcare data analysts can explore delay trends and model improvements.
