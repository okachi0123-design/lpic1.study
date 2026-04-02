# Shell
## Overview 
- コマンドを実行するプログラム
## ShellTypes
- sh Bourneの基本的なコマンド実行プログラム
- bash　Bourne Again shの改良版
- csh　C言語に似ている
- tcsh cshの改良版
- ksh　Korn Bourneの改良版
- zsh　Kshにbashやtcshの性能を追加した高機能ver
## 変数
### Shell変数　
- そのシェル内だけでの変数 
### 環境変数
- 環境の変数　
- 後で追加したShellにも適用される
- exportが必要　
## PATH
- 外部コマンドを見つけ出す
- コマンドを打ち込んだ際にシェルが自動でPATHの順で探してくれる
###PATHの確認方法
- echo $PATH 
###PATHの追加方法
- PATH=$PATH:追加したいDir名　末尾に追加
- PATH=/Dir:$PATH　先頭に追加
###Point
- export で子プロセスにも適用
- $PATH=/mydir にするとPATHが完全に置き換えられるから危険
- 変更したPATHはターミナルを閉じると戻る
