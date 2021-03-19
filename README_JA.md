# Mplayer-Radio-Compact
mplayerでインターネットラジオを再生するときに表示を見やすくするツール

## Requirement  
* Unix/Linux OS
* gcc (C言語のコンパイル用)
* mplayer (aptといったパッケージ管理システムでインストールできます)

## Usage 
src.cをコンパイルして次のように実行してください。
``` bash
mplayer "Internet radio stream URL" | "the compiled binary"
```

### Note
インターネットラジオが現在の曲情報の表示に対応していない場合、情報は表示されません。

### Screenshot 
![sample](https://user-images.githubusercontent.com/80367947/111733028-45b95300-88ba-11eb-9671-096fc6693a6c.png)
