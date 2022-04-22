# what is it
A simple revert proxy using nginx with docker-compose

# How to use it

You will need to adjust the nginx.conf file base on your need e.g. change the port to different than 9000, change the server listener host,...

Then run the container by docker-compose command
```
  docker-compose up -d
```
Test it by access the url
```
  localhost:9000
```
you will reveive 503 error page

  
