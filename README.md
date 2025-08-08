# AI Web Scraper 2.0

This agent can:

- Search websites.
- Extract and clean text.
- Use AI to summarize context.

## How to Use

Open the bash in the folder you want to save the agent.

```Bash
git clone https://github.com/DataSciGina/ai-web-scraper.git
cd ./ai-web-scraper
```

**Recommendation:** Create virtual environment.

```Bash
python -m venv venv
venv/Scripts/activate
pip install
streamlit run ./ai_web_scraper-2.0.py
```

... and send the URL with the content you want to summarize.

## Tech Stack

- **requests:** Fetches web page data.
- **beautifulsoup4:** Extracts and cleans text from HTML.
- **langchain_ollama:** Uses Ollama for AI-powered summarization.
- **streamlit:** Builds a Web UI for the web scraper.
- **FAISS**
- **ChromaDB:** Vector Database.

## Releases

### 2.0

#### Upgrades

- Storing scraped content in a vector database (FAISS).
- Allows users to search stored knowladge.
- Retrieving relevant content using AI.

#### New Workflow

- Scrape the website.
- Embed the content.
- Store it in FAISS (Vector Database).
- Enable AI-powered search on stored content.

### 1.0

- Search websites.
- Extract and clean text.
- Use AI to summarize context.