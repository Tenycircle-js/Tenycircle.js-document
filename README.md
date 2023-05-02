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
