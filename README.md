# xap-client  [LINUX]
For **v3.0.52.26 (Final Fantasy Update)**
By **Gerosity**
All credits to original owners
**Triggerbot not working**

# Changelog:

    Updated Offsets - UC Forum
    Team Gamemode (Toggle, Load Config after changing) - https://github.com/Pesci-Apu/Apu
    Draw Box - https://www.unknowncheats.me/forum/3956658-post524.html
    Draw Skeleton- https://www.unknowncheats.me/forum/3956658-post524.html
    Draw Names - https://github.com/Pesci-Apu/Apu
    Show Near - https://www.unknowncheats.me/forum/3956658-post524.html
    ESP Max Distance - https://www.unknowncheats.me/forum/3956658-post524.html
    Load Config

xap-client UC Link: https://www.unknowncheats.me/forum/apex-legends/606842-xap-client-aimbot-esp-triggerbot.html

# Original README.md
So yeah, this thing was made by me, I was very bored so I took T_Tape's Menu and grinder's features and put them together to create this monstrosity. The code is still very messy so if you want to improve it, go ahead.
I'll will be very grateful if you do so.

**Disclaimer: This code is for educational purposes only .**

# Credits
arturzxc: for the features (ESP, Triggerbot, Aimbot) and X11Display's XTestFakeRelativeMotionEvent

Koelion (Braziliana): menu, aimbot calculations

unguhelvu : Seer-Styled ESP

unknowncheats: basic knowledge and offsets


# Previews

![enter image description here](https://i.imgur.com/7mVlPrr.png)

# Installation
**1.Install dependencies**

    sudo apt-get install -y libudev-dev
    sudo apt install cmake xorg-dev libglu1-mesa-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev
    sudo apt-get install build-essential
    sudo apt-get install libx11-dev
    sudo apt-get install libxtst-dev

**2.Build glfw**

    git clone https://github.com/glfw/glfw.git
    cd glfw
    mkdir build
    cd build
    cmake ..
    make
    sudo make install

**3. Clone repo**

    git clone https://github.com/Gerosity/xap-client-v3.0.52.26.git
    cd xap-client-v3.0.52.26

**4. Build and Run**

    mkdir build
    cd build
    cmake ..
    make
    sudo ./xapclient
    
**5. Press Insert to toggle the Menu (You can only interact with the Menu and the game when the menu is active).**
