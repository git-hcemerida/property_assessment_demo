# Property Assessment Demo
This repository contains the code and files used in publishing an interactive dashboard for a client interested in identifying parts of their property where the slope is:

- Below 15 degrees (Class 1), or
- Greater than or equal to 15 degrees (Class 2)

## Installation
Create an environment and run the following command:

```shell
pip install requirements.txt
```

or when using conda after creating and activating the environment:
```shell
conda install --file requirements.txt
```

## Usage
Launch Jupyter Notebook and run the file `property_assessment.ipynb` to create the necessary input files for the interactive map (`class.geojson` and `property_boundaries.geojson`).

Next, to generate and export the interactive map, open and run `folium_map.ipynb`.



## License

This project is licensed under the [MIT License](LICENSE.md).