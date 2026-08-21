# Markdown で書いたページの例 (sub1.md)

## Section 1: コードブロックの書き方
### 例) 実行ファイルを格納したフォルダの調べ方
```bat
for /F %i in ('where notepad.exe') do @echo 絶対path=%i & @echo フォルダ=%~di%~pi & echo.
```

## Section 2: LINKの使い方
### [トップページへもどる](./index)
* リンクは単に./index と拡張子を付けないで書けばよい．
* なお，**いま見ているページ** は markdownで書かれた sub1.md から生成された sub1.html である．
もとになった markdown へのリンクは ./sub.md であり，実際，それぞれのリンクは
[markdownの原稿](/webSkelton/sub1.md)，[生成されたhtml](./sub1.html)である．
