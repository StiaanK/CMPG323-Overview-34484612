# CMPG323-Overview-34484612
This is used to manage a project that implements the Scrum and Agile frameworks. This projects consists of 4 smaller projects (5 includig this repo) and a Portfolio of Evidence.


### Repos for smaller projects:
  - Project 2(API Development): https://github.com/StiaanK/CMPG323-Project2-34484612
  - Project 3(Standards & Patterns): https://github.com/StiaanK/CMPG323-Project3-34484612
  - Project 4(Testing & RPA): https://github.com/StiaanK/CMPG323-Project4-34484612
  - Project 5(Reporting & Monitoring): https://github.com/StiaanK/CMPG323-Project5-34484612

This is how the projects tie into one project:

![Untitled Diagram](https://user-images.githubusercontent.com/102803595/184359850-9a64affd-b278-412e-b5aa-3f9113f9ae27.png)


### Branching Strategy:
Each repo will have 2 branches namely main and develop.

main indicates the working project
develop indicates that development is currently taking place.
After a branch under develop is completed and tested, it will then be merged into the main branch.


### .gitignore files:
The .gitignore files will indicate which files will be ignored when files are uploaded to the repo. Files that will be ignored are ones that contain sensitive data. This will apply for all the projects.


### Credentials and sensitive info storage:
This information will be added to .gitignore list and will be stored in a separate file and will not be included in the reposotry, unless it is needed. 

### Burnout chart:
![Screenshot 2022-08-18 153307](https://user-images.githubusercontent.com/102803595/185408524-5ebeadd3-e36d-45aa-ba07-433fb0293212.png)

# CMPG323-Project2-34484612

## When Page is not found
### Testing:
Ensure the URL ends with /swagger/index.html to interact with the API via Swagger.

### Seeing API file:
Ensure the URL contains /swagger/v2/swagger.json

## Authentication
### Step 1: Login
1. Press on the /api/Authenticate/login with the credentials: Username: 'steve' and Password: 'Abc123@'

2. If an 401 error is encountered  it means the credentials are wrong or the user is not added to the database this can be fixed by registering an user (See Registering users section).

3. If the credentials are correct, a token will then be generated.

4. Copy the token within the parenthesis ("<Token>").  <Token> represents you're token and will last an hour.
  
### Step 2: Autherise
1. Press on the Autherise button in the top right conner.
  
2. Enter 'Bearer <Token>' into the promt.

3. You will now be autherised to use the Methods of the controllers.

## Registering users:
1. For normal users press on api/Authenticate/register

2. For admin users press on api/Authenticate/register-admin
 
  ### Passwords:
  Passwords require atleast A capital leter, a number and a special charachter.
  
3. Enter the required data into the fields within the parenthesis
  
## Methods:
  
  ### Get:
  The get methods return all the entries of their respected table.
  
  ### Post:
  The post methods creates a new record within
  
  ### Get with {id}:
  This get method returns a specific record that is selected by reciveing its ID.
  
  ### Put:
  Updates a specific record in their respected table that is selected by reciveing its ID.
  
  ### Delete:
  Removes a specific record in their respected table that is selected by reciveing its ID.
  
  ### Get with Catagory id:
  Returns all the devices that have the same catagory id
  
  ### Get with Zone id:
   Returns all the devices that have the same catagory id
  
# CMPG323-Project3-34484612
### Login:
1. Click on the Login Button
2. Enter your credentials
3. If the credentials are not valid, then will you need to register.
### Registration:
1. Enter the required information into the fields 
!!Passwords require atleast A capital leter, a number and a special charachter!!
## Working with data:
### Selecting Table:
1. Click on the name of the table you wish to view
### Creating a record:
1. Click on the plus symbol next to the table name
2. Enter the required information into the fields 
3. Ensure all the fields are not NULL
4. Click on Create to add the record
### Edit a record:
1. Click on the pencil icon
2. Enter the required information into the fields 
3. Click on Save to update the record
### View a single record:
1. Click on the eye icon 
2. Click on Back to List to return to all the records
### Delete a record:
1. Click on the garabage can icon
2.Click on Delete to remove the record
### Logout:
1. Click on the logout button

# CMPG323-Project4-34484612
This project is used to test a web application by using UiPath. 
It tests the creation of objects aswell as the deletion of them

# CMPG323-Project5-34484612
In this project a report was made for stakeholders regardng the newly developed IoT API. Multiple graphs where made and that displays data regarding the devices that are connected. Stakeholders wll now be able to make decisions regarding this project.


