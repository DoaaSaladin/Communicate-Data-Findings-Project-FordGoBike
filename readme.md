# (Ford Go Bike Dataset)
## by (Doaa Saladin)


## Dataset

>The Ford Go Bike is the Bike-share system operating in SanFrancisco Bay Area, USA. Present at more than 360 stations across San Francisco with two types of plans:

>- Subscriber: a monthly or annual Membership that grants the member unlimited 45-minute trips.
>- Customer: a single ride access that grants the casual user a 30-minute ride within 24 hours.

>Our dataset belongs to february 2019 and includes users data, stations, and time/date of servicing for each trip. At the time of this project, it was not to download historic data from the provided hyperlinks. Therefore the investigated data can be summerized as follows:
>- Trip_duration (in seconds)
>- Trip start time and date
>- Trip end time and date
>- Start station name
>- Start station id
>- start station coordinate (latitude and longitude)
>- End station name
>- End station id
>- End station coordinate (latitude and longitude)
>- Bike id
>- User type
>- User birth year

> The dataset has 183,412 rows and 16 columns in total.
> Each row (observation) represents a bike trip that started during February 2019 in Sanfrancisco.
> Types of data:

>- Categorical: stations' names, user type (subscriber/casual user), gender, and bike Id.
>- Numerical: trips' durations, the coordinates of the stations (latitude/longitude), and births years.
> Some users didn't provid their year of birth or their gender during the registration process. All of these fragmentations need to be taken into account, during the exploration phase.

> User gender Source of data: https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv
Limitations: The developed exploratory data analysis is limited to the available dataset from february 2019.

## Summary of Findings

>- The mojrity of the trips took place during the early morning hours and the during the afternoons.

>- The usage patterns in terms number of rides and duration/trip have positive proportional relationship within the same user segment, a user segment with higher numbers of rides has also higher trips dusrations.

>- The main target audienceare young adult male subscribers aged between 25 to 34 years old.

>- The female population of San Francisco are quit high, despite that the Ford-GoBike community is very small.

>- Female subscribers and female customers consume a bit longer duration/trip than male users>

>- The older the user, the longer duration the ride takes.

>- Female users are generally younger than male users.

>- Most users are between 25 and 34 years old and the second big segment ages between 35 and 44 years.

>- Users with ages above 100 years were considered as system input invalidity.

>- Customers from both genders tend to consume nearly 1.5X - 2X the trip duration the duration taken by subscribers.


## Key Insights for Presentation

> The presentation featured the relevance of usage pattrens in terms of the number of rides, durations and duration per ride and the main target audience (segment of user by user type, gender and age) to determine their preferences and future development areas.
