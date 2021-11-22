---
title: Markdown記法一覧
create: 2021-11-22
update:
tags: markdown
image:
lang: ja
description: テスト記事
publish: true
---

# 記法一覧

Markdown 記法の確認用。md ファイルを汎用的に使いまわせる様に、可能な限り GitHub Flavored Markdown に準拠したい。

## 見出し heading

```
# 見出し h1
## 見出し h2
### 見出し h3
#### 見出し h4
```

## リスト

```
- Hello!
- Hola!
  - Bonjour!
  * Hi!
```

- Hello!
- Hola!
  - Bonjour!
  * Hi!

### 番号付きリスト

```
1. First
2. Second
```

1. First
2. Second

## テキストリンク

```
[アンカーテキスト](リンクのURL)
```

[アンカーテキスト](#)

## 画像

```
![altテキスト](https://画像のURL)
```

![twitter @not_you_die logo](https://pbs.twimg.com/profile_images/1392923716036689924/fIDxhNo9_400x400.png)


### 画像にリンクを貼る

```
[![altテキスト](画像のURL)](リンクのURL)
```

## テーブル

```
| Head | Head | Head |
| ---- | ---- | ---- |
| Text | Text | Text |
| Text | Text | Text |
```

| Head | Head | Head |
| ---- | ---- | ---- |
| Text | Text | Text |
| Text | Text | Text |

## コードブロック

```
```js
function(a, b){
 return a + b;
}
```
```

```js
function(a, b){
 return a + b;
}
```

### ファイル名を表示する

```
```js:sum.js
```

```js:sum.js
function(a, b){
 return a + b;
}
```

## 数式
Katex を利用したい

### 数式のブロックを挿入する

```
$$
e^{i\theta} = \cos\theta + i\sin\theta
$$
```

$$
e^{i\theta} = \cos\theta + i\sin\theta
$$

### インラインで数式を挿入する

`$a\ne0$`というように`$`ひとつで挟むことで、インラインで数式を含めることができます。たとえば$a\ne0$のようなイメージです。

## 引用

```
> quote
>> quote
```

> quote
> quote

## 注釈
```
脚注の例[^1]です。インライン^[脚注の内容その2]で書くこともできます。

[^1]: 脚注の内容その1
```

脚注の例[^1]です。インライン^[脚注の内容その2]で書くこともできます。

[^1]: 脚注の内容その1

## 区切り線
```
---
```

---

## インラインスタイル
```
*イタリック*
**太字**
~~打ち消し線~~
インラインで`code`を挿入する
```

*イタリック*
**太字**
~~打ち消し線~~
インラインで`code`を挿入する

### インラインのコメント
```
<!-- TODO: ◯◯について追記する -->
```

<!-- TODO: ◯◯について追記する -->


## 参照

- [GitHub - GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Zenn.dev - ZennのMarkdown記法一覧](https://zenn.dev/zenn/articles/markdown-guide)
- [Qiita - Markdown記法 チートシート](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)
