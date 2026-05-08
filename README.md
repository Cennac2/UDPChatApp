# An unsecure UDP chat app!

## How to use
### Server
Simply run the server.exe file and input a port that will be used, make sure it's not already used by another app!
Server does not support Linux! Tested only in Windows 10.
### Client
For a Client to connect use the IP of the device where the Server is hosted in, for localhost use the IP `127.0.0.1`. Port is `4218` by default but is changeable.
Client Name can be anything but not an empty value.

The client offers both a GUI (Made with Raylib) and a CLI option, GUI is the default option however you may use the argument `-nogui` to use CLI.
```bash
client.exe -nogui
```
If you'd like to enter the values through arguments then use the following command:
```bash
client.exe -ip <ip address> -port <port> -name <name>
client.exe -ip 127.0.0.1 -port 4218 -name cennac
```

## Build
### Make + GNU GCC Compiler
```bash
make server
make client
```
### Note
The code will be compiled inside the build folder of the project directory. This only works for Windows 10/11! (Only tested in Windows 10)
and yes this sends raw text over the network, what a great app!
