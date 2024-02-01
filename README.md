# GithubSearchApp

# GIF:
![Animation2](https://github.com/SakirParlakbileker/GithubSearch/assets/147662891/0a2ca8c8-ef79-42f5-997f-7bb0e37bcb68)

This GitHub project is a simple web application that allows users to search for GitHub users and view their basic information along with some of their repositories. Here's a breakdown of the technologies used in the project:

# HTML: 
The structure and layout of the web pages are defined using HTML. HTML is used to create the form, user cards, and error messages that are displayed to the user.

# CSS: 
Cascading Style Sheets (CSS) are used to style the HTML elements, providing visual enhancements and improving the overall presentation of the application.

# JavaScript (with Axios): 
JavaScript is used to add interactivity to the application. The Axios library is utilized for making HTTP requests to the GitHub API endpoints asynchronously. The main functionalities implemented in JavaScript include:
Fetching user data from the GitHub API based on user input.
Displaying user information such as name, username, bio, follower count, following count, and public repository count.
Handling errors, such as when a user is not found or when there is an issue fetching repository data.
Dynamically updating the DOM to display user information and repository links.
Event handling for form submission and user input.

# GitHub API:
The application interacts with the GitHub API to retrieve user data and repository information. It utilizes endpoints such as 
`https://api.github.com/users/{username}` to fetch user details and `https://api.github.com/users/{username}/repos`to fetch repositories belonging to a specific user.
# Font Awesome Icons: 
The application utilizes Font Awesome icons to enhance the visual presentation of user information and repository links.

Overall, the project is a simple yet effective demonstration of using HTML, CSS, and JavaScript to interact with external APIs like the GitHub API, allowing users to search for GitHub users and explore their repositories.

