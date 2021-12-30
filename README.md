# BengaluruHousePricePrediction
### Building a Model to Predict the Price of the House in a Banglore

### Data Information :
* area_type	,availability	,location	,size	,society	,total_sqft	,bath ,	balcony	,price
* Rows*Columns (13320, 9)

### Data Cleaning(Not done much) and dropping some feature
* We have to predict the price so we have to drop this feature(from my point of view in order to make more genralize data)'area_type','society','balcony','availability(as it doesnt matter becox we are predicting price)' 
* Some least number of null Values ao i have literally dropped the values

### Feature Engineering 
* Added new feature(integer) column for bhk (Bedrooms Hall Kitchen form i.e 2 BHK or 2 Bedroom etc) that can actually makes sense to Data

