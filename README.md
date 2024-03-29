

# Topbar
`eww`
[x] Move between workspaces.
[ ] make sure shell completions are loaded. `eww shell-completions`
[x] Power / Battery tracking.
[ ] Network connectivity status.
[ ] Network connect/disconnect.
[ ] Network Wifi Selection.
[ ] Power Menu
    - [ ] Shutdown
    - [ ] Sleep.
    - [ ] Lock.
    - [ ] Logout.
[ ] Sound.
[ ] Bluetooth.
[ ] Settings.
[ ] Spotify.
[ ] Notifications.
[ ] Search.
[ ] Window explorer: https://github.com/DreamMaoMao/hycov
[ ] Open applications.

# Bindings

Mirror nvim panels.
[ ] MOD + h|j|k|l -> Navigate the tiles (currently arrow keys)
[ ] MOD + shift + h|j|k|l -> Move the tiles around.



# Configurations

[ ] hyprland
[ ] hyprlock
[ ] hypridle
[ ] alacritty
[ ] neovim
[ ] eww
[ ] swww
     - [ ] Seasonal Backgrounds.
[ ] oh-my-posh

[ ] zshrc
[ ] tmux
[ ] fonts
[ ] image terminal support


# Install

[ ] zsh openssh sudo 

```
pacman -S base-devel
```


## Networking Install

```
pacman -S network-manager iwd dnsutil
```

## Extras

```
pacman -S yazi zoxide tree
# maybe not the one below, might be a dead project.
sudo pacman -Sy python-ueberzug
```

exa?

# Uncategorised

[ ] show wallpapers given time of day. (show morning wall paper really early)


---

# Hyprland Workspaces


File `/tmp/hyprland_workspace_position` is used to track the current workspace. Programs like eww depend on this for event driven updating.


# Design insperation

https://dribbble.com/shots/21534554-Cyberpunk-2077-PPT-Template


# Set up serial devices

References: [Arch Wiki: Arduino](https://wiki.archlinux.org/title/Arduino) [Arch Wiki: Working with Serial](https://wiki.archlinux.org/title/Working_with_the_serial_console#Making_Connections)

```
echo 'SUBSYSTEMS=="usb-serial", TAG+="uaccess"' | sudo tee -a /etc/udev/rules.d/01-ttyusb.rules
```


# Developer environment

Enable git to handle large files:

```
git lfs install
```

# Remapping Keys

