# World-Bank-Global-Education-Analysis

This repository is a demonstration of different EdStats Indicators of World Bank on Education [Submission of EDA Project (AlmaBetter Edutech Private Limited)]. The World Bank EdStats (Education Statistics) All Indicator Query holds over 4,000 internationally comparable indicators that describe education access, progression, completion, literacy, teachers, population, and expenditures. The indicators cover the education cycle from pre-primary to vocational and tertiary education and also holds learning outcome data from international and regional learning assessments (e.g. PISA, TIMSS, PIRLS), equity data from household surveys, and projection/attainment data. 

In this project, We are going to explore and analyse the data to identify variation of indicators across the globe, which countries are more alike and different.

**Video demonstration** [click here](https://www.youtube.com/watch?v=MZ5x0zMBiLc)

 **Python libraries used for analysis:** Pandas, Numpy, Matplotlib, Seaborn

**NoteBook:** Colaboratory

**Dataset Sources:** https://pytutorial.com/python-country-list, https://www.a4id.org/policy/understanding-the-developeddeveloping-country-taxonomy/)

## **The list of indicators and countries have been selected for analysis:**

### **The list of indicators have been selected for analysis:**

**The list of indicators have been selected for Adjusted Net Enrolment Rate (AER) of India in different educational levels during 2000-2030**

- Adjusted net enrolment rate, lower secondary, both sexes (%) - UIS.NERA.2

- Adjusted net enrolment rate, lower secondary, female (%) - UIS.NERA.2.F 

- Adjusted net enrolment rate, lower secondary, male (%) - UIS.NERA.2.M 

- Adjusted net enrolment rate, primary, both sexes (%) - SE.PRM.TENR 

- Adjusted net enrolment rate, primary, female (%) - SE.PRM.TENR.FE 

- Adjusted net enrolment rate, primary, male (%) - SE.PRM.TENR.MA 

- Adjusted net enrolment rate, upper secondary, both sexes (%) - UIS.NERA.3  

- Adjusted net enrolment rate, upper secondary, female (%) - UIS.NERA.3.F 

- Adjusted net enrolment rate, upper secondary, male (%) - UIS.NERA.3.M

**The list of indicators have been selected for the population rate of India between 20-24 age group in different educational levels during 2000-2030 (Based on Barro-Lee dataset)**

- Barro-Lee: Percentage of female population age 20-24 with no education - BAR.NOED.2024.FE.ZS 

- Barro-Lee: Percentage of female population age 20-24 with primary schooling. Completed Primary - BAR.PRM.CMPT.2024.FE.ZS

- Barro-Lee: Percentage of female population age 20-24 with secondary schooling. Completed Secondary - BAR.SEC.CMPT.2024.FE.ZS

- Barro-Lee: Percentage of female population age 20-24 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.2024.FE.ZS
 
- Barro-Lee: Percentage of population age 20-24 with no education - BAR.NOED.2024.ZS

- Barro-Lee: Percentage of population age 20-24 with primary schooling. Completed Primary - BAR.PRM.CMPT.2024.ZS

- Barro-Lee: Percentage of population age 20-24 with secondary schooling. Completed Secondary - BAR.SEC.CMPT.2024.ZS

- Barro-Lee: Percentage of population age 20-24 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.2024.ZS

**The list of indicators have been selected for the population rate of India between 25-29 age group in different educational levels during 2000-2030 (Based on Barro-Lee dataset)**

- Barro-Lee: Percentage of female population age 25-29 with no education - BAR.NOED.2529.FE.ZS

- Barro-Lee: Percentage of female population age 25-29 with primary schooling. Completed Primary - BAR.NOED.2529.ZS

- Barro-Lee: Percentage of female population age 25-29 with secondary schooling. Completed Secondary - BAR.PRM.CMPT.2529.FE.ZS

- Barro-Lee: Percentage of female population age 25-29 with tertiary schooling. Completed Tertiary - BAR.PRM.CMPT.2529.ZS
 
- Barro-Lee: Percentage of population age 25-29 with no education - BAR.SEC.CMPT.2529.FE.ZS

- Barro-Lee: Percentage of population age 25-29 with primary schooling. Completed Primary - BAR.SEC.CMPT.2529.ZS

- Barro-Lee: Percentage of population age 25-29 with secondary schooling. Completed Secondary - BAR.TER.CMPT.2529.FE.ZS

- Barro-Lee: Percentage of population age 25-29 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.2529.ZS

**The list of indicators have been selected for the population rate of India between 30-34 age group in different educational levels during 2000-2030 (Based on Barro-Lee dataset)**

- Barro-Lee: Percentage of female population age 30-34 with no education - BAR.NOED.3034.FE.ZS

- Barro-Lee: Percentage of female population age 30-34 with primary schooling. Completed Primary - BAR.PRM.CMPT.3034.FE.ZS

- Barro-Lee: Percentage of female population age 30-34 with secondary schooling. Completed Secondary - BAR.SEC.CMPT.3034.FE.ZS

- Barro-Lee: Percentage of female population age 30-34 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.3034.FE.ZS
 
- Barro-Lee: Percentage of population age 30-34 with no education - BAR.NOED.3034.ZS

- Barro-Lee: Percentage of population age 30-34 with primary schooling. Completed Primary - BAR.PRM.CMPT.3034.ZS

- Barro-Lee: Percentage of population age 30-34 with secondary schooling. Completed Secondary - BAR.SEC.CMPT.3034.ZS

- Barro-Lee: Percentage of population age 30-34 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.3034.ZS

**The list of indicators have been selected for the population rate of India between 35-39 age group in different educational levels during 2000-2030 (Based on Barro-Lee dataset)**

- Barro-Lee: Percentage of female population age 35-39 with no education - BAR.NOED.3539.FE.ZS

- Barro-Lee: Percentage of female population age 35-39 with primary schooling. Completed Primary - BAR.PRM.CMPT.3539.FE.ZS

- Barro-Lee: Percentage of female population age 35-39 with secondary schooling. Completed Secondary - BAR.SEC.CMPT.3539.FE.ZS

- Barro-Lee: Percentage of female population age 35-39 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.3539.FE.ZS
 
- Barro-Lee: Percentage of population age 35-39 with no education - BAR.NOED.3539.ZS
 
- Barro-Lee: Percentage of population age 35-39 with primary schooling. Completed Primary - BAR.PRM.CMPT.3539.ZS

- Barro-Lee: Percentage of population age 35-39 with secondary schooling. Completed Secondary - BAR.SEC.CMPT.3539.ZS

- Barro-Lee: Percentage of population age 35-39 with tertiary schooling. Completed Tertiary - BAR.TER.CMPT.3539.ZS

**The list of indicators have been selected for Capital Expenditure (CapEx) of India in different types of educational institutions during 2000-2030**

- Capital expenditure as % of total expenditure in lower secondary public institutions (%) - UIS.XSPENDP.2.FDPUB.FNCAP

- Capital expenditure as % of total expenditure in primary public institutions (%) - UIS.XSPENDP.1.FDPUB.FNCAP

- Capital expenditure as % of total expenditure in public institutions (%) - UIS.XSPENDP.FDPUB.FNCAP

- Capital expenditure as % of total expenditure in secondary public institutions (%) - UIS.XSPENDP.23.FDPUB.FNCAP

- Capital expenditure as % of total expenditure in tertiary public institutions (%) - UIS.XSPENDP.56.FDPUB.FNCAP

- Capital expenditure as % of total expenditure in upper-secondary public institutions (%) - UIS.XSPENDP.3.FDPUB.FNCAP

**The list of indicators have been selected for the correlation between different factors affecting economic growth of India during 2000-2030**

- Barro-Lee: Percentage of population age 20-24 with no education - BAR.NOED.2024.ZS

- Barro-Lee: Percentage of population age 25-29 with no education - BAR.NOED.2529.ZS

- Barro-Lee: Percentage of population age 30-34 with no education - BAR.NOED.3034.ZS

- Barro-Lee: Percentage of population age 35-39 with no education - BAR.NOED.3539.ZS

- Internet users (per 100 people) - IT.NET.USER.P2

- Personal computers (per 100 people) - IT.CMP.PCMP.P2

- Population growth (annual %) - SP.POP.GROW

### **The list of countries have been selected for analysis:**

**The list of countries have been selected for the population rate in low income group during 2005-2014**

- Afghanistan
- Bangladesh
- Nepal
- Zimbabwe
- Myanmar

**The list of countries have been selected for the population rate in lower middle income group during 2005-2014**

- India
- Sri Lanka
- Pakistan
- Bhutan
- Indonesia

**The list of countries have been selected for the population rate in upper middle income group during 2005-2014**

- China
- Brazil
- South Africa
- Thailand
- Malaysia

**The list of countries have been selected for the population rate of in high income: nonOECD group during 2005-2014**
- Saudi Arabia
- Singapore
- United Arab Emirates
- Kuwait
- Oman

**The list of countries have been selected for the population rate in high income: OECD group during 2005-2014**
- Australia
- Canada
- Japan
- United Kingdom
- United States

**The list of countries have been selected for the population rate in combined income group during 2005-2014**
- India
- China
- United States
- Oman
- Nepal

**The country have been selected which comes under developing country or developed country (based on GDP per capita)?**
- India

**The list of countries have been selected for the GER in different educational levels in 2010**
- India - IND
- Nepal - NPL
- Pakistan - PAK
- China - CHN
- Bangladesh - BGD

