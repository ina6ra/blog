---
title: Lambda でのハマりどころ色々
slug: lambda-search-list
status: publish
published: true
date: 2021-08-15T05:50:02.345Z
modified: 2021-08-15T05:50:02.397Z
---
非同期処理が動作しないので色々と気を付ける必要あり

- [【array-foreach-async】forEach()でasync/awaitを使おうとして失敗した皆へ - Qiita](https://qiita.com/jinto/items/2c49b1f2530cd3587677)
  - forEach の中で非同期処理が使えない。for-of を使う
  - return を continue に直すのも忘れずに
