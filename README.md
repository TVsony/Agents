# Web and Finance Agent System
This project integrates various tools and models to create a team of agents capable of retrieving information from the web and financial data sources. 
The agents utilize models like Groq and OpenAI, along with tools such as DuckDuckGo and YFinance, to gather data and present it in a structured format.

## Features
***Web Agent:** Retrieves web search results from DuckDuckGo.

**Finance Agent:** Fetches financial data, such as stock prices, analyst recommendations, and company information, from Yahoo Finance.

**Agent Team:** Combines both agents into a team to handle complex queries that require web and financial data.

### Technologies Used
- Phi: The agent framework used to build and manage the agents.
- Groq: A model that provides high-performance processing for various tasks.
- OpenAI: Another model used for tasks that require natural language understanding (currently commented out).
- DuckDuckGo: A tool to search the web for relevant information.
- YFinance: A tool to access stock market data and financial information.
- dotenv: A Python library used to manage environment variables.
**Setup Instructions**
Prerequisites
Before setting up the project, ensure that you have the following installed:

Python 3.8+.
Pip (Python package manager).

**Install Dependencies**
pip install -r requirements.txt

**Set Up Environment Variables**
API_KEY=<your-api-key>


Example Outputs
Query: "Summarize analyst recommendations and share the latest news for NVDA"

Expected Output:

Analyst recommendations for NVDA.
Latest news articles related to NVDA.
The results will be displayed in a structured format (tables, markdown).

Contributing
Feel free to fork the repository, create issues, and submit pull requests. Contributions to improve the functionality of agents or add new tools are welcome.
