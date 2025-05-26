# IFIHPAIdata: Highly Pathogenic Avian Influenza Data

## Introduction

IFIHPAIdata is a project that provides data on Highly Pathogenic Avian Influenza (HPAI) detections in wild birds. This data is compiled from publicly available resources and aims to be a valuable resource for researchers, policymakers, and the general public interested in tracking and understanding the spread of HPAI.

## Data Source

The data presented in this project was sourced from the Animal and Plant Health Inspection Service (APHIS), a part of the United States Department of Agriculture (USDA).

- **URL:** [https://www.aphis.usda.gov/livestock-poultry-disease/avian/avian-influenza/hpai-detections/wild-birds](https://www.aphis.usda.gov/livestock-poultry-disease/avian/avian-influenza/hpai-detections/wild-birds)
- **Date Accessed:** February 28, 2025

## Data Description

The core data is contained in the `HPAI_data.csv` file. This file is a comma-separated values (CSV) document that includes detailed information about each HPAI detection.

Below is a description of each column in the `HPAI_data.csv` file:

- **State:** The US state where the HPAI detection occurred.
- **County:** The county within the state where the HPAI detection occurred.
- **Collection Date:** The date when the sample was collected from the bird.
- **Date Detected:** The date when HPAI was confirmed in the sample.
- **HPAI Strain:** The specific strain of the Highly Pathogenic Avian Influenza virus identified (e.g., H5N1).
- **Bird Species:** The species of the wild bird from which the sample was taken.
- **WOAH Classification:** The classification of the bird species according to the World Organisation for Animal Health (WOAH). WOAH is an intergovernmental organization responsible for improving animal health worldwide.
- **Sampling Method:** The method used to collect the sample (e.g., found dead, hunter-harvested).
- **Submitting Agency:** The agency or organization that submitted the sample for testing.

## Example Usage

The data in `HPAI_data.csv` can be analyzed using various tools that support CSV file formats. For example, users can utilize Python libraries like Pandas, R, or spreadsheet software such as Microsoft Excel or Google Sheets to load, process, and visualize the data.

```python
# Example using Python and Pandas
import pandas as pd

# Load the dataset
df = pd.read_csv('HPAI_data.csv')

# Display the first 5 rows
print(df.head())

# Get a summary of detections by state
print(df['State'].value_counts())
```

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements, find errors in the data, or want to contribute in other ways, please open an issue or submit a pull request on the project repository.

## License

License information is not currently available. Please refer to the data source (USDA APHIS) for any specific terms of use related to the original data.
