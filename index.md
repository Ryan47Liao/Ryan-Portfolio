## Welcome to Ryan Liao's Portfolio
### [Project 1: Divvy bike #3: Real Time Intellegence System](https://github.com/Ryan47Liao/Divvy_Time_Series)
  Chicago, IL July 2022 –> Now (In Progress)
 Taking the divvy-dock-balancing challenge to the next level. Leverage the power of AWS SageMaker to deliver real-time solutions to Divvy's biggest challenge. 
![blueprint](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/divvy_rtis_bluePrint.png)

### [Project 2: EVE-Online BigData Project](https://raw.githubusercontent.com/Ryan47Liao/Divvy-Bike-Dock-Balancing-Analysis)
  Chicago, IL Apr 2022 –> June 2022    
[Get this Data on Kaggle](https://www.kaggle.com/datasets/leonidasliao/eveonline-tradingwar) 
- Create databases on Hadoop, and Google Storage that contains over 200Gs of data to be analyzed on PySpark through virtual machine clusters on Google Dataproc
- Optimize ETL data pipelines through multiprocessing to speed the entire preprocessing process by over 99%
- Leverage both Big Query and PySpark to flatten NoSQL data into structured ones and engineer new features by joining multiple tables
- Built model pipelines that clean, cross-validate, and tune hyperparameters to predict warfare outcomes using PySpark MLlib

![data_meta](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/EVE_data_info.png)

![data_eng](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/data%20eng.png)

### [Project 3: Divvy bike #2: Time Series Forecasting](https://github.com/Ryan47Liao/Divvy_Time_Series)
  Chicago, IL Apr 2022 –> June 2022   
[Get this Data on Kaggle](https://www.kaggle.com/datasets/leonidasliao/divvy-station-dock-capacity-time-series-forecast)
- Conduct thorough time series EDA on its trend, intervention, outliers, stationarity, seasonality, and forecastability to guide and engineer data for better model performance
- Cluster panel data across over 1000 stations and 5 years into 2 clusters using K-means to distinguish stations that were impacted by Covid to be modeled separately.
- Map station-ID to Neighborhood-ID based on coordinates collected from Google geo-encoding API, thus connecting with originally disconnected tables and aggregating horizontally to increase data forecastability
- Forecast station traffic and dock availability using an ensembled model of VARMA and frequency-based multi-seasonal SARIMA in real-time to guide the maintenance intervention ahead of time to prevent station overload

![TBASTS](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/TBASTS.png)

![Covid Impact](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/Clustering_based_EDA.png)

![InterventionModel](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/Intervention_modeling.png)


### [Project 4: Divvy bike #1: Dock Balancing Analysis](https://github.com/Ryan47Liao/Divvy-Bike-Dock-Balancing-Analysis)
  Chicago, IL Jan 2022 –> Apr 2022
- Converted structured travel history into graphs and generated network graphs using Networkx, visualized user
travel patterns to identify potential communities suffering from bike balancing problems, and pinpoint top
stations by calculating node centrality
- Mapped station-ID to Neighborhood-ID based on coordinates collected from Google geo-encoding API, thus
connecting with originally disconnected relational databases and reducing dimension by over 80%
- Created new features that keep track of all dock’s capacity by simulating over travel history data, visualizing
each station’s dock availability which directly addresses the capacity imbalance problem
- Performed clustering on each station’s dock capacity trend using k-means, leading to insights that generated
client-ready visualization and solution that has an NPV equivalent to 36% annual revenue in the estimate

![Graph](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/GRAPH.gif)

![Capacity change over time](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/CAP.gif)

### [Project 5：Yelp's recommendation system](https://github.com/Ryan47Liao/Yelp-Recommendation-System)
  Chicago, IL Jan 2022 –> Apr 2022
- Built databases and environments on remote servers using Hadoop through Ubuntu to facilitate teamwork
- Reprogrammed feature engineering pipeline through NumPy vectorization and programming techniques to
not only boost total running time by 5 times but also solved memory overflow issues due to huge dataset
- Conducted time series analysis using Facebook Prophet, broke down review trend by its seasonality, and
guided the generation of time-related features
- Implemented a content-based collaborative filtering recommendation engine that has an NDCG of 0.92
![Yelp workflow](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/Yelp.png)
![Database](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/RCC.png)

### [Project 6: Realtime Intelligent Crypto Trading System](https://github.com/Ryan47Liao/Realtime_intelligent_trading_system)
  Chicago, IL Jan 2022 –> Apr 2022
- Collected streaming data from social media using python sockets, API requests, selenium, and beautiful soup
to build a database to explore correlation with Bitcoin prices
- Cleaned bot-generated data by first manually tagging tweets through shared patterns, then cluster tweets using
k-means to bulk identify, eventually increasing tweet subjectivity by over 40%
- Performed sentimental analysis on social media activities along with the tweet volume, transaction volume,
and google search trends to build models which predict Bitcoin price fluctuations with an R-square of 0.93
- Constructed server and client that handles streaming data of Bitcoin prices and tweeter, predicts future price
and generates trading signals in real-time that out-performs baseline algorithm in backtesting by over 2000%
![image](https://user-images.githubusercontent.com/62736640/160002223-74db0d21-b0a9-46ee-8ead-fd975c1da1f0.png)
![backtesting](https://raw.githubusercontent.com/Ryan47Liao/Demo/main/Backtesting.png)
