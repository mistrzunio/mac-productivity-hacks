# mac zoom hacks

1. Create alias to join meeting from terminal shell (replace `ZOOM_ORG_DOMAIN` and `ZOOM_MEETING_ID` with your values):

` echo $'alias startzoom=\'open "zoommtg://ZOOM_ORG_DOMAIN.zoom.us/join?action=join&confno=ZOOM_MEETING_ID"\'' >> ~/.zshrc`
