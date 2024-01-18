# My-Xfce4-BSPWM-Config

## Overview
This repository hosts configuration files for a desktop environment setup using Xfce4 as the Desktop Manager and BSPWM as the Window Manager. It's tailored for users who appreciate the simplicity of BSPWM along with the functionality of Xfce4.


![Configuration Preview](https://github.com/Jayasurya-Marasani/My-Xfce4-BSPWM-Config/blob/main/my%20first%20rice.png)


## Getting Started

### Prerequisites
- A working Linux installation.
- Xfce4 pre-installed. (This was tested on an Arcolinux installation with Xfce4.)
- `paru` or another AUR helper for installing packages from the Arch User Repository (AUR).
-  **Fonts Used:**
      1. [Inter Font](https://fonts.google.com/specimen/Inter)
      2. [JetBrains Mono Font](https://fonts.google.com/specimen/JetBrains+Mono?query=JetBrain)
- [Gogh Terminal Themes](https://gogh-co.github.io/Gogh/)
      - Used Tokyo Night theme


### Installation

1. **Update Your System:**
Ensure your system is up-to-date:
```bash
sudo pacman -Syu
```
2. **Install BSPWM and SXHKD and other packages:**
Use paru or your preferred AUR helper:
```bash
paru -S bspwm sxhkd ttf-inter ttf-jetbrains-mono a-candy-beauty-icon-theme-git xcursor-breeze
``` 
3. **Clone the Repository:**
Clone this repository to your local machine:
```
https://github.com/Jayasurya-Marasani/My-Xfce4-BSPWM-Config.git
```
4. **Configuration Setup:**
Create the necessary directories if they don't exist:
```
mkdir -p ~/.config/bspwm
mkdir -p ~/.config/sxhkd
```
Copy the bspwmrc and sxhkd configuration files to their respective directories:
```
cp My-Xfce4-BSPWM-Config/bspwmrc ~/.config/bspwm/
cp My-Xfce4-BSPWM-Config/sxhkdrc ~/.config/sxhkd/
```

5. **Make bspwmrc Executable:**
   ```
   chmod +x ~/.config/bspwm/bspwmrc
   ```

## Video Walkthrough

For a detailed video walkthrough of the installation and setup process, you can follow this YouTube link:

[![Video Walkthrough](https://img.youtube.com/vi/HxLW_dEx574/0.jpg)](https://www.youtube.com/watch?v=HxLW_dEx574)


## Contributing
Contributions to improve the configuration or add new functionalities are welcome. Please open an issue or submit a pull request with your proposed changes.

## License

This project is open-source and available under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
