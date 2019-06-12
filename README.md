# WordGuessServer
A word guessing game server made using netcat and sockets in C.

## How to Play

Instructions on how to play the game on your local computer.
#### Set-up server
Clone repository and cd into the repository folder. Run this to create the server:
```
./wordsrv dictionary.txt
```

#### Connect from client
Open a new terminal window and enter:
```
nc -c localhost 59185
```
<br>
The game should be running now. Open up multiple terminal windows to simulate multiple clients.
