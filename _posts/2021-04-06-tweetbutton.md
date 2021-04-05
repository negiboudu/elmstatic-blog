---
title: ぶろぐいじりを進めています
tags: software 
---

## ツイートボタン作り

[ツイートボタンの作り方](https://help.twitter.com/ja/using-twitter/twitter-buttons)を見ながらツイートボタンを作りました。なるほどこうやって作っていたのね。世の中の人は。１つ謎が解き明かされた気持ちです。

## やりたいことがあと２つ

1. NetlifyCMSの導入
root階層に配置したいものを_resourcesフォルダに入れれば良いようだというのが[Elmstaticのドキュメント](https://korban.net/elm/elmstatic/)を見てわかりました。これなら、NetlifyCMSに必要なadminディレクトリを作ることもできそう。
1. elm-uiを使ってページのデザイン
Elmstaticが生成したファイルをじろじろ見て回りましたが、どうやら```_layouts/Page.elm```だけ修正すれば良さそうです。Elmstaticはelm-cssを使っているようですが、これをelm-uiに置き換えて、レイアウトを大幅に変えてみたいと思います。