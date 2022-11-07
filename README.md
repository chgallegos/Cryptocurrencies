# Cryptocurrencies
## Overview

The purpose for the cryptocurrencies analysis was to help the company with an offering of new cryptocurrencies to its customers. Given the condition of the vast amount of cryptocurrencies, a report was requested in order to group and create a classification system for this investment. Therefore allowing the customers to have a better understanding of the world of cryptocurrencies.

----
## Results

The process for the analysis was divided into 4 steps:

**- Preprocessing the Data for PCA**
In this step, the data was ultimately standarized by use of the StandardScaler

![Screenshot](https://github.com/chgallegos/Cryptocurrencies/blob/main/resources/standard_scaler.png)

**- Reducing Data Dimensions Using PCA**
For the purposes of PCA, the data was chosen to be reduced into three principal components

![Screenshot](https://github.com/chgallegos/Cryptocurrencies/blob/main/resources/principal_components.png)


**- Clustering Cryptocurrencies Using K-means**
With K-means, we first created an elbow curve in order to find the most appropriate value for K

![Screenshot](https://github.com/chgallegos/Cryptocurrencies/blob/main/resources/elbow_curve.png)

Subsequently, the predicted values were included into a dataframe indexed with its cryptocurrency

![Screenshot](https://github.com/chgallegos/Cryptocurrencies/blob/main/resources/K-means_column.png)

**- Visualizing Cryptocurrencies Results**

Finally, two visualizations were created in order to see the clusters of cryptocurrencies, thus providing a great tool to see the similarities and differences of the different types of crypto.

![Screenshot](https://github.com/chgallegos/Cryptocurrencies/blob/main/resources/2d_plot.png)

![Screenshot](https://github.com/chgallegos/Cryptocurrencies/blob/main/resources/3d_plot.png)