# hud
hud opens a chrome window with a list of urls.
You write the urls in a file.
You can have many of these files.

Example:
```
$ echo "http://facebook.com" >> $HUD_ROOT/bored
$ echo "http://reddit.com" >> $HUD_ROOT/bored
$ echo "http://fuckyeahdementia.tumblr.com" >> $HUD_ROOT/bored
$ hud bored
```

# Install
Place the hud script somewhere on your path.

hud will try to make $HUD_ROOT, which defaults to /var/lib/hud, when invoked.
You may need to run it with sudo the first time.

Source .hud_complete in your shell profile to get tab completion.
