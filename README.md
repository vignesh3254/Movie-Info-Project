
# Movie Info

This project is a simple web application that allows users to search for movie information using the OMDB API. The application includes an authentication system with sign-up and sign-in functionalities. Once signed in, users can search for movies and view detailed information.

## Description
The authentication page provides two forms for users to sign in and sign up. Upon successful sign-in, users are redirected to the movie library page.
## HTML Structure
1. Header: Contains navigation buttons (Sign In, Sign Up).
2. Sign In Form: Includes email and password fields.
3. Sign Up Form: Includes username, email, and password fields.
## CSS (styles.css)
Basic styling for the header, navigation buttons, and forms.
## JavaScript
1. Functions to toggle between the Sign In and Sign Up forms.
2. Form submission handlers to simulate sign-in and sign-up actions.
# Movie Library Page

## Description
The movie library page allows users to search for movies by title using the OMDB API and displays the results in a card format.

## HTML Structure
1. Header: Contains navigation links (Home, Sign Out).
2. Search Form: Includes a text input and a search button.
3. Result Section: Displays movie information.

## CSS
1. Styling for the header, navigation links, search form, and result cards.
2. Background image styling.

## JavaScript (with jQuery)
1. Form submission handler to fetch movie data from the OMDB API.
2. Function to display movie information in a formatted card.
3. Sign Out button handler to redirect to the authentication page.

## OMDB API Integration
1. The OMDB API is used to fetch movie data.
2. An API key (apikey=310d9198) is required to access the OMDB API.
3. AJAX requests are made using jQuery to fetch and display movie data.

## Note
1. The server-side authentication script (auth.php) is not included in this example. You need to implement the backend logic to handle authentication if required.
2. Ensure you have a valid OMDB API key and update it in the JavaScript code if necessary

## Dependencies
1. Bootstrap 5.3.2: For styling the movie library page.
2. jQuery 3.7.1: For making AJAX requests and handling DOM manipulations
## How to Run the Project

1. Clone the repository:

```bash
  git clone https://github.com/your-username/movie-library-project.git
```

2. Open the project directory:

```bash
  cd movie-library-project
```

3. Open index.html in your browser to access the authentication page.

4. Sign up or sign in to be redirected to the movie library page.

5. On the movie library page, enter the name of a movie and click "Search Movie" to view the details.
    
## Acknowledgements

1. OMDB API for providing movie data.
2. Bootstrap for CSS framework.
3. jQuery for simplifying JavaScript operations.