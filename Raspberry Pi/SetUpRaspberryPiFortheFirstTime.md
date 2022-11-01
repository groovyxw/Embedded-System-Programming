# Preparation

Raspberry Pi 4 B Board

USB-C power supply

Micro SD card with Reader/Adapter (64 GB is preferred)

Monitor with micro-HDMI to HDMI cable, Keyboard, Mouse (Used once, only for the first-time setup)

Ethernet Cable (Optional, we can choose that connect/login to the board in wireless mode, e.g. WIFI)
<img width="452" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199293001-4c7e1b35-08d0-4bee-9866-26ab66a4d90c.PNG">



# Set Up

## Step1. Format Micro-SD card and Install Raspberry Pi OS using Raspberry Pi Imager on your laptop

1. Download Raspberry Pi Imager Tool using this link.
2. Install Raspberry Pi Imager
3. Insert micro-SD card into the related slot in your laptop and Launch Rapberry Pi Imager
   Choose OS  -- "Raspberry Pi OS (32-bit) "
   
   Choose Storage -- "SD card device you want to use"
   
   <img width="223" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199294132-327b38a0-d271-467d-a82c-0bdebc6e4b76.PNG">

After the above steps are done, you have downloaded the OS into your SD Card successfully.

## Step2. Config Raspberry Pi 

1. Insert the micro-SD card into raspberry pi board 
2. Connect raspberry Pi with all others components needed
   Connect Monitor, Keyboard and Mouse with your Raspberry Pi Board
   <img width="300" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199295004-e56feafc-18ac-4d10-a074-4bd0f15f9516.PNG">






3. Power on 
   After power on, you should see the power led is on.
   <img width="308" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199295465-399be5ae-1213-47a3-90fc-a0eff19c93bd.PNG">












   On the monitor, you will see raspberry pi screen.
   
   <img width="328" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199295811-959be2f3-2f43-4ba0-b53c-33e36caa66be.PNG">





4. Config
   Following the instruction on the monitor, do configuration.
   <img width="327" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199295913-d2da8a04-dfdb-4979-824a-31648598bdd6.PNG">
   
   
   
   
   
   
   
   
   
   
   
   
   

   <img width="327" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199296031-9f07a4c4-417b-4a3e-9bf6-09975c81d7ef.PNG">
   
   
   
   
   
   
   
   
   
   
   

    Remember the username and password that are used for logging into your raspberry pi board later.
    
    
    <img width="334" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199296203-a9c8acdc-f968-41c0-af65-e2b609737e88.PNG">
    
    
    
    
    
    
    
    
    
    
    

    <img width="332" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199296551-ec08b3fe-10df-47ac-bc22-f0a25269dc5e.PNG">
    
    
    
    
    
    
    
    
    
    
    

    <img width="338" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199296731-ca872f4f-e98b-4211-a6f4-509550b11352.PNG">
    
    
    
    
    
    
    
    
    
    

    So far, we have done the basic setup for the board already!!!!
    
    
    
5. Get the IP information of your Raspberry Pi Board 
    Open a terminal and type "ifconfig"
    <img width="285" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199297754-a56fbaee-6443-4337-bb8c-8b1e39f655fa.PNG">
    
    Now you have got the IP information.
    Note: If you want to connect Raspberry Pi Board with Ethernet cable, use eth0 ip address   information; otherwise, if you want to connect Raspberry Pi board in WIFI mode, use wlan0 ip address information.
    
    
    
6. Enable SSH and VNC interfaces, otherwise, you could not log in the board by PuTTY/VNC Viewer in next Step. 
    
    <img width="297" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199298013-98d4b4fa-aa56-4890-86df-e262c8c52b13.PNG">
    
    
    
    
    
    
    
    
    
    
    <img width="346" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199298141-86ecd699-6d0b-4f6a-a3f5-e49e52ff0303.PNG">
    
    










7.	Back to your PC/laptop, Download and Install Tool PuTTy or VNC Viewer

    Putty login:
    
    <img width="332" alt="Capture" src="https://user-images.githubusercontent.com/52802567/199298395-3aaf5a35-b6b3-4c6b-9fc0-86d93c67cadd.PNG">
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    <img width="339" alt="ssh" src="https://user-images.githubusercontent.com/52802567/199298671-ba7b164d-1a0c-46a3-b3a9-2e88236e08d3.PNG">
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    

    VNC viewer login:
    
   <img width="342" alt="vnc" src="https://user-images.githubusercontent.com/52802567/199298690-dc5a6928-db34-45af-ad95-51e56b3e80b7.PNG">
