# 🧠 AI Insurance Agent

A pipeline for automatically scraping, classifying, summarizing, and reporting insurance-relevant articles — tailored for insurance agents to stay informed on climate risk, market trends, and more.

---

## 🗂️ Project Structure

```css
ai-insurance-agent/
│
├── src/
│   ├── scraper.py              # Web/news API scraping logic
│   ├── classify.py             # Classify article into domain (e.g., Climate Risk)
│   ├── dashboard.py            # Homepage/dashboard logic
│   ├── insights.py             # Generate insights from processed articles
│   ├── article_sorting.py      # Score and sort articles by relevance
│   ├── summarizer.py           # LLM-based summary generation
│   ├── report_generator.py     # Generate final structured report
│
├── requirements.txt
├── README.md
└── main.py                    # Orchestrates the full flow

```

## 🚀 How It Works Project

Scraping: Uses scraper.py to fetch relevant articles from the web or news APIs.

Classification: Articles are categorized into domains (e.g., Climate Risk) using classify.py.

Scoring & Sorting: article_sorting.py evaluates and prioritizes articles by relevance.

Summarization: summarizer.py utilizes LLMs to condense articles into concise summaries.

Insight Generation: insights.py derives key insights and takeaways.

Reporting: report_generator.py compiles a final structured report (reports.json).

Dashboard: dashboard.py powers the homepage interface to view outputs.

```

## 🛠️ Setup Instructions
1. Clone the Repository

```css
git clone https://github.com/NomikaGajula/ai-insurance-agent.git
cd ai-insurance-agent
```
---

