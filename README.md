# AirBnB-Python-Project

<h2>Project Overview</h2>

This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, Seabornfor cleaning, visualization, and analysis.

![New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2](https://github.com/user-attachments/assets/a5afbec7-4fa6-41cc-a021-898f4ce1afbd)


<h2>Objective</h2>

The goal of this project is to:

1.	Analyze room types, prices, and availability across different neighborhoods.

2.	Understand host behavior and listing patterns.

3.	Detect potential outliers in prices.

4.	Provide recommendations for guests and hosts based on insights.

	


<h2>Dataset</h2>

The dataset contains 20,765 entries and 22 features, including:

•	id: Unique identifier for each listing

•	name: Title of the Airbnb listing

•	host_name: Name of the host

•	neighborhood_group: Group (borough) where the listing is located

•	latitude/longitude: Geolocation of listings

•	price: Nightly rental price

•	room_type: Type of accommodation (e.g., entire home, private room)

•	reviews_per_month: Average monthly reviews for the listing

•	availability_365: Number of available days in the year.


<h2>Steps and Workflow</h2>


<h3>1. Data Cleaning</h3>
   
•	Handle missing data: price, neighborhood, and beds columns had null values.

•	Fix data types: Converted last_review to a datetime object.

•	Remove outliers: Listings with prices > $1,000 were capped to avoid skewed visualizations.



<h3>2. 	EDA (Exploratory Data Analysis)</h3>



  <h4>1.	Room type distribution:</h4>

  •	Visualized the count of each room type using bar plots.
      
  •	Identified Entire home/apt as the most common room type 


<h4>2. Neighborhood group insights:</h4>


1.	Room type distribution:
	
	o	Visualized the count of each room type using bar plots.

	o	Identified Entire home/apt as the most common room type.




4.	Neighborhood group insights:
	
	o	Analyzed price variations by boroughs.

	o	Manhattan had the highest average prices.

7.	Availability trends:
	
	o	Used heatmaps to show correlations among price, availability_365, number_of_reviews, and beds.

10.	Price distribution:
	
	o	Used histograms to show the distribution of prices.

	o	Majority of the listings were priced between $50 - $300.

13.	Host listings:
	
	o	Analyzed hosts with multiple listings using boxplots to identify key contributors.

16.	Review behavior:
	
	o	Used pair plots to show relationships between number of reviews, price, and availability.



<h3>3. Data Visualization</h3>

•	Pairplot: To see correlations among price, availability, and number of reviews.

•	Heatmap: Showing correlations among numerical features.

•	Histograms and Boxplots: To detect outliers in price.

•	Bar Charts: Displaying room types and neighborhood group distributions.




<h2>Key Findings and Insights</h2>

   





   1.	Price Trends:
      
		o	Manhattan has the most expensive listings, followed by Brooklyn.

		o	Entire homes/apartments cost significantly more than private or shared rooms.

2.	Room Type Distribution:
	
	o	Entire homes/apartments are the most common, but private rooms offer budget-friendly options.

3.	Outliers in Price:
	
	o	Few listings priced at $10,000+ were detected, indicating the need to filter such extreme values.

4.	Availability Patterns:
	
	   o	   Listings with high availability tend to have lower prices and more reviews, likely due to better guest experience.

5.	Host Behavior:
	
	o	Some hosts manage multiple listings, indicating a trend toward professional hosting.





## Conclusion
This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using EDA techniques, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.
