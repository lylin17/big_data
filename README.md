# Spatial-Temporal Analysis of Chicago Taxi Rides

This is a 3-student group project for CS5344 Big Data Analytics taken under the Master of Science in Business Analytics programme in NUS. TThe project centers on getting insights of profitable taxi pickup/dropoff locations by employing k-means clustering, graph theory and frequent pattern mining to extract patterns from a large amount of taxi trip data. The project report is available ( https://drive.google.com/file/d/12bRiYH2-HiIDfCQ7KrGrZQIJM2w_oG43/view?usp=sharing) for more details regarding the approach and results obtained. My contribution to the project in on using graph theory (transitivity and pagerank) to identify important nodes in a taxi trip subgraph made up of high fare trips. This project served as a proof-of-concept for the methodology used to extract high fare route/time combinations from a large dataset of taxi trip records. Only 1 year of data was used here and a larger dataset comprising of data collected over a longer time period can be used for more practical business applcations. Data used in this project can be found on Kaggle (https://www.kaggle.com/chicago/chicago-taxi-rides-2016/data)

Code provide as Jupyter notebooks to run in databricks, https://databricks.com/try-databricks. 
To run graphframes in databricks:
1. Download graphframes-0.5.0-spark2.1-s_2.11.jar from https://spark-packages.org/package/graphframes/graphframes
2. Create library and attached jar file to working cluster in databricks, https://docs.databricks.com/user-guide/libraries.html#create-a-library

Frequent pattern mining.ipynb: Frequent pattern mining of trip data using ml package
Graph Model.ipynb: Graph analysis of trip data using graphframes package
K-means Clustering.ipynb: K-means clustering of data subsets using ml package

