# Wordpress # 
This is a dockerized enviroment to WordPress developers.

## Base Usage ##
1- open `.env` file.  
2- set a unique value for `COMPOSE_PROJECT_NAME`.  
3- set WordPress version  
4- set MySQL version
5- set Port number that must be free to use.
6- run `docker-compose up -d`

## Directory Structure ##
To keep wordpress unchanged, you are not faced with wordpress directories 
directly. However, you must keep in mind that `themes`, `plugins`, `languages`, 
`uploads` directories are those you saw in `wp-content` directory of WordPress. 
In addition, you have access to wordpress configuration files in `config` directory.  

## Publish ##
At this time there is not any building support on this repository. however, You 
can easily copy your themes and plugins and paste anywhere you desire.

## Feature Request ##
This is an ongoing project. Feel free to share your ideas and request new 
features, just open a new issue and tell what you need!

