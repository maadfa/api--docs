DELETE – To Remove Data from the Server

DELETE is used when you want to remove something from the server .It includes deleting a file, a user, or a saved alert.DELETE is a type of request used in REST APIs to remove or delete data from the server. When you send a DELETE request, you are telling the server to permanently erase a specific item, such as a user account, a post, or a saved alert. For example,  You can send DELETE request if you no longer need Bitcoin price alert your app.  The server would remove it from the database. DELETE requests usually don’t need a body.It just needs the correct URL with the ID of the item to be deleted. It is like clicking a “delete” or “trash” button on an app.Once it is  deleted, it is gone from the system.

It is like clicking a “Delete” button which removes the item .

# Delete a Bitcoin Alert


Let’s say you created a Bitcoin price alert with ID 3, and now you want to delete it


``` ruby
https://myapp.com/api/alerts/3
``` 

This tells the server to Delete the alert that has ID 3.You don’t need to send any data .The server knows what to delete based on the ID in the URL.

