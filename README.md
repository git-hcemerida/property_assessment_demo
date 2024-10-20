# Property Assessment Demo
This repository contains the code and files used in publishing an interactive dashboard for a client interested in identifying parts of their property where:

- Slope < 15°

## Installation
Create an environment and run the following command:

```shell
pip install requirements.txt
```

or when using conda after creating and activating the environment:
```shell
conda install --file requirements.txt
```

Note: this was tested on MacBook Pro M2 running on macOS Sequioa 15.0.1

## Usage
Launch Jupyter Notebook and run the file `property_assessment.ipynb` to create the necessary input files for the interactive map (`class.geojson` and `property_boundaries.geojson`).

Next, to generate and export the interactive map, open and run `folium_map.ipynb`.

## Website
You can check out the website here using any modern desktop browser: https://git-hcemerida.github.io/property_assessment_demo/

## Credits
- Elevation data from [Geoscience Australia](https://www.ga.gov.au/) accessed through [Elvis - Elevation and Depth - Foundation Spatial Data](https://elevation.fsdf.org.au/)
- ESRI (Basemap)


## License

This project is licensed under the [MIT License](LICENSE.md).