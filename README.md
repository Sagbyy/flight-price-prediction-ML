# Flight Price Prediction ML Project

This project implements a machine learning model to predict flight prices based on various features such as airline, source, destination, stops, and timing information. The model helps users estimate flight costs for better travel planning.

## Project Overview

The project analyzes a dataset of flight information to build a predictive model for flight prices. It includes:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model development and evaluation

## Dataset

The dataset (`data/flight_dataset.csv`) contains flight information with the following features:

- Airline
- Source and Destination cities
- Number of stops
- Flight duration
- Departure and Arrival times
- Price (target variable)
- Date information (Day, Month, Year)

## Setup

### Prerequisites

- Python 3.12
- Conda (for environment management)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/flight-price-prediction-ML.git
cd flight-price-prediction-ML
```

2. Create and activate the Conda environment:

```bash
conda env create -f environment.yml
conda activate flight-price-prediction-ML
```

## Project Structure

```
flight-price-prediction-ML/
├── data/
│   └── flight_dataset.csv    # Flight price dataset
├── environment.yml           # Conda environment configuration
├── notebook.ipynb           # Jupyter notebook with analysis
├── instruction.pdf          # Project instructions
└── README.md               # Project documentation
```

## Dependencies

The project uses the following main Python libraries:

- numpy
- pandas
- matplotlib
- jupyter
- scipy
- seaborn
- plotly

All dependencies are specified in the `environment.yml` file.

## Usage

1. Activate the Conda environment:

```bash
conda activate flight-price-prediction-ML
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `notebook.ipynb` to view the analysis and model development process.

## Analysis Features

The notebook includes:

- Data loading and exploration
- Feature preprocessing and engineering
- Visualization of flight distributions
- Price prediction model development

## Contributing

Feel free to fork the project and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.
