# Arch Linux Fresh Install Packages

## [ Overview ]
These are my notes, and I plan to write an installation script around my needs. As a Python programmer trying to utilize Linux in the most efficient way possible. with a slight hint of ricing. 


## [ Base Install ]
```bash
sudo pacman -S --noconfirm base base-devel linux-firmware sudo wget curl tmux git zsh wayland gzip htop neovim networkmanager openssh iproute2 net-tools bind-tools inetutils python ntp nodejs npm unzip
```

## [ Base Commands ]
```bash
sudo systemctl enable sshd
sudo systemctl start sshd
sudo systemctl enable ntpd
sudo systemctl start ntpd
sudo timedatectl set-ntp true
```

## [ Advanced Features ]
Zsh + Powerlevel10k
```bash
yay -S --noconfirm zsh-theme-powerlevel10k-git
echo 'source /usr/share/zsh-theme-powerlevel10k/powerlevel10k.zsh-theme' >> ~/.zshrc
```
## [ Neovim + Themes + Plugins ]
### (Make it Like VS Code)
https://github.com/bcampolo/nvim-starter-kit/tree/python#neovim-starter-kit-for-python-  
Video: https://youtu.be/jWZ_JeLgDxU)

## [ Window Manager ]
Hyprland
### [ Window Applications ]
```bash
Browsers
Brave
Chromium
Firefox
Terminals
Alacritty
Kitty (Best)
Sound
```
```bash
sudo pacman -S pipewire pipewire-alsa pipewire-pulse pipewire-jack
sudo pacman -S pavucontrol
```

## Audio Visualizer
```bash
Cava
```
CLI Visualizer: cli-visualizer]
```bash
yaourt -S cli-visualizer
```

## [ Gaming ]
```bash
sudo pacman -S mesa
```
### For NVIDIA users:
```bash
sudo pacman -S nvidia nvidia-utils
```
### Install Wine
```bash
sudo pacman -S wine
```
### Steam / Games
```bash
sudo pacman -S steam
```
### Miscellaneous
GameMode: A valuable tool for gamers on Linux, helping to maximize performance by temporarily adjusting system settings during gameplay. It can lead to a smoother and more enjoyable gaming experience, especially for resource-intensive titles.
```bash
sudo pacman -S gamemode
```

## [ Chat Clients ]
```bash
Discord
Telegram Desktop
HexChat
```

