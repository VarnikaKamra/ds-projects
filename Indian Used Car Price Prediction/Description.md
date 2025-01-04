Indian Used Car Price Prediction
The aim of this project to predict the price of the used cars in indian metro cities by analyzing the car's features such as company, model, variant, fuel type, quality score and many more.

About the Dataset
The "Indian IT Cities Used Car Dataset 2023" is a comprehensive collection of data that offers valuable insights into the used car market across major metro cities in India. This dataset provides a wealth of information on a wide range of used car listings, encompassing details such as car models, variants, pricing, fuel types, dealer locations, warranty information, colors, kilometers driven, body styles, transmission types, ownership history, manufacture dates, model years, dealer names, CNG kit availability, and quality scores.

Data Dictionary
Column Name	Description
ID	Unique ID for each listing
Company	Name of the car manufacturer
Model	Name of the car model
Variant	Name of the car variant
Fuel Type	Fuel type of the car
Color	Color of the car
Killometer	Number of kilometers driven by the car
Body Style	Body style of the car
Transmission Type	Transmission type of the car
Manufacture Date	Manufacture date of the car
Model Year	Model year of the car
CngKit	Whether the car has a CNG kit or not
Price	Price of the car
Owner Type	Number of previous owners of the car
Dealer State	State in which the car is being sold
Dealer Name	Name of the dealer selling the car
City	City in which the car is being sold
Warranty	Warranty offered by the dealer
Quality Score	Quality score of the car

Conclusion
In the course of this data science project aimed at predicting used car prices in major Indian metro cities, several significant insights have emerged through exploratory data analysis and machine learning techniques. These insights shed light on both the demand and pricing dynamics within the Indian used car market, offering valuable information to both prospective buyers and sellers.

Demand and Price Trends: One of the most notable observations is the strong correlation between demand and price within the used car market. Lower-priced used cars enjoy a significantly higher demand, indicating a preference among consumers for budget-friendly options. In contrast, luxury car manufacturers such as MG, Mercedes Benz, BMW, Volvo, and KIA command the highest prices. This highlights a trend where consumers are more inclined to opt for new luxury cars instead of pre-owned ones.

Fuel Type Influence: Fuel type plays a pivotal role in pricing, with the market predominantly comprising petrol and diesel cars. Diesel cars, while not overwhelmingly prevalent, do exhibit slightly higher pricing compared to their petrol counterparts.

Color Preferences: Car color also contributes to the pricing dynamics, as common colors like white, grey, silver, and black are in high demand, while more exotic colors such as burgundy, riviera red, dark blue, and black magic tend to fetch higher prices in the used car market.

Kilometer Reading Impact: An analysis of the odometer readings reveals that most cars listed for sale have covered fewer than 10,000 kilometers. Unsurprisingly, cars with lower mileage tend to command higher prices, underlining the importance of mileage in pricing determination.

Body Style Preferences: Body style preferences vary among consumers, with hatchbacks, SUVs, and sedans being the top choices. Conversely, MPVs and luxury SUVs are typically more expensive.

Age and Resale Value: The age of a car is a pivotal factor influencing its resale value. Newer cars, typically those under 5 years old, tend to have higher prices, reflecting a demand for relatively younger used vehicles.

Geographic Price Variation: Significant variation in car prices across different regions has been observed. Delhi, Maharashtra, and Rajasthan stand out as the top states with the highest car prices. Additionally, specific dealers like Car Estate, Star Auto India, and Car Choice consistently list cars at higher prices.

Owner Type and Warranty Impact: Buyers often prefer cars with a 1st owner type, leading to increased demand and higher prices for such vehicles. Additionally, cars offering warranties tend to command slightly higher prices, as warranties provide assurance to potential buyers.

Quality Score and Pricing: The quality score of a car has a direct bearing on its price. Cars with higher quality scores generally command higher prices in the market.

In terms of machine learning models, decision tree regressor and random forest regressor models were employed to predict car prices. Among these, the random forest regressor model demonstrated superior performance. An examination of feature importance revealed that car age, body style, and car manufacturer are the key drivers affecting car prices.

This data-driven project equips both buyers and sellers in the Indian used car market with valuable insights, empowering them to make informed decisions and facilitating more accurate price predictions.
