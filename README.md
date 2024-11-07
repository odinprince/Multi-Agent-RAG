This project on a multi-agent internet research assistant using OpenAI Swarm & Llama 3.2.
The app takes a user query, searches the web for it, and turns it into a well-crafted article.

The assistant is built using:
- Ollama for running LLMs locally
- OpenAI Swarm for multi-agent orchestration
- Streamlit for the UI

  
Key component:

1️⃣ Agent 1: Web search and tool use

The web-search agent takes a user query and then use the DuckDuckGo search tool to fetch results from internet.

2️⃣ Agent 2: Research Analyst

The role of this agent is to analyse and curate the raw search results and make them ready to use for the content writer agent.

3️⃣ Agent 3: Technical Writer

The role of technical writer is to use the curated results and turn them into a polished, publication-ready article .

4️⃣ The Chat interface 

Finally we create a Streamlit UI to provide a chat interface for our application. 
