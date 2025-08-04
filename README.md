# 🧠 BRAINTEASER

The BrainTeaser Project is a large-scale, multinational data science initiative conducted across Spain, Italy, and Portugal. It aims to enhance clinical support for patients with Amyotrophic Lateral Sclerosis (ALS) and Multiple Sclerosis (MS) by integrating multimodal data from clinical records, environmental monitoring, and patient-generated sources. Utilizing cost-effective sensors and smart applications, BrainTeaser collects and analyzes health, lifestyle, and environmental data to deliver personalized, data-driven insights for both patients and clinicians.

Within this project, I developed code modules for the automated collection, integration, and preprocessing of weather condition data across the three participating countries—Italy, Spain, and Portugal. These components enabled the alignment of large-scale environmental datasets with clinical timelines, supporting longitudinal exposure analysis for patients with ALS and MS.

## 💻 Code Components

### `WeatherDataCollection.py`
This script handles the initial collection and preparation of weather data. Its main components are:

* **Data Collection**: Gathers large-scale weather data from the **Copernicus (E-OBS dataset)**, a key European data source.
* **Location Mapping**: Calculates the closest European weather station locations corresponding to the project’s MS patient locations.
* **Dataset Preparation**: Prepares the collected weather dataset for integration with air quality data, another crucial dataset within the project.

### `Missing_Weather_Data_Imputation.py`
This script addresses missing data within the weather datasets:

* **Data Imputation**: Fills in missing data in specific locations using the **K-Nearest Neighbor (KNN) imputation method**, with Euclidean distance as the metric.

## 🗓️ Data Collection Period & Copernicus Versions

Clinical and environmental data, including air pollution and weather data, are being collected from **2011 to 2024**. Consequently, the weather data is organized into four distinct parts based on the collection years: **2011-2021, 2022, 2023, and 2024**.

Copernicus updates its dataset annually, releasing new versions each year. Below are the relevant Copernicus versions that include the data for the years of interest:

* **2011 - 2021**: Version 25
* **2022**: Version 27
* **2023**: Version 29
* **2024**: Version 30
