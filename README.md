# IBM-Data-Science-Course-7-FInal-Project

This is the final project for course 7 in the IBM Data Science course on Coursera. In this project, we take on the role of a data analyst working at a real estate investment trust. The goal is to determine the market price of a house given a set of features (i.e., number of bedrooms, square footage of the home, condition, etc.). These features will be used to analyze and predict housing prices. The dataset included in this project contains house sale prices for King Count, including Seattle, between May 2014 and May 2015. 

The following criteria and skillset are covered in this project:
1. Libraries used:
   - Pandas and Seaborn for importing dataset as csv file and displaying the dataframe
   - Matplotlib and Seaborn used along with Pandas for data visualization (i.e. creating graphs, boxplots)
   - NumPy and Scikit-learn for machine learning tasks such as regression polynomial regression, etc.
2. Obtain statistical summary of data and clean up dataset by removing NAN values and replacing with the mean of the column with replace()
3. Exploratory data analysis (boxplots, correlation, linreg)
4. Model development by fitting a linear regression model and calculating R^2 (correlation of determination) in order to predict price
5. Creating pipeline object to predict price
6. Model evaluation and refinement by splitting data into training and testing sets and using Ridge regression object on training data, and perform second order polynomial transform on both training and testing data.

The following variables are used for analysis in this project: 
|Variable|	Description   |
|--------|----------------|
|id	     |A notation for a house|
|date	|Date house was sold|
|price	|Price is prediction target|
|bedrooms	|Number of bedrooms|
|bathrooms	|Number of bathrooms|
|sqft_living	|Square footage of the home|
|sqft_lot	|Square footage of the lot|
|floors	|Total floors (levels) in house|
|waterfront	|House which has a view to a waterfront|
|view	|Has been viewed|
|condition	|How good the condition is overall|
|grade	|overall grade given to the housing unit, based on King County grading system|
|sqft_above	|Square footage of house apart from basement|
|sqft_basement	|Square footage of the basement|
|yr_built| Built Year|
|yr_renovated|	Year when house was renovated|
|zipcode	|Zip code|
|lat	|Latitude coordinate|
|long	|Longitude coordinate|
|sqft_living15	|Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area|
|sqft_lot15	|LotSize area in 2015(implies-- some renovations)|
