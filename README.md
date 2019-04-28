# raspberry_pi_web_server

Here, I setup web server in my Raspberry Pi. I made a website in Pi to show temperature and humidity using DHT22 sensor.   
Main files are:-  
1. lab_app_uwsgi.ini  
2. lab_app_nginx.conf  
3.  lab_app.py  

# Wiring Scheme:-

![Alt text](wiring_schematic.png?raw=true "Optional Title") 

# Screenshots:-

## Front_page:-
![Alt text](Screenshots/page1.png?raw=true "Optional Title")

## Temperature:-
![Alt text](Screenshots/page2_1.png?raw=true "Optional Title")

## Humidity:-
![Alt text](Screenshots/page2_2.png?raw=true "Optional Title")


# Front End:-
Javascript

Jquery

# Backend:-
Flask

mySQL

# Web server:-
Nginx - Gateway to connect to uWSGI,  by proper port number and IP address using lab_app_nginx.conf

uWSGI - Connect to flask server by creating socket using lab_app_uwsgi.ini
