# CDSCell-and-FullColorLED
## arduino,sample,chuo-u
This document is made by [gitfab](http://gitfab.org)
---
#概要
Arduinoで照度センサ（CDS Cell）とフルカラーLEDを連携させるサンプルです。

照度センサをタッチセンサのように使い、フルカラーLEDの色を切り替えます。

フルカラーLEDはPWM点灯しています。

<iframe src="//www.youtube.com/embed/XAALDR1qXBY" frameborder="0" height="225" width="400"></iframe>
---
#準備
以下のものを準備してください。

###ソフトウェア

1. [Arduino IDE](http://arduino.cc)

###ハードウェア

1. Arduino （Unoが扱いやすいです）
1. ブレッドボード
1. [フルカラーLED](http://akizukidenshi.com/catalog/g/gI-02476/)
1. [CDSセル](http://akizukidenshi.com/catalog/g/gI-00110/)
1. 抵抗：330Ω x4
1. ジャンパワイヤ

簡単のために330Ωの抵抗に統一しています。
「参考」の「回路について」のリンクを参考にすることで、より正確な回路が作れます。
---
#ハードウェア

以下の図のように配線します。

![スクリーンショット 2013-12-13 17.48.59.png](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED-Sample/master/gitfab/resources/スクリーンショット-2013-12-13-17.48.59.png)

以下は回路図のFritzingファイルです。

[fullColorLED-CDSCell.fzz](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED-Sample/master/gitfab/resources/fullColorLED-CDSCell.fzz)
---
#ソフトウェア
ソースコードは[githubレポジトリ](https://github.com/oshimaryo/FullColorLED_and_illuminanceSensor)にアップされています。

画面右下側にある「Download ZIP」ボタンをクリックして、デスクトップにダウンロードします。
![スクリーンショット 2013-12-13 17.20.54.png](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED/master/gitfab/resources/スクリーンショット-2013-12-13-17.20.54.png)


ダウンロードしたzipファイルを解凍し、"LED_illuminanceSensor.ino"ファイルを
Arduinoで開きます。

![スクリーンショット 2013-12-13 17.23.22.png](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED/master/gitfab/resources/スクリーンショット-2013-12-13-17.23.22.png)

「→」マークの「マイコンボードに書き込む」ボタンをクリックすれば、ソフトウェアの書き込みは完了です。

![スクリーンショット 2013-12-13 17.19.45.png](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED/master/gitfab/resources/スクリーンショット-2013-12-13-17.19.45.png)
---
#完成図


![IMG_6206.jpg](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED/master/gitfab/resources/IMG_6206.jpg)
---
# 参考

### 回路について

1. [フルカラーLED](http://www.geocities.jp/zattouka/GarageHouse/micon/Arduino/RGBLED/RGBLED1.htm)
1. [CDSセル](http://happy-arduino.blogspot.jp/2012/02/blog-post_16.html) 
1. [抵抗のカラーコードの見かた](http://part.freelab.jp/s_regi_list.html)

### 回路図の作り方

1. [Fritzing](http://fritzing.org/download/)

### Arduinoダウンロード

1. [Arduino](http://arduino.cc/)
---
