# Space-X-Falcon-9-First-Stage-Landing-Prediction
Space-X-Falcon-9-First-Stage-Landing-Prediction
Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against space X for a rocket launch.

This project involves data collection, data wrangling, data scraping, data visualisation. In addition, interactive dashboards were constructed and machine learning pipelines were used to predict if the first stage will land successfully.

Lab 1_Data Collection: Objectives of this lab were to 'Request to the SpaceX API' and 'Clean the requested data'. Cleaning the data included converting into datetime type, filtering the falcon 9 dataset from the dataset, dealing with missing data etc.

Lab 2_Web Scraping:  In this lab web scraping was done using BeautifulSoup to collect Falcon 9 historical launch records from a [Wikipedia page titled List of Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches). Extracted Falcon 9 launch records in HTML table from Wikipedia, parsed the table and converted it into a Pandas data frame.

Lab 3_Data Wrangling: exploratory Data Analysis (EDA) was done to find some patterns in the data and determine what would be the label for training supervised models.

Lab 4_Exploratory Data Anaylysis using SQL: In this lab EDA was done to analyse the data better using SQL and uploading the dataset into the corresponding table in a Db2 database.

Lab 5_EDA_Data Visualisation: performed exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib.

Lab 6_LaunchSite Analysis using Folium: performed interactive visual analytics using Folium. In this lab marked all launch sites on a map, marked the success/failed launches for each site on the map and calculate the distances between a launch site to its proximities to find some geographical patterns about launch sites.

Lab 7_Dashboard an interactive app using Plotly Dash: In this lab, a Plotly Dash application was built for users to perform interactive visual analytics on SpaceX launch data in real-time.

Lab 8: In this lab, a machine learning pipeline was created to predict if the first stage will land given the data from the preceding labs.
