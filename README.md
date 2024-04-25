# Plane Ticket Price Prediction With Random Forest Cross Validation: 91%

![pexels-yeochan-lee-834950780-19567707](https://github.com/roniantoniius/Plane-Ticket-Price-Prediction-with-Random-Forest/assets/121453378/35d3753a-c1b7-4436-a544-6477a562f5b3)

Source: Pexels.com

## Airplane Ticket Price Prediction Project on a site 🤨 🧐 
#### 1. Business Understanding 😇 
Here I want to try to predict airfares in India 😆😆😆. Airfare prediction is crucial in the airline industry to help passengers and airlines in effective travel planning and pricing strategies 😱😱. The problem to be solved includes understanding what factors affect airfare fluctuations, such as travel season, airline, flight route, and departure time. By building an accurate prediction model, we can help passengers get a better estimate of ticket prices before booking, while airlines can use this information to optimize their pricing strategies. This project also aims to give the public a better insight into the dynamics of airfare prices and explain the concept of machine learning in a context relevant to the aviation industry. Therefore, one of the solutions that I can create is a prediction model (if I can get to the deployment stage with azure/aws). In this kernel, I will mostly use some techniques from linear regression. Come on 🫡


#### 2. Data Understanding 😁
The 2019 airfare in India dataset is a collection of data that contains information about airfare prices for various airlines and flight routes in India. The features in this dataset include information such as airlines, departure date, departure and destination airports, flight routes, departure and arrival times, flight duration, number of stops, additional information about the flight, and ticket prices. This dataset can be used to predict or analyze what factors affect airfares in India in 2019, such as travel season, airline popularity, or departure time.

- Airline: the airline operating for a particular flight. These airlines can influence ticket prices based on reputation, type of service, and popularity.
- Date_of_Journey: the departure date of the flight. Airfares may vary by season, day of the week, or holiday.
- Source: the departure city or airport of the flight. Ticket prices can also be affected by the popularity of a particular route.
- Destination: the destination city or airport of the flight. Like the source, the ticket price may differ depending on the final destination.
- Route: the route of the flight which includes any stops or transfers that may be made. The number and type of stops can affect the price.
- Dep_Time: the departure time of the airplane. Ticket prices may vary depending on the departure time (morning, afternoon, evening).
- Arrival_Time: arrival time of the aircraft at the final destination. The duration of the trip may affect the ticket price.
- Duration: The duration of the flight from departure to arrival. A shorter or longer duration may affect the ticket price.
- Total_Stops: The number of stops during the flight. Ticket prices are usually more expensive for non-stop flights compared to those with multiple stops.

- Additional_Info: Additional information about the flight such as special services, baggage rules, or other details. This may affect the ticket price.
- Price: the target or variable to be predicted. Airfare price is a continuous variable that we want to estimate based on the other features in the dataset.

#### 3. Data Preparation: Feature Engineering 😢
- Outlier Removal
- Unvariate and Bivariate Analysis

#### 4. Modeling 😨 😰
- Decision Tree Regressor
- Random Forest Regressor
- XGGradient Boost

#### 5. Evaluation 🧐 🤓 😎
- MSE
- RMSE
- R2
