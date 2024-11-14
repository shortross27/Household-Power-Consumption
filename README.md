# Individual Household Electric Power Consumption Dataset
This dataset contains measurements of electric power consumption in a single household over a period of nearly four years. The data was recorded every minute and includes various electrical quantities and sub-metering values, making it suitable for time series analysis, energy forecasting, anomaly detection, and data visualization tasks.

## Dataset Information
- **Source:** UCI Machine Learning Repository
- **Creator:** Georges Hebrail (GE Medical Systems)
- **Data Format:** .txt
- **Size:** ~20MB
- **Time Period:** December 2006 - November 2010

## Features
The dataset consists of the following attributes:

- **Date:** Date in the format dd/mm/yyyy
- **Time:** Time in the format hh:mm:ss
- **Global_active_power:** Household global active power in kilowatts
- **Global_reactive_power:** Household global reactive power in kilowatts
- **Voltage:** Minute-averaged voltage in volts
- **Global_intensity:** Household global intensity (current) in amperes
- **Sub_metering_1:** Energy sub-metering No. 1 (in watt-hours of active energy) – typically for the kitchen
- **Sub_metering_2:** Energy sub-metering No. 2 (in watt-hours of active energy) – typically for laundry
- **Sub_metering_3:** Energy sub-metering No. 3 (in watt-hours of active energy) – typically for climate control systems

## Missing Values
This dataset has some missing values that are indicated by the symbol ?. Handling these missing values through imputation or removal is recommended before performing any analysis.

## Getting Started
### Prerequisites
- Python 3.6+
- Libraries: pandas, numpy, matplotlib (for basic data handling and visualization)

## Potential Applications
- **Energy Forecasting:** Predict household energy consumption patterns.
- **Anomaly Detection:** Identify unusual spikes in power usage.
- **Load Profiling:** Segment data by different usage patterns.
- **Correlation Analysis:** Investigate relationships between features (e.g., voltage and active power).

## License
Please refer to the UCI Machine Learning Repository for any licensing or usage terms for this dataset.
