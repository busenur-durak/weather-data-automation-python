# Weather Data Automation

A scheduled Python job that collects Istanbul weather from the Turkish State Meteorological Service, stores it, and sends a warning when the temperature falls below 10°C.

Selenium reads the live page. The job writes CSV and JSON, keeps a 7-day temperature history, draws a weekly trend with Matplotlib, and sends the alert over SMTP.

## Run

```bash
pip install selenium webdriver-manager schedule matplotlib
python weather_automation.py
```

Run it from the `weather_automation` folder.

## Stack

Python, Selenium, schedule, Matplotlib, SMTP

## Author

Busenur Durak · Management Information Systems, İzmir Bakırçay University
