## README

This is a bot used for farming Energy Elixirs for Wizard101 through Grub Guardian.

The bot is programmed in Python 3.10.6 and uses OpenCV's 'Template Matching' feature to match images to the game's GUI and complete the level for you.

The bot only works on the Tanglewood Way stage, and the BlueStacks instance must be in Fullscreen and at 1980x1080 (Untested) resolution.

The strategy used by the bot is from my YouTube video "How to farm free Wizard101 energy elixirs on Grub Guardian"

To run the bot, you first must have Grub Guardian installed on Bluestacks (Instructions in section below).

Next, you must install Python and the required Python Libraries. (OpenCV, Pyautogui, Numpy) The links can be found in the 'Installed Libraries' section of this readme.

You can install these to your version of Python by running the command 'python -m pip install opencv-python numpy pyautogui' in your Command Prompt (Windows only).

Make sure to open the Repository's folder if you are using VSCode. If you do not, the script will not be able to access the images in the imgs folder.

Additionally, the player must have a Mega (Not Ultra, as it will NOT work!) Life Pet equipped, as well as the Wysteria Map Pack and Star Guardian unlocked for this program to function correctly.

Finally, launch the game, login, and set it on the Wysteria Map page (Shown below).

<img src="imgs/wysteriaWorldPack.PNG" alt="Alt Text" width="300" height="200">

Now, simply run the program and the bot will loop through the game farming Tanglewood Way for you.

The approximate rate of Energy Elixirs (EEs) is 1 EE per 5 runs, although this can vary due to RNG.

## Guide to Installing Grub Guardian on Bluestacks
**Disclaimer:** These steps will likely not work for players outside of the US.

1. Download and install [BlueStacks](https://support.bluestacks.com/hc/en-us/categories/4407981230349-BlueStacks-X) to your PC.
2. Open 'BlueStacks Multi-Instance Manager'
3. In the 'Multi Instance Manager', press the blue '+Instance' button (Shown below).

    <img src="imgs/instanceButton.PNG" alt="Alt Text" width="100" height="42">

4. If a pop-up appears asking if you want to create a Fresh Instance or Clone Instance, click Fresh Instance.
5. Choose Android version 'Nougat 32-bit.' This ensures that you are on the correct version of Android for the game.
6. **(Optional)** Change CPU Cores to Low, Memory Allocation to Basic, and Performance Mode to Low to conserve resources.
7. Start the BlueStacks instance you just created.
8. In a **PC browser**, download the [Amazon Appstore App](<https://www.amazon.com/gp/mas/get/amazonapp>) for Android.
9. Click the 'Install APK' button on the right side of your BlueStacks Instance (shown below).

    <img src="imgs/installAPK.PNG" alt="Alt Text" width="340" height="200">

10. Navigate to where you downloaded the Amazon Appstore App and click it to install it to BlueStacks.
11. Once it is installed, open the Amazon Appstore App and Login. Then, search "Grub Guardian" in the app's searchbar and install it.
12. Grub Guardian should now be installed on your BlueStacks instance and be ready to play.

# Known bugs/issues
- None currently

# Installed Libraries
- [Pyautogui](https://pyautogui.readthedocs.io/en/latest/)
- [OpenCV](https://pypi.org/project/opencv-python/)
- [NumPy](https://numpy.org)
- [Time](https://docs.python.org/3/library/time.html)

# Other Resources
- [Python](https://www.python.org/downloads/)
- [Guide for Installing Grub Guardian on Bluestacks](<https://www.reddit.com/r/Wizard101/comments/12tj3s1/a_semicomprehensive_guide_to_playing_grub/>) (by AmazingBadgamer)
- [Amazon Appstore App](<https://www.amazon.com/gp/mas/get/amazonapp>)
- [Tanglewood Way Free EE Strategy](<https://www.youtube.com/watch?v=iWpcQNuVs2g>) (by me)