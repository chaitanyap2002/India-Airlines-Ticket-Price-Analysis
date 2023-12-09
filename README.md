# India-Airlines-Ticket-Price-Analysis
India Airlines Ticket Price Analysis with Power BI &amp; Python 

Objective

As an aviation enthusiast, I've undertaken an exploratory data analysis of Indian airline ticket prices. The aviation market, having faced rock-bottom ticket prices during the peak of the Covid-19 pandemic, is now recovering. However, recent geopolitical events and rising ATF prices have led to soaring ticket prices. This project aims to understand the factors influencing ticket prices in India. The analysis covers aspects such as the number of flights available across India, ticket availability across different classes, price range across different classes, and more.

Check out the project .

About the Dataset
The dataset, sourced from Kaggle, is considered secondary data. It comprises details from the "Easemytrip" website, offering flight booking alternatives between India's top 6 metro areas. The cleaned dataset consists of 11 characteristics and 300,261 data points, gathered in two stages: business class and economy class tickets. The data spans 50 days, from February 11 to March 31, 2022.

Dataset Link: [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

Dataset Features

Airline: Name of the airline firm (categorical).
Flight: Flight code of the aircraft.
Source City: City where the flight departs (categorical).
Departure Time: Time intervals categorized into bins.
Stops: Number of stops between source and destination cities.
Arrival Time: Time intervals categorized into bins.
Destination City: City where the aircraft lands (categorical).
Class: Total number of hours needed to travel between cities (permanent).
Duration: Total number of hours needed to travel between cities (permanent).
Days Left: Derived feature (trip date subtracted from booking date).
Price: Ticket price (target variable).

Power BI Visualization Dashboard

Click to view the Power BI Dashboard. The dashboard provides a quick overview of ticket prices between different cities, flying with different airlines in different classes, along with flight duration.

Conclusion

'Air Asia' offers the cheapest flight tickets in Economy class, while 'Air India' is the cheapest in Business class.

Booking tickets 3-7 weeks before travel is more economical than buying within 3 weeks, as prices rise rapidly.

Ticket prices grow linearly with the duration of the flight, peaking at 20 hours, with some outliers.

Flights departing late at night and arriving early morning or late at night are the cheapest.

Flight prices increase with an increase in the number of stops.


Delhi offers the cheapest flights, while Hyderabad is the most expensive city to fly to.

Vistara had the highest number of flights, accounting for 42.60% across all 6 airlines in India.

For detailed insights, refer to the Power BI Dashboard. Feel free to explore the code and contribute to the analysis. Feedback and suggestions are always welcome!
