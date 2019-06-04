# IoT-with-Raspberry-Pi
A first effort on an IoT project.

This is a learning project.  I am a great problem solver, but I am in need of having my skillset refreshed.  I decided to 
do some initial work on an Internet of Things (IoT) project.  I choose the Raspberry Pi as the "Thing."  The exact nature 
of the project is not defined, as learning will take me in unknown directions.

My overall concept of the IoT is that a smart phone, iPad, computer, or other device is used to communicate over the internet
to monitor and control an embedded device -- the Thing.

After a bit of research, I found that the Raspberry Pi is often being used as the embedded device.  So I bought a Raspberry Pi.  It was straight forward to set it up on my local network with WiFi.

The first task is to communicate with the RPi over the local internet.  I have a linux (Ubuntu 18.04) computer set up for development work, and I will use that system to communicate both ways with the RPi.

I have decided to take on the project of a completely automated kitchen.

The inspiration for this project comes from sci-fi where a person says they want a particular meal, and it appears in the meal delivery box.  I suppose the process is some sort of molecular assembler.  So, in our world, we need a user interface (browser based with realtime updates), a recipe/menu system (database), an inventory system (database), a storage and retrival system (item recognition--computer vision), a reorder system (supply chain management), material handling system (robotics with computer vision), individual process stations, a scheduling and routing system, quality management system, auto cleaning systems, preventive maintenance system, and safety systems with built-in failsafes. Artificial Intelligence (AI) should learn the users preferences and be able to make suggestions for meals. Also, data should be collected from all kitchens so that overall supply requirments can be understod and used to reduce waste in the supply chain from producer to consumer.

I am choosing to first work on setting up a browser that can control and monitor, in near realtime, a Rasberry Pi's inputs and outputs (I/O).
