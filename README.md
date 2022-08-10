# FindTheK

#Libaries Imported
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler

#Read crypto data csv file into dataframe
"./crypto_market_data.csv"

#![image](https://user-images.githubusercontent.com/106267420/183801688-a6051bb3-442f-4730-9e83-c29c1cdc9167.png)


# Take a look at the elbow curve suggestion on number of cluster that could be enough
![image](https://user-images.githubusercontent.com/106267420/183801775-12e6f4bf-6abf-4037-beed-7402d9c76307.png)


#Using the 24hr and 7d percent change in price as the demensions to see how the clusters responded
![image](https://us#er-images.githubusercontent.com/106267420/183802110-aeef1732-618c-4a87-aef3-f6b4aeabf25b.png)

#Implement the Principal Component Analysis
![image](https://user-images.githubusercontent.com/106267420/183802284-ea868aab-8984-4b06-848e-63d50b47fd8d.png)
