# Data to Decisions: ML SOLUTIONS FOR WATER CHALLENGES IN THE BORDERLAND

**Data Exploration and Discussion**

We will clean and use climate data from Google Earth Engine (GEE) to predict evapotranspiration (ET).  For each technique, the input and output are as follows:

**Input**: A raster image with a pixel resolution of 1000 meters.

**Output**: Models that use some features to predict the target ET.

**Models**
  - Random Forest Regressor
  - Multilayer Perceptron (MLP) 

**Model Statistics and Analysis:**   
+ Shapley Additive Explanations (SHAP) 

# Data Source
Google Earth Engine Daymet V4: Daily Surface Weather and Climatological Summaries [Source](https://developers.google.com/earth-engine/datasets/catalog/NASA_ORNL_DAYMET_V4#bands)

# Links to Google Colab Notebooks  
+ Working with Google Earth Engine (GEE): [Link](https://colab.research.google.com/drive/1kYd6yYcE9T_begejLNAZsq8rSI4PM98o?usp=sharing)
+ Additional Classification Notebook [Link](https://colab.research.google.com/drive/1e5W2TZ2Zs5dX6V0F5eNVWcV8t3e7uNqU?usp=sharing)

# How to Run

The application code is made available as a Python notebook that can be executed online with Google Colab.    
Note that shared notebooks have been pre-executed, and runtime outputs are shown accordingly.   

To run from scratch:   
1. Open the Link to the Working with Google Earth Engine (GEE) notebook.
2. Go to the GEE Code Editor on the following link [GEE Code Editor](https://www.google.com/url?sa=D&q=https://code.earthengine.google.com/&ust=1754929416164522&usg=AOvVaw0vcMigCqS8q18KCJGc0f7i) and sign in. 
3. Change the name of the Project inside the notebook and authenticate your account.
4. To run model notebooks: Run the notebook and wait for a pop-up window to authenticate. The code should run without complications.
5. To execute the notebook, go to Runtime->Run all. Each code section can also be executed individually.

# Participating Institutions
The University of Texas at El Paso (UTEP)  

# Contributors
Damian Gallegos Espinoza - UTEP   
Natalia Villanueva Rosales - UTEP  

# License
This software code is licensed under the [GNU GENERAL PUBLIC LICENSE v3.0](./LICENSE) and uses third-party libraries that are distributed under their own terms (see [LICENSE-3RD-PARTY.md](./LICENSE-3RD-PARTY.md)).

# References 
[1] M. M. Thornton, R. Shrestha, Y. Wei, P. E. Thornton, and S.-C. Kao, “Daymet: Daily Surface Weather Data on a 1-km Grid for North America, Version 4,” ORNL DAAC, Dec. 2020, doi: 10.3334/ORNLDAAC/1840. <br><br>
[2] M. M. Thornton, R. Shrestha, Y. Wei, P. E. Thornton, and S.-C. Kao, “Daymet: Daily Surface Weather Data on a 1-km Grid for North America, Version 4 R1,” ORNL DAAC, Nov. 2022, doi: 10.3334/ORNLDAAC/2129.




