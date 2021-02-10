+++
author = "chibo"
title = "個人メモ"
date = "2020-09-07"
description = "Guide to Thumbnails in Hugo"
tags = [
    "コラム",
    "ドキュメント",
]
thumbnail= "images/1-3.jpg"

+++

#### Hugo + Netlifyでブログを作ったけど、わからないことが多いのでちょっとしたメモ。

##### config.tomiについて

summarylength →　サマリのテキスト文字数を決めることができる。

日本語で記事作成の場合　→　HasCJKLanguage = true　を追加するとsummarylengthが正常に動く。（苦労した）


##### [Params]について（config.tomi）

socialShare
記事をSNSに連携するためのアイコンが表示。

readingTime
この記事を読むのに何分程度かかるのか表示。

wordCount
記事の文字数を表示。


#####　記事作成の際の設定

タグの設定
→tags: [ "Hugo", "go" ]　←複数設定したいときはこのように書く。

カテゴリーの設定
---
title: "ここにタイトル"
date: 2019-02-20
draft: flase
categories: [ "ここに入力" ]
---








#画像を貼りたい場合

![This is a image](/images/ URLをいれる )

↓こうなる（必ずstaticディレクトリにいれること！）
thumbnail= "images/tio.jpg"


Thumbnails can be enabled easily by setting the `thumbnail` parameter in the frontmatter to an image such as `"images/landscape.jpg"`. 

Make sure to copy the image the `static/images/` directory.

ああああああ
```
あ


