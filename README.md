
# 🌍 Earthquake Insight: Real-Time Data Fetcher using Python APIs

A mini-project built using Python's built-in libraries to fetch real-time earthquake data from the USGS (United States Geological Survey) API based on timestamp and magnitude filters.

This project helps in understanding how to:
- Work with real-world public APIs
- Make HTTP requests using `urllib`
- Handle JSON responses
- Deal with timestamps using `datetime`
- Filter and display meaningful data


## 📌 Features

- 📅 Fetch earthquake data from a specific date range
- 🌐 Uses USGS public API (no authentication required)
- 🔍 Filters by minimum magnitude
- 🕒 Converts UNIX timestamps to human-readable datetime
- 🐍 Uses only built-in Python libraries — no external dependencies
## 🚀 How to Run

1. Clone the Repository
```bash
git clone https://github.com/your-username/earthquake-insight.git
cd earthquake-insight
```

2. Run the Script
```
python fetch_quakes.py
```

3. Input When Prompted
```
Enter number of past days (e.g., 3)

Enter minimum magnitude (e.g., 4.5)
```
