# 🚀 Neuracraft Researcher

## 🚀 Quickstart

**Prerequisites**: Install [uv](https://docs.astral.sh/uv/) package manager:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Install packages:

```bash
uv sync
```

Set your API keys in your environment:

```bash
export ANTHROPIC_API_KEY=your_anthropic_api_key_here  # Required for Claude model
export GOOGLE_API_KEY=your_google_api_key_here        # Required for Gemini model ([get one here](https://ai.google.dev/gemini-api/docs))
export TAVILY_API_KEY=your_tavily_api_key_here        # Required for web search ([get one here](https://www.tavily.com/)) with a generous free tier
export LANGSMITH_API_KEY=your_langsmith_api_key_here  # [LangSmith API key](https://smith.langchain.com/settings) (free to sign up)
```

## Usage 

Run a local [LangGraph server](https://langchain-ai.github.io/langgraph/tutorials/langgraph-platform/local-server/) with a web interface:

```bash
uv run langgraph dev
```

LangGraph server will open a new browser window with the Studio interface, which you can submit your search query to:

<img width="2869" height="1512" alt="Screenshot 2025-11-17 at 11 42 59 AM" src="https://github.com/user-attachments/assets/03090057-c199-42fe-a0f7-769704c2124b" />
