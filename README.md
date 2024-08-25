# USER AND USERGROUP MANAGEMENT PROJECT
This is a simple .NET project designed to manage user groups and users. The application allows the creation, editing, and deletion of both user groups and users. The data is displayed in tables on the same page, providing an easy-to-use interface for managing these entities.

# Features

###  User Group Management:
Create a new user group by entering a group name and a group code.
Display a list of all user groups in a table on the same page.
Edit or delete existing user groups directly from the table.

### User Management:
Create a new user by entering a username, full name, password, and confirming the password.
Display a list of all users in a table on the same page.
Edit or delete existing users directly from the table.

### Project Structure

#### Controllers: Handles the request and response between the views and the models. 

*UserGroupController.cs:* 
 Manages user group operations.
*UserController.cs:* Manages user operations.

#### Models: Contains the classes representing the entities in the application.
*UserGroup.cs:* Represents a user group with properties for name and code.

*User.cs:* Represents a user with properties for username, full name, and password.

### Views: Contains the Razor pages or HTML files that define the user interface.
*UserGroupView.cshtml:* Interface for managing user groups.
*UserView.cshtml:* Interface for managing users.

### Database: We use the my sql server as the database to store the data from frontend to backend .

#### Usage

#### Adding a User Group:

Navigate to the User Group management page.
Enter the user group name and code.
Click "Submit" to add the user group.
The new user group will appear in the table below the form.
![welcoming to the site](https://github.com/user-attachments/assets/467584eb-1bac-43da-8e90-c78aec661640)

![Usergroup page](https://github.com/user-attachments/assets/27e3fcf3-93a0-4476-b8d6-90ae17bba440)
![usergroup input](https://github.com/user-attachments/assets/340c8773-290d-4ec4-b3fe-fde9995dc164)
![usergroup added](https://github.com/user-attachments/assets/ac124671-0324-45f6-8db5-0c55e3fd4df7)
![multiple data added usergroup](https://github.com/user-attachments/assets/fec75893-c4f6-41ce-a0c9-4204ee4c4304)


#### Searching User Groups:
Use the search functionality to filter user groups by name or code in the table.
![searching usergroup](https://github.com/user-attachments/assets/26e58b0c-a980-4bc4-a2de-ceb2017bcfea)
![search through code](https://github.com/user-attachments/assets/8d364d7c-9e68-4a35-aeab-06f70a72a67c)


#### Editing/Deleting a User Group:

Locate the user group in the table.
Click the "Edit" button to modify the group.
Click the "Delete" button to remove the group.
Adding a User:
![modified](https://github.com/user-attachments/assets/4c6065c2-e6df-458d-acda-55290536393f)
![repeated](https://github.com/user-attachments/assets/a6c5a925-6e3e-4024-b832-efce960df3ef)
![updated usergroup name](https://github.com/user-attachments/assets/255834d1-c0b7-4621-ad22-de9b5bc472d0)
![deleted the usergroup](https://github.com/user-attachments/assets/be241771-055f-4539-ad14-615aa4225e38)
![deleted](https://github.com/user-attachments/assets/07b5342a-4ab3-4d80-92dd-25bee35d79fe)

Navigate to the User management page.
Enter the username, full name, password, and confirm the password.
Click "Submit" to add the user.
The new user will appear in the table below the form.
![user page](https://github.com/user-attachments/assets/766da27e-a0cf-418f-a315-e7ee624f7828)
![user input](https://github.com/user-attachments/assets/69cc5c10-e492-484b-9556-e101fbbe41f9)
![submited user](https://github.com/user-attachments/assets/50fb73c4-f770-422c-b34f-be45d02167c9)

#### Editing/Deleting a User:

Locate the user in the table.
Click the "Edit" button to modify the user details.
Click the "Delete" button to remove the user.
![edit user](https://github.com/user-attachments/assets/b5076629-d51b-4479-8d01-83b91bf14294)
![edited](https://github.com/user-attachments/assets/f963083f-afea-4943-b94d-db834a9645cb)
![delete user](https://github.com/user-attachments/assets/0b72b648-26db-4de4-bfea-cb6a36fb5f80)
![deleted user](https://github.com/user-attachments/assets/9b89af19-cc6f-42a5-a99f-189a510f6793)
