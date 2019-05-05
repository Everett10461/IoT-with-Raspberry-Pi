# IoT-with-Raspberry-Pi
A first effort on an IoT project.

This is a learning project.  I am a great problem solver, but I am in need of having my skillset refreshed.  I decided to 
do some initial work on an Internet of Things (IoT) project.  I choose the Raspberry Pi as the "Thing."  The exact nature 
of the project is not defined, as learning will take me in unknown directions.

My overall concept of the IoT is that a smart phone, iPad, computer, or other device is used to communicate over the internet
to monitor and control an embedded device -- the Thing.

After a bit of research, I found that the Raspberry Pi is often being used as the embedded device.  So I bought a Raspberry Pi.  It was straight forward to set it up on my local network with WiFi.

The first task is to communicate with the RPi over the local internet.  I have a linux (Ubuntu 18.04) computer set up for development work, and I will use that system to communicate both ways with the RPi.  The first attempt is to make a TCP-IP connection and transfer a simple file between the two devices.

I use Eclipse for an IDE with the Egit plugin.  TCP-IP will be done using network sockets.  There will be three Eclipse projects:  
1. TCP-IP server on the Linux desktop system.
2. TCP-IP client on the Linux desktop system.
3. TCP-IP server on the Raspberry Pi system Linux system.

Item 3, TCP-IP server on the Raspberry Pi system, is a separate build using the TCP-IP server for Linux desktop.
The separate build is required because the two systems have different processors (desktop is x86 and RPi is ARM).
Building the binary executable the ARM processor will be done on the desktop system with a cross-compiler.

All the source code will be typed in from scratch to make the learning experience closer to actual program development.
Egit will be used to track the changes.
I am using [this tutorial](https://www.binarytides.com/socket-programming-c-linux-tutorial/) for my source.



