**Executive Summary**
This report presents a comprehensive analysis of Pakistan's quarterly GDP growth rates, aiming to identify periods of economic recession and assess their severity. Utilizing data from the State Bank of Pakistan, this analysis employs standard economic indicators and methodologies to provide insights into the country's economic performance over recent years.

**Data Collection**
The dataset underpinning this analysis was sourced from the State Bank of Pakistan's official website (https://www.sbp.org.pk/ecodata/index2.asp). This website offers a wealth of economic data, including quarterly GDP growth rates, which serve as a critical indicator of the country's economic health. The data was collected by navigating the website's sections dedicated to economic data, selecting the relevant timespan, and downloading the quarterly GDP growth rates. The downloaded data was then compiled into an Excel spreadsheet, QGDP.xlsx, for further analysis.

**Data Preprocessing**
Prior to analysis, the dataset underwent a series of preprocessing steps to ensure accuracy and relevance:

**Loading the Data:** The dataset was loaded into a pandas DataFrame, a structure that facilitates data manipulation and analysis in Python.
Initial Review: A preliminary examination of the data was conducted to understand its structure, which includes the fiscal year and the GDP growth rate for each quarter.
**Data Cleaning:** Although the dataset was relatively clean, given its source, it was necessary to verify the consistency of the format, especially the fiscal year notation and the numerical representation of the growth rates.
Recession Analysis
A recession is typically defined as two consecutive quarters of negative GDP growth. This analysis sought to identify such periods within the dataset by:

**Marking Negative Growth:** Each quarter with negative GDP growth was flagged.
Identifying Consecutive Negative Growth: The analysis pinpointed quarters where negative growth occurred consecutively, adhering to the recession definition.
Highlighting Recession Periods: Based on the identification of consecutive negative growth, specific periods were highlighted as potential recessions.
Severity of the Recession
The severity of identified recessions was evaluated based on the depth and duration of the economic contraction. This involved calculating the total number of consecutive quarters of negative growth and the cumulative GDP contraction during these quarters. A severe recession is characterized by significant declines in GDP over multiple quarters, reflecting pronounced economic downturns.

**Results**
The analysis revealed two significant periods of economic contraction that could be characterized as recessions:

Fiscal Year 2019-20: This period saw a sharp contraction, with a notable quarter experiencing a GDP decline of -8.02%.
Fiscal Year 2022-23: Another period of economic downturn was identified, with a quarter showing a -2.72% decline in GDP.
These findings were visualized through a graph that plotted the quarterly GDP growth rates over time, with recession periods highlighted. This visualization aids in understanding the temporal dynamics of economic performance and the impact of recessions.

Conclusion
The analysis, grounded in economic theory and leveraging data from the State Bank of Pakistan, underscores the utility of GDP growth rates as an indicator of economic health. By identifying and assessing periods of recession, this report contributes to a nuanced understanding of Pakistan's economic challenges and resilience. The insights derived from this analysis not only shed light on past economic performance but also provide a basis for informed policy-making and future research.
