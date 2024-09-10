# Travel Budget Planner

## Description
This data feature combines two APIs: **Beacon Currency** and **Amadeus**. It’s designed for people planning to travel to another country. The goal is to help them plan their travel budget in the local currency for a specific city.

The user can input the city into the program and get an estimated budget for hotel costs in that city. Here’s how it works: using the **Amadeus API**, the program retrieves hotel offers and calculates the average cost of a hotel stay. The user can adjust the check-in date, number of rooms, and number of adults. Then, the program uses the **Beacon Currency API** to convert the estimated hotel cost into the desired currency, which the user can also set.

## About APIs
I chose these APIs mainly because they’re free and easy to use. The **Amadeus API** offers various endpoints and other services, which means there’s potential for adding more features in the future. The **Beacon Currency API** has lenient restrictions on usage and quota limits, so it’s been simple to work with.

## How to Use
Using this feature is simple. It’s written in **Google Colab**, so all you need to do is run the code blocks from top to bottom, one by one. **Please do not skip any code blocks**. You will have to get API keys, secret keys and authentication token, which is discussed in the next section.

## Prerequisites and Setup
There’s no need to install anything, but you will need to set up **Google Colab**. 

Also, note that I wrote the authentication tokens, API keys, and an API secret from my account at the top. If they expire or do not work, you’ll need to sign in to the **Amadeus API** and **Beacon Currency API** to get your own authentication tokens, API keys, and secrets. The links to the appropriate webpages are included in the **Google Colab** document. In Google Colab, add Amadeus API key as "Amadeus"; add Amadeus secret key as "AmadeusSecret"; and add Beacon Currency API key as "CurrencyBeacon". 
