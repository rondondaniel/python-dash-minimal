# Python Dash Minimal

A minimal Dash application built with Python. This application demonstrates how to build a simple interactive dashboard with dropdown selection and line chart visualization.

## Features

- Interactive dropdown menu for country selection
- Dynamic line chart showing population changes over time
- Clean, responsive UI

## Screenshot

When running the application, you'll see an interface with:
- A title at the top
- A country selection dropdown
- A line chart showing population data over years for the selected country

## Installation

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Setup

Clone this repository:
```bash
git clone git@github.com:rondondaniel/python-dash-minimal.git
cd python-dash-minimal
```

Install the required dependencies:
```bash
pip install -r requirments.txt
```

## Usage

Run the application with:
```bash
python dash_minimal.py
```

Then open your web browser and navigate to:
```
http://127.0.0.1:8050/
```

## Dependencies

- Dash 3.0.4
- Plotly 6.1.2
- Pandas 2.3.0

## Data Source

The application uses the Gapminder dataset which contains information about countries' population, life expectancy, and GDP over time.

## License

MIT
