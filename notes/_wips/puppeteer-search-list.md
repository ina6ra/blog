---
title: Puppeteerでハマったとこなど
slug: puppeteer-search-list
description: ""
status: publish
published: true
date: 2021-08-07T09:31:55.954Z
modified: 2021-08-15T05:40:29.682Z
links: []
---
ググっても出てこないことがよくある。。

- [node.js - puppeteer page evaluate use require module in page evaluate - Stack Overflow](https://stackoverflow.com/questions/61487726/puppeteer-page-evaluate-use-require-module-in-page-evaluate)
  - page.evaluate()の中に外で宣言した変数とかは使えない。結構面倒でハマる
- [puppeteerでの要素の取得方法 - Qiita](https://qiita.com/go_sagawa/items/85f97deab7ccfdce53ea)
- [javascript - Puppeteer page.evaluate querySelectorAll return empty objects - Stack Overflow](https://stackoverflow.com/questions/46377955/puppeteer-page-evaluate-queryselectorall-return-empty-objects)
  - querySelectorAll では素直に配列で返ってこないので Array.from で囲む
