---
tags: [_archives]
title: Kindle Fire に TVer と DMM をインストールする方法
created: '2020-10-23T23:35:32.328Z'
modified: '2020-10-26T23:06:20.264Z'
---

### TVer と DMM が動作しない

Kindle Fire Hd 8（第７世代）をセットアップし直したら TVer と DMM が起動しなかった。  
６月頃にやった時はできたので、古いバージョンのを入れればできるだろうと調査して解決しました。

<!--more-->

### キモは Google Play 開発者サービス

結論から言うと Google Play 開発者サービスの旧バージョンを入れないとダメでした。  
しかもかなり古いバージョンの **20.15.40** を入れる必要があり、  
APKPure のサイトからは入手できないので以下のサイトから導入します。

- [Google Play Services 旧バージョン \- Android](https://google-play-services.jp.uptodown.com/android/versions)
- [ダウンロード google play services 20\.15\.40 \(000304\-311554077\) 無料 \(android\)](https://google-play-services.jp.uptodown.com/android/download/2252562)

あとは TVer と DMM、Google Play Store は最新版でおｋです。  
Kindle に APKPure を導入してそこからインストールします。

- [APKPure APKを通じてオンラインで APK をダウンローダする \| APKPure公式サイト](https://apkpure.com/jp/)
- [Android 用の Google Play Store APK をダウンロード](https://apkpure.com/jp/google-play-store/com.android.vending)
- [Android 用の TVer（ティーバー）\- 民放公式テレビポータル \- 無料で動画見放題 APK をダウンロード](https://apkpure.com/jp/tver%EF%BC%88%E3%83%86%E3%82%A3%E3%83%BC%E3%83%90%E3%83%BC%EF%BC%89-%E6%B0%91%E6%94%BE%E5%85%AC%E5%BC%8F%E3%83%86%E3%83%AC%E3%83%93%E3%83%9D%E3%83%BC%E3%82%BF%E3%83%AB-%E7%84%A1%E6%96%99%E3%81%A7%E5%8B%95%E7%94%BB%E8%A6%8B%E6%94%BE%E9%A1%8C/jp.hamitv.hamiand1)
- [Android 用の DMM動画プレイヤー APK をダウンロード](https://apkpure.com/jp/dmm%E5%8B%95%E7%94%BB%E3%83%97%E3%83%AC%E3%82%A4%E3%83%A4%E3%83%BC/com.dmm.app.movieplayer)

全てインストールしたら一旦 Kindle を再起動しましょう。  
これで TVer と DMM が起動して問題なく使えるはずです。

### ただし問題は残る

ただ完全解決ではなくて、Google Play 開発者サービスを更新して下さいとの表示が通知に出続けます。  
バージョンを一つでも上げたら動作しなくなるのでそのまま気にせず使い続けるしかありません。

ちなみに Show Mode に対応して内部の Android バージョンも上がった第８世代の Fire でも確認しました。  
結果は第７世代と同様に通知表示が出続け、Google Play 開発者サービスのバージョンを上げたら  
TVer などが起動できなくなりました。
