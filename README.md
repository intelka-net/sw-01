# SW-01
Intelka Smart Switch 1 Gang Repo

This repo purpose is to give everyone interesed a deeper look to the IntelKA Single Switch available for purchase at https://www.intelka.net

What is it?
It's an MQTT Wifi Wall Mounted Smart Switch that can be linked with any MQTT Compatible Smart House Software, like HomeAssistant, OpenHAB, NodeRed... etc. using the popular ESP8266

IMPORTANT: Requires a Neutral Cable at the installation box

Why did you make it?
Because I tried to buy off the shelf switches and they force you to use their own app, give away your personal information to some obscure company lost somewhere in the middle of the woods and by the time you realize you already have multiple apps to control your house appliances, depending on the terms of service of each cloud provider they could potentially ask for money later on to keep your house running including the risk of someone hacking in due to some security issue.

What makes it special?
At home we use both IOS and Android and it allows me to integrate directly with Apple Products through HomeAssistant + HomeKit and also with HomeAssistant + Google Assistant and keep other products working through only one App!

You can link it with any MQTT compatible software! You can directly send it commands, it has a physical button to press and give physical feedback and blend in as a normal wall switch.

Where are the files for 3D Printing?
You'll find in this repository a "fitting" file for you to check if the switch dimensions are good for your wall. If you're satisfied with the footprint you can then go to my website https://www.intelka.net and purchase for what I consider a reasonable price an assembled switch for you to play with! That way you support my work and allow me to spend more time creating cool home automation projects! :D

What about the code? 
I wrote my own special firmware that handles my current needs, super light weight and very little configuration (Only enter your WiFi and MQTT Broker details and you're set to go!) by using the MQTT Auto Discovery feature from HomeAssistant to make it automagically show up on your dashboard!. I'm trying to make my hobby a small business I provide the compiled version in .hex version you can easily burn it on any ESP8266 board and following the Simplified Diagram you can check out if this would work for you. If that would be the case you can then go to my website https://www.intelka.net and purchase for what I consider a reasonable price an assembled switch for you to play with! That way you support my work and allow me to spend more time creating cool home automation projects! :D

![SimplifiedSchematicSW01](https://user-images.githubusercontent.com/122814994/212727556-2644c7e3-6e7e-4ecf-8637-206c9392de77.jpg)

What about ESPHome?
If you're part of the group that uses ESPHome you can get the YAML file in this Repo. I had tried using ESPHome recently but for my specific setup (Raspberry Pi Zero W 2 ) can't handle it, it's too resource intensive! By using my own firmware I can run all my smart wall switches natively (No Addons!) But please feel free to go ahead and check the YAML sketch.

Give it a try!


