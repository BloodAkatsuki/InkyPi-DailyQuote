# InkyPi Daily Quote Plugin

An [InkyPi](https://github.com/fatihak/InkyPi) plugin that displays a fresh inspirational quote on your e-ink display, fetched daily from ZenQuotes with built-in fallback quotes for offline use.

## Screenshot

<!-- Add a screenshot of the plugin running on your display here -->

## Features

- Fetches a random quote from [ZenQuotes](https://zenquotes.io) on each refresh
- Falls back to a built-in collection of quotes if the API is unavailable
- Three font size options: Small, Normal, Large

## APIs Used

- **[ZenQuotes API](https://zenquotes.io/api)** — free, no API key required. Limited to a reasonable number of requests per day on the free tier.

## Installation

Run the following command on your Raspberry Pi:

```bash
inkypi plugin install daily_quote https://github.com/BloodAkatsuki/InkyPi-DailyQuote
```

## Status

Actively maintained.
