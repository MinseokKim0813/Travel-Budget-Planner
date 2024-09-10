# Travel Budget Planner

## Description
This feature integrates two APIs: **Beacon Currency** and **Amadeus**, designed to assist travelers in planning their trip budgets in the local currency of their destination. The tool allows users to input a city and receive an estimated budget for hotel costs in that city.

Here’s how it works: the **Amadeus API** retrieves hotel offers based on the user's specified city, check-in date, number of rooms, and number of adults. It then calculates the average hotel cost. Once the hotel cost is estimated, the **Beacon Currency API** converts it into the desired currency, which the user can also set. 

These APIs were chosen because they are free, easy to use, and flexible. The **Amadeus API** offers various endpoints and services, providing potential for future feature development. The **Beacon Currency API** was selected for its lenient usage restrictions and quota limits, making it ideal for frequent API calls.

## How to Use
Using this feature is straightforward. It was developed in **Google Colab**, so simply run the code blocks from top to bottom in sequence. **Make sure not to skip any code blocks.**

## Prerequisites and Setup
There are no installations required. Simply set up **Google Colab**. 
