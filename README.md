# Commodity Price Forecasting MVP

This project is a Minimum Viable Product (MVP) for predicting the future prices of 22 agricultural commodities using SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) model. The application allows users to select any commodity from a dropdown menu and visualize the forecasted price trend along with the year-wise values.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

## Technologies Used

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Flask (or Streamlit if using web-based deployment)
- Plotly (for interactive graph visualization)

## Project Structure

```bash
├── agripricepredictor.py # Main application file
├── DatasetSIH1647.csv    # Dataset for 22 commodities with year-wise price data
├── requirements.txt      # Python dependencies
└── README.md             # This file
```

## Installation

### Prerequisites

- Make sure you have **Python 3.10** or later installed.
- Install `pip` if it's not already installed on your system.

### Setup

1. **Clone the repository** to your local machine:

```bash
git clone https://github.com/Debajyoti137/Predicting_Prices_of_Agri-Horticulture_Commodities
cd predicting-prices-of-agri-horticultural-commodities-using-ai-ml
```

2. **Install dependencies** using the following command:

```bash
pip install -r requirements.txt
```

3. **Set up the dataset**: Ensure `DatasetSIH1647.csv` is placed in the root directory with the correct format.

## Usage

1. **Run the application**:

   To start the Streamlit application, run the following command in your terminal:

   ```bash
   streamlit run agripricepredictor.py
   ```

2. **Open the browser** and navigate to `http://localhost:8501` (or appropriate local server for Streamlit).

3. **Select a commodity**: Use the dropdown menu to select a commodity and click on "Submit."

4. **View the forecast**: The app will display a graph showing the price forecast of the selected commodity along with year-wise predicted values.

## Example

Once the application is running, selecting "Rice" from the dropdown will display a line graph forecasting rice prices from 2025 to 2029, along with the actual price values for 2014–2024.

## License

This project is licensed under the MIT License.
