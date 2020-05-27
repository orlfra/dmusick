# dmusick
This little script will let you play music using just dmenu, youtube-dl and mpv


# Requirements 
  - dmenu
  - youtube-dl 
  - mpv 
  
 # Installation 
 
  Put dmusick into your /usr/bin directory (or whatever directory intended for binaries) <br />
    ```$ git clone https://github.com/veryown/dmusick && cd dmusick``` <br />
    ```$ chmod ugo+x dmusick``` <br />
    ```$ sudo cp dmusick /usr/bin```
  
  # Usage 
   from terminal<br />
      ```$ dmusick```<br />
   or as I prefer invoke it from your wm's config <br />
      Example with dwm (savedconfig or config.h or whatever): <br />
     ```static const char *dmusisk[] = { "dmusick", "-m", dmenumon, "-fn", dmenumon, "-nb", col_gray1, "-nf", col_gray2, "-sb", col_gray1, "-sf", col_gray2, "-p", "♬ ", NULL };```<br />
      and invoke it with a keybinding of your choice <br />
      ```{ MODKEY,                       XK_c,      spawn,          {.v = dmusick   } },```<br />
  
  
  # Screenshots: 
  
 ![](https://github.com/veryown/dmusick/blob/master/27May_12-07-05.png)
 ![](https://github.com/veryown/dmusick/blob/master/27May_12-07-23.png)
 ![](https://github.com/veryown/dmusick/blob/master/27May_12-07-37.png)
 ![](https://github.com/veryown/dmusick/blob/master/27May_12-07-54.png)
 
 # Now with history: 
  	
 ![](https://github.com/veryown/dmusick/blob/master/27May_14-02-08.png)

