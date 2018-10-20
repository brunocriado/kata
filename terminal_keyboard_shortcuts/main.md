# Terminal Keyboard Shortcuts - Kata

This is a terminal keyboard shortcuts kata. Practice every single day to do not forget these tricks.
They gonna help you a lot in your day by day on the terminal.

## Before start

- Symbols:
    **^** - Control
    **%** - Alt


### Kata 1

- Command line as example. Copy and paste (but don't run) to your terminal.
    ```
    ps aux | grep ssh | grep -v grep | grep -v sshd | awk {'print $3'} | xargs -r kill -9
    ```

- Back to the begin of the line: **^a**
- Forward to the end of the line: **^e**
- Back 7 character: 7x **^b**
- Go to the end of the line again but now forwarding characteres: 7x Go to the end of the line again but now forwarding
    characteres **^f**
- Back to the last pipe: 4x **%b**
- Forward to the end again using: 4x **%f**
- Delete `-9` not using backspace or delete key: 2x **^h**
- Delete the entire xargs command: 3x **^w**
- Back to awk command: 3x **%b**
- Clear to end of line: **^k**
- Stop this exercise: **^c**
- Clear screen: **^l**


### Kata 2

- Example. Copy and paste (but don't run) to your terminal.
    ```
    ssytemctl list-all --units | fuse gerp
    ```

- Back two characters: 2x **^b**
- Swap cursor with the previous character: **^t**
- Back to the beginning line: **^a**
- Forward two characters: 2x **^f**
- Swap cursor with the previous character: **^t**
- Forward five words: 5x **%f**
- Swap cursor with the previous word: **%t**
- Back three words: 3x **%b**
- Swap cursor with the previous word: **%t**

- Now you should have the correct command: `systemctl list-units --all | grep fuse`

