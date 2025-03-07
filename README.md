# Web and Financial Agent
This project implements two AI agents using the Phi framework: a Web Agent for searching information online and a Finance Agent for retrieving financial data. These agents utilize OpenAI's GPT-4o-mini model and various tools for enhanced functionality.
## **Features**

- **Web Agent**: Uses DuckDuckGo to fetch search results and always includes sources.

- **Finance Agent**: Retrieves stock prices, analyst recommendations, company information, and news using YFinance.

- **Storage**: Utilizes SQLite for storing agent interactions.

- **Playground UI**: Provides a user-friendly interface for interacting with agents.

- **FastAPI Integration**: Uses FastAPI to serve the Playground app.
  ## **Installation**
  Ensure you have Python installed, then install the necessary dependencies:
  ```sh
  pip install phi fastapi uvicorn
  ```
  ## **Code Overview**

- **Web Agent**:

  - Uses DuckDuckGo for web searches.
- **Finance Agent**:

  - Uses YFinanceTools to retrieve financial data.

