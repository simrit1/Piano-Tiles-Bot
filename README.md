# Piano-Tiles-Bot
Created a simple bot to play the famous Piano Tiles game. The program is based off the functions that the PyAutoGUI module has to offer.

## Important Documentations:

- **PyAutoGUI's Documentation:** I used this documentation to become familiar with the functions that the PyAutoGUI module has to offer. The PyAutoGUI module plays a crucial role in my Python script because the entire clicking process depends on this module's functions. We use it to scope our coordinates of each of the 4 pixels, check when to click based on the RGB comparison, and perform the click operation. To view the PyAutoGUI module's documentation click [PyAutoGUI documentation](https://pyautogui.readthedocs.io/en/latest/#).

## Key Details:
- The main idea is to simply recognize if any of the 4 pixels we took match the RGB colour code of the tile that must be clicked. If any of the pixels match the desired tile's colour, we perform the click operation. To stop the clicking process, a while loop is set in place and will be terminated upon pressing 'q'.

- LEFTMOST COLUMN: X-761, Y-707.
- LEFT COLUMN: X-887, Y-707.
- RIGHT COLUMN: X-1007, Y-707.
- RIGHTMOST COLUMN: X-1136, Y-707.

- THE RGB CODE OF THE TILE TO CLICK WAS (17, 17, 17)

**Note: This program works with the Piano Tiles game from the website: http://tanksw.com/piano-tiles/. To play it on another website, adjust the coordinates and find the appropriate RGB value for the tile to click.**

## Visuals:
- To view a video of the project in action click [here](https://github.com/akkik04/Piano-Tiles-Bot/blob/main/Project%20Visuals/Piano%20Tiles%20Project%20Video.MOV).

Here is a picture of the Piano Tiles grid for better visualization.

![Piano Tiles Project Grid](https://user-images.githubusercontent.com/81925146/130273366-3b328839-6412-4ce4-acee-457bc1651524.png)
