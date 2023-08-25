# Parrot PwnBox Terminal Configuration

![Parrot PwnBox](https://i.imgur.com/JTJogTF.png)

Welcome to the Parrot PwnBox Terminal Configuration repository! This repository all the configuration files and terminal preferences to that you usually see on the hack the box pwnbox machines. I exported the preferences from one of the virtual machines I have spawned. I am putting it here on github mainly for myslef, but for anyone else who wants to use it.

## Table of Contents
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Customization](#customization)

## Getting Started
1. **Clone the Repository:** Start by cloning this repository to your local machine:

   ```bash
   git clone https://github.com/bojtalepenye/parrot-pwnbox-terminal-config
   ```

2. **Navigate to the Directory:** Move into the cloned directory:

   ```bash
   cd parrot-pwnbox-terminal-config
   ```

## Configuration
3. **Copy Configuration Files:** Depending on your preference, copy the provided configuration files to your home directory:

   ```bash
   cp .zshrc ~/.zshrc
   cp .bashrc ~/.bashrc
   cp .profile ~/.profile
   ```
   Make sure that you back up your current config files.
   
5. **Terminal Preferences:** Follow the instructions to apply the provided terminal preferences (colors, etc.).
## Terminal Preferences
   ```bash
   dconf load /org/mate/terminal/ < htbpwnbox-terminal-profile
   ```
Restart your terminal and then check the profiles
Now you have that Parrot PwnBox terminal look.

## Customization
Feel free to customize any of the provided configuration files and terminal preferences to match your personal preferences.
Happy hacking!
