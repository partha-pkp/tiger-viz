# Tiger Terrains and Timelines: Visualizing India’s Tiger Territories 🐯

⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐

## This project received an honorable mention at [Data Visualization Challenge 2024](https://data.library.arizona.edu/data-viz-challenge/previous-winners) !!
<div align="center">
<h3>
<a href="https://tiger-viz.netlify.app/">Check the dashboard now!!</a>
</h3>
</div>
⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐




## Background
- The recent report on the status of tigers by the National Tiger Conservation Authority (NTCA) of India estimates a significant increase in the tiger population across the country.
- The tiger-populated habitats within the nation have been categorized into 5 landscapes viz.
  - Shivalik Hills and Gangetic Plains,
  - Central Indian and Eastern Ghats,
  - Western Ghats,
  - Northeast Hills and Brahmaputra Flood Plains, and
  - Sundarbans
 
## Aim
- The present work aims to visualize these landscapes as an interactive 3D model using spatial data, and the tiger population using a line plot.


## Data
- The [NTCA report](https://ntca.gov.in/assets/uploads/Reports/AITM/status_of_tiger-copredators-2022.pdf) - obtained from [NTCA official website](ntca.gov.in)
- [Spatial data](https://www.diva-gis.org/gdata) of India
- The `xlsx` files titled `central_ind_data.xlsx`, `north_east_data.xlsx`, `shivalik_data.xlsx`, `sundarbans_data.xlsx`, and `west_ghats_data.xlsx` contain the latitude and longitude coordinates of each habitat which were mapped manually from the NTCA report
- The `line_plot_data.xlsx` file was developed based on the Tabular data in `Table 1.3.2` of the NTCA report

## Visualisations (Glimpse!)
- For the 3D plot,
  - the Indian terrain spatial data available online was used.
  - Then, the latitude and longitude coordinates of the landscapes mapped manually using the NTCA report were plotted over the terrain.
  - This mapping process was the most challenging task.
 
<h6 align="center">3D Plot - Perspective 1</h6> 
<p align="center">  
<img src="sandbox/plot.png" width="600" height="500">
</p><be>

<h6 align="center">3D Plot - Perspective 2</h6> 
<p align="center">  
<img src="sandbox/plot4.png" width="500" height="500">
</p><be>

<h6 align="center">3D Plot - Perspective 3</h6> 
<p align="center">  
<img src="sandbox/plot3.png" width="600" height="500">
</p><br>

- Further, the tiger population estimates from the report were extracted and presented as a line plot in plotly (the plot below is a static version!).
<h6 align="center">Line Plot</h6> 
<p align="center"> 


<img src="sandbox/line_plot.png" width="700" height="350">
</p><br>

- It can be observed from the plot that there has been an increase in the number of tigers since 2006.
- Hopefully, the conservation efforts will continue to yield much better results. 🤞🤞

### Repo Organization

The following are the folders involved in the Project repository.

-   **dashboard.qmd:** The source code file.
  
-   **tiger-viz.Rproj:** The _R_ project file
  
-   **data/:** Used for storing any necessary data files for the project, such as input files.

-   **figures/:** Used for storing the output images.

-   **sandbox/:** This is the workspace for _Brainstorming_ (Does not impact the workflow).

