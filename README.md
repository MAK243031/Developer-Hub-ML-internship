# Anomaly Detection in Time Series Data

This project explores different techniques for detecting anomalies in time series data. The analysis is performed on real-life data related to CPU utilization of an EC2 instance.

## Data

The dataset used in this project is the `ec2_cpu_utilization_24ae8d.csv` file from the Numenta Anomaly Benchmark (NAB) repository.

-   **Dataset:** [https://github.com/numenta/NAB/blob/master/data/realAWSCloudwatch/ec2_cpu_utilization_24ae8d.csv](https://github.com/numenta/NAB/blob/master/data/realAWSCloudwatch/ec2_cpu_utilization_24ae8d.csv)
-   **Labels:** [https://github.com/numenta/NAB/blob/master/labels/combined_labels.json](https://github.com/numenta/NAB/blob/master/labels/combined_labels.json)

The dataset contains 4032 data points recorded every 5 minutes, starting on February 14th at 14:30. It is available under the AGPL-3.0 license.

## Dependencies

The following Python libraries are required to run this notebook:

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   sklearn
-   scipy

## How to Run

1.  Open the notebook in Google Colab.
2.  Ensure you have downloaded the `ec2_cpu_utilization_24ae8d.csv` file and placed it in a directory named `data` in the same location as your notebook, or update the file path in the notebook accordingly.
3.  Run all the cells in the notebook.

## Methods Explored

The notebook demonstrates the application of the following anomaly detection techniques:

-   Median Absolute Deviation (MAD)
-   Isolation Forest
-   Local Outlier Factor (LOF)
