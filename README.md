# Streamsniperty's Picom Configuration File

This repository holds my configuration file for Picom. I wanted to explain the forks of Picom that I use.

### ibhagwan's Picom

I use ibhagwan's Picom fork for window curvature. In addition, ibhagwan's fork can be used for blurring windows. 
If you want rounded windows and kawase blur, use ibhagwan's Picom.

#### How to install

In order to install ibhagwan's Picom, go to his GitHub page: `https://github.com/ibhagwan/picom`. All the instructions should be on the README.

### jonaburg's Picom

I use jonaburg's Picom fork for window animations. This is the current Picom fork I am using for my 2021 awesomeWM project.

#### How To Install

In order to install jonaburg's Picom, go to his GitHub page: `https://github.com/jonaburg/picom`.

However, in his README, some dependencies are missing for Debian/Ubuntu. I included some other necessary dependencies needed to build the project. As a result, if you are using a Debian/Ubuntu distro, copy and paste this line into your terminal first, before compiling and installing the project from his website. 

`sudo apt install libpcre3-dev gcc meson ninja-build libxext-dev libxcb1-dev libxcb-damage0-dev libxcb-xfixes0-dev libxcb-shape0-dev libxcb-render-util0-dev libxcb-render0-dev libxcb-randr0-dev libxcb-composite0-dev libxcb-image0-dev libxcb-present-dev libxcb-xinerama0-dev libxcb-glx0-dev libpixman-1-dev libdbus-1-dev libconfig-dev libgl1-mesa-dev libevdev-dev uthash-dev libev-dev libx11-xcb-dev`
 
