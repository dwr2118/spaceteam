# Spaceteam

A modified version of the base code for ESP32 version of the game 'Spaceteam'

Original base code: [https://github.com/ttseng/COMS3930-Fall2024/blob/main/Module%203/espaceteam.ino](https://github.com/ttseng/COMS3930-Fall2024/blob/main/Module%203/espaceteam.ino)

Contributing members: Aliya Tang, Diego Rivas Lazala, Hari Manasa Bhimaraju, and Karin Novelia

![game_over_screen](https://github.com/user-attachments/assets/d6385f60-8493-4d72-8d2a-c9ca3559a64b)
## What you will need:
1. Several LilyGo T-Display board (at least 2 for the game to run).
2. Install the correct [driver](https://github.com/Xinyuan-LilyGO/TTGO-T-Display) for the LilyGo T-Display.
3. USB-C cable with working data connections.
4. Install the [Arduino IDE](https://www.arduino.cc/en/software)

## Arduino IDE Setup:
1. Download the TFT_eSPI library by Bodmer:
    - Open Arduino IDE
    - Click Tools > Manage Libraries
    - Search for "tft_espi" by Bodmer and click install.
    - Navigate to the library on your computer's file manager (e.g., Documents/Arduino/libraries/tft_espi
    - Open the file "User_Setup_Select.h"
    - Comment out "#include <User_setup.h>" near the top of the page
    - Uncomment "#include <User_Setups/Setup25_TTGO_T_Display.h>" further down the page (the lines are in numeric order).

2. Install the ESP 32 Board Library:
    - We will install it through Arduino IDE.
    - First, go to [this website](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html) and under "Installing using Arduino IDE" copy the "Stable release link".
    - Open Arduino IDE.
    - Click File > Preferences
    - At the bottom of the "Settings" tab, in "Additional boards manager URLs", paste the stable release link in the text box, click OK.
    - Click Tools > Board > Boards Manager
    - Search for 'esp32' by Espressif and click Install
      
## How to recreate this project:
1. After setting up, connect your board to your computer with the USB-C cable.
2. Open Arduino IDE. Click the upper-left dropdown menu to select your Board and Port. It will usually pop-up as "LilyGo T-Display" on port "COM xx".
4. Open 'espaceteam.ino' and upload it to all ESP32 devices
5. Try out the game for yourself!

## Design Documentation: 
Read more about our creative processes [here](https://tinyurl.com/interactive-spaceteam). 
