# Gun Violence Data Analysis Dashboard
## Brief Overview
Developed an interactive Tableau dashboard analyzing U.S. gun violence trends across time and geographic regions. Transformed complex datasets into clear visualizations and storyboards to highlight regional patterns, long-term trends, and public safety insights using data analysis and visualization techniques.

## Link to Story
https://public.tableau.com/app/profile/dalton.willis/viz/Willis_Story_Final/FinalStoryBoard?publish=yes

## Formal Report
### Introduction
Gun violence remains one of the most significant public health and safety concerns in the United States, with rates “rising from 92 deaths per day to 132 deaths per day from 2012 to 2022” (Saunders et al., 2025). Discussions surrounding firearm violence tend to involve political debates, legislation, healthcare concerns, and community safety, but large-scale patterns behind these incidents can sometimes be difficult to understand through statistics alone. By exploring this topic through an incident-level analysis, the goal is to use data from the Gun Violence Archive to explore how incidents vary across states and over time.
  
This project focuses on identifying measurable patterns within the data itself rather than simply attempting to explain why gun violence occurs. By organizing the information into an interactive story dashboard, the project allows viewers to explore where incidents occur most frequently, how trends changed over time, and which demographic groups were most commonly involved in incidents.
  
This visualization is designed for a general audience rather than researchers/ experts in criminal justice or public policy. The goal was to make the findings more understandable for individuals with little or no experience in interpreting datasets or interactive dashboards. Since gun violence affects communities across the country, this project aims to help viewers better understand the scale and distribution of these incidents in a way that seems visually clear.

### Research Questions
The original research questions evolved throughout the development process as I became more familiar with the dataset and its limitations. The final project focused on three central questions:
- How does the frequency of gun violence incidents vary across U.S. states?
- Which regions exhibit the highest concentration of incidents?
- How have gun violence incidents changed over time?

As I explored the dataset further, demographic patterns also became an important secondary focus. Variables involving children, teenagers, and adults provided additional context that helped strengthen the overall story.

### The Data
This project uses the Gun Violence Archive dataset, which contains over 200,000 recorded gun violence incidents in the United States from 2013–2018. Each row represents a single incident and includes information about location, date, injuries, fatalities, and participant demographics.
  The analysis focused primarily on structured variables that were consistently recorded across the dataset, including:
- state and city for geographic analysis
- date for temporal trends
- n_killed and n_injured for measuring severity
- Age_0-11Child, Age_12-17Teen, and Age_18+Adult for demographic comparisons

To simplify the analysis, incidents were grouped into severity categories based on the total number of victims involved. This allowed clearer, and more uniform comparisons between states, time periods, and age groups throughout the dashboards. 

### Visualization Description
This Tableau story is organized into multiple dashboards(four total) that guide viewers through different aspects of the analysis. The overview dashboard introduces the dataset and explains the project’s goals, variables, and research questions. It provides viewers with background information needed to understand the rest of the story.

The first analysis dashboard focuses on geographic and temporal trends. Maps and state-level visualizations show where incidents concentrated in the United States, while line graphs and yearly trend charts illustrate how incident frequency and severity changed over time. Severity categories were created using the total number of victims involved in each incident, helping simplify comparisons between low-severity and high-severity events.

The second analysis dashboard examines demographic patterns, particularly comparisons between incidents involving children, teenagers, and adults. This dashboard uses age-group classifications from the dataset to show how different geographic groups are represented across states and incident severity categories. One key feature in this dashboard is the ability to select a specific state on the map for deeper analysis. When a state is selected, the other visualizations automatically update to display data only for that state. This allows users to compare demographic patterns and incident severity at both the national and state level without leaving the dashboard.

The conclusion dashboard finishes the story by summarizing the project’s major findings and connecting those findings to existing scholarly and public research on firearm violence.

<table>
<tr>
<td align="center">

**Figure 1.** Live Demonstration of Analysis 2 Dashboard Features

<a href="https://www.youtube.com/watch?v=vzSGy8r5bDQ" target="_blank">
  <img 
    src="https://github.com/user-attachments/assets/59a0abef-389d-4f02-96a4-4cb47ca32dbb"
    alt="Second Analysis Dashboard Demo"
    width="600">
</a>

<p align="center" width="600">
<i>
Note. This demonstration highlights the interactive features of the second analysis dashboard, including state-based filtering and hover tooltips that allow users to explore detailed information dynamically. The image links to the video.
</i>

</td>

</tr>
</table>

### Findings
This project revealed that gun violence incidents are geographically concentrated, and were heavily concentrated in highly populated states such as Illinois, California, Florida, and Texas. Geographic clustering was strongest in large urban regions and throughout the Eastern half of the United States.

<div align="center">

**Figure 2.** Geographic Distribution of Gun Violence Incidents in the U.S.

<img 
  src="https://github.com/user-attachments/assets/e6faa750-2261-41a4-86a9-1785a2d3c330"
  alt="Geographic Distribution of Gun Violence Incidents"
  width="600">

<p align="center">
<i>
Note. This heat map visualization highlights the density of recorded gun violence incidents across the United States, with darker and brighter regions representing areas where incidents occurred more frequently throughout the dataset period.
</i>
</p>

</div>

The temporal analysis revealed a steady increase in recorded incidents between 2013 and 2017 before declining in 2018. This shift in incident levels suggests that gun violence patterns fluctuated over time rather than remaining stable.

<div align="center">

**Figure 3.** Trend of Gun Violence Incident Severity Over Time (2013 - 2018)

<img 
  src="https://github.com/user-attachments/assets/44ce13ce-5a41-4eb3-9c1d-ca1752b07d53"
  alt="Trend of Gun Violence Incident Severity Over Time"
  width="600">

<p align="center">
<i>
Note. This stacked bar chart illustrates how both lower-severity (orange) and no victim (red) gun violence incidents changed over time, showing an increase in incidents through 2017 before declining in 2018.
</i>
</p>

</div>

The demographic analysis depicted adults (18+) as the largest contributor to incidents across all severity categories. However, incidents involving teenagers and children still represented an important public safety concern.

<div align="center">

**Figure 3.** Gun Violence Incidents Over Time by Age Group

<img 
  src="https://github.com/user-attachments/assets/b27fb9df-546c-4603-94fe-b0c85ffa617f"
  alt="Gun Violence Incidents Over Time by Age Group"
  width="600">

<p align="center">
<i>
Note. This line chart compares incident involvement across age groups over time in the country, showing that adults (dark green) consistently represented the largest share of recorded incidents, while incidents involving teenagers (lime green) and children (yellow) remained present at lower but persistent levels throughout the dataset period.
</i>
</p>

</div>

In regards to incident severity, most incidents involved only 1-4 victims (low severity). High-severity incidents were drastically less common but still concentrated in states with the highest overall incident frequency. Overall, the findings demonstrate that gun violence patterns are not evenly distributed across the United States and instead vary significantly by geography, time period, and demographic group.

### Next Steps
If this project were to be further developed in the future, the integration of external datasets related to population densities, income levels, and healthcare access. Combining these variables with the incident data could help explore possible relationships between gun violence and broader social conditions.

The addition of a more detailed demographic analysis, including gender patterns or comparisons between rural and urban areas, would also greatly strengthen this project. Additional interactivity could also improve the user experience by allowing viewers to filter incidents by year, state, or severity level directly within the dashboards.
