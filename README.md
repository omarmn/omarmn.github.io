<a href="https://omarmn.github.io/OmarNooreddin_07_2019_PT.pdf">My CV</a>

<h1>List of Projects</h1>

<h3>Introduction</h3>

Below is a list of Data Analysis projects I worked on. The code is mostly written in R, except where it's explicitly mentions Python. Each project has an abstract, and a linked header to the RMarkdown file or Jupyter Notebook:

<h3>
  <a href="https://github.com/omarmn/omarmn.github.io/blob/master/Sen%202%20Image%20Acquirer%20(Version3-class).ipynb">Sentinel 2 Image Acquirer/NDVI Builder (Python)</a>
</h3>

A Sentinel 2 image acquirer and NDVI builder. Given a set of dates and an Area of Interest (AOI), it will:
- Connect to Sentinel 2
- Acquire images for the AOI
- Download those images
- Create a mosaic (if needed)
- Create an NDVI for the AOI (and export png's)

The class also:
- Converts CRS
- Converts file format from JP2 to tiff

<h3>
  <a href="https://github.com/omarmn/omarmn.github.io/blob/master/GEDI%20Overview.ipynb">GEDI Image Exploration (Python)</a>
</h3>

This Jupyter notebooks explores how to read and plot GEDI (Global Ecosystem Dynamics Investigation) images, which is a LiDAR instrument attached to the International Space Station.

<h3>
  <a href="https://github.com/omarmn/omarmn.github.io/blob/master/TLS%20-%20ALS%20%20Data.ipynb">TLS and ALS image Exploration (Python)</a>
</h3>

This Jupyter notebooks looks at TLS (Terrestrial Laser Scanning) and ALS (Airborne Laser Scanner) images, which are essentially point cloud images.

<h3>
  <a href="https://omarmn.github.io/Espinhal.html">Law Compliancy Through Remote Sensing (Python)</a>
</h3>

Similar to the below project, this Jupyter Notebook tries to shed some light on the use of Normalised Difference Vegetation Index (NDVI) coupled with satellite imagery to check whether areas designated as a Defensible Space by Portuguese government, has been complied with by clearing the area from trees. With this analysis though, it is known exactly which date the clearing took place, and the type of cleaning (cutting down trees completely) for the parcel of land that is being investigated. As such, the results have more credence.

<h3>
  <a href="http://rpubs.com/omarmn/dsfdsj">Satellite Image Analysis using Normalised Difference Vegetation Index</a>
</h3>

This work investigates the use of remote sensing (satellite imagery), coupled with vegetation index (NDVI) to ascertain whether areas designated by the Portguese have complied with the law of fire protection and prevention. In analysing the images and applying the index, there is evidance that compliancy (or lack of it) can be acertained.

<h3>
  <a href="http://rpubs.com/omarmn/closerchallenge">Machine Learning (NLP) - Complaints Classfier</a>
</h3>

This piece of work, sets out to build a a complaints classifier using Machine Learning algorithms. The training set, is a complaints database, which contains a description of the issue and the "type" of the issue. Also, in this work endeavours to propose a new complaints categorisation (or a new issue "type") by use of Machine Learning algorithm.

<h3>
  <a href="http://rpubs.com/omarmn/dslr">Vegetation Index Research by use of Remote Sensing</a>
</h3>

This paper endeavours to identify Defensible Spaces (DS) by use of satellite imagery and areas marked for cleaning by municipalities (using KML files) coupled with use of Vegetation Indicies. Different indicies will be employed in order to decide which index will be the most suitable in identifying a DS. The premis of this assumption, is that DS will be cleared from vegetation, therefore there will be a starck contrast between the DS and the neighbouring areas. 


<h3>
  <a href="http://rpubs.com/omarmn/machinelearning">Machine Learning - Fitness Exercise Classifier</a>
</h3>

This project's aim was to build a classifier to classify correct vs incorrect execution of a gym exercise based on activity monitors sensor data (i.e Fitbit, Nike FuelBand). The data set used for training, is readings from such trackers with classification from A (correct execution) to E (completely incorrect execution). Various training methods were selected, starting with an accuracy of 49% and moving all the way to an accuracy of 99.4% (with Random Forest).

<h3>
  <a href="http://rpubs.com/omarmn/regression">Multivariate Regression Model for Petrol Consumption of Cars</a>
</h3>

This paper will endeavour to answer two questions: (1) Is an automatic or manual transmission better for a car's Miles Per Gallon (MPG); (2) What are the variables that affect MPG? Based on this,s we will build a model. For this investigation we shall use the "mtcars" data set in R.

<h3>
  <a href="http://rpubs.com/omarmn/milestoneReport">NLP - N-gram Text Analysis</a>
</h3>

This paper analyses three text files containing tweets, news articles and blog posts in order to build features for a text predictor.

<h3>
  <a href="http://rpubs.com/omarmn/statinference">Hypothesis Testing - Effects of Vitamin C on Tooth Growth</a>
</h3>

This paper will endeavour to perform basic inferential data analysis on the Tooth Growth data set. More precisely, it will assess the effects of vitamin C on tooth growth in guinea pigs, and will try and conclude if there's a strong relationship or not.

<h3>
  <a href="http://rpubs.com/omarmn/RepReAssign2">Exploratory Data Analysis - Effects of Weather Events on Public Health and Economy</a>
</h3>

This analysis will investigate the effects of weather events on public health and economic costs. The data being used is sourced from NOAA:<a href="https://www.noaa.gov/">https://www.noaa.gov/</a>  spanning the year 1950 to 2011.

<h3>
  <a href="http://rpubs.com/omarmn/activityexpl">Exploratory Data Analysis of Activity Monitor (e.g Fitbit)</a>
</h3>

This analysis uses data from an activity monitor and it aims to answer the following questions:
- What is the mean number of steps taken per day?
- What is the average daily activity pattern?
- Are there differences in activity patterns between weekdays and weekends?
- It also attempts to impute missing data

<h3>
  <a href="http://rpubs.com/omarmn/energyconsump">Exploratory Data Analysis of Household Energy Consumption</a>
</h3>

This analysis visualises energy consumption in households across two days: 1/2/2007 to 2/2/2007.



