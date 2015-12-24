# タイトル
square Ver1.0  

## 著者
Masuko Koeda as みるく (<http://white-stage.com/>)

## 説明
「WAIproCSS Ver2.7.1 for Geeklog2.1.0」をベースに  
レスポンシブWebデザイン&HTML5のテーマを作成。  
PCは2カラム,タブレットは中央ブロック1カラム&左右ブロック２カラムレイアウト、  
スマートフォンは中央ブロック&左右ブロック1カラムレイアウト。

詳しくは、<http://white-stage.com/article.php/square>をご覧ください。

## ライセンス  
WAIproCSSのライセンスに準じます。WAIproCSSのライセンスは下記の通りになります。  

This program is free software; you can redistribute it and/or modify it under the terms of  
the GNU General Public License as published by the Free Software  
Foundation; either version 2 of the License, or (at your option) any laterversion.  


This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;  
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
See the GNU General Public License for more details.


--日本語訳--  
このプログラムは、フリーソフトウェアです。フリーソフトウェア財団が発表しているように  
GNU一般向けライセンスの条件の下で。再配布するか、修正する事が出来ます。  


ライセンスのバージョン2.0、もしくは(オプションによっては)それ以降のバージョンをご使用下さい。  


このプログラムは、お役に立てる事を願って配布されていますが、何の保証もないプログラムです。  
特定の目的の為に販売または他のプログラムに適合させるという保障は含まれておりません。  
詳細は、GNU一般向けライセンスをご覧下さい。  


==============================================================================  

## ファイル構成
squareフォルダ（テーマのファイルです。）  
  ｜  
RADME（解説ファイル[このファイルです。]）  

==============================================================================  


## 仕様
* HTML5&レスポンシブWebデザイン(リキッドレイアウト)のテーマです。

* 大画面での可読性を考慮し、横幅は1920px以上広がらないよう設定しています。

* PCでは2カラムレイアウト、タブレットやスマートフォンでは1カラム(iPadとAndroidのlandscapeは左右ブロック２カラム)レイアウトで作成し、PCとタブレット&スマートフォンではそれぞれ最適なデザインになるよう作成しています。

* 横幅の小さいスマートフォンサイズでもPCで表示させている情報と同様の情報が得れるので、スマートフォンでアクセスしても情報が欠けることがありません。

* デザインの変更があってもHTMLは1つなのでCSSのみの修正だけで済むので作業効率が良いです。

* タブレット及びスマートフォンでのユーザビリティを考慮し、input(送信等)などのボタンはタッチしやすいよう大きくしています。

* テーマ「square」も「WAIproCSS」と同様、アクセシビリティに配慮して作成しています。

* 管理画面のコンフィギュレーション > テーマの拡張設定タブにある"右ブロックを常に表示する"を「いいえ」にして使用してください。(「はい」にするとレイアウトが崩れてしまいますのでご注意ください！)

* PC用デザインでdiv#container div#wrapper div#centerblocks に設定している min-height: 780px; は、左カラムのヘッダとグローバルナビゲーションを足した高さを設定しています。左カラムより右カラムが高さが短くなると背景色が切れたようになってしまう為、高さの最低値を指定してます。ご自分のサイトのナビゲーションの数に合わせて変更してください。

* PC版デザインは、jQueryの「jquery.tile.js」(<http://urin.github.io/jquery.tile.js/>)プラグインを使用してトップページメイン部分のブロックの高さを揃えています。

* 横幅785以下の環境ではアクセシブルなドロワーメニュー(<http://heydonworks.com/practical_aria_examples/#hamburger>)を使用しています。(よりアクセシブルになるようほんの少し改良しています)

* ドロワーメニューを開いた時は、「×」ボタン又はメニューを選択するまではフォーカスはグローバルナビゲーション内のみの移動になります。

* Geeklog 2.1.0日本語パッケージ拡張版に梱包されているプラグインの表示確認はしておりますが、tableで構成されている又はCSSでfloatを使用しているプラグインについては、スマートフォンのサイズには対応していない事をご了承ください。(情報が欠けたり動作しないという事はありませんが、レイアウトは崩れはご自身で調整してください)

* facebookの窓 等 横幅を絶対値で指定している箇所がある場合、その数値(横幅)より小さいサイズのデバイスで閲覧すると横スクロールバーが出てしまうかレイアウトが崩れる可能性があるのでご注意ください。(ご自身で横幅を調整してください)


## テーマ使用方法
「square」フォルダをlayout/にアップロードして下さい。


# 表示確認
Windows 7 / Firefox39.0.3,Google Chrome44.0.2403.130,Internet Explorer 11 10 9  
Mac OS X 10.10.4 / Firefox 39.0.3,Google Chrome44.0.2403.130,Safari 8.0.7  
iPod touch / iOS 8.4 Safari,iPad2 / iOS 8.4 Safari,GALAXY SC-04E / Android4.4.2 標準ブラウザ・Chrome44.2.2403.133  


# 読み上げ確認
Windows 7 / Internet Explorer 11 PC-Talker7,Firefox39.0.3 NVDA2015.1jp  
iPad2 / iOS 8.4 Safari VoiceOver,GALAXY SC-04E / Android4.4.2 標準ブラウザ Talkback  


