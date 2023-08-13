
# Movie NTT

  

Movie Catalog site.

  

## Features

  

- You will [create a subtheme](https://www.youtube.com/watch?v=hPXUn_D2-lE) and customize it using CSS.

- The **homepage** of this site will list Movies in spotlight and the user must be able to click in the movie ‘title’, ‘image’, or, ‘short description’ **to open the movie page in another tab**.

- The **movie page** must have the ‘movie title’, ‘movie poster’, ‘movie synopsis’ and the list of actors in this movie.

- The **actor page** must have the ‘actor name’, ‘actor picture’, ‘actor biography’ and the list of movies in the site that this actor has played a role.

- There must be a **Search** feature in the site header. The user must be able to find movies and actors.

- This site wont take any user registration.

  

## Local environment requirement

 - PHP 8.1
 - Composer
 - Lando

 
## Install process

 1. Clone repo "git clone git@github.com:zatarain21/movie-ntt.git"
 2. Go into "movie-ntt" directory
 3. Run "lando Start"
 4. Run "Composer install"
 5. Run "lando drush movie-ntt-app.lndo.site site:install" for a basic installation
 6. Import database 
 7. Rebuilt Cache