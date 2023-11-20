# Not just 1.5°C

This repository documents the creation process behind the "Not just 1.5°C" poster. The poster was created for the [Little Pictures competition](https://climate.esa.int/en/littlepicturescompetition/). 

## Data

For temperature trends, surface temperature data from the ERA5 reanalysis dataset was used. The data was downloaded from the Climate Data Store using the script `download_data_temperature.py`.

## Code

The code for the project is based on the public application [
Global temperature trend monitor
](https://cds.climate.copernicus.eu/cdsapp#!/software/app-c3s-global-temperature-trend-monitor?tab=app) in the Climate Data Store. The notebook `create_plot.ipynb` was used to process the data and create a plot.

## Poster

The poster was created using [Inkscape](https://inkscape.org/). The design is inspired by the example little pictures in the [Gallery](https://climate.esa.int/en/little-pictures-gallery/) of the competition.

## Accessibility
The poster was tested for accessibility using the online tool [Coblis](https://www.color-blindness.com/coblis-color-blindness-simulator/) and version to simulate the perception of the design with color blindness are available in the folder `accessibility/`.

## Sources
- Inspiration for the code: https://cds.climate.copernicus.eu/cdsapp#!/software/app-c3s-global-temperature-trend-monitor?tab=app
- Data: Hersbach, H., Bell, B., Berrisford, P., Biavati, G., Horányi, A., Muñoz Sabater, J., Nicolas, J., Peubey, C., Radu, R., Rozum, I., Schepers, D., Simmons, A., Soci, C., Dee, D., Thépaut, J-N. (2023): ERA5 monthly averaged data on single levels from 1940 to present. Copernicus Climate Change Service (C3S) Climate Data Store (CDS), DOI: 10.24381/cds.f17050d7 (Accessed on 17-11-2023)
- List of global cities: https://en.wikipedia.org/wiki/Global_city
- Position of the cities from: https://geohack.toolforge.org/
- Computation of the temperature anomaly: https://climate.copernicus.eu/surface-temperature
- Accessibilty for color blindness: https://www.color-blindness.com/coblis-color-blindness-simulator/