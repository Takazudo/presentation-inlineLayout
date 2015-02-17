<h1 style="line-height:1.4;font-size:3em">Inline Layout</h1>

<p style="margin-bottom:0;padding-bottom:0">高津戸壮 <a href="https://twitter.com/Takazudo">@Takazudo</a></p>

----

# 自己紹介

<div style="display:table; width: 100%">
<div style="display:table-cell; vertical-align:middle; width:60%; vertical-align:top; padding:30px 0 0">
<ul>
<li>高津戸壮 (たかつど たけし)</li>
<li><a href="http://www.pxgrid.com/">株式会社ピクセルグリッド</a></li>
<li>フロントエンドエンジニア</li>
<li><a href="twitter.com/Takazudo">@Takazudo</a></li>
</ul>
</div>
<div style="display:table-cell; vertical-align:middle; width:40%"><img src="myAdditions/takazudo.jpg" width="300" alt=""></div>
</div>

----

# 今日話すこと

<ul style="font-size:1.6em">
<li>font-size</li>
<li>line-height</li>
<li>vertical-align</li>
<li>inline-block</li>
</ul>

----

<pre style="font-size:2em"><code>&lt;div&gt;&lt;img&gt;&lt;/div&gt;
&lt;div&gt;&lt;img&gt;&lt;/div&gt;</code></pre>

---

<img style="width:50%" src="myAdditions/imgs/etc/imgs1.png" class="x-nodeco">

---

<img style="width:50%" src="myAdditions/imgs/etc/imgs2.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/gifs/expect.gif" class="x-nodeco">

---

<pre style="font-size:1.2em"><code>img { vertical-align: top; }</code></pre>

---

<img style="width:50%" src="myAdditions/imgs/etc/imgs3.png" class="x-nodeco">

---

<p style="font-size:2em">このスペースって何？</p>

----

<img style="width:100%" src="myAdditions/imgs/etc/bullets.png" class="x-nodeco">

---

<p style="font-size:2em">うまく位置揃わない</p>

----

# 今日のメニュー

1. 画像下部の余白の謎
2. アイコン画像の縦位置調整
3. アイコンを飛び出させる
4. チェックボックスやラジオボタンの配置
5. リストのポッチ
6. カラムレイアウト

----

# 1. 画像下部の<br>余白の謎

----

<img style="width:40%" src="myAdditions/imgs/1/x2.png" class="x-nodeco">

```html
<p><span>The quick brown...</span></p>
```

```css
p {
  font-size: 16px;
  line-height: 16px;
}
span {
  background: pink;
}
```

---

<img style="width:100%" src="myAdditions/imgs/1/1.png" class="x-nodeco">

---

<img style="width:40%" src="myAdditions/imgs/1/x3.png" class="x-nodeco">

```css
p {
  font-size: 16px;
  line-height: 24px;
}
```

---

<img style="width:100%" src="myAdditions/imgs/1/2.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/1/3.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/1/4.png" class="x-nodeco">

```css
p {
  font-size: 16px;
  line-height: 24px;
}
```

----

<img style="width:100%" src="myAdditions/imgs/1/5.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/1/6.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/1/7.png" class="x-nodeco">

----

<img style="width:50%" src="myAdditions/imgs/1/x4.png" class="x-nodeco">

```html
<p>The <b>quick</b> <em>brown</em> <i>fox</i> jumps...</p>
```

---

<img style="width:100%" src="myAdditions/imgs/1/x1.png" class="x-nodeco">

```html
<p>The <b>quick</b> <em>brown</em> <i>fox</i> jumps...</p>
```

```css
p  { font-size: 12px; line-height: 18px; }
b  { font-size: 20px; line-height: 30px; }
em { font-size: 30px; line-height: 40px; }
i  { font-size: 40px; line-height: 50px; }
```

---

<img style="width:100%" src="myAdditions/imgs/1/8.png" class="x-nodeco">

```css
p  { font-size: 12px; line-height: 18px; }
b  { font-size: 20px; line-height: 30px; }
em { font-size: 30px; line-height: 40px; }
i  { font-size: 40px; line-height: 50px; }
```

----

<img style="width:100%" src="myAdditions/imgs/2/1.png" class="x-nodeco">

```css
img.A { vertical-align: top; }
img.B { vertical-align: bottom; }
```

---

<img style="width:100%" src="myAdditions/imgs/2/2.png" class="x-nodeco">

```css
img.C { vertical-align: text-top; }
img.D { vertical-align: text-bottom; }
```

---

<img style="width:100%" src="myAdditions/imgs/2/3.png" class="x-nodeco">

```css
img.E { vertical-align: baseline; }
img.F { vertical-align: middle; }
```

---

<img style="width:100%" src="myAdditions/imgs/2/4.png" class="x-nodeco">

```css
img.G { vertical-align: 5px; }
```

---

<img style="width:100%" src="myAdditions/imgs/2/5.png" class="x-nodeco">

```css
img.H { vertical-align: central; }
```

----

#### vertical-align: top

<img style="width:100%" src="myAdditions/imgs/2/x-top.png" class="x-nodeco">

---

<img style="width:80%" src="myAdditions/imgs/2/6-top.png" class="x-nodeco">

<img style="width:80%" src="myAdditions/imgs/2/1.png" class="x-nodeco">

----

#### vertical-align: bottom

<img style="width:100%" src="myAdditions/imgs/2/x-bottom.png" class="x-nodeco">

---

<img style="width:80%" src="myAdditions/imgs/2/6-bottom.png" class="x-nodeco">

<img style="width:80%" src="myAdditions/imgs/2/1.png" class="x-nodeco">

----

#### vertical-align: text-top

<img style="width:100%" src="myAdditions/imgs/2/x-text-top.png" class="x-nodeco">

---

<img style="width:80%" src="myAdditions/imgs/2/6-text-top.png" class="x-nodeco">

<img style="width:80%" src="myAdditions/imgs/2/2.png" class="x-nodeco">

---

#### +line-height: 1

<img style="width:100%" src="myAdditions/imgs/2/x-text-top-lh1.png" class="x-nodeco">

※leading部分がなくなるから

----

#### vertical-align: text-bottom

<img style="width:100%" src="myAdditions/imgs/2/x-text-bottom.png" class="x-nodeco">

---

<img style="width:80%" src="myAdditions/imgs/2/6-text-bottom.png" class="x-nodeco">

<img style="width:80%" src="myAdditions/imgs/2/2.png" class="x-nodeco">

----

#### vertical-align: baseline

<img style="width:100%" src="myAdditions/imgs/2/x-baseline.png" class="x-nodeco">

---

<img style="width:80%" src="myAdditions/imgs/2/6-baseline.png" class="x-nodeco">

<img style="width:80%" src="myAdditions/imgs/2/3.png" class="x-nodeco">

----

#### vertical-align: middle

<img style="width:100%" src="myAdditions/imgs/2/x-middle.png" class="x-nodeco">

---

<img style="width:80%" src="myAdditions/imgs/2/6-middle.png" class="x-nodeco">

<img style="width:80%" src="myAdditions/imgs/2/3.png" class="x-nodeco">

----

#### vertical-align: 10px

<img style="width:100%" src="myAdditions/imgs/2/x-length.png" class="x-nodeco">

---

<img style="width:70%" src="myAdditions/imgs/2/6-length.png" class="x-nodeco">

<img style="width:70%" src="myAdditions/imgs/2/4.png" class="x-nodeco">

----

## ちょっとまとめ

`vertical-align`の値により色々スペースができる

<img style="width:80%" src="myAdditions/imgs/1/5.png" class="x-nodeco">

----

# 2. アイコン画像の<br>縦位置調整

----

<img style="width:100%" src="myAdditions/imgs/etc/bullets.png" class="x-nodeco">

----

<img style="width:40%" src="myAdditions/imgs/3/x1.png" class="x-nodeco">

---

```html
<ul>
  <li><img src="icon.png" width="10" alt=""> xAhy 鈴</li>
  <li><img src="icon.png" width="20" alt=""> xAhy 鈴</li>
  <li><img src="icon.png" width="30" alt=""> xAhy 鈴</li>
  <li><img src="icon.png" width="40" alt=""> xAhy 鈴</li>
  <li><img src="icon.png" width="50" alt=""> xAhy 鈴</li>
</ul>
```

----

#### vertical-align: top

<img style="width:70%" src="myAdditions/imgs/3/x-top.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/top.png" class="x-nodeco">

----

#### vertical-align: bottom

<img style="width:70%" src="myAdditions/imgs/3/x-bottom.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/bottom.png" class="x-nodeco">

----

#### vertical-align: text-top

<img style="width:70%" src="myAdditions/imgs/3/x-text-top.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/text-top.png" class="x-nodeco">

----

#### vertical-align: text-bottom

<img style="width:70%" src="myAdditions/imgs/3/x-text-bottom.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/text-bottom.png" class="x-nodeco">

----

#### vertical-align: baseline

<img style="width:70%" src="myAdditions/imgs/3/x-baseline.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/baseline.png" class="x-nodeco">

----

#### vertical-align: 4px

<img style="width:70%" src="myAdditions/imgs/3/x-length.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/length.png" class="x-nodeco">

---

#### vertical-align: -4px

<img style="width:100%" src="myAdditions/imgs/3/length2.png" class="x-nodeco">

----

#### vertical-align: middle

<img style="width:70%" src="myAdditions/imgs/3/x-middle.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/middle.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/x4.png" class="x-nodeco">

```css
img {
  vertical-align: middle;
}
```

----

#### 微調整の例

<img style="width:70%" src="myAdditions/imgs/3/x-adjust.png" class="x-nodeco">

---

<img style="width:100%" src="myAdditions/imgs/3/x2.png" class="x-nodeco">

```css
img {
  vertical-align: middle;
  position: relative;
  top: -0.1em;
}
```

----

## ちょっとまとめ

* とりあえず`middle`ベースがいいんじゃない？
* アイコンのサイズとか決めちゃうと楽


----

<img style="width:40%" src="myAdditions/imgs/3/x3.png" class="x-nodeco">

----

# 3. アイコンを<br>飛び出させる

----

<img style="width:40%" src="myAdditions/imgs/4/x0.png" class="x-nodeco">

```html
<ul>
  <li><img>彼は背後に...</li>
  <li><img>それはあまり...</li>
</ul>
```

----

<img style="width:40%" src="myAdditions/imgs/4/x1.png" class="x-nodeco">

```css
ul {
  border: 3px solid #000;
  list-style-type: none;
}
li {
  padding: 0 0 10px 32px;
}
img {
  width: 24px;
  height: 24px;
  vertical-align: middle;
}
```

----

<img style="width:40%" src="myAdditions/imgs/4/x2.png" class="x-nodeco">

```css
ul {
  border: 3px solid #000;
  list-style-type: none;
}
li {
  padding: 0 0 10px 32px;
  text-indent: -32px; /* 1行目だけ左に32pxずらす */
}
img {
  width: 24px;
  height: 24px;
  vertical-align: middle;
}
```

---

<img style="width:80%" src="myAdditions/imgs/4/exp2.png" class="x-nodeco">

----

<img style="width:40%" src="myAdditions/imgs/4/x3.png" class="x-nodeco">

```css
ul {
  border: 3px solid #000;
  list-style-type: none;
}
li {
  padding: 0 0 10px 32px;
  text-indent: -32px;
}
img {
  width: 24px;
  height: 24px;
  vertical-align: middle;
  margin: -14px 8px -10px 0; /* 32px確保 + 上下の高さ殺し */
}
```

---

<img style="width:80%" src="myAdditions/imgs/4/exp1.png" class="x-nodeco">

```
margin-top: -14px;
margin-bottom: -10px;
```

----

## ちょっとまとめ

`text-indent`で戻した部分に  
アイコンを置くと便利そう

----

# 4. チェックボックス<br>やラジオボタンの配置

----

<img style="width:80%" src="myAdditions/imgs/4/x4.png" class="x-nodeco">

```html
<ul>
  <li><label><span><input type="radio"></span>彼は...</label></li>
  <li><label><span><input type="checkbox"></span>それは...</label></li>
</ul>
```

----

<img style="width:80%" src="myAdditions/imgs/4/x5.png" class="x-nodeco">

```css
ul {
  list-style-type: none;
  border: 3px solid #000;
}
li {
  padding: 0 0 10px 25px;
}
```

----

<img style="width:80%" src="myAdditions/imgs/4/x6.png" class="x-nodeco">

```css
ul {
  list-style-type: none;
  border: 3px solid #000;
}
li {
  padding: 0 0 10px 25px;
  text-indent: -25px;
}
```

----

<img style="width:80%" src="myAdditions/imgs/4/x7.png" class="x-nodeco">

```css
span {
  display: inline-block;
  width: 20px;
  margin: -17px 5px -13px 0;
  vertical-align: middle;
  background: red;
}
input {
  display: block;
  margin: 0 auto;
}
```

---

<img style="width:100%" src="myAdditions/imgs/4/x8.png" class="x-nodeco">

----

## インラインブロック

* `display: inline-block`
* 外からは`<img>`のようなインライン<br>置換要素のようにレイアウトされる
* 中にブロックレベルの要素を入れられる
* なかなか柔軟に使えるので色々活躍

----

# 5. リストのポッチ

----

<img style="width:50%" src="myAdditions/imgs/5/x1.png" class="x-nodeco">

```html
<ul>
  <li>彼は背後に...</li>
  <li>それはあまり...</li>
</ul>
```

```css
li {
  padding: 0 0 10px 16px;
  background: url(bullet.png) no-repeat 0 .45em;
}
```

----

<img style="width:50%" src="myAdditions/imgs/5/x2.png" class="x-nodeco">

---

<img style="width:50%" src="myAdditions/imgs/5/x8.png" class="x-nodeco">

----

<img style="width:50%" src="myAdditions/imgs/5/x3.png" class="x-nodeco">

```css
li {
  padding: 0 0 10px 16px;
}
li:before {
  content: '';
  width: 8px;
  height: 8px;
  display: inline-block;
  background: url(bullet.png) no-repeat 0 0;
  vertical-align: middle;
}
```

----

<img style="width:50%" src="myAdditions/imgs/5/x4.png" class="x-nodeco">

```css
li {
  padding: 0 0 10px 16px;
  text-indent: -16px; /* 左へ */
}
li:before {
  content: '';
  width: 8px;
  height: 8px;
  display: inline-block;
  background: url(bullet.png) no-repeat 0 0;
  vertical-align: middle;
}
```

----

<img style="width:50%" src="myAdditions/imgs/5/x5.png" class="x-nodeco">

```css
li {
  padding: 0 0 10px 16px;
  text-indent: -16px;
}
li:before {
  content: '';
  width: 8px;
  height: 8px;
  display: inline-block;
  background: url(bullet.png) no-repeat 0 0;
  vertical-align: middle;
  margin: -5px 8px -3px 0; /* マージン調整 */
}
```

----

<img style="width:70%" src="myAdditions/imgs/5/x6.png" class="x-nodeco">

---

<img style="width:70%" src="myAdditions/imgs/5/x7.png" class="x-nodeco">

----

<img style="width:80%" src="myAdditions/imgs/5/x9.png" class="x-nodeco">

----

## ちょっとまとめ

色々細かいレイアウト制御に便利

----

# 6. カラムレイアウト

----

<img style="width:80%" src="myAdditions/imgs/inlineBlock.png" class="x-nodeco">

```html
<div>Hello! Hello! Hello!</div>
```

----

<img style="width:70%" src="myAdditions/imgs/inlineBlock_2.png" class="x-nodeco">

```css
.box {
  display: inlie-block;
  vertical-align: middle;
}
```

```html
<div>
  Hello! 
  <div class="box">...</div>
  Hello!
</div>
```

----

<img style="width:80%" src="myAdditions/imgs/inlineBlock_3.png" class="x-nodeco">

```html
<div>
  Hello! 
  <div class="box">...</div>
  <div class="box">...</div>
  Hello!
</div>
```

----

<img style="width:80%" src="myAdditions/imgs/inlineBlock_4.png" class="x-nodeco">

```html
<div>
  <div class="box">...</div>
  <div class="box">...</div>
  <div class="box">...</div>
</div>
```

----

<img style="width:80%" src="myAdditions/imgs/inlineBlock_5.png" class="x-nodeco">

----

# まとめ

----

* インラインレイアウトの仕組みを知れば<br>いろいろ悩むところ減って捗る
* 細かいところにも大きなところにも使えて<br>いろいろ応用が効くヤツ
* IE8〜なら概ね問題なく使えるので<br>じゃんじゃん使ってるね既に

----

<img style="width:50%" src="myAdditions/jqbook.png" alt="">

----

<img src="myAdditions/imgs/cgcard.jpg" alt="" style="width: 75%" class="x-nodeco">

---

* [CSS再入門 - inline layout 1](https://app.codegrid.net/entry/inline-layout-1)


----

# ありがとう<br>ございました
