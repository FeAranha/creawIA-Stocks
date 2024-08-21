# [Framework CrewIA](/https://docs.crewai.com)

![image](https://github.com/user-attachments/assets/00c6f09b-3a09-4be1-9793-afb83224cc0b)

Analyse Apple Stocks price history:

- Agent: Stock Price Analyst
  - Tool: Yahoo! Finance
  - Task: Get Stock Price
- Agent: DuckDuckGo Analyst
  - Tool: Search WEB
  - Task: Get News
- Agent: Stock Analyst Write
  - Tool: Tasks delegation
  - Task: Write Analyses