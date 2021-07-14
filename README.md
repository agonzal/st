# st (Simple Terminal)

```
       _______ ___ ___ ___ _______ ___     _______           
       |   _   |   |   Y   |   _   |   |   |   _   |          
       |   1___|.  |.      |.  1   |.  |   |.  1___|          
       |____   |.  |. \_/  |.  ____|.  |___|.  __)_           
       |:  1   |:  |:  |   |:  |   |:  1   |:  1   |          
       |::.. . |::.|::.|:. |::.|   |::.. . |::.. . |          
       `-------`---`--- ---`---'   `-------`-------'          
  _______ _______ _______ ___ ___ ___ ______  _______ ___     
 |       |   _   |   _   |   Y   |   |   _  \|   _   |   |    
 |.|   | |.  1___|.  l   |.      |.  |.  |   |.  1   |.  |    
 `-|.  |-|.  __)_|.  _   |. \_/  |.  |.  |   |.  _   |.  |___ 
   |:  | |:  1   |:  |   |:  |   |:  |:  |   |:  |   |:  1   |
   |::.| |::.. . |::.|:. |::.|:. |::.|::.|   |::.|:. |::.. . |
   `---' `-------`--- ---`--- ---`---`--- ---`--- ---`-------'
              :::::a suckless production:::::
```

This is my custom build of suckless st (simple terminal) which includes:::

## Patches:

- alpha 
- Ligatures
- sixel 
- scrollback
- Clipboard
- Alpha(Transparency)
- Boxdraw
- w3m
- font2
- right click paste
- st desktop entry
- newterm
- anysize
- anygeometry
- xresources
- sync patch
- live reload 
and more...
  <br>

## How to apply Xresources and live-reload ?

```shell
alias load="kill -USR1 $(pidof st)"
alias  use="xrdb merge"

$ use ~/.Xresources && load

```

## Install <br>

`cd st (this repo) `<br>
`sudo make install `<br>

## Default Keybindings<br>

<pre>
ctrl + shift + c        Copy  <br>
ctrl + shift + v        Paste <br>
alt  + comma            Zoom in <br>
alt  + .                Zoom out <br>
alt  + g                Reset Zoom<br>
alt  + s                Increase Transparency<br>
alt  + a                Decrease Transparency<br>
alt  + m                Reset Transparency<br>
copy anything and right click on the terminal ( will paste the copied thing ) 
mod + alt + enter    open a new terminal with same cwd ( current working directory )
alt + k                 scroll down 
alt + j                 scroll up
</pre>

you can change all of these in config.h... That's it... cause a simple terminal deserves a 
simple readme.md
<br>
