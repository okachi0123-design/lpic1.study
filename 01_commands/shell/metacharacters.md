# Metacharacter
## MetacharacterTypes
- ＊ 任意の文字列になる　  *.txt なら a.txt bd.txt xja.txtなど
- ? 任意の１文字になる　?.txt なら　a.txt b.txt ...
- [] カッコ内の列挙された文字のいずれか１つにマッチする　data.1~data.99まで１づつあるとき、　data.[24] で　data.2 data.4　data.24はマッチしない
- {} カッコ内の文字列で全パターン生成　data.{1,23,4} でdata.1 data.23 data.4
## Points
- メタキャラクタを文字列として扱うなら\*みたいにする

  
