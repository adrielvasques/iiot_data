# Real Sensor Data from Manufacturing Equipment

This repository contains structured real sensor data from two pieces of equipment within a manufacturing plant, specifically from a compressor and a pump. The data is organized into folders reflecting the different equipment and sensors used in the data collection process. This repository includes only a sample of the actual data, as the information is sensitive. However, this kind of data can be seen as a scientific contribution and can serve as a basis for new applications.

## Folder Structure

### Compressor Data
The compressor data is stored under two main directories:
- `UMB`: Contains data from the Basic Measurement Unit (Unidade de Medida Básica), monitoring electrical parameters such as voltage and instantaneous power.
- `wiseComp`: Stores data from the Wise-2410 sensor, which is used for vibration monitoring.

### Pump Data
The pump data includes information collected from four different sensors:
- `hex@`: Provides real-time and historical data monitoring.
- `ite`: Delivers voltage, current, and power data.
- `wise`: Data from the Wise-2410 sensor similar to the compressor setup.
- `wiseMotor`: Contains specific motor-related monitoring data.

## Data Format

All data are initially stored in raw format and then processed into `.csv` files for easier analysis. Each folder corresponds to a specific sensor with the data structured for optimal retrieval and analysis.

## Access and Contribution

This data is available for public access and contribution. If you wish to contribute or have any queries regarding the data, please follow the standard GitHub pull request model or raise an issue in this repository.
