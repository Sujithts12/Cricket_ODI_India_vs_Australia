
# Dashboard: ODI – India vs Australia: Visualizing the Game Key Moments & Player Metrics
    
## 📁 Project File
- [cricket.pbix](./cricket.pbix)

## 📊 Power BI Report Download

The report is provided in `.pbix` format and is designed to be opened using **Microsoft Power BI Desktop**.  
Please ensure you have Power BI Desktop installed to view and interact with the dashboard.

Project File

## LinkedIn
https://tinyurl.com/IndiaVsAustraliaDashboard

## Problem Statement

In the world of cricket, analyzing player performance is often challenging due to the availability of raw statistics in scattered formats. While platforms like ESPN Cricinfo provide comprehensive data, the absence of interactive and visually engaging insights makes it difficult for fans, analysts, and coaches to quickly evaluate batting and bowling performance.

The challenge lies in:

Transforming large volumes of raw cricket statistics into meaningful insights.

Enabling player-wise analysis for comparing performance across different matches.

Showcasing key performance indicators (KPIs) like runs, strike rate, wickets, economy rate, etc., in an intuitive and interactive manner.

Enhancing storytelling with visuals and navigation to make cricket analytics more engaging and accessible.


This project addresses these challenges by building an interactive Power BI Dashboard that analyzes batting and bowling statistics of players in India vs Australia ODI matches. The dashboard leverages Cricinfo’s Statsguru data (imported directly from the web) and provides slicers, buttons, and KPI visuals to make performance tracking interactive, insightful, and user-friendly.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a web.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : It was observed that in few of the columns errors & empty values were present.
- Step 4 : Empty values and null values were replaced.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : In the report view, under the insert tab,two text box was added in two report page to the canvas, for highlighting Batting and bowling data 
- Step 7 : Visual filters (Slicers) were added for  field named "Players Name".
- Step 8 : 14 card visuals were added to the Batting Data Analysis canva, representing Runs, Strike rate, Not outs, matches, Innings, Highest score, Number of 6s, Number of 4s, Half Centuries, Centuries, Ball Faced, Zeros, Span. 
- Step 9 : 12 card visuals were added to the bowling Data Analysis canva, representing Runs, Strike rate, Wickets, Over, Maiden Over, Matches, 5 wickets, 4 Wickets, Average, Economy, Winnings, Span.
- Step 10 : A card visual was also added to the both report design area representing the name of the players.
- Step 11 : Python Pandas was used to scrap image URLs from Wikidata to render images dynamically in visual.
  
Above step enabled displaying player profile pictures inside Power BI dashboards, making the analysis more engaging.

- Step 12 : In the report view, under the insert tab, using shapes option from elements group a rectangle and parallelogram was inserted & similarly using image option Indian tricolour flag was added to the report design area.

## 🖼️ Report Snapshot

### 🧢 Batting Performance Report Snapshot (Power BI DESKTOP)

#### 1️⃣ Batting Insights – Part 1
![Batting1](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Batting1.png)

#### 2️⃣ Batting Insights – Part 2
![Batting2](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Batting2.png)

#### 3️⃣ Batting Insights – Part 3
![Batting3](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Batting3.png)

#### 4️⃣ Batting Insights – Part 4
![Batting4](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Batting4.png)

---

### 🎯 Bowling Performance Report Snapshot (Power BI DESKTOP)

#### 1️⃣ Bowling Overview
![Bowling0](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Bowling0.png)

#### 2️⃣ Bowling Insights – Part 1
![Bowling1](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Bowling1.png)

#### 3️⃣ Bowling Insights – Part 2
![Bowling2](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Bowling2.png)

#### 4️⃣ Bowling Insights – Part 3
![Bowling3](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Bowling3.png)

#### 5️⃣ Bowling Insights – Part 4
![Bowling4](https://raw.githubusercontent.com/Sujithts12/Cricket_ODI_India_vs_Australia/main/Bowling4.png)

---

## 👨‍💻 Author
*Dashboard Created By:* Sujith TS 

*Date:* 20th August 2025

## 📂 Download .pbix Project File
- [cricket.pbix](./cricket.pbix)

🎥 [Watch the interactive video demo on LinkedIn] 
## Link : https://tinyurl.com/IndiaVsAustraliaDashboard

## 📌 Data Source WEB
All cricket statistics used in this dashboard have been sourced from  
[ESPN Cricinfo – Statsguru](https://stats.espncricinfo.com/)


