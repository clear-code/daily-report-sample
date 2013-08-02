daily-report-sample
===================

Sample repository of daily reports for [commit comment service](http://www.clear-code.com/services/commit-comment.html).

See also https://github.com/clear-code/commit-comment-tools .

## Usage

1. Fork and clone this repository.
2. Commit your daily reports.

## How to write daily report (In Japanese)

### 1. 自分の名前.txt というファイル名のテキストファイルを用意する。

他の人と被らないようにする。

### 2. 以下のフォーマットで日付、読んだ割合、コミットを読んで印象に残ったことについて記載する

anonymous.txt:

````
    2013-1-31:90%:
      あの人があんなコードを書いてしまうなんて!!
    2013-1-30:40%:特になし
    2013-1-29:100%:
      自分のお試しコードで GError のメモリリークを指摘された
      C++ でサブクラスでオーバーライドするメソッドにも virtual を付ける
      C++11 だと final キーワードが入ってる。contextual keyword
````

* 一行で書くときは 2013-1-30 の行のようにコロン(":")で区切って書く。
* コメントを別の行に書くときはスペースでインデントしてから書く。
* コメントは 2013-1-29 のケースのように複数行書くこともできる。
* 日付は 2013-01-01 のようにゼロパディングしてもよい。
* フォーマットを決めているのは後でツールを使用して集計するため。

記録は上に新しい日付のものを追加する。
下に追加しても集計時には問題ないため、下に追加する方がやりやすい場合は下に追加してもよい。
どちらでもやりやすさが変わらなければ上に追加すること。

### 3. 適切なコミットログを書いてコミットして push する。

コミットメールを流す設定が既にできている場合は push するとコミットメールが流れて、みんながその記録を読むことができる。


