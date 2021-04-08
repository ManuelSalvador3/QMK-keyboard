# **QMK-keyboard** 
Files for the different layouts for my KBD67 rev2.   
 
Basically in this respository you wil find the files for the layouts for my keyboar.  
I have 2 layouts, one being a VIA compatible layout you can just load to your own keyboard from the VIA software.  
The other one is a .c file where i explicitly create the layout and i also create two functions to use the backlight of the pcb as a caps lock.  

I have been using this layout for the last year, until i applied some case foam to better up the sound of the keyboard and now i just used the VIA layout and a white LED soldered to the caps lock.


## On the qmk folder you will find 3 files:  
**rules.mk** - Basically it just the default one, i didt change anything, i just copied from another layout.  
**config.h** - Same as rules.mk, i just got the default one from another layout.  
**keymap.c** - .c file where the real layout is defined.  
The first array you will find in keymap.c is the layer 0 where all the normal keys are located and where the only difference is the far right column where i have media keys to Play/Pause, Previous, Next and Delete.  
![layer0](https://user-images.githubusercontent.com/27558633/114104980-2cf5f900-98cc-11eb-9142-8606ae44dfad.PNG)  

The second array is the layer 1 where you will find some lighting keys for the brightness, Hue, On/Off and some different modes like breathing etc.  
![layer1](https://user-images.githubusercontent.com/27558633/114104992-31221680-98cc-11eb-8a96-e92a4a89a920.PNG)


 ### **If you dont understand the keycodes, you can check them here: https://beta.docs.qmk.fm/using-qmk/simple-keycodes/keycodes**


In the VIA folder you will find a json file that defines the layoyut and that you can just upload to VIA and flash the layout into your board. 
In the folder you will also find a jpg of the layout which is the next one:  

## **Layer0:**  
![layer0](https://user-images.githubusercontent.com/27558633/114104740-beb13680-98cb-11eb-82f6-e7386e1b70ef.jpg)  

## **Layer1:**    
![layer1](https://user-images.githubusercontent.com/27558633/114104790-d8527e00-98cb-11eb-87b1-3f18d150f94a.jpg)



### **If you don't understand something you can visit de QMK documentation or just ask me!!**
