--> Clear DNS cache
sudo killall -HUP mDNSResponder


--> capture a portion of the screen
shift + cmd + 4

--> capture a portion of the screen and save to clipboard
shift + control + cmd + 4

--> disable Cmd+Shift+L = `Search in google` feature
it takes clipboard and send it to safari
https://apple.stackexchange.com/questions/180038/strange-behavior-within-ms-word-using-command-shift-l-launches-safari-sometimes

--> List open ports
lsof -PiTCP -sTCP:LISTEN

--> "cannot be opened because the developer cannot be verified" problem
xattr -r -d com.apple.quarantine /path/to/folder
xattr -d com.apple.quarantine /path/to/app