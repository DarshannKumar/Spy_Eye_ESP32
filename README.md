# Spy_Eye_ESP32

ESP32-CAM, socket.io, node.js
2022.08.
This project based on

ESP32-CAM fastest way to stream video output to nodejs server with socketIO
Inglebard/esp32cam-relay
timum-viw/socket.io-client
Main goal
Create simple Survillance system with multiple ESP32-CAM modules. Some other great projects, like Easytarget Camera Webserver are very usefull, but I neede some extra functionality like:

more camera
React on client side
etc
CameraWebServer
Arduino sketch with the following features:

custom hostname
IP last segment as hostname extension --> used on server and client side
extended function

Client
Simple node.js responded html file
React app
Server
Node.js server with socket.io

TODO
Client rewrite into React. --> done
Server side
send to connected clients the camera id-s (ESP32CAM- < IP >) --> done
Authentication
Sketch:
config page in AP mode
save config to sd)
add name (like: Livingroom)
MQTT optional send connected cam name and ip address
Authentication
