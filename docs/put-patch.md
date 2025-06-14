# PUT – To Update or Replace Existing Data
PUT is a type of request used in REST APIs to update or replace existing data on the server.PUT  request adds new data and replace the previous one.For example, if you want to update your profile information like name, email, and phone number, the app sends a PUT request with all the updated details. The server then saves this new information and replace the old data entirely.


PUT is used when you want to update something completely on the server. It replaces the old data with the new data that you send.You can imagine that you are filling out a complete form to update your profile. When you click 'Save', all the old information is replaced with the new details you just entered.PUT method works in same way.It updates everything.



# Example: Update a User Profile
If you have a user with ID 5, and you want to update all their information.Then you can use PUT request.


``` 
https://myapp.com/api/users/5
``` 

Data You Send


``` 
{
  "name": "Ali Raza",
  "email": "ali@example.com",
  "phone": "03001234567"
}
``` 
This tells the server to rplace everything about user 5 with this new data.”

 So, PUT is used when you're sending the complete updated data.

 # PATCH 

 PATCH is a type of request that is used in REST APIs to make a small update or partial change in data on the server. Unlike PUT, which replaces all of the data, PATCH is used when you only want to change one or two specific fields. For example, if a user wants to update just their email address without changing their name or phone number, a PATCH request is sent with only the new email. The server then updates only that part of the data,and rest of data remains the same. PATCH is helpful when you don’t want to resend all the information.





