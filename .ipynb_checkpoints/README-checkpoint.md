# H1 San Francisico Housing Market

This challenge was too take housing data and visualise it to accomplish the following:

1. Calculate and plot the housing units per year.

2. Calculate and plot the average prices per square foot.

3. Compare the average prices by neighborhood.

4. Build an interactive neighborhood map.

then come up with conclusions about the housing market to provide to a real estate start up



---

## Technologies
This application is written in Python 3.7

this application uses the following packages:
OS 
pandas
load_dotenv
plotly.express
pyviz hvplot
pathlib
nodejs 
and access to the mapbox API via a mapbox token 


---

## Installation Guide

Before running the application first install the following dependencies.

python
- First item  conda install -c plotly plotly=4.13.
- Second item conda install -c pyviz hvplot
- Third item conda install -c conda-forge nodejs=12
  
Mapbox needs to be signed up for and a access token generated
a .env file also needs to be created to store you MABPOX_API_TOKEN, and imported into the notebook via load_dotenv
The housing data CSVs housing_per_year, neighborhoods_coordinates, sfo_neighborhoods_census_data all need to be loaded into the notebook via the pd.read_csv function

---

## Examples

![alt text](graph codejpg.jpg)

![alt text](housing line.jpg)

---

## Usage

To use the data simply clone the repository.

The charts can be made bigger, smaller, in a different style, or a different type of chart entirely

Other CSVs could also be examined and the resulting charts will provide insight 
```
---

## Contributors

Sean Patel (myself) seanpatel076@gmail.com
---

## License

License is public anyone can use or make changes to this application
