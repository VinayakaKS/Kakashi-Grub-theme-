# Kakashi-Grub-theme-
A minimalistic grub theme with Kakashi sensei as background  

# Usage
Method 1
1. Clone the repo ($ git clone {repo link})
2. Run the install.sh file using root previlages ($ sudo ./install.sh)

Method 2
1. Clone the repo ($ git clone {repo link})
2. Copy the theme to /boot/grub/themes/
3. Edit /etc/default/grub file. Find the line starting with "#GRUB_THEME" or "SET_THEME" and change it to "GRUB_THEME=/boot/grub/themes/Kakashi/theme.txt" or "SET_THEME=/boot/grub/themes/Kakashi/theme.txt""
4. Run sudo update-grub
