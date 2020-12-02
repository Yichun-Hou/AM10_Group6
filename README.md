# Booking.com: Analysis and Visualization of European Luxury Hotel Ratings 
## AM10_Group6

**Story Time:** We are a group of individuals working within the Data Analytics Team at Booking.com, and have been asked to gather insights on the mid- to high-end (luxury) hotel market in Europe. We are to present our results to our Team Lead. 

As such, our analysis will incorporate the following questions and components:
- an initial investigation of an external dataset on global hotel chains by segment, to get an overview of the strength of presence of luxury hotels in Europe, as well as the general distribution of hotel segments in our geographic area of interest 
- distribution of ratings per country 
- mapping of individual luxury hotels per city by average review score 
- sentiment analysis: overview of the number of positive / negative words per review per continent, and per region; word clouds of most mentioned positive and negative words in reviews 
- an investigation into bot (duplicate) entries
-	a final check of linear regression as to how predictive nationality and natural language processing (number of positive / negative words) are in predicting individual ratings


**Data:**
For a preliminary analysis, we used the dataset below to get an overview of the distribution of global hotel chains.

[Link](https://www.kaggle.com/ployyyywa/global-hotel-chain-presence) - Dataset on global hotel chain presence

The main dataset contains 515K customer reviews containing scores for a total of 1493 random luxury hotels across Europe, in the capitals of six selected countries of interest. These include the United Kingdom, the Netherlands, France, Italy, Spain, and Austria. 

[Link](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe) - Main dataset regarding mid & high-end hotel reviews in Europe

The csv file contains 17 fields. The description of each field is as below:
Hotel_Address: Address of hotel.
Review_Date: Date when reviewer posted the corresponding review.
Average_Score: Average Score of the hotel, calculated based on the latest comment in the last year.
Hotel_Name: Name of Hotel
Reviewer_Nationality: Nationality of Reviewer
Negative_Review: Negative Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Negative'
ReviewTotalNegativeWordCounts: Total number of words in the negative review.
Positive_Review: Positive Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Positive'
ReviewTotalPositiveWordCounts: Total number of words in the positive review.
Reviewer_Score: Score the reviewer has given to the hotel, based on his/her experience
TotalNumberofReviewsReviewerHasGiven: Number of Reviews the reviewers has given in the past.
TotalNumberof_Reviews: Total number of valid reviews the hotel has.
Tags: Tags reviewer gave the hotel.
dayssincereview: Duration between the review date and scrape date.
AdditionalNumberof_Scoring: There are also some guests who just made a scoring on the service rather than a review. This number indicates how many valid scores without review in there.
lat: Latitude of the hotel
lng: longtitude of the hotel

