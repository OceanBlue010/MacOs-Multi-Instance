# Roblox Multi-Instance Launcher for macOS

This script allows you to launch multiple instances of Roblox on macOS, each in its own separate terminal window.
Features ( cause I don't know if it's possible from just doing it in 1 window )

    Multi-Instance Launch: Opens multiple Roblox instances.

Prerequisites

    macOS: This script is specifically designed for macOS.

    Roblox Player: Ensure Roblox is installed in your /Applications folder. The script expects the executable at /Applications/Roblox.app/Contents/MacOS/RobloxPlayer.

    Terminal Access: You will need to run this script from your macOS Terminal application.

How to Use

To run the script directly from GitHub, open your Terminal and execute the following command:

    bash <(curl -s https://raw.githubusercontent.com/OceanBlue010/MacOs-Multi-Instance/refs/heads/main/multi-instance)

Follow the Prompts

The script will guide you through the process:

    "How many Roblox instances do you want to open (1-9)?": Enter a number between 1 and 9 for the desired number of Roblox instances.

    "Do you want to open [X] Roblox instances, each in a new terminal window? (y/n):": Confirm your choice by typing y and pressing Enter. If you type n, the script will exit.

The script will then launch each Roblox instance in a new terminal window, pausing for 10 seconds between each launch.

# Important Reminders

    Do NOT close the terminal windows where Roblox instances are running, or the Roblox instance associated with that terminal will close.

    To use separate accounts for each instance, you will need to manually sign in and sign out within each Roblox instance as needed.


# some other stuff I wanna add to this

- [ ] : Add windows support
- [ ] : Make a windows ui
- [ ] : Make a MacOs ui
- [ ] : Make a website about it

Working on the website right now so hopefully this doesn't take long haha
    
