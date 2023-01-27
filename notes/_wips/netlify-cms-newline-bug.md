---
title: Netlify CMSでの日本語入力バグをどうにかする
slug: netlify-cms-newline-bug
description: 日本語入力というかWindowsでのバグ
status: draft
published: false
date: 2021-08-08T08:49:56.908Z
modified: 2021-08-08T08:49:56.948Z
links: []
---
とりあえずbodyをtextにしてプレビューも無効にすれば問題は起きない

以下のプラグインでも解決できるけどMarkdownで保存できない

- [netlify-cms-widget-richtext - npm](https://www.npmjs.com/package/netlify-cms-widget-richtext)

真面目に解決するならtext WidgetをラップしてMarkdownプレビューを追加するようなのを作るしか無い

- [netlify-cms/packages/netlify-cms-widget-text at master · netlify/netlify-cms](https://github.com/netlify/netlify-cms)

プラグイン作る時に参考になりそうなやつ

- [chrisboustead/netlify-cms-widget-async-select: An async select widget for netlify-cms which can populate entries from a valid endpoint. Allows for sending custom headers, data/value fields and transformations.](https://github.com/chrisboustead/netlify-cms-widget-async-select)
- [sformisano/netlify-cms-widget-simple-uuid: A simple Netlify CMS widget to autogenerate IDs for collection items.](https://github.com/sformisano/netlify-cms-widget-simple-uuid)
