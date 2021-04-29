# passmenu-wofi-wayland
passmenu + wofi, inelegantly hacked together to work with wl-copy &amp; sway

It's [zx2c4's](https://www.zx2c4.com/) wonderful passmenu script, modified to work with rofi & sway.

Essentially, I took out the `xdotool` part, and use wofi instead of dmenu.  It then clears the clipboard after 45 seconds.

Add something like this to your sway config:

```
set $passmenu /home/alex/git/dotfiles/scripts/passmenu-rofi-wayland
bindsym $mod+Shift+P exec $passmenu
```

I'm sure this can be improved, but this has been working for me great so far.

### Please!
Feel free to message me, open issues, make a pull request, or suggest any changes!
