# A Visualisation: River Pollution in Malaysia

The webpage contains visualisation of Water Quality Index (WQI) of rivers in Malaysia in the years 2015 to 2017. 

## Dataset (in the directory 'data')
- 1n1s_rivers.csv is cleaned from the raw dataset from [Malaysian Open Data Portal](https://www.data.gov.my/data/ms_MY/dataset/pengkelasan-kualiti-air-bagi-sungai-sungai-di-bawah-program-satu-negeri-satu-sungai)
- causes_pollution.csv is cleaned from the raw dataset from [Malaysian Open Data Portal](https://www.data.gov.my/data/ms_MY/dataset/sungai-yang-tercemar-mengikut-negeri-dan-punca-punca-pencemarannya-pada-tahun-2009)
- rivers_wqi.csv is compiled and cleaned from the raw datasets from multiple sources:
  - [Department of Environment Malaysia](https://www.doe.gov.my/portalv1/wp-content/uploads/2018/09/iv-EQR2016.pdf)
  - [Department of Environment Malaysia](https://www.doe.gov.my/portalv1/wp-content/uploads/formidable/5/Kualiti-Air-Sungai.pdf)
- change_percentage.csv is computed from 1n1s_rivers.csv
- river_network.csv is computed from rivers_wqi.csv

## Vega & Vega-Lite JSON files (in the directory 'vg_json')

- 1n1s_heat.vg.json: A heat map showing the development of class of WQI of rivers under the government scheme of 1 State 1 River (1S1R, or 1 Negeri 1 Sungai in Malay)
- causes_barchart.vg.json: A barchart showing the causes of pollution recorded in 2009. 
- diverging_stacked_barchart.vg.json: A diverging barchart showing the percentage of rivers that has no change, increased or decreased WQI from 2015 to 2017
- donut_2015.vg.json, donut_2016.vg.json, donut_2017.vg.json: Donut charts of rivers in each class in 2015, 2016 an 2017 respectively. 
- merged_rivers_centroids.json: The TOPOJSON file of centroids position of rivers, used for labelling of rivers.
- merged_rivers.json: The TOPOJSON file of line of rivers. 
- msian_states_labels.json: The TOPOJSON file of centroids position of states in Malaysia, used for labelling of states. 
- msian_states.json: The TOPOJSON file of geometries of states. 
specified. 
- rivers_map.vg.json: A map of Malaysia, containing shapes of states and rivers, where rivers are coloured by the class of their WQI. 

## Webpage

- index.html: Webpage of visualisation. 
- styles.css: Styling of the webpage. 
- resources: contains icons from [Freepik](https://www.freepik.com/)

## Dependencies

- [Vega](https://vega.github.io/)
- [Vega-Lite](https://vega.github.io/vega-lite/)
- [Google Fonts](https://fonts.google.com/)
- [Bootstrap](https://getbootstrap.com/)
- [JQuery](https://jquery.com/)
- [Popper](https://popper.js.org/)

## Usage

To see the visualisation, please refer [here](https://hyuanai.github.io/FIT3179/Malaysian%20River%20Pollution/). Otherwise, navigate to the files interested for the resources used in the webpage as listed above. 

## Contributors

Ho Yuan Ai (Student ID: 29566061) is the main contributor to the visualisation. 

## Special Thanks

Dr. Ting Chai Wen for supervising the project and providing some useful suggestions.
