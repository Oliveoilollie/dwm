this is Livs DWM build! 


here is my not so FAQ! ~

here are the keybindings ^^ youll know them when you see them [config.def.h](https://github.com/Oliveoilollie/dwm/blob/main/config.def.h) right now im in the proccess of changing some.~

ok so what did i actually do to dwm.~
   - [alpha](https://dwm.suckless.org/patches/alpha/) adds some transparency to the panel.
   - [vanity-gaps](https://dwm.suckless.org/patches/vanitygaps/) adds some gaps to the windows (i think it adds layouts as well??? we will see).
   - [default-tags](https://dwm.suckless.org/patches/default_tag_apps/) makes a tag have its own shortcut for applications.   
   - [fadeinactive](https://dwm.suckless.org/patches/fadeinactive/) duh does what it says in the name.
   - [rotate-stack](https://dwm.suckless.org/patches/rotatestack/) makes moving windows a bit easier lol.
   - [rotate-tags](https://dwm.suckless.org/patches/rotatetags/) same but with tags.
   - [status-cmd](https://dwm.suckless.org/patches/statuscmd/) makes status bar clickable with scripts and dwm blocks.
   - [swallow](https://dwm.suckless.org/patches/swallow/) runs GUI apps in the ST terminal.

what do i need to run this? (neeeeeeeeeeeeeerd).~
    - xlib
    - xorg
    - [st](https://st.suckless.org/) or [LST](https://github.com/Oliveoilollie/LST) or change the default terminal in the config.def.h

not needed to compile but i recommend anyway!~
    
    - picom (or any standalone compositor for those alpha affects)
    - dwmblocks (i will have my own build uploaded once i am done)
    - xinit (so you can start it and have it launch applications)
    - nitrogen or feh (walpapers)

how do i build it im a noobie.~
    ``` git clone https://github.com/Oliveoilollie/dwm.git
     cd dwm
     sudo make install clean```

tip - delete config.h (not config.def.h) every time you compile so you dont mess stuff up!
![dwmforster](https://github.com/Oliveoilollie/dwm/assets/121829495/695fa086-906d-43c7-9d2e-3c25eec150ba)

![dwm](https://github.com/Oliveoilollie/dwm/assets/121829495/aad997a6-f2b1-4184-a512-6f94af4b7dff)


   
   
