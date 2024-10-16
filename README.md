# Stock Price Alert and News Notification System

This project monitors stock prices, fetches relevant news articles, and sends notifications using Twilio SMS. It's built using Python and integrates with APIs like Alpha Vantage for stock prices and News API for the latest news.

## Features
- **Stock Price Monitoring:** Compares stock prices between yesterday and the day before.
- **News Fetching:** Retrieves the top 3 news articles if the stock price changes significantly.
- **SMS Notifications:** Sends the articles to a specified phone number using Twilio.

## Technologies Used
- **Python** for scripting
- **Alpha Vantage API** for stock data
- **News API** for fetching news articles
- **Twilio API** for sending SMS messages
- **Flask (optional)** for integrating with a web-based front end

## Getting Started

### Prerequisites
- Python 3.x installed on your system
- `requests` library for handling HTTP requests
- Twilio account for sending SMS messages
- Alpha Vantage API key for accessing stock data
- News API key for fetching news articles


  ### Installation

1. **Set up the required accounts:**
   - **Twilio**: Create a Twilio account [here](https://www.twilio.com/try-twilio). You'll need to obtain your Account SID and Auth Token from the Twilio dashboard.
   - **News API**: Sign up for a News API account [here](https://newsapi.org/register) to get your API key.
   - **Alpha Vantage**: Register for an Alpha Vantage account [here](https://www.alphavantage.co/support/#api-key) to get your API key.

2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
