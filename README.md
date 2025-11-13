🎧 Spotify Music Insights Dashboard (Power BI + DAX)

This project transforms raw Spotify listening history into a fully interactive analytics dashboard.
The goal was simple: turn everyday music habits into meaningful insights using Power BI and advanced DAX.

🎯 Overview

Streaming habits reveal patterns — genres you gravitate toward, listening hours, favorite artists, mood shifts, and more.
This dashboard digs deeper into your Spotify data and answers:

Which artists dominated your year?

How did your listening patterns evolve over time?

What percentage of your library contains explicit tracks?

What’s the average length of your sessions?

How popular are the songs you listen to?

Built using Spotify CSV export and advanced DAX measures, this dashboard uncovers hidden trends in your music taste.

🧠 Features
✔ Listening Overview

Total Songs Played

Distinct Songs

Distinct Artists

Total Duration Played (minutes/hours)

✔ Song Popularity Metrics

Average Popularity

Max/Min Popularity

Avg Duration (in minutes)

✔ Explicit vs Non-Explicit Analysis

Explicit Song Count

Non-Explicit Song Count

% Explicit Tracks

✔ Music Type Breakdown

Albums vs Singles

Position 1 hits

Historical / yearly trends

✔ Deep Interactivity

Clean drill-downs, filter panels, and time-based exploration.

⚙️ Tech Stack

Power BI Desktop & Power BI Service

Spotify Listening History (CSV Export)

Advanced DAX (via DAX Query View)

Data Modeling

Custom Measures & Time Intelligence

🧩 DAX Measures Implemented

Using DAX Query View, dozens of measures were batch-created efficiently, including:

📌 Core Metrics

Total Songs

Distinct Songs

Distinct Artists

Total Listening Minutes

📌 Popularity Metrics

Avg Popularity

Max Popularity

Min Popularity

Avg Song Duration (in minutes)

📌 Explicit Analysis

Explicit Count

Non-Explicit Count

% Explicit Tracks

📌 Music Breakdown

Album Count

Single Count

Position 1 Hits

Songs by Year

Monthly Trend

📊 Dashboard Visuals

The final Power BI report includes:

KPI Cards for high-level metrics

Bar Charts for artist/album dominance

Donut Charts for explicit breakdown

Line Charts for monthly or yearly patterns

Tables for detailed track-level analysis

Filter Pane for genre, year, artist, mood

Every visual adds depth to your listening behavior.

🔍 Key Insights from the Analysis

Top artists dominate a major share of listening time

High explicit-track share reflects genre & mood patterns

Popularity scores reveal preference for mainstream or niche music

Time-series trends show how listening behavior changes through the year

📁 Dataset

Exported from Spotify’s “Download your data” feature (CSV files)

Includes fields such as track name, artist, played timestamp, duration, popularity, explicit flag, album type, etc.

🎥 Demo

Attached in the repository or README assets:
A short video demo showcasing dashboard interactivity and key visuals.

🚀 How to Use This Project

Export your Spotify data (CSV)

Load it into Power BI

Apply the data model & measures

Publish to Power BI Service (optional)

Explore your own listening insights

🏁 Summary

This project combines music + analytics, turning your Spotify habits into a rich visual story using Power BI and DAX.
It’s a perfect blend of data modeling, visualization, and storytelling — showing how everyday data can reveal real patterns.
