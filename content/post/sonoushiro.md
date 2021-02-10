+++
author = "chibo"
title = "個人メモ"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo"
tags = [
    "コラム",
    "ドキュメント",
]
thumbnail= "images/landscape.jpg"

+++

#### Hugo + Netlifyでブログを作ったけど、わからないことが多いのでちょっとしたメモ。
見出し「#の数でh調整 + 半角改行」↑は#４つのh4

#改行をいれるにはスペース２つ　　これ

** で文字列を挟む。

コードは`で囲む

`hugo new site chibo`

#画像を貼りたい場合

![This is a image](/images/ URLをいれる )

↓こうなる（必ずstaticディレクトリにいれること！）
thumbnail= "images/tio.jpg"


Thumbnails can be enabled easily by setting the `thumbnail` parameter in the frontmatter to an image such as `"images/landscape.jpg"`. 

Make sure to copy the image the `static/images/` directory.

ああああああ
```
あ


