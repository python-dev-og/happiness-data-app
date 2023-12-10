![Python Version](https://img.shields.io/badge/python-3.11-blue.svg)
![Pandas Version](https://img.shields.io/badge/pandas-2.1.4-blue.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Streamlit](https://img.shields.io/badge/made%20with-Streamlit-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)


# In Search for Happiness: Data Visualization 

## Project Overview

"In Search for Happiness" is an interactive data visualization web application built using Streamlit and Plotly. It allows users to explore relationships between different factors such as GDP, Happiness, and Generosity. The application provides a user-friendly interface to select data for the X and Y axes and visualizes the relationship through a scatter plot.

## Features

- **Interactive Axis Selection**: Users can select the data to be displayed on the X-axis and Y-axis from the options: GDP, Happiness, and Generosity.
- **Dynamic Data Visualization**: Based on the user's selection, the application dynamically generates a scatter plot to represent the relationship between the chosen variables.
- **Responsive Design**: The application is built to adapt its layout for different screen sizes and devices.

## Installation

To run this project, you need to have Python installed on your system along with the following packages:

- Streamlit
- Plotly
- Pandas

You can install these packages using pip:

```bash
pip install streamlit plotly pandas
```

## Usage

1. Clone the repository or download the source code.
2. Navigate to the folder containing the application.
3. Run the application using Streamlit:

   ```bash
   streamlit run app.py
   ```

4. The application should now be running on your local server. By default, it can be accessed at `http://localhost:8501`.

## Data Source

The application uses a dataset named `happy.csv`, which should contain columns corresponding to GDP, Happiness, and Generosity. Ensure that this dataset is present in the same directory as the application.

## Contributing

Contributions to enhance the application are welcome. Please follow standard coding practices and ensure proper documentation when submitting pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE.md).

## Acknowledgments

- Streamlit and Plotly teams for their excellent libraries.
- The dataset providers for the comprehensive data enabling this analysis.


![Screenshot 2023-12-10 at 1.48.47 PM.png](..%2F..%2F..%2F..%2F..%2FDesktop%2FScreenshot%202023-12-10%20at%201.48.47%E2%80%AFPM.png)