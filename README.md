# João Pedro Stuart - Work collection
-- Portfolio of my WIP and finished projects.

# Project 1) [Clustering Analysis to balance player skills of a generic cellphone game](https://github.com/jstuartpieri/players_skill_cluster_analysis)

* Used their API to get players data.
* Used SQL (postgres) to extract Matches and Goals tables.
* Data processing and data wrangling to prepare data to be ingested in the cluster model.
* Dendrogram Analysis
* Agglomerative cluster -- using 6 clusters to split players (used wins and defeat features to cluster ensembling).

![](https://github.com/jstuartpieri/stuart_portfolio/blob/master/images/clustering_img.png)


# Project 2) Classifier to predict wind profiles using load sensors

WIP, EDA - Semptember 15th.

# Project 3) Regressor to predict wind shear values

WIP, EDA - Semptember 15th.

# Project 4) [Buying a used car - Scrapping and Analyzing OLX car's data](https://github.com/jstuartpieri/scrapping_carros_olx)

* Scrapy framework used along with Python to scrape car's data from OLX site.
* Pre-processing to correct some bad formatted data and delete some missing values rows.
* Wrangling data to met some chosen criterias and exported to a csv file.
* Analyzed the data using excel to choose potential good offers.

![](https://github.com/jstuartpieri/scrapping_carros_olx/blob/master/images/image.png)

# Project 5) AWS truepower API wind characterists batch run extraction, processing and Analyssis

This project was done to marketing intelligence GE Renewable Energy team and it's confidential, so code and image previas can not be disclosed.

* AWS truepower API wind characteristics extraction in monthly scope using theirs API -- was used Python to batch run several sites at once -- text file used to store params needed to include as headers in POST method (used to feed batch run inputs).
* Data processing and data wrangling to prepare data to be ingested in Tableau along many other internal datasets.
* Tableau ensembling to give a global viz of wind onshore characteristics using AWS truepower wind data.

# Project 6) LATAM onshore wind Marketing Analysis (Tableau vizualization)

* Using multiple datasets some API extracted others GE internal was created a vizualization to cover some LATAM onshore wind marketing analytics.
* Covered analytics were:
  * Prospect and wind resources, Region Overview, Competitive Landscape, Customer Overview, OEM Selection, Turbines Selection.
  
 

# Project 7) MongoDB localhost configuration to store scrapped rotten tomatoes movies data

* Scrapped Rotten Tomatoes data and exported in JSON format.
* Configured a localhost MongoDB server using 2 shards, each with 3 replicasets to store data extracted.
* Imported rotten tomatoes JSON formatted extracted data to MongoDB shards.
