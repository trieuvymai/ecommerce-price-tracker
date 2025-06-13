# E-commerce Price Tracker 🛒

## Features
- Scrapes real-time prices from Amazon and eBay
- Stores historical prices
- Alerts on price drops below threshold
- Streamlit dashboard for trends and summaries

## How to Run
```bash
pip install -r requirements.txt
streamlit run main.py
```

## Configuration
Update `config.json` to add products:
```json
{
  "products": [
    {
      "url": "https://www.amazon.com/dp/B0949M5M7X",
      "site": "Amazon",
      "name": "Sample Product",
      "base_price": 99.99,
      "threshold": 95.00
    }
  ]
}
```

## License
MIT
