# Weather Prediction vs. Actual Comparison

This project compares weather predictions with actual weather data to evaluate the accuracy of the forecast. The goal is to analyze how well weather forecasts align with real-world conditions.

The analysis is performed using the `weather_prediction_evaluation.ipynb` Jupyter notebook, which contains all the code necessary to load, process, and compare the forecast data with the real-world weather measurements.

## Overview

Weather forecasts are an essential part of daily life, yet they are not always perfectly accurate. This project aims to analyze how accurate weather predictions are by comparing them with actual weather data.

The analysis is performed using the `weather_prediction_evaluation.ipynb` Jupyter notebook, which contains all the code necessary to load, process, and compare the forecast data with the real-world weather measurements.

## Set-Up

You will need to set up a few things before running the project


### Download files

To download the required files you will:

1.) Clone this repository 

```bash
git clone https://github.com/TheJoshBrod/ForecastEvaluator.git
```

2.) Navigate to the proper folder

```bash
cd ForecastEvaluator
```

3.) Open the Jupyter notebook file (vscode has a [free extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter))

```bash
code .
```

### Jupyter Notebook Requirements

Before running the project, ensure you have the following dependencies installed:

- Python >= 3.12.6
- Jupyter Notebook
- Required Python libraries

You can install the required dependencies using `pip`:

```bash
pip install -r Requirements.txt 
```

### API key

To run the project you will also need an API key from:

https://www.weatherapi.com/

WeatherAPI has a free tier api token that can be used for this project

Once you create an account and generate an API key create a `.env` file formatted as:

```.env
weatherApiKey = "<API KEY HERE>"
```

Note: `weather_prediction_evaluation.ipynb` uses the python-dotenv library to locally and securely load the .env file for storing and accessing your API key.

## Running the file

The project will take you step by opening the `weather_prediction_evaluation.ipynb` file and running each cell as it says to. 

PLEASE MIND THE TODOs AND CHANGE APPROPRIATELY TO YOUR NEEDS

## Usage

Once the notebook is running, it will:

- Load weather prediction data and actual weather measurements.
- Perform an analysis comparing the accuracy of the predictions.
- Generate visualizations and statistical insights into the accuracy of the weather forecasts.

You can customize the analysis by adjusting input parameters or using different datasets.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or bug fixes. Contributions are welcome!

## License

This project is open-source and available under the MIT License.