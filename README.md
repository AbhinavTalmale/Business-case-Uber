# Business Case: Uber

### Insights: 
-   **Late Evenings** and **Early Mornings** are not recommended for **Airport-City transport** or vice versa.
    
-   There is very high demand for cabs from Airport to City between **5:00 PM – 9:00 PM**, but the supply is very less due primarily due to **‘No Cabs Available'**.
    
-   There is very high demand for cabs from **City to Airport** between **5:00 AM – 9:00 AM**, but the supply is very less primarily due to **'Ride Cancellations'**.
    
-   Among the assumed time slots, we can see that the **Late Evening** and **Early Morning** time slots has got the highest gap. This means that during evening & morning hours the probability of getting a cab is very less.

### Reason for Supply-Demand gap:

-   In the Supply-Demand graph from Airport to City, between 5:00 PM to 9:00 PM there is very high demand for cabs because the supply is very low due to ‘No Cars Available’.
    
-   The ‘No Cars Available’ is due to the fact that in the previous hours fewer people travelled from City – Airport and so fewer cars are available in near Airport.
    
-   Likewise, in Supply-Demand graph from City – Airport, between 5:00 AM to 9:00 AM, there is very high demand for cabs because the supply is very low due to Ride Cancellations.
    
-   This is because there were fewer trips to Airport that completed in the previous hours, so now the cabs have to come from a long distance (City) to pickup the passenger and then they have to wait for the passenger’s arrival, so the drivers cancel the trip.

### Recommendations:
-   Awarding incentive for waiting time will encourage the drivers to wait at Airport.
    
-   Drivers could be compensated for taking the night shifts hence covering the 00:00 – 5:00 time slot.
    
-   Seeing this analysis trends, few cabs could be placed in Airports proactively.
    
-   Drivers to be rewarded for the Airport rides making up for the loss in time.
    
-   The cab discovery range to be increased for Airport location, so that the search for cabs would be on a wider range.

### About Uber:

Uber is a transportation company that offers a variety of services, including ride-hailing, food delivery, and freight transport. Uber is headquartered in San Francisco, California, and operates in over 70 countries and 10,500 cities worldwide.

  
### Business Problem:

Uber has received some complaints from their customers facing problems related to ride cancellations by the driver and non-availability of cars for a specific route in the city.

The uneven supply-demand gap for cabs from City to Airport and vice-versa is causing a bad effect on customer relationships as well as Uber is losing out on its revenue.

The aim of analysis is to identify the root cause of the problem (i.e. cancellation and non-availability of cars) and recommend ways to tackle the situation.

  
### Dataset:

The company collected the timestamp data of customers who purchased requested and used the Uber Cabs in July 2016. The dataset has the following features:

| Features                     | Description                                     |
|------------------------------|-------------------------------------------------|
| `Request id`                    | Request id                                         |
| `Pickup point`                 | Pickup point                                      |
| `Driver id`                     | Driver id                                    |
| `Status`                        | Status of the Ride                                     |
| `Request timestamp`                 | Timestamp when the Ride was requested                             |
| `Drop timestamp`              | Timestamp when the Ride was completed                                               |


