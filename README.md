# AI Seminar: Data to Decisions: ML SOLUTIONS FOR WATER CHALLENGES IN THE BORDERLAND

**Data Exploration and Discussion**

We will clean and use climate data from Google Earth Engine (GEE) to predict evapotranspiration (ET).  For each technique, the input and output are as follows:

**Input**: A raster image with a pixel resolution of 1000 meters.

**Output**: Models that use some features to predict the target ET.

We also estimate how well each model performs.

# Data Source
Google Earth Engine Daymet V4: Daily Surface Weather and Climatological Summaries [Source](https://developers.google.com/earth-engine/datasets/catalog/NASA_ORNL_DAYMET_V4#bands)

# Links to Google Colab Notebooks  
+ AI Seminar Colab: [Link](https://colab.research.google.com/drive/1kYd6yYcE9T_begejLNAZsq8rSI4PM98o?usp=sharing)      

# How to Run

The application code is made available as a python notebook that can be executed online with Google Colab.    
Note that shared notebooks have been pre-executed, runtime outputs are shown accordingly.   

To run from scratch:   
1. Open link to the target notebook.
2. Generate a dataset following the instructions on Data consolidation and Curation notebook.
3. To run model notebooks: import the input dataset file (All-state8.xlsx) generated from the previous notebook.
4. To execute the notebook go to Runtime->Run all. Each code section can also be executed individually.

# Participating Institutions
The University of Texas at El Paso (UTEP)  

# Contributors
Damian Gallegos Espinoza - UTEP   
Natalia Villanueva Rosales - UTEP  

# License
This software code is licensed under the [GNU GENERAL PUBLIC LICENSE v3.0](./LICENSE) and uses third party libraries that are distributed under their own terms (see [LICENSE-3RD-PARTY.md](./LICENSE-3RD-PARTY.md)).

# References 
[1] M. M. Thornton, R. Shrestha, Y. Wei, P. E. Thornton, and S.-C. Kao, “Daymet: Daily Surface Weather Data on a 1-km Grid for North America, Version 4,” ORNL DAAC, Dec. 2020, doi: 10.3334/ORNLDAAC/1840. <br><br>
[2] M. M. Thornton, R. Shrestha, Y. Wei, P. E. Thornton, and S.-C. Kao, “Daymet: Daily Surface Weather Data on a 1-km Grid for North America, Version 4 R1,” ORNL DAAC, Nov. 2022, doi: 10.3334/ORNLDAAC/2129.


