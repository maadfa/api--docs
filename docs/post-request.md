POST is used when you want to send new data to the server to create something — like signing up for a new account, adding a comment, or saving a product in a shopping cart.

 You can hink of it like filling out a form and clicking “Submit.” The data you send gets stored on the server as something new.If you want to set an alert when Bitcoin hits $65,000. You would send a POST request like this

 '''ruby
 https://myapp.com/api/alerts
 '''
You will send data like this 

{
  "coin": "Bitcoin",
  "alert_price": 65000
}

This will send request to server to  create a new alert for Bitcoin at the price of $65,000.The server receives this data and adds a new entry in its database.

You will recieve response like this

'''
{
  "message": "Alert created successfully",
  "id": 7
}
'''

POST is a type of request used in REST APIs to add something new to the server. When you use a POST request, you're asking the server to create a new entry using the data you send. This is commonly used when you're creating a new user account, submitting a form, sending a message, or uploading a file. For example, when you sign up on a website, your name, email, and password are sent to the server through  POST request, and the server stores this as a new user record. While get gets data from server, POST actually saves new information to the server. POST requests usually carry data in the body.It is  often in JSON format.Post requests are a important part of most web and mobile applications that involve user input.

