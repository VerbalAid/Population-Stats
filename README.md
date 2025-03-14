# Interactive Dashboard

This is a simple interactive dashboard built with Dash, Plotly, and Bootstrap. The dashboard allows users to select a year from a dropdown and view a bar chart showing the GDP per capita for different countries in that year.

## Features:
- **Year Selection**: Users can choose a year to filter the data.
- **Interactive Bar Chart**: The bar chart updates based on the selected year, displaying GDP per capita for different countries.

## Requirements:
- Python 3.x
- Dash
- Plotly

## Installation:

1. Clone this repository:
    ```bash
    git clone <repository-url>
    ```

2. Install required libraries:
    ```bash
    pip install dash plotly
    ```

## Running the App:

1. Navigate to the project directory and run the app:
    ```bash
    python app.py
    ```

2. Open a browser and go to `http://127.0.0.1:8050` to view the dashboard.

## Customization:
- Replace the sample data (`px.data.gapminder()`) with your own dataset by modifying the `df` variable.
- Add more interactive components or visualizations as needed.

## License:
This project is open-source and available under the MIT license.
