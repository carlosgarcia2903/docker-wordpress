/**** Start project ****/

To install we have to execute the next command:

docker-compose -f docker-compose.yaml up

This command create environment MySql, PHP and download wordpress.


You have to change the path example: 
volumes:
      - /Users/workspace/Projects/sitewordpress/wordpress/:/var/www/html/