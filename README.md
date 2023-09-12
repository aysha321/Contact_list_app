# Contact-List-React-Coding-Ninjas

Hosted Website Link : - https://glittery-basbousa-43b701.netlify.app/


This is a simple Contact List app built using React that allows users to manage their contacts. The app utilizes the jsonplaceholder.typicode.com API to fetch and display contact information. Users can also add, update, and delete contacts, but these actions are performed on the client side only.

Components Overview  :- 
App.js: The main entry point of the application where routing is configured.
context.js: A custom context provider to manage the contact list and related functions.
Components/Home: Contains the Home.js component to display the list of contacts.
Components/Loader: Contains the Loader.js component to display a loading spinner.
NavBar: Contains the Navbar.js component for the navigation bar at the top.
Pages/AddToContact: Contains the AddToContact.js component for adding new contacts.
Pages/EditContact: Contains the EditContact.js component for editing existing contacts.


Properties and Functions  :- 
contactList: An array containing the list of contacts.
setContactList: A function to update the contactList state.
isLoading: A boolean state to track loading status.
setIsLoading: A function to update the isLoading state.
deleteContact: A function to delete a contact from the list.
nameRef: A useRef to hold the name input reference.
emailRef: A useRef to hold the email input reference.
numberRef: A useRef to hold the phone number input reference.
handleClear: A function to reset input fields after performing actions.

Components/Home/Home.js :-
contactList: Array of contacts to be displayed.
isLoading: Boolean indicating if contacts are being fetched.
deleteContact: Function to delete a contact from the list.

Components/Loader/Loader.js  :-
Displays a loading spinner while waiting for data.

NavBar/Navbar.js :-
Displays the navigation bar at the top.

Pages/AddToContact/AddToContact.js :-
nameRef, emailRef, numberRef: useRef references for input fields.
handleClear: Function to reset input fields.
handleSubmit: Function to add a new contact.

Pages/EditContact/EditContact.js :-
contactList: Array of contacts to be displayed.
nameRef, emailRef, numberRef: useRef references for input fields.
handleClear: Function to reset input fields.
handleSubmit: Function to edit an existing contact.

Instructions :- 
Clone the repository and navigate to the project directory.
Run npm install to install the project dependencies.
Run npm start to start the development server.
Run npm run build to get build file of the App.
Access the App at :- https://glittery-basbousa-43b701.netlify.app/

Features :-
Fetches and displays users from the API.
Add a new contact using a POST request (simulated on the client side).
Edit a contact using a PUT request (simulated on the client side).
Delete a contact using a DELETE request (simulated on the client side).


![Screenshot (3460)](https://github.com/ABHINEET4/Contact-List-React-Coding-Ninjas/assets/108821830/b015d219-3c8e-4b72-b851-ddaea131a848)


![Screenshot (3461)](https://github.com/ABHINEET4/Contact-List-React-Coding-Ninjas/assets/108821830/8a60410b-75e8-4fd9-b429-9b19318d5045)


![Screenshot (3462)](https://github.com/ABHINEET4/Contact-List-React-Coding-Ninjas/assets/108821830/df996793-91a4-4bda-a012-870049277bd7)


![Screenshot (3463)](https://github.com/ABHINEET4/Contact-List-React-Coding-Ninjas/assets/108821830/f245adee-a1cd-4483-a926-5ce3fffdcf0f)


![Screenshot (3464)](https://github.com/ABHINEET4/Contact-List-React-Coding-Ninjas/assets/108821830/8e088353-6b68-496a-8687-c535ac2b9a7d)







