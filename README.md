# dmusick
This little script will let you play music using just dmenu, youtube-dl and mpv


# Requirements 
  - dmenu
  - youtube-dl 
  - mpv 
  
 # Installation 
 
  Put dmusick into your /usr/bin directory (or whatever directory intended for binaries)
    -```$ git clone https://github.com/veryown/dmusick && cd dmusick``` 
    -```$ sudo cp dmusick /usr/bin```
  
  # Usage 
    from terminal
      ```$ dmusick```
    or as I prefer invoke it from your wm's config 
     Example with dwm (savedconfig or config.h or whatever): 
     ```static const char *dmusisk[] = { "dmenu_musick", "-m", dmenumon, "-fn", dmenumon, "-nb", col_gray1, "-nf", col_gray2, "-sb", col_gray1, "-sf", col_gray2, "-p", "♬ ", NULL };```
     and invoke it with a keybinding of your choice
      ```{ MODKEY,                       XK_c,      spawn,          {.v = dmusick   } },```
