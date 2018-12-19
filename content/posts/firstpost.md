---
title: "Angular Service"
date: 2018-12-19T12:47:16+09:00
draft: true
---

## Service
サービスとは、コンポーネントやディレクティブから利用されて使う。一定の処理役割を持つコードをサービスでまとめます。

ということは、Componentに書いてるロジック部分を Service へ移動させるということか。

[angular.jp](https://angular.jp/)のチュートリアルには
`コンポーネント内では直接データの取得や保存を行うべきではありません。`と書いてあるので、Componentで定義されたすべてのロジック部分はサービス化すべき、ということですね。

[サンプルコード書いてみた](https://stackblitz.com/edit/service-try)

