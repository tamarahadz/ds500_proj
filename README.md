# ds500_proj
Final Project for DS2500

## Data Availibility
Week 1:
NA NA NA 5 6 7 NA

Week 2:
NA 10 NA 12 13 14 NA 

Week 3:
NA 17 18 19 20 21 NA

Week 4:
NA 24 25 26 27 NA NA

In addition to location and weather data, beach closings from prior weeks will be recorded as % open Week 1, % open Week 2, % open Week 3. This will be used to predict whether the beach was open on Week 4. Since a KNN is a binary classification model and does not give us a probability, we will evaluate the accuracy of our model based on whether the beach was open on Wednesday, July 26th. The full list of features is shown below:

## Features for each Beach:
- Latitute
- Longitude
- % of days open on week 1
- % of days open on week 2
- % of days open on week 3
- Average rainfall on week 1
- Average rainfall on week 2
- Average rainfall on week 3

## Labels for each Beach: 
- Closed on July 27th (True or False)
