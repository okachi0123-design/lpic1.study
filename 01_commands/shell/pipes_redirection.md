# Overview 
- コマンドの入出力先を表す
## | 
### Overview 
- コマンドの出力を次のコマンドの入力に渡す
### Example
- ls | sort でlsの結果を並び替え 
## Tee
### Overview
- コマンドの出力をファイルに書き込むと共に次の入力に渡す
### Option
- -a 置き換えずに追記
### Example
- ls | tee ls.log | sort でlsの結果をls.logに保存しつつ並び替え 
## Redirect
### Types
- '> 'コマンドの出力をファイルに保存
- '>>'　コマンドの出力をファイルに追記
- < 後に続くファイルの内容をコマンドの標準入力に
- << 終了文字　終了文字列が出るまで入力を続ける
- 2> エラー出力を書き込む
- 2>> エラー出力を追記する
### Combination
- (commands) > (file) 2>&1 コマンドの出力とエラーをどっちもfileに書き込み　&1で標準出力１と同じところという意味
- (commands) >> (file) 2>&1 上の追記Ver.
### Points 
- (commands) 2> /dev/null でエラーを消す
