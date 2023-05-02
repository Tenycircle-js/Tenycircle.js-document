# Tenycircle.js-document
# ダウンロード
## githubから
ダウンロードして
```html
<script src="pass/to/Tenycircle.min.js"></script>
```
## cdnから
jsdeliverなどで
```html
<script src="https://cdn.jsdelivr.net/gh/Tenycircle-js/Tenycircle.js@main/TenyCircle.min.js"></script>
```
# 使用する方法
`$.メソッド名(引数)`

または

``` $.メソッド名`引数(文字のみ)` ```
# `$.`を省略
```javascript
with ($) {
  //コード
}
```
(推奨されません)
# 各メソッドの説明
## `$.id`メソッド
### 概要
idでDOM要素を取得します
### 引数 １つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
$.id`id1`.innerHTML
```
## `$.class`メソッド
### 概要
classでDOM要素群を取得する
### 引数 １つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
$.class`class1`
```
## `$.name`メソッド
### 概要
name属性でDOM要素群を取得します
### 引数 １つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
$.name`name`
```
## `$.tag`
### 概要
タグ名でDOM要素群を取得する
### 引数 1つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
$.tag`button`
```
## `$.text`メソッド
### 概要
対象のテキストを取得、または再定義する
### 引数 2つ htmlElement , string※無くてもいい
### 返り値
第2引数を設定しなかったら対象のtextContent
設定したらなし
### 使用例
```javascript
$.text($.id`a`,"new text!!")
```

