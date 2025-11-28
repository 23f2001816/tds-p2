# LLM Analysis Quiz Project (Using AIPipe + GPT-5-nano)


## Key Features

- Uses AIPipe proxy for GPT-5-nano access
- Headless browser for JavaScript rendering
- File download and processing (PDF, CSV, JSON)
- Data analysis with pandas
- Visualization with matplotlib/seaborn
- AI-powered quiz solving
- Automatic answer submission
- Multi-stage quiz handling
- Time-aware processing (under 3 minutes)

## AIPipe Usage

This project uses AIPipe as a proxy to access GPT-5-nano:
- Base URL: https://aipipe.org/openrouter/v1
- Model: openai/gpt-5-nano
- Budget: 10 cents per week (free tier)

## Troubleshooting

ChromeDriver issues:
bash
pip install webdriver-manager


Timeout errors:
- Check internet connection
- Increase timeout values in httpx calls

Memory issues:
- Monitor file sizes (max 1MB for submissions)
- Use data streaming for large files