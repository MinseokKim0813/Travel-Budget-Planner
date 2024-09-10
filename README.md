# Travel Budget Planner

## Description
It is a data feature that combines two APIs: **Beacon Currency** and **Amadeus**. It was designed for people who are planning to travel to another country. The purpose is to help them plan the budget for traveling to a specific city in the local currency.

The user can input the city into the program and get the estimated budget for hotel costs in the city. Here is how it works: using the **Amadeus API**, it gets the hotel offers from the API and calculates the average hotel cost. The user can adjust the check-in date, number of rooms, and number of adults. Then, with the calculated estimated cost for the hotel, the program uses the **Beacon Currency API** to convert that cost into the desired currency. The user can set the currency as well.

These two APIs were chosen mainly because they were free. Plus, the **Amadeus API** supports various endpoints and other services, so in the future, it could also develop additional features. The **Beacon Currency API** has lenient restrictions on API usage and limit quotas, so it was easy to use.

## How to Use
How to use the data feature is simple. It was written in **Google Colab**, so the user simply needs to run the code blocks from top to bottom, one by one. **Please do not skip any code blocks.**

## Prerequisites and Setup
For the prerequisites or setup, there is no need to install anything except for setting up Google Colab.
