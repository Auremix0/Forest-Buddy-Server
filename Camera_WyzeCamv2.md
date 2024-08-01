# Capabilities  - WyzeCamv2

The WyzeCamV2 [Dafang hack](https://github.com/EliasKotlyar/Xiaomi-Dafang-Hacks) allows for alot of different interesting uses, although the page can be a little daunting to look at. This page is to reference the capabilites of the hack along side the specific camera in use. This is based on our research and use of the hack. While all the information listed may work, they may not be the most efficient way to use the hack. A lot of this is **TRIAL AND ERROR** and as we find things, we will update this page.

## Installation

Downloading the hack can be a tad complicated, but this video by [Will Surridge Tech](https://www.youtube.com/@WillSurridgeTech) makes it alot easier.

[![Flash Neos or Wyze Camera with Custom Dafang Firmware - Tutorial](http://img.youtube.com/vi/DD7mLfk_l9I/0.jpg)](http://www.youtube.com/watch?v=DD7mLfk_l9I "Flash Neos or Wyze Camera with Custom Dafang Firmware - Tutorial")

All you will need is a:
  Micro SD card
  WyzeCamV2
  Windows/Mac OS/Linux device
  Software to format FAT32.


### 1. Changing to Custom Firmware
Changing the Firmware is really simple, yet infuriatingly annoying.

  #### 1a Formating
  Starting off we're going to format our SD card. We used the Standard Formating tool that comes with Windows.

  **CAUTION** - the firmware may fail to install if you do not format the card as FAT32.
  #### 1b Downloading the Custome Firmware
  We will have to travel to the Dafang hack page and navigate to [How to install the CFW](https://github.com/EliasKotlyar/Xiaomi-Dafang-Hacks?tab=readme-ov-file#how-to-install-the-cfw). Afterwards we want to select **Wyzecam V2** to start the download of CFW-#.##.bin. When downloaded, change the name of the **CFW-#-##.bin** to **demo.bin**, and put it into our formatted SD card

  **Tip:** if you're installing the hack on multiple cameras, then you can just save this one SD card to use on all of them. It seems reusable, and we have not ran into any issues.
  
  #### 1c Flashing the Custom Firmware
  Remember how we said it was Infuriating? This is the step that caused that sentiment. Firstly start by inserting the SD card into the ***unplugged*** camera. Then start to hold the set up button and get a comfortable grip, you're going to hold this button for a while. Once you find a grip that is comfortable, plug in the camera *WHILE HOLDING THE SET UP BUTTON*, you're going to hold it for about 30 seconds or so. 

  Based on our expirience, it takes about 60 to 120 seconds for it to finish flashing. The camera will go through an array of blue, yellow, and blue-yellow LEDS, but for us it always ends in the LED turning off completly. Additionally, if you hear the Wyze Chime, you either: 
      1: Did not hold the set up button before or during the flashing stage
      Solution: uplug the camera, and try again.
      2: Did not change the name or install demo.bin to the SD card
      Solution: Install the firmware and try again
      3: Did not format the SD card with the file system FAT32
      Solution: find a software that allows you to format your drive to FAT32. Additionally the Dafang hack page mentioned partitioning, so if nothing has fixed your issue, attempt that solution.

### 2. Installing the Hack Itself
here we will list step by step how to install the hack to the camera. We can also add the connection to the internet part. Conisder also having this a list of steps, instead of compounding steps. this is only for installation.



If you encounter any issues, just reference back to the video.
