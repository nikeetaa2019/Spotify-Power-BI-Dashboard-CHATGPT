# Spotify-Power-BI-Dashboard-CHATGPT
A Data Visualization Project using Power BI &amp; ChatGPT
Project Overview

This project presents a Spotify Top Songs Dashboard built using Power BI.
The goal was to transform raw Spotify dataset into meaningful insights about artists, tracks, popular genres, streams, and performance trends.

I also used ChatGPT to support the data cleaning steps, DAX creation, summary writing, and dashboard storytelling — making the workflow faster and more efficient.

🚀 Key Features
1️⃣ Overview Page

Total songs, artists, and streams

Popular genres

Trends and patterns in listening behaviour<img width="592" height="330" alt="Song page" src="https://github.com/user-attachments/assets/f8f42b08-c714-47a7-8f3d-844f97ed7db2" />
<img width="599" height="337" alt="Overview page" src="https://github.com/user-attachments/assets/25e9e6a4-6c78-4bc5-816b-1cfd0e06e3d8" />
<img width="596" height="335" alt="Index page" src="https://github.com/user-attachments/assets/443955b3-9ae7-4a17-bbcf-2077b1117c1a" />
<img width="601" height="332" alt="Artist Page" src="https://github.com/user-attachments/assets/857b7c7c-10fe-43f9-8ac3-45c001aca845" />


2️⃣ Artist Analysis Page

Artist-wise performance

Total streams by artist

Top tracks for each artist

3️⃣ Songs Insight Page

Song duration vs popularity

Track-level KPIs

Filters by mood, genre, and artist

🛠️ Tools & Technologies

Power BI Desktop

Power Query (Data Cleaning)

DAX (Measures & Calculations)

ChatGPT (for data transformation guidance and insight generation)

Spotify Dataset (CSV)

🔍 Important DAX Measures Used
Total Streams = SUM(Songs[Streams])

Average Popularity = AVERAGE(Songs[Popularity])

Total Duration (Minutes) = 
SUM(Songs[Duration_ms]) / 60000

📈 Insights Generated

Most streamed artists and top-performing songs

Peak popularity patterns

Relationship between duration, popularity, and stream count

Genres that dominate global listening

Artist contribution to total streams

🎯 Purpose of the Project

Strengthen Power BI data modelling skills

Practice dashboard design & storytelling

Learn better DAX usage

Integrate AI support (ChatGPT) into analytics workflow

Build a portfolio-ready project for recruiters and hiring managers
