# FinWebAI

FinWebAI is a versatile, multi-agent system that leverages advanced language models and specialized tools for financial analysis and web search. It integrates Groq, YFinance, and DuckDuckGo to provide insightful financial data, conduct web searches, and summarize information seamlessly.

![Using the agent in playground](Screenshot%202024-12-29%20142633.png)

## Features

### Multi-Agent Architecture
FinWebAI combines the capabilities of multiple agents to handle distinct tasks efficiently:

1. **Web Search Agent**
   - **Purpose**: Searches the web for information.
   - **Tools Used**: DuckDuckGo.
   - **Key Features**:
     - Always includes sources in responses.
     - Displays results in Markdown format.
     - Provides enhanced transparency by showing tool calls.

2. **Finance AI Agent**
   - **Purpose**: Provides detailed financial analysis.
   - **Tools Used**: YFinanceTools.
   - **Key Features**:
     - Summarizes stock prices, analyst recommendations, and stock fundamentals.
     - Displays company news.
     - Uses tables for structured data representation.
     - Ensures transparency by showing tool calls.

### Multi-Agent Collaboration
- **Multi-Agent Team**: Combines the Web Search Agent and Finance AI Agent to deliver comprehensive results.
- **Unified Response**:
  - Uses tables and Markdown formatting for better readability.
  - Includes all relevant sources for information credibility.

## Usage

### FinWebAI Agents
- **Web Search Agent**: Efficiently searches the web and includes sources for all information.
- **Finance AI Agent**: Delivers financial insights with structured data presentation.
- **Multi-Agent System**: Collaborates to generate detailed and reliable responses for complex queries.

### Example Query
- **Query**: "Summarize analyst recommendations and share the latest news for NVDA."
- **Response**: Provides a summary of analyst recommendations, relevant news articles, and key financial metrics for NVIDIA, presented in a clear and structured format.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this software under the terms of the license.

---

For any questions or contributions, feel free to open an issue or submit a pull request on the GitHub repository.

