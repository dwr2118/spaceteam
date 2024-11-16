# Spaceteam

What you will need:
1. A LilyGo T-Display board.
2. Install the correct [driver](https://github.com/Xinyuan-LilyGO/TTGO-T-Display) for the LilyGo T-Display.
3. USB-cable with working data connections.
4. Install the [Arduino IDE](https://www.arduino.cc/en/software)

Arduino IDE Setup:
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
      
How to recreate this project:
1. After setting up, connect your board to your computer with the USB-C cable.
2. Open Arduino IDE. Click the upper-left dropdown menu to select your Board and Port. It will usually pop-up as "LilyGo T-Display" on port "COM xx".
4. Open module.ino and click the right arrow button in the top-left to upload the code to your board.
5. Marvel at the moving hearts~ And feel free to experiment--try changing the colors, the sizes of the hearts, whatever you'd like!

Read more about our creative processes here: 
1. Diego: ()
2. Karin: ()
3. Aliya: ()
4. Hari: ()
