# Track-Slack
Developing a real-time chat analysis tool leveraging NLP and machine learning to extract insights, monitor sentiment, and enhance user engagement

Blog link: https://sites.google.com/view/trackslack?usp=sharing

# Chat Analysis Overview

## Background
Originally, the intention was to analyze Slack data to understand team communication dynamics. However, due to the unavailability of suitable datasets and challenges in data collection, WhatsApp chat data was chosen as an alternative. While the platform differs, the analysis goals remained consistent: to uncover insights into messaging behaviors and patterns within a group setting.

## Features
- **Conversion to DataFrame:** Convert raw WhatsApp chat text files into a structured pandas DataFrame for easy analysis.
- **User Anonymization:** Anonymize usernames in the chat data to ensure privacy while still allowing for user-level analysis.
- **Message Frequency Analysis:** Analyze message frequencies by date, day of the week, month, and user to identify messaging patterns.
- **Visualization:** Generate various plots, including line plots, bar plots, and pie charts, to visualize message patterns and distributions.
- **Emoji Analysis:** Extract and analyze emoji usage in the chat to understand the emotional tone and expressions within the conversations.
- **Active Hours/Days:** Identify the most active hours and days for messaging to optimize communication and engagement.
- **Word Cloud Generation:** Generate word clouds from the chat messages to visually represent the most frequently used words.

## Usage
1. **Install Required Libraries:** Make sure you have the required Python libraries installed, including pandas, matplotlib, seaborn, wordcloud, emoji, and regex.
2. **Provide Chat Data:** Replace the file path in the `rawToDf` function call with the path to your WhatsApp chat text file.
3. **Run the Script:** Execute the script, and it will perform various analyses and generate visualizations based on the chat data.
4. **Explore Insights:** Explore the generated plots and insights to understand messaging patterns, user behavior, and overall dynamics of the WhatsApp group.

*Note: The script assumes a specific format for the WhatsApp chat text file. If your chat file has a different format, you may need to modify the parsing functions accordingly to ensure accurate analysis.*
