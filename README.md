# iot-project

 ####
 It is connecting to this websocket using one of the esp32's socket libraries.
 ####
 Esp32's role is; receiving data from the socket and transmitting commands to the arduino uno who is connected to the rx tx. And in addition, a data from arduino uno transmits it to our socket server.
 ####
 Arduino uno, on the other hand, performs the task of opening the relay and sending the value in the potentiometer to us, according to the incoming commands.
 ####
 I also prepared a simple frontend (reactjs). With using this website, you can connect to the socket server and send command or view the data which are coming from esp32.


Keywords:
esp32 socket client
####
socket web server 
