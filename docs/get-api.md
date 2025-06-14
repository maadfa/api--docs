# GET

GET is the most commonly used type of request in REST APIs. It is used to get or fetch data from the server.A GET request is sent behind the scenes when you open a website or view your profile in an app to ask the server for that information. For example, if you want to see the current Bitcoin price or check the weather in your city, your device sends a GET request to the API, and the server responds with the latest data. GET requests are safe because they do not change anything 

GET request is used to get data from the server like reading a user’s profile.A GET request is used when you want to get information from a server. You are not sending or changing anything.You are just asking the server to show you something.

# Example : Bitcoin API ( To Get current Bitcoin price)

 You can send a GET request to a public Bitcoin API.

'''bash
https://api.coindesk.com/v1/bpi/currentprice.json
'''

This URL sends a GET request to Coindesk’s server.The server replies with Bitcoin price data in JSON format

# Sample Response:


'''json
{

  time: {

    updated: Jun 14, 2025 12:03:00 UTC

  },

  bpi: {

    USD: {

      rate: 66,345.20

    }

  }

}
'''

# Weather API (Getting current weather info)


You want to check the weather in London. You can use a weather API like OpenWeatherMap.

Example URL:

'''bash
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY
'''


This sends a GET request to the OpenWeatherMap server to get weather data.The server returns weather data for London.

## Sample response 

'''json
{

  weather: [

    {

      main: Clouds,

      description : overcast clouds

    }

  ],

  main: {

    temp : 289.5

  },

  name: London

}
'''

