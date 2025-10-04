# Scraping niche YouTube automation

## Configuration

Set the YouTube Data API key as an environment variable before running the scraper:

```bash
export YOUTUBE_API_KEY="your-api-key"
python scraper
```

The scraper will read the `YOUTUBE_API_KEY` variable at startup and exit with an error if it is not provided.
