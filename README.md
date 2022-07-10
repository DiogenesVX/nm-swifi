# nm-swifi
The simple way to manage your network with GUI.
This is a network utility which provides a simple GUI for basic network operations, it is basically nmcli with yad.
I created it for myself to use with sway on Debian. If someone finds it useful for his/her situation, I'd be happy :).
It was tested on Debian Stable, it might as well run on your version/distribution.

# What you can do with nm-swifi
   1. Get the list of all available Wi-Fi networks (SSIDs).
   2. Connect/Disconnect to any Wi-Fi network of your choice (unless you know the password :)).
   3. Enable/Disable Wi-Fi.
   4. Edit connections (with nm-connection-editor).
   5. No root required for anything.

# Screenshot
![Alt text](https://github.com/DiogenesVX/nm-swifi/blob/main/nm-swifi.png)

# Usage
  just launch the script the way you like (either with a key combination, or with a .desktop launcher or simply ./nm-swifi)
  
 Make sure you have the following packages installed:
 
      sed
      yad
      grep
      gawk
      coreutils
      libnotify-bin
      network-manager
      network-manager-gnome (optional, provides nm-connection-editor)

   On Debian XFCE you just have to install yad:
   
       sudo apt install yad
