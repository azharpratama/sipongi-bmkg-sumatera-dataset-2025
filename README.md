# Sumatera Environmental Data Repository 2025

This repository contains a comprehensive collection of environmental monitoring data for provinces in Sumatera, Indonesia for the year 2025. The dataset combines two major Indonesian environmental monitoring systems:

1. **SIPONGI+**: Forest and land fire monitoring data from the Ministry of Environment and Forestry (KLHK)
2. **BMKG**: Weather and climate data from the Meteorological, Climatological, and Geophysical Agency

## Dataset Structure

The dataset is organized by data source and province:

### Provinces Included

1. Bengkulu
2. Jambi
3. Riau
4. Sumatera Barat (West Sumatra)
5. Sumatera Selatan (South Sumatra)
6. Sumatera Utara (North Sumatra)

### Current File Organization

- **Root directory**: Contains SIPONGI+ forest fire monitoring data as consolidated Excel files for each province
  - `bengkulu.xlsx`
  - `jambi.xlsx`
  - `riau.xlsx`
  - `sumatera-barat.xlsx`
  - `sumatera-selatan.xlsx`
  - `sumatera-utara.xlsx`

- **Province subdirectories**: Contain BMKG weather and climate monthly data breakdowns
  - For each province, monthly climate data is available for January through May 2025:
    - `[province]-januari.xlsx`
    - `[province]-februari.xlsx`
    - `[province]-maret.xlsx`
    - `[province]-april.xlsx`
    - `[province]-mei.xlsx`

## Data Description

This combined dataset contains two types of environmental monitoring data:

### SIPONGI+ Data (Root Directory Files)
Forest and land fire monitoring data including:
- Hotspot detection and monitoring
- Forest and land fire incidents (Karhutla - Kebakaran Hutan dan Lahan)
- Burned area measurements (in hectares)
- Fire management and response information
- Location data of fire incidents by province and district
- Temporal data on fire occurrences

### BMKG Data (Province Subdirectories)
Weather and climate data including:
- Daily temperature readings (minimum, maximum, average)
- Precipitation/rainfall data
- Humidity measurements
- Wind speed and direction
- Air pressure
- Weather conditions (sunny, cloudy, rain, etc.)
- Air quality measurements where available

## Usage

This combined dataset can be used for:

### Fire-related Analysis
- Forest and land fire research and analysis
- Monitoring of fire hotspot trends across different provinces
- Comparing fire incidents between different regions in Sumatera
- Seasonal variation analysis in forest fire occurrences
- Supporting fire prevention and management strategies
- Environmental impact assessment of forest fires

### Climate Analysis
- Weather pattern analysis and trends across Sumatera provinces
- Climate change impact studies for the region
- Precipitation and temperature trend analysis
- Correlation between weather conditions and forest fire incidents

### Integrated Environmental Analysis
- Studying relationships between weather conditions and forest fire occurrences
- Developing predictive models for fire risk based on weather patterns
- Environmental policy and planning based on combined climate and fire data
- Educational and research purposes on environmental sciences

## Data Sources

This dataset was compiled from two official Indonesian government sources:

1. **SIPONGI+** (Sistem Pemantauan Karhutla): A forest and land fire monitoring system developed by the Directorate of Forest Fire Control (Direktorat Pengendalian Kebakaran Hutan) under the Ministry of Environment and Forestry of Indonesia (KLHK). The official website is available at [https://sipongi.menlhk.go.id/](https://sipongi.menlhk.go.id/).

2. **BMKG** (Badan Meteorologi, Klimatologi, dan Geofisika): Indonesia's Meteorological, Climatological, and Geophysical Agency responsible for weather forecasting, climate monitoring, and related services. Daily climate data is available through their online portal at [https://dataonline.bmkg.go.id/data-harian](https://dataonline.bmkg.go.id/data-harian).

## Last Updated

May 2025

## License

Please refer to the respective agencies' data usage policies:
- Ministry of Environment and Forestry of Indonesia's (KLHK) policies: See [Disclaimer](https://sipongi.menlhk.go.id/disclaimer-ft) and [Privacy Policy](https://sipongi.menlhk.go.id/privacy-policy) pages.
- BMKG data usage policies: Check BMKG's [official website](https://www.bmkg.go.id/) for data sharing and usage terms.
