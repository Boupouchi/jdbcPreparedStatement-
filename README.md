
# JDBC

Here is an overview of the key features of the client and service management application:

Creating Clients:
Users can create new clients by entering their information into the text fields (name, first name, date) in the user interface. They also choose a service from a dropdown list to associate the client with an existing service. By clicking the "Add" button, the details of the new client are sent to the database via JDBC, and the client is added to the list.

Updating Clients:
Users can update the information of an existing client by selecting them from the displayed table. The text fields are automatically pre-filled with the selected client's data, allowing users to make modifications. By clicking the "Edit" button, the changes are sent to the database via JDBC, and the client's data is updated.

Deleting Clients:
Users have the option to delete a client by selecting them in the table. By clicking the "Delete" button, the selected client's ID is used to remove the client from the database via JDBC. A deletion confirmation is requested to prevent accidental deletions.

Client Search:
The application offers a client search function. By pressing the "Search" button, a search window opens, allowing users to specify criteria such as the client's name or first name. Search results are displayed in another table, enabling users to select a specific client.

Service Management:
In addition to client management, the application also supports service management. Services are retrieved from the database and presented in a dropdown list when creating or updating a client. This allows users to associate each client with an existing service.

Display of Client List:
The complete list of clients is displayed in a user interface table. Client information, such as their name, first name, date, and service, is presented in a readable format for easy reference.

Responsive Interface:
The user interface responds in real-time, meaning that suggested data changes (addition, modification, or deletion) are reflected instantly in the interface.

Overall, this application provides a comprehensive set of features for client and service management. It facilitates data management in a user-friendly way through a graphical interface.


## Screenshots

![App Screenshot]()

