# mac zsh shell rebinding cursor keys:

Add following bindings to your `~/.zshrc`:

```
bindkey "\e[A" history-search-backward
bindkey "\e[B" history-search-forward
```

now, when you start type a command, up and down arrow kesys will search in search matching commands in history, try:
```
$ cd 
```
then cycle through history using up and down arrow kesys

# start zoom call from mac terminal: 

1. Create alias to join meeting from terminal shell (replace `ZOOM_ORG_DOMAIN` and `ZOOM_MEETING_ID` with your values):

` echo $'alias startzoom=\'open "zoommtg://ZOOM_ORG_DOMAIN.zoom.us/join?action=join&confno=ZOOM_MEETING_ID"\'' >> ~/.zshrc`
