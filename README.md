

---

# Stock News Alerter

This Python-based Stock News Alerter keeps you updated with the latest market developments by sending real-time alerts to your phone and email. Whether it's major price changes, earnings reports, or breaking news, this tool ensures you stay informed and make timely decisions.

## Features

- **Real-Time Alerts**: Get immediate notifications on significant stock news.
- **Customizable Tracking**: Monitor specific stocks based on your interests.
- **Multiple Alert Channels**: Receive updates via SMS and email.
- **User-Friendly Interface**: Easy setup and configuration for personalized alerts.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/stock-news-alerter.git
   cd stock-news-alerter
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

1. **Set up your API keys**:
   - **Stock News API**: Sign up for a stock news API and add your API key to the `config.py` file.
   - **Twilio API (for SMS)**: Sign up for Twilio, then add your SID, Auth Token, and phone number to the `config.py` file.
   - **SMTP settings (for Email)**: Add your email provider's SMTP settings in `config.py`.

2. **Customize your alerts**:
   - Edit `stocks_to_track.txt` to include the stocks you want to monitor.
   - Adjust the alert conditions in `config.py` to your preferences.

## Usage

Run the program with:

```bash
python stock_news_alerter.py
```

The script will start monitoring the selected stocks and send alerts as configured.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
