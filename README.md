# Real-Time Stock Data Visualization
## Project Structure:
```
websocket-stock-data/
│
├── app.py                     # Main application entry point (WebSocket client + tabular storage + visualization)
├── requirements.txt            # Python dependencies
├── Dockerfile                  # Docker configuration
├── .dockerignore               # Files to ignore during Docker build
├── .github/
│   └── workflows/
│       └── ci.yml              # GitHub Actions workflow for CI/CD
│
├── data/
│   ├── stock_data.csv          # CSV file to store the tabular data
│   └── sample_data.json        # Example of incoming JSON data
│
├── tests/
│   ├── test_app.py             # Unit tests for app.py (test WebSocket connection, parsing, and storage)
│   └── __init__.py             # Init file for the tests module
│
├── utils/
│   ├── websocket_utils.py      # Helper functions to handle WebSocket connection and JSON parsing
│   └── visualization_utils.py  # Helper functions to create stock data visualizations
│
├── static/
│   └── stock_plots/            # Directory to store generated stock data visualizations
│
└── README.md                   # Project documentation (overview, setup instructions, etc.)
```
