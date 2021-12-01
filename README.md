# my-custom-xmonad
My custom xmonad scripts, free for anyone to use!!

# Dependencies :

  This Config uses tint2 panel so keep that handy
  
  
  
  I used alacritty as my default terminal emulator so have alacrity on you
  
  
  Keep nitrogen as well for setting the wallpaper etc
  
  
  if you are on arch/gentoo or something of that sort you probably need to install firefox
  
  
  i aslo have a shortcut built in for brave browser although that can be removed through simply editting the config
  
  Dmenu
  
  Xmonad
  
  some terminal text editor (vim/nano/whatever ye got)
  
  some file manager (nemo/ranger/dolphin/whatever ye fancy)
  
  htop cuz why not
  
  
## Note: if the first thing you see is a black screen do not worry! The panel will take a few seconds to load and at first boot there is no wallpaper




# Installation :

really not much.... just clone the repo ( git clone https://github.com/surya8thesun/my-custom-xmonad ), move the xmonad.hs to .xmonad folder  (i hope you have installed xmonad by now) taking care that you have already made the folder otherwise you will essentialy just end up renaming the file, move the tint2rc to the .config/tint2 folder, again, make sure tint2 is installed and the folder is already created, then if you have a login manager you are set! if you don't, then add 
"exec xmonad" to your .xinitrc file then startx, and you should boot into the config

# keyboard shortcuts :
    
    Win + Shift + Enter ----------> alacritty
    
    Win + P ------> dmenu

    Win + Q -------> refreshes the windows manager

    Win + Shift + Q ----------> logs out of xmonad


    Win-Shift-c   ------------> Close/kill the focused window

    Win-Space     ------------> Rotate through the available layout algorithms

    Win-Shift-Spac------------> Reset the layouts on the current workSpace to default

    Win-n         ------------> Resize/refresh viewed windows to the correct size
    
    Win-Tab       ------------>ove focus to the next window

    Win-Shift-Tab ------------>ove focus to the previous window

    Win-j         ------------>ove focus to the next window

    Win-k         ------------>ove focus to the previous window

    Win-m         ------------>ove focus to the master window
    
    Win-Return  -----> Swap the focused window and the master window

    Win-Shift-j -----> Swap the focused window with the next window

    Win-Shift-k -----> Swap the focused window with the previous window
    
    Win-h -------> Shrink the master area

    Win-l -------> Expand the master area

    Win-t -------> Push window back into tiling; unfloat and re-tile it,

    Win-comma ----> Increment the number of windows in the master area

    Win-period -------> Deincrement the number of windows in the master area





everything else is in the config, just scroll to the very bottom (the xmonad.hs config)







