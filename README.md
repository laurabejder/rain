# Denmark is getting rainier

In this repository I examine the development in precipitation in Denmark. During the past decade, precipitation has increased by almost 20 percent. I look into the yearly rainfall, how rainy each month has been on average and compare different historical periods spanning from the late 19th century to 2020. 

The content of this notebook is presented in the article [Has It Always Been This Rainy?](https://laurabejder.com/rain/)

## In this repository
### Notebooks
- `analysis.ipynb`: This notebook analyses the DMI data. The notebook provides code for the cleaning, aggragation and grouping of the data.
- `data_visualization.ipynb`: This notebook uses the R package ggplot to create the basic visualization of the data. The visualizations were later imported to Adobe Illustrator and then converted into responsive html using ai2html.

## Inside the data directory
Inside this directory, you can find all the data used in the analysis.

## Inside the visuals directory
This directory contains the outputs of the ggplots created in data_visualization.ipynb and the versions edited in Adobe Illustrator.

## Project Description
### Aim of the project
### Data collection

The historical data was collected by the Danish Meteorological Institute (DMI). It can be downloaded as a zip file [here](https://www.dmi.dk/fileadmin/Rapporter/2021/DMIRep21-02.zip). 

This repository only contains the files used for this project but the original data folder also has information on daily precipitation for other parts of Denmark as well as sunlight, temperature etc. 

The documentation for the data and data collection is provided by DMI in the reports [Denmark – DMI Historical
Climate Data Collection 1768-
2020](https://www.dmi.dk/fileadmin/Rapporter/2021/DMIRep21-02.pdf) and [Ekstreme nedbørhændelser i
Danmark](https://www.dmi.dk/fileadmin/Rapporter/2021/DMIRap21-06.pdf).

### Findings

### Data analysis process
I did a lot of different groupings of the data to get a better sense of how the precification rates have changed in Denmark. For the historical comparisons I ended up applying DMI's 30-year groupings instead of decades (too short) or centuries (too long). 

### New skills
For this project I used Adobe Illustrator and ai2html for the second time. I have expanded my experience with editing ggplot outputs in Illustrator but this time I also practiced using other fonts than the ones initially supported by ai2html (Georgia and Arial).

I also practiced by ggplot skills including using polar x-axes, making trend lines, and tweeking the graph to get as close to the result as possible before exporting it to illustrator. 
