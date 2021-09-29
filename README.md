# **Environmental-Hydrology-for-Data-Science-Project**
<br>


## **Problem Statement**

 ![](https://media.giphy.com/media/Wp7FNB13QfqEGpB00a/giphy.gif)
 <br>
 
 
 
 **Forest fires** are a major environmental issue, creating economical and ecological damage while endangering human lives. Fast detection is a key element for controlling such phenomenon. To achieve this, one alternative is to use automatic tools based on local sensors, such as provided by meteorological stations. In effect, meteorological conditions (e.g. temperature, wind) are known to influence forest fires and several fire indexes, such as the forest **Fire Weather Index (FWI)**, use such data.
 
 With the aid of technology and sensors, our aim to predict when these forest fires would occur, their intensity(extent of spread) and hopefully create a model based on the data    available in the forest Fire Weather Index(FWI) dataset. In particular, the area of interest chosen for this project is the  Montesinho natural park situated in Northeast Portugal.
 <br>
 
 
 ## Objective
 
 
By undertaking this project, I intend to explore and experiment using a **Data Mining** approach to predict the burned area of forest fires.Different models such as  Support Vector Machines (SVM) and Random Forests would be trained with the given data, and the one with the highest accuracy(which is able to predict forest fires as precise as possible) would be selected. 

The primary aim of this project is to be able to predict the burned area of small fires, which are more frequent. Such knowledge is particularly useful for improving firefighting resource management (e.g. prioritizing targets for air tankers and ground). 
 <br>
 
 ## Dataset used
 
 The following dataset, attached in the same repository titled 'forestfires.csv' is a dataset obtained from [here](https://www.kaggle.com/sumitm004/forest-fire-area).  The dataset is obtained from the forest Fire Weather Index(FWI) which is the standard measure for forest fire intensity, based off of Canada.
 
 The following dataset contains data from 517 fires which took place in the Monteninho Natural Park, and consists of six components, which are as follows:
 
   1. X - x-axis spatial coordinate within the Montesinho park map: 1 to 9
   2. Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9
   3. Month - month of the year: "jan" to "dec" 
   4. Day - day of the week: "mon" to "sun"
   5. FFMC - FFMC index from the FWI system: 18.7 to 96.20
   6. DMC - DMC index from the FWI system: 1.1 to 291.3 
   7. DC - DC index from the FWI system: 7.9 to 860.6 
   8. ISI - ISI index from the FWI system: 0.0 to 56.10
   9. Temp - temperature in Celsius degrees: 2.2 to 33.30
   10. RH - relative humidity in %: 15.0 to 100
   11. Wind - wind speed in km/h: 0.40 to 9.40 
   12. Rain - outside rain in mm/m2 : 0.0 to 6.4 
   13. Area - the burned area of the forest (in ha): 0.00 to 1090.84
 
 Here's a depiction of what the attributes of the FWI system means:
 ![](https://www.researchgate.net/profile/Ari-Venaelaeinen/publication/285955800/figure/fig3/AS:406088869531653@1473830539797/Fire-weather-index-calculation-scheme.png)
<br>

## Pipeline of the Project

As this is a fairly common Machine Learning problem, the Lifecycle of a ML problem can be applied here.It is as follows:

![](https://www.xenonstack.com/hubfs/xenonstack-machine-learning-pipeline.png)

In this case, the process is simplified as we have the collected data, so the process of collecting and storing can be bypassed. We will start our process by examining and cleaning the data (Preprocessing).

Progress can be measured by the following milestones:
- [X] Data Visualization
- [X] Data Preprocessing
- [] Data Analysis/ Parameter Selection
- [] Model Selection and Training
- [] Model analysis and Validation
- [] Model Deployment


<br>

## Architecture or Model

The low level data flow diagram(DFD) is represented as follows:

![Level 0 DFD](https://github.com/Ankith-kumaran/Environmental-Hydrology-for-Data-Science-Project/blob/main/Level%200-%20DFD.png) 
