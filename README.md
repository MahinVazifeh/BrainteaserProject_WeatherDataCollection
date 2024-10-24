# BRAINTEASER 

The BrainTeaser project is a data science initiative that aims to harness the potential of big data, including health, lifestyle, and environmental data, to provide support for patients with amyotrophic lateral sclerosis (ALS) and multiple sclerosis (MS), along with their clinicians. Leveraging cost-efficient sensors and applications, BrainTeaser integrates large clinical datasets containing both patient-generated and environmental data.

I developed the following codes to collect and preprocess weather data for the three countries involved in this project: Italy, Spain, and Portugal. The main components of the code are:

    Data Collection: Gathering large-scale weather data from the Copernicus (E-OBS dataset), a key European data source.
    Location Mapping: Calculating the closest European weather station locations that correspond to the project’s MS patient locations.
    Data Imputation: Addressing missing data in certain locations using the K-Nearest Neighbor (KNN) imputation method, with Euclidean distance as the metric.
    Dataset Preparation: Preparing the weather dataset to be integrated with air quality data, another key dataset collected within the project.
    
In this project, clinical and environmental data, including air pollution and weather data, are being collected from 2011 to 2024. As a result, the weather data is organized into four parts based on the collection years: 2011 to 2021, 2022, 2023, 2024

Copernicus updates the dataset annually, releasing new versions each year. Below are the relevant Copernicus versions that include the data for the years of interest:

    2011 - 2021: Version 25 
    2022: Version 27 
    2023: Version 29
    2024: Version 30

     
