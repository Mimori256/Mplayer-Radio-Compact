# Mplayer-Radio-Compact
A tool for Unix/Linux that makes Internet radio song information by mplayer easier to read.

## Requirement  
* Unix/Linux OS
* gcc (C compiler)
* mplayer (You can install it from package manage system such as apt)

### Usage 
Compile src.c in this repository. And execute
``` bash
mplayer "Internet radio stream URL" | "the compiled binary"
```

#### Note
It can work if the Internet radio stream doesn't show the information of the song playing currently.
