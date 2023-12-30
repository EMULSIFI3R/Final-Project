# Final-Project
Final Exercise

This project has been made Throught out the last week of December, but wasnt able to be uploaded in Github

10/29/1013

File name has been changed from FinalHandOn.html to FinalProjects


This is an HTML document with embedded JavaScript and CSS, creating a web page for exploring and discovering information about movies. It is a simple movie explorer application that uses the TMDb (The Movie Database) API to fetch movie data.

Purpose:
The purpose of this application is to allow users to search for movies and explore details about them, including their titles, posters, overviews, release dates, vote averages, directors, cast members, and related movies. The design includes a responsive layout to adapt to different screen sizes.

How to Use:
Search for a Movie:

Enter the name of a movie in the search input field.
Click the "Explore" button or press Enter to search for the entered movie.
Explore Trending Movies:

By default, the application automatically displays trending movies of the week.
View Movie Details:

Click on a movie poster to view detailed information about the selected movie in a modal.
The modal displays the movie title, poster, overview, release date, vote average, director, cast, and related movies.
Close Modal:

To close the detailed view modal, click the "x" button in the top-right corner or click outside the modal.
Upcoming Movies:

Click on the "Cinematic Quest" heading to trigger a function (showUpcomingMovies) that could potentially show upcoming movies (though this function is currently commented out in the code).

Technologies Used:
HTML: Structure and content of the web page.
CSS: Styling for the layout and visual elements.
JavaScript: Interactivity and functionality, including fetching data from the TMDb API.
TMDb API: Provides movie-related data (title, poster, etc.).


Key Components:
Search Input: Allows users to enter the name of a movie.

Explore Button: Initiates the movie exploration based on the entered search term.

Movie Cards: Display basic information about movies, including title and poster.

Detailed View Modal: Appears when clicking on a movie poster, providing in-depth information about the selected movie.

Upcoming Movies Functionality: There's a commented-out function (showUpcomingMovies) that might have been intended to show upcoming movies when clicking on the "Cinematic Quest" heading.

Note:
The TMDb API key is included in the script. Ensure that the API key is kept secure and not exposed to the public in a production environment. Also, make sure to comply with TMDb's terms of use when using their API.
