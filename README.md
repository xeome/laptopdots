
![jomo_dotfiles](https://cdn.discordapp.com/attachments/739162076886597715/954111167926767636/unknown.png)

This is my personal repo for my Arch linux configurations.

# Dependencies

| Type                  | Package(s)                |
|-----------------------|---------------------------|
| WM                    | `i3-gaps`                                
| Bar                   | `polybar`                                
| Launcher              | `rofi`                                   
| Compositor            | `picom-git`                              
| Notifications         | `dunst`                                  
| Terminal              | `alacritty`                              
| GTK                   | `Fluent Dark`                            
| QT                    | `Fluent Round Dark`                      
| Icons                 | `papirus-dark`                           
| Cursor                | `adwaita`                                
| File manager          | `pcmanfm-qt`                             
| Screenshot tool       | `flameshot`                              
| Polkit manager        | `lxsession`                              
| Fonts                 | `ttf-iosevka-nerd ttf-jetbrains-mono` [1]
| Wallpaper manager     | `nitrogen`                               
| Editor                | `neovim`<br> `neovide` (neovim client)   

[1] For icons on `polybar` and `alacritty`.  
Raw dependency list `i3-gaps polybar rofi picom-git dunst alacritty flameshot pcmanfm-qt nitrogen neovim lxsession ttf-iosevka-nerd`

# Installation  
After you get the dependencies instructions should apply to any distro (these commands will overwrite your configs).  
```
cd ~/Downloads
git clone https://github.com/xeome/laptopdots.git
git clone https://github.com/sahibjotsaggu/San-Francisco-Pro-Fonts.git
cd ./San-Francisco-Pro-Fonts
mkdir ~/.fonts
cp -r * ~/.fonts
cd ..
cd ./laptopdots
cp -r .config ~/ && cp -r .local ~/
```

# Some shortcuts
| Shortcut               | Action                        |
|------------------------|-------------------------------|
| Super + Return (enter) | Launch terminal (`kitty`)         
| Super + E              | Launch file manager (`pcmanfm-qt`)
| Super + Q              | Launch web browser (`chromium`)   
| Super + Shift + C      | Close focused application         
| Super + Shift + R      | Restart window manager            
| Super + Shift + Q      | Quit window manager               
| Super + R              | Start program launcher (`rofi`)   
| Super + 1-9            | Switch workspaces from 1 to 9     

## Screenshots

![Screenshot1](https://cdn.discordapp.com/attachments/739162076886597715/953326286829408267/rice.png)
