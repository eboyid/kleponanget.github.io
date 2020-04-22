+++
author = "eboyid"
title = "Tata Penulisan Markdown"
date = "2020-04-21"
description = "Contoh artikel dasar penulisan Markdown dan format elemen HTML."
tags = ["markdown", "css", "html", "themes"]
categories = ["TUTORIAL"]
images  = ["img/2020/post-2020-02.png"] 
+++

<!--This article offers a sample of basic Markdown syntax that can be used in Hugo content files, also it shows whether basic HTML elements are decorated with CSS in a Hugo theme.-->

Ini adalah artikel tentang dasar - dasar penulisan Markdown yang digunakan dalam konten Hugo, juga elemen dasar HTML yang digunakan dalam tema CSS Hugo. 
<!--more-->

## Headings

Berikut ini adalah elemen HTML `<h1>`-`<h6>` yang memperlihatkan 6 tingkatan bagian Judul. `<h1>` adalah ukuran yang terbesar dan `<h6>` adalah yang terkecil.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraf

Sedangkan ini adalah contoh penulisan dalam Paragraf. Penulisan dengan format biasa seperti saat mengetik pada pengolah kata `<Microsoft Word>` atau pengolah kata lainnya. Penulisannya biasa, pengetikan dilakukan terus sampai satu paragraf selesai. Jadi dalam satu baris penulisan pada text editor akan menghasilkan satu kalimat saat ditampilkan di website. 

Ini adalah contoh lain penulisan paragraf, yakni paragraf kedua. Cukup berpindah baris dengan menekan `<enter>` dan anda akan berpindah paragraf dengan jarak satu baris

Lalu ini adalah paragraf ketiga.

## Blockquotes

Blockquote adalah elemen yang memperlihatkan konten yang dikutip dari sbuah sumber, bisa berupa sitasi pada `<footer>` atau `<sitasi>`. Dapat dibuat dalam baris perubahan seperti anotasi atau abeviasi.

#### Blockquote tanpa atribut

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>


[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Inline&nbsp;&nbsp;&nbsp;     | Markdown&nbsp;&nbsp;&nbsp;  | In&nbsp;&nbsp;&nbsp;                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code`     |

## Code Blocks

#### Code block with backticks

```
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
#### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Item
1. First Sub-item
2. Second Sub-item

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
