# GitHub
[https://github.com/lambda0\koumei/lambda0koumei.github.io](https://github.com/lambda0koumei/lambda0koumei.github.io)

[https://github.com/lambda0koumei/.emacs.d](https://github.com/lambda0koumei/.emacs.d)

# 開発環境
- macbook-air M1
- phpstorm
- emacs
- karabiner-elements
- alfred

# markdownメモ
\# 見出し
\[リンク名\]\(アドレス\)


# emacsメモ
- ブックマーク登録
c-x r m
- ブックマークリストを表示
c-x r l
- 任意のブックマークに移動
c-x r b
- フレームサイズの取得
 - (frame-width)
 - (frame-height)
f1 b
- キーバインド一覧を表示

- バッファを開き直す c-x c-v

## Emacs Lisp
- アトム:number, symbol, string
- リスト:アトムを()で囲んだもの

### とりあえず覚えること
- セミコロンで行コメント
- 一時変数宣言は基本的にlet*
- グローバル変数宣言はsetq。一時変数の上書きも可能
- formatで文字列をフォーマットできる
- messageでメッセージを表示できる
- kill-newで文字列をコピーできる
- insertで文字列をバッファに入力できる
- buffer-file-nameでファイル名を取得できる
- default-directoryで現在のフォルダ名を取得できる
- c-x c-eで文字列を評価できる(例えば文字列"buffer-file-name"を選択した状態で実行するとファイル名が表示される)
- locate-dominating-fileでファイルが存在するディレクトリを指定したディレクトリから上方向に検索する。
- read-file-nameでファイルを読み込むことができる
- defunで関数定義
- interactive




### 評価
- symbolを評価したとき、格納されている値を返す。
- number, stringを評価したとき、それをそのまま返す。
- 1 -> 1
- "hi" -> "hi"
- リストを評価したとき、関数として実行する。
- (+ 1 2) -> 3
- (message "hi") -> hiを返し、かつ表示する。
- (* hoge fuga) -> symbolは全て評価される。
- (1 2 3) -> symbolがないため、エラーが発生する。
- '(1 2 3) -> (1 2 3) -> 先頭に ' = quoteをつけると評価を抑制する。
- (quote (1 2 3)) -> (1 2 3) -> 同上
- nil以外は全て真である。

### 関数
- setq
- setq(a 1) -> aに1を代入する。
- setf
- defun
- cons コンスセルを作る。リストはコンスセルを連ねたもの。
- (1 2 3) = (1 . (2 . (3 . nil)))
- car
- cdr
- assoc
- assq
- rassq
- add-to-list
- append
- macroexpand
- pop
- push
- setf(cdr(assoc ...


# gitメモ
- git add.
- git commit -m "add"
- git push -u origin master(-u = --set-upstream)

# GitHub
[https://github.com/lambda0\koumei/lambda0koumei.github.io](https://github.com/lambda0koumei/lambda0koumei.github.io)

[https://github.com/lambda0koumei/.emacs.d](https://github.com/lambda0koumei/.emacs.d)

# 開発環境
- macbook-air M1
- phpstorm
- emacs
- karabiner-elements
- alfred

# markdownメモ
\# 見出し
\[リンク名\]\(アドレス\)


# emacsメモ
- ブックマーク登録
c-x r m
- ブックマークリストを表示
c-x r l
- 任意のブックマークに移動
c-x r b
- フレームサイズの取得
 - (frame-width)
 - (frame-height)
f1 b
- キーバインド一覧を表示

- バッファを開き直す c-x c-v

## Emacs Lisp
- アトム:number, symbol, string
- リスト:アトムを()で囲んだもの

### とりあえず覚えること
- セミコロンで行コメント
- 一時変数宣言は基本的にlet*
- グローバル変数宣言はsetq。一時変数の上書きも可能
- formatで文字列をフォーマットできる
- messageでメッセージを表示できる
- kill-newで文字列をコピーできる
- insertで文字列をバッファに入力できる
- buffer-file-nameでファイル名を取得できる
- default-directoryで現在のフォルダ名を取得できる
- c-x c-eで文字列を評価できる(例えば文字列"buffer-file-name"を選択した状態で実行するとファイル名が表示される)
- locate-dominating-fileでファイルが存在するディレクトリを指定したディレクトリから上方向に検索する。
- read-file-nameでファイルを読み込むことができる
- defunで関数定義
- interactive




### 評価
- symbolを評価したとき、格納されている値を返す。
- number, stringを評価したとき、それをそのまま返す。
- 1 -> 1
- "hi" -> "hi"
- リストを評価したとき、関数として実行する。
- (+ 1 2) -> 3
- (message "hi") -> hiを返し、かつ表示する。
- (* hoge fuga) -> symbolは全て評価される。
- (1 2 3) -> symbolがないため、エラーが発生する。
- '(1 2 3) -> (1 2 3) -> 先頭に ' = quoteをつけると評価を抑制する。
- (quote (1 2 3)) -> (1 2 3) -> 同上
- nil以外は全て真である。

### 関数
- setq
- setq(a 1) -> aに1を代入する。
- setf
- defun
- cons コンスセルを作る。リストはコンスセルを連ねたもの。
- (1 2 3) = (1 . (2 . (3 . nil)))
- car
- cdr
- assoc
- assq
- rassq
- add-to-list
- append
- macroexpand
- pop
- push
- setf(cdr(assoc ...


# gitメモ
- git add.
- git commit -m "add"
- git push -u origin master(-u = --set-upstream)

