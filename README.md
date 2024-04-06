The goal of this project is to develop a custom logistic regression algorithm for predicting forest cover types.
The data set is the Covertype Data Set retrieved from the UCI Databse Repository. It is a multivariate data with categorical and integer data. the dataset consists of 581012 rows and 54 columns. The goal of this study is to predict forest cover type from cartographic variables only, without using remotely sensed data. The study area consists of four wilderness areas located in the Roosevelt National Forest of northern Colorado, representing forests with minimal human-caused disturbances.

The independent variables in the dataset were derived from US Geological Survey (USGS) and US Forest Service (USFS) data and contain binary (0 or 1) columns of data for qualitative independent variables, such as wilderness areas and soil types. The actual forest cover type for each observation (30 x 30 meter cell) was determined from USFS Region 2 Resource Information System (RIS) data.

Based on the information provided about the wilderness areas, we can infer that the primary tree species and elevational range differ among the areas. Neota has the highest mean elevational value and spruce/fir as its primary species. Rawah and Comanche Peak have lower mean elevational values and lodgepole pine as their primary species, followed by spruce/fir and aspen. Cache la Poudre has the lowest mean elevational value and tends to have Ponderosa pine, Douglas-fir, and cottonwood/willow as its primary species.

It is important to note that Rawah and Comanche Peak are more typical of the overall dataset due to their assortment of tree species and range of predictive variable values, while Cache la Poudre may be more unique due to its relatively low elevation range and species composition.

Given this information, it may be possible to predict forest cover type based on cartographic variables such as elevation, soil type, and wilderness area. However, it may be challenging to accurately predict forest cover type without using remotely sensed data, which could provide additional information about vegetation density, canopy cover, and other important variables.

In summary, predicting forest cover type from cartographic variables only is a challenging task, but it may be possible to make accurate predictions using information about elevation, soil type, and wilderness area. However, the unique characteristics of each wilderness area and the limitations of cartographic data should be taken into consideration when making predictions.

It is a reasonable goal to aim for an accuracy of around 94% in the classification task of predicting forest cover types based on cartographic variables. This level of accuracy would allow for effective classification of forest cover types and could provide valuable insights into the environment and habitat supported by each type of forest cover.

However, it is important to note that achieving such a high accuracy may be challenging and could depend on the quality of the data, the choice of classification algorithm, and the specific features used for classification. Therefore, it may be necessary to experiment with different algorithms and feature sets to find the best combination for achieving the desired accuracy.

Team work: Ananya Das Manolyl, Delaney Grace Helgeson, Aniket Dhirajkumar Divya Bharthi

Source : https://archive.ics.uci.edu/ml/datasets/Covertype
P.S: Done as Academic project
