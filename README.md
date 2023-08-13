
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

## Install process in local

 1. Install Lando
 2. Follow this process to create a clean installation of drupal https://docs.lando.dev/drupal/getting-started.html to have the this images working on docker (bitnami/mysql:5.7.29-debian-10-r51 &
devwithlando/php:8.1-apache-4)
 3. Add remote repo "git remote add origin git@github.com:zatarain21/movie-ntt.git" 
 4. Pull files from repo
 5. Run "composer update"
 6. Import database 
 7. Rebuilt Cache

## Install process in a web server

 1. Create database and user as usual
 2. Clone the repo  "git clone git@github.com:zatarain21/movie-ntt.git"
 3.  Run "composer install" to get core, modules and vendor files
 4. Install drupal from web or drush
 5. Import database 
 6. Rebuilt Cache
