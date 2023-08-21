# tour-of-go
tour of go の最初から以下までやりました。
わからなかったところをメモ

## https://go-tour-jp.appspot.com/basics/2
- グループ化？
  - ()で囲うと、いちいちimport OO と書くのと同じ意味で、よりスッキリするのでこう書こうということ。

## https://go-tour-jp.appspot.com/basics/5
- なに？
  - 個別に書かなくても、同じ型ならまとめて書けるよ
  - 文章が長いと、人間って読みつらくなるので、なるべく短く書こう。シンプルイズベスト。

## https://go-tour-jp.appspot.com/basics/7
- GOってなに？
  - GO言語のこと。golangとも言ったりする。
- ステートメントってなに？
  - たいてい、他のワードと組み合わせて書いてあるので、ほかのワードそのものを指す。
  - 例えば return は、原文の英語だと return だけだと意味が通じなくなるのでステートメントってつける。

## https://go-tour-jp.appspot.com/basics/9
- varってなに？
  - これは変数ですよという宣言。合図。

## https://go-tour-jp.appspot.com/basics/10
- :＝ってなに？
  - :=を使うとvarとかつかわずにショートカットができる

## https://go-tour-jp.appspot.com/basics/12
- ゼロ価ってなに？
  - その型の持つ標準の値。

## https://go-tour-jp.appspot.com/flowcontrol/1
- c言語ってなに？
  - 以下の引用部分だね。これらはGo以外のプログラミング言語のことです。
```text
Note: 他の言語、C言語 や Java、JavaScriptの for ループとは異なり、 for ステートメントの3つの部分を括る括弧 ( ) はありません。なお、中括弧 { } は常に必要です。
```

## https://go-tour-jp.appspot.com/flowcontrol/6
- スコープってなに？
  - 直訳的に説明すると `見える部分` かな。  
  この問題の場合は、 _ifステートメントのスコープ_ なので、「ifの中でだけ有効です。」と読み替えるといいよ。

## https://go-tour-jp.appspot.com/flowcontrol/8              
- z² ってなに？
  - 乗数のことだよ。zをxに置き換えると馴染みがありそうかな？  
  少し難しい内容なので読み飛ばしていいよ。

## https://go-tour-jp.appspot.com/flowcontrol/9
- シーケンスってなに？
  - 英語で書くと _sequence_ と書くよ。辞典などで意味を調べてみよう。
