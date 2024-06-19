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
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/3a948eaf-5d1d-421a-a3a0-789195227ad9)


**Top 10 Most Active Days**
Identifies the days with the highest number of messages exchanged, providing insights into peak activity periods.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/a22411d3-1750-4daa-bf3e-8fdee0119043)


**Top 10 Active Users**
Analyzes the participation of users based on the number of messages sent, highlighting the most active contributors.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/65c2209d-a965-4ff9-8b9c-31577156ea96)


**Message Length Analysis**
Examines the average length of messages sent by top users, revealing communication styles and patterns.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/f51d41a2-8278-481d-9d15-67cd0e519ab1)


**Media Usage**
Investigates the frequency of media sharing (images, videos) within the chat, identifying users who share media most frequently.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/c9e3c9af-adbf-44fd-989d-cfb72effe3e7)


**Emoji Analysis**
Quantifies and visualizes the usage of emojis within the chat, revealing popular emoticons and expressions.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/ec6c3965-fd10-4408-a47e-72efb9520fab)


**Temporal Patterns**
Analyzes message exchange patterns throughout the day to identify peak messaging hours.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/9127074e-778c-4162-8b82-5bc79d3986d9)


**Heatmap Analysis**
Combines day-wise and month-wise message counts into a heatmap to visualize communication patterns over different time frames.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/cc4beb63-5f98-4eb9-8188-603ec410caa3)


**WordCloud Analysis**
Generates a WordCloud to highlight the most frequently used words in the chat, excluding common stopwords.
![image](https://github.com/SolankiRahul3307/Capstone_Project---WhatsApp_Chat_Analysis/assets/140326711/be712435-ddbd-4ad2-b2e7-a271679c2da9)

