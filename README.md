User Directory Manager
Overview
The User Directory Manager is a JavaScript-based web application that allows users to view and filter a list of users retrieved from a remote API. The application provides a user-friendly interface to search for users and displays relevant information in a table format.

Features
Fetches user data from a remote API (https://dummyjson.com/users).
Maps and displays user information in a table.
Supports filtering users based on the provided search term.
Utilizes local storage to cache user data for a better user experience.
Usage
Open the index.html file in a web browser.
Users are greeted with a table displaying user information fetched from the API.
Use the search input field to filter users by name.
Installation
No installation is required. Simply open the index.html file in a web browser to use the application.

Configuration
The project can be easily configured by modifying the UserDirectoryManager class instantiation in the script.js file. Customize the API URL, user mapping function, display and filter selectors, and storage key according to your requirements.

javascript
Copy code
const userDirectoryManager = new UserDirectoryManager({
    apiUrl: 'https://dummyjson.com/users',
    userMapperFn: (userData) => {
        // Customize user data mapping here
    },
    displaySelector: '#userTable tbody',
    filterSelector: '#filterUsers',
});

Project hosted via Vercel - https://users-gold.vercel.app/
Dependencies
The project uses pure HTML, CSS, and JavaScript. No external libraries or frameworks are required.

Contributing
Contributions are welcome! Feel free to open issues or pull requests.

License
This project is licensed under the MIT License.
