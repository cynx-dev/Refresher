# URL Refresher Tool

A simple Python tool that repeatedly sends requests to a specified URL at random intervals.
It can be used to simulate page activity, test endpoint availability, or automatically refresh pages for monitoring purposes.

## Features

* Simple command-line interface
* Random refresh intervals (1–5 seconds)
* Colored console output
* Custom URL input
* Lightweight and easy to run

## How It Works

The script continuously sends HTTP requests to a given URL using Python's `requests` library.
Between each request, the program waits for a random amount of time to simulate non-constant traffic.

## Example Use Cases

* Testing if a webpage or endpoint stays responsive
* Monitoring uptime of small web services
* Simulating basic traffic for development/testing
* Automatically refreshing a page without opening a browser

## Requirements

* Python 3
* `requests`
* `colorama`

Install dependencies:

```bash
pip install requests colorama
```

## Usage

Run the script:

```bash
python main.py
```

Then enter the URL you want to refresh when prompted.

Example:

```
Enter the URL to refresh: https://example.com
```

The program will then send requests to the URL at random intervals.

## Important

This tool is intended for **testing, educational purposes, and monitoring your own services**.
Always respect the terms of service of websites and avoid using it in ways that could negatively impact others.

## Author

Created by **@cynx**
