+++
author = "chibo"
title = "個人メモ（Hugo）"
date = "2020-09-07"
description = "Guide to Thumbnails in Hugo"
tags = [
    "メモ",
]
thumbnail= "images/hugo.png"

+++

#### Hugo + Netlifyでブログを作ったけど、わからないことが多いのでちょっとしたメモ。


##### 新規投稿をする
hugo new posts/ファイル名.md


##### config.tomiについて

ここでサクッと設定できて初めて触った時驚いた。

**summarylength = 0**

→　サマリのテキスト文字数を決めることができる。本ブログでは0に設定。

**日本語で記事作成の場合**

→　HasCJKLanguage = true を追加するとsummarylengthが正常に動く。



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



###### 画像を貼りたい場合

![This is a image](/images/ URLをいれる )

↓こうなる（必ずstaticディレクトリにいれること！）
thumbnail= "images/tio.jpg"

※現在なぜか反映されず
記事のディレクトリに手動で配置必要かも。。。


#### マークダウンの記述まとめ

水平線　***

取り消し線　~~で挟む

文中にコードを差し込む　` （バッククォート）で挟む。

テキストリンク　[hoge] ＋　(https://hoge.com)　= [hoge](https://hoge.com)

改行　行末にスペースを2つ付ける。