# Patient Demographics Dashboard

## Overview

The Patient Demographics Dashboard is an interactive Jupyter Notebook that provides visualizations and analysis of patient demographic data. The dashboard includes various analyses such as age distribution, gender distribution, ethnicity distribution, insurance type distribution, and marital status distribution.

## Features

- **Interactive Visualizations**: Uses Plotly for creating interactive histograms and charts.
- **Age Group Analysis**: Visualizes the distribution of patients across different age groups.
- **Gender Analysis**: Shows the distribution of patients by gender and within age groups.
- **Ethnicity Analysis**: Displays the distribution of patients by ethnicity.
- **Insurance Analysis**: Illustrates the distribution of patients by insurance type.
- **Marital Status Analysis**: Presents the distribution of patients by marital status.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/patient-demographics-dashboard.git
    cd patient-demographics-dashboard
    ```

2. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    ```sh
    jupyter notebook
    ```

## Usage

1. Open the `dashboard.ipynb` file in Jupyter Notebook.
2. Run all the cells to load the data and initialize the dashboard.
3. Use the dropdown menu to navigate through different analysis pages.

## Data

The dataset used in this dashboard is a sample CSV file named `patients.csv` located in the `extracted_data` directory. The file contains the following columns:

- `ID`: Unique identifier for each patient.
- `DOB`: Date of birth of the patient.
- `GENDER`: Gender of the patient.
- `ETHNICITY`: Ethnicity of the patient.
- `INSURANCE`: Type of insurance the patient has.
- `MARITAL_STATUS`: Marital status of the patient.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or inquiries, please contact Naila Rais at naila123rais@gmail.com
