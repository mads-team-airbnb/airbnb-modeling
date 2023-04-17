# airbnb-modeling
<h2>Capstone Project: Airbnb Price Predictor</h2>
<h3>About our Project</h3>
Our goal was to develop a price prediction model for Airbnb listings. We designed this model with hosts in mind to help them decide how to price their listings. We did exploratory data analysis on four cities including Austin, Chicago, Nashville and Portland and decided to narrow our focus to only Austin for the final model. This folder contains exploratory data analysis, failure analysis and sentiment analysis using NLP.

<h3>Clone the repo</h3>
https://github.com/mads-team-airbnb/airbnb-modeling.git

Then, install the necessary packages
pip install -r requirements.txt

<h3>Data</h3>
The Airbnb data used in these notebooks is publicly available data and was obtained from Inside Airbnb (http://insideairbnb.com/).

The datafiles used in these notebooks can be accessed at https://drive.google.com/file/d/1WtPMSnGDZRgz-XPmtmooaNlK8NkFdca2/view?usp=share_link

Here is a brief description of the datafiles located in the google drive and what notebooks they were used in:

<h4>Exploratory Data Analysis</h4>
Calendar.csv contains the calendar of listings for each city scraped in 12/2022
Listings.csv contains the scraped data for 12/2022 for all cities
Neighbourhoods.csv contained the scrapped date for the neighborhoods in each city scraped in 12/2022 
Reviews.csv contains the reviews for all cities scraped in 12/2022

<h4>NLP Sentiment Analysis</h4>
reviews-Austin032023.csv.gz contains the reviews for Austin scraped in 03/2023 
reviews-Austin062022.csv.gz contains the reviews for Austin scraped in 06/2022
reviews-Austin092022.csv.gz contains the reviews for Austin scraped in 09/2022
reviews-Austin122022.csv.gz contains the reviews for Austin scraped in 12/2022

<h4>Final Model and Failure Analysis</h4>
City_lat_long_coordinates.csv contains the latitude and longitude for each city
Austin_listings.csv.gz contains all 4 quarters listing datasets for Austin 
Failure Analysis.csv contains the combined X_test, y_test and y_pred values combined into one sheet using 

<h3>Airbnb Modeling folder</h3>
Holds five notebooks for exploratory data analysis, failure analysis and NLP analysis.
Capstone_Data_Exploration_Khem.ipynb shows the exploratory data analysis conducted by Khem
Capstone_Exploratory.ipynb shows  the exploratory data analysis conducted by Jackie
Capstone_Models_NLP.ipynb shows the impact of using sentiment analysis on the random forest regressor
Exploratory Data Analysis part 1.ipynb shows the exploratory data analysis conducted by Rachel
Failure_Analysis.ipynb shows failure analysis including looking at the differences in true and predicted prices with specific examples from the test set

<h3>Credits</h3>
These notebooks were created by Khem Sok, Rachel Cokeley, and Jacqueline Shulack
