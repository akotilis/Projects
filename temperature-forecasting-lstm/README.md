# Temperature Forecasting using LSTM

This project aims to forecast temperature using Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN) that is particularly effective for time series prediction. The project utilizes a dataset containing historical climate data to train the model and make predictions.

## Objectives

- To preprocess and analyze historical temperature data.
- To build and train an LSTM model for temperature forecasting.
- To evaluate the model's performance and visualize the results.

## Project Structure

```
temperature-forecasting-lstm/
├── notebooks/
│   └── Temperature Forecasting using LSTM time series.ipynb  # Jupyter notebook with code and documentation
├── data/
│   └── README.md  # Information about the dataset used
├── requirements.txt  # List of required Python packages
└── README.md  # Main documentation for the project
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/akotilis/temperature-forecasting-lstm.git
   cd temperature-forecasting-lstm
   ```

2. **Install Required Packages**
   It is recommended to create a virtual environment before installing the dependencies. You can use `pip` to install the required packages listed in `requirements.txt`.
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**
   Launch Jupyter Notebook and open the `Temperature Forecasting using LSTM time series.ipynb` file.
   ```bash
   jupyter notebook notebooks/Temperature\ Forecasting\ using\ LSTM\ time\ series.ipynb
   ```

## Key Findings

- The LSTM model was able to capture the temporal patterns in the temperature data effectively.
- Visualizations demonstrate the model's predictions compared to actual temperature values, showcasing its forecasting capabilities.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
