**WhatsApp Chat Analysis**
This project aims to analyze a WhatsApp chat exported in .txt format to gain insights into the messaging behavior of a group or individual over time. The analysis includes visualizations and metrics covering message frequency, active users, message length, emoji usage, and temporal patterns.

Table of Contents
Description
Features
Data Retrieval & Preprocessing
Exploratory Data Analysis
Total Messages Over Time
Top 10 Most Active Days
Top 10 Active Users
Message Length Analysis
Media Usage
Emoji Analysis
Temporal Patterns
Heatmap Analysis
WordCloud Analysis


**Description**

This project analyzes a WhatsApp chat log exported as a .txt file to uncover insights such as message frequency, active users, message length, emoji usage, and temporal patterns. By leveraging Python libraries like pandas, matplotlib, seaborn, and emoji, the project provides visualizations and statistical summaries to understand communication dynamics within the group.

**Features**

Data preprocessing to structure raw chat data into a pandas DataFrame.
Visualizations include bar plots, line graphs, count plots, and heatmaps.
Analysis of message frequency, active users, average message length, media usage, and emoji trends.
WordCloud visualization to showcase the most used words in the chat.
Insights into temporal patterns including most active days, hours, and months.

**Data Retrieval & Preprocessing**

To start the analysis, the WhatsApp chat .txt file was loaded into a pandas DataFrame. Messages were processed to extract timestamps, users, and message content, which were then used for further analysis.

**Exploratory Data Analysis**

**Total Messages Over Time**
Visualizes the frequency of messages over months to identify trends in communication intensity.

**Top 10 Most Active Days**
Identifies the days with the highest number of messages exchanged, providing insights into peak activity periods.

**Top 10 Active Users**
Analyzes the participation of users based on the number of messages sent, highlighting the most active contributors.

**Message Length Analysis**
Examines the average length of messages sent by top users, revealing communication styles and patterns.

**Media Usage**
Investigates the frequency of media sharing (images, videos) within the chat, identifying users who share media most frequently.

**Emoji Analysis**
Quantifies and visualizes the usage of emojis within the chat, revealing popular emoticons and expressions.

**Temporal Patterns**
Analyzes message exchange patterns throughout the day to identify peak messaging hours.

**Heatmap Analysis**
Combines day-wise and month-wise message counts into a heatmap to visualize communication patterns over different time frames.

**WordCloud Analysis**
Generates a WordCloud to highlight the most frequently used words in the chat, excluding common stopwords.
