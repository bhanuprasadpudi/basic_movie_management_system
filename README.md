# basic_movie_management_system
basic_movie_management_system
Basic Movie management system:

Overview:
The purpose of this movie management system is to provide users with a convenient way to organize and keep track of their movie collection. It allows users to perform various actions related to movies, such as adding new movies, listing existing ones, marking movies as watched, finding specific movies, updating movie details, deleting movies, and clearing the entire movie database. By offering these features, the system simplifies movie management and enhances the user’s movie-watching experience.

Description:
Project is based on lists, dictionaries, functions, modules in python. This is Base model of the Basic Movie management system.


Let’s break down its functionality:

=> Main program:

1.User Menu:
The script displays a menu of options for the user to choose from.
The available options are:
'a': Add a new movie
'l': List all movies
'w': Mark a movie as watched
'f': Find a movie
'u': Update a movie
'd': Delete a movie
'c': Clear all movies
'q': Quit the program

2.Functions:
The script defines several functions corresponding to the menu options:
.prompt_add_movie(): Prompts the user to input details (title, director, release year, and rating) for a new movie and adds it to the movie database.
.prompt_list_movies(): Lists all movies in the database, including their details (title, director, release year, IMDb rating, and whether they have been watched).
.prompt_watched_movie(): Asks the user to input the name of a movie they’ve watched and marks it as watched in the database.
.prompt_find_movie(): Searches for a movie based on user input (e.g., title or director) and displays relevant details.
.prompt_update_movie(): Allows the user to update details (e.g., rating) for a specific movie.
.prompt_delete_movie(): Deletes a movie from the database based on user input.
.prompt_clear_all_movies(): Clears all movies from the database.
.menu(): Continuously prompts the user for their choice until they select ‘q’ (quit).

3.Usage:
Users can interact with this script by selecting options from the menu.
For example, if a user chooses option 'a', they will be prompted to input details for a new movie, which will then be added to the movie database.


=> Module program:

1.Functions in module:
.create_movie_list(): Although currently empty, this function could potentially be used to initialize the movie list or perform other setup tasks.
.show_movies(): Returns the list of movies stored in the movies variable.
.add_movie(title, director, year, rating): Adds a new movie to the list with the specified details.
.movie_watched(title): Marks a movie as watched based on its title.
.find_movie(): Allows users to search for movies by title, director, year, or rating.
.delete_movie(title): Removes a movie from the list based on its title.
.update_movie(title): Enables users to update movie details (title, director, year, or rating).

2.Usage:
Users can interact with the system using the menu options from the main program.
The functions in module enhance the system by allowing users to add movies, mark them as watched, search for specific movies, update movie details, and delete movies.

=>Functionality:
.Adding a Movie ('a'): Users input details (title, director, release year, and rating) for a new movie, which is then added to the movie list.
.Listing Movies ('l'): The system displays all movies in the database, including their details (title, director, release year, IMDb rating, and whether they’ve been watched).
.Marking a Movie as Watched ('w'): Users enter the name of a movie they’ve watched, and the system updates the movie’s status accordingly.
.Finding Movies ('f'): Users can search for movies based on title, director, year, or rating.
Updating Movie Details ('u'): Users select a movie by title and update its details (title, director, year, or rating).
Deleting a Movie ('d'): Users specify a movie title to remove it from the list.
Clearing All Movies ('c'): Removes all movies from the database.

Tools used: spyder(anaconda)


Conclusion:
The movie management system I had created is a versatile tool for organizing and tracking your movie collection. It allows you to add, list, update, search, and delete movies effortlessly. Enjoy managing your favorite films! 🎬📝
