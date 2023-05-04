# SunFounder Pico-4wdカーキット活動報告
## SunFounder Pico-4wdカーキットとは...!?
![SunFounder Pico-4wdカーキット](https://docs.sunfounder.com/projects/pico-4wd/en/latest/_images/pico-4wd.png)

<img src="https://docs.sunfounder.com/projects/pico-4wd/en/latest/_images/pico-4wd.png" width="320">
Pico-4wdは、Raspberry Pi Picoベースのロボットカーキットです。
グレースケールセンサーモジュールと超音波モジュールを装備し、ライントラッキング、崖検出、フォロー、障害物回避機能を実行できます。車の下部と後部に組み立てられたRGBボードは、暗闇の中で最もクールな精神になります。このSunFounder Pico-4wdカーキットはMicroPythonに基づいたサンプルコードを提供しているので、すぐに始めることができるとされています。

***



## 今日やったこと
  1. Thonny IDEをインストール(ver. 4.0.2)
  2. PicoにMicroPythonをインストールする
  3. ライブラリをPicoにアップロードする
  4. モジュールをテストする

### 1.Thonny IDEをインストール(ver. 4.0.2)
　公式が用意してくれた[URL](https://docs.sunfounder.com/projects/pico-4wd/en/latest/index.html)に飛び、ThonnyのWEBサイト[”Thonny”](https://thonny.org)に飛びました。ThonnyのサイトでMac os用のソフトをダウンロードしました。

### 2.PicoにMicroPythonをインストールする
 Thonnyを開き、BOOTSELボタンを長押しし、マイクロUSBケーブルでPicoをコンピュータに接続します。Picoがモニタに表示されたら、BOOTSELボタンを放します。ここで、「右下隅にあるインタプリタ選択ボタンをクリックし、[Micropythonのインストール]を選択します。」とありますが、このインストール画面が出てこない。この原因にver.が古いのでは？と疑ったが、最新と表示されるのでもう少し、原因追求をする必要がある。

### 3.ライブラリをPicoにアップロードする
 これはできた。[SunFounder Pico-4wd Car Code](https://github.com/sunfounder/pico_4wd_car/archive/refs/heads/main.zip)このファイルの「libs」をアップロードする。

### 4.モジュールをテストする
Picoの電源を入れて、モーターをテストする。[SunFounder Pico-4wd Car Code](https://github.com/sunfounder/pico_4wd_car/archive/refs/heads/main.zip)から、「tests」をアップロードし、Run Current script(F5)を押せば動き出すはずであったが、動かない。。。
>2. PicoにMicroPythonをインストールする
>>この部分がやはりうまくいっていないと考えた。
今日はここまで




|あべ|まや|
|---|---|
|---|---|
