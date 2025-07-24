 　# Buildguide for cool436tb
<br>


## 0 部品の確認
<br>
Follow the BOM on github's readme.md to make sure that all the parts are available.
<br>
githubのreadme.mdのBOMに沿って、部品が全て揃っているかを確認してください。
<br>


## 1 ダイオードのはんだ付け

If the diode is already soldered, please skip this operation.
<br>
すでにダイオードのはんだ付けされている場合は、この作業を省略してください。
<br>
<br>
This work is done on the left and right keyboard boards respectively.
<br>
この作業は左右のキーボード基板でそれぞれ行います。
<br> 
Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
As expected, it is compatible with SMD type.
<br>
ダイオードは、SMDタイプに対応しています。
<br>
Diodes have polarity, so be careful about the direction in which they are installed.
<br>
ダイオードには極性がありますので、取り付ける向きに注意してください。
<br>

[ダイオード（SMD)のはんだ付けの動画](https://youtu.be/ODk16bd4XkA)
<br>
[ダイオード（リードタイプ）のはんだ付けの動画](https://youtu.be/lbAQkKzNawM)
<br>
[ダイオード（リードタイプ）のはんだ付けの動画２](https://youtu.be/3hWZjaBROL8)

<br>

## 2  スイッチソケットのハンダ付け

Cool436tb supports choc switch sockets.
<br>
cool436tbでは、chocのスイッチソケットに対応しています。
<br><br>
Solder the switch socket to the back of the keyboard board.
<br>
キーボード基板の裏面にスイッチソケットのハンダ付けをします。
<br>

[Switch socketハンダ付け動画](https://youtu.be/ZnbgaueMR4w?si=_JLjD--3HJJ5Pu7Q)


<br>

## 3 Seeed xiao nRF52840 Plusのハンダ付け

<b>Note</b>
<br>
次の動画を参考にしてハンダ付けをしてください。
<br>
[xiao ble plusのハンダ付け動画](https://youtu.be/T4O7NxNUMdo?si=k7QdqWDq2rmBUDI5)



## 4  電池ボックス取り付け

![](img/img00010.jpg)

Insert the battery box from the bottom of the board and temporarily fix it in place with masking tape. Then, cut off the leads sticking out from the top of the board with pliers or something similar, and solder them.
<br>
電池ボックスを基板の下面から、差し込み、マスキングテープで仮固定します。そして、基板の上面から飛び出したリードをニッパーなどで切り取り、ハンダ付けをしてください。
<br>
![](img/img00012.jpg)

![](img/img00010.jpg)


## 5 スライドスイッチのハンダ付け

Insert the switch from the underside of the PCB with the tab facing outwards.
<br>
スイッチのつまみが外側に向くようにして、PCBの下面から差し込みます。
<br>
Temporarily fix it in place with masking tape or something similar, then cut off the part sticking out on the top surface of the PCB with pliers, and then solder it.
<br>
マスキングテープなどで仮固定をしてから、PCBの上面に出た部分をニッパーで切り取ってから、はんだ付けします。
<br>


[スライドスイッチのはんだ付けの作業動画](https://youtu.be/5nkRklibay4)

<br>

## 6 リセットスイッチのハンダ付け

The switch button faces down and is inserted into the underside of the PCB.
<br>
スイッチのボタンが下に向くようにして、 PCBの下面から差し込みます。
<br>
Temporarily fix it in place with masking tape or something similar, then cut off the part sticking out on the top surface of the PCB with pliers, and then solder it.
<br>
マスキングテープなどで仮固定をしてから、PCBの上面に出た部分をニッパーで切り取ってから、はんだ付けします。


[リセットスイッチハンダ付け動画](https://youtu.be/Pl24Exfh8b8)

## ７ トップケースに装着する

Slide the PCB into the top case, making sure the side with the xiao ble is facing down.
<br>
トップケースの中にスライドさせて、PCBを入れます。その際、xiao bleが付いている面が下になるように注意してください。
<br>
<br>

## ８　キースイッチの装着

Insert the key switch in the following order: top case, then PCB.
<br>
トップケース、PCBの順になるように、キースイッチを差し込んでください。
<br>
When inserting the key switch, make sure the pins are straight.
<br>
キースイッチを差し込む時、キースイッチのピンが真っ直ぐになっているか、確認してください。
<br>

## ９ 動作確認について

ファームウェアの導入について、こちらの記事を参考にしてください。
<br>
[自作キーボードへのzmk_firmwareのインストールについて](https://sizu.me/m_ki/posts/kvixkn2mec6a)

<br>
ここに、uf2書類があります。
<br>
https://github.com/telzo2000/cool436/tree/main/firmware

https://github.com/telzo2000/zmk-config-cool436


<br>
Keymapの編集について、こちらの記事を参考にしてください。

[zmk_firmwareでのキーマップ編集について](https://sizu.me/m_ki/posts/m3devs7be5km)


![](img/img00001.jpg)

## 10 ボトムケースの装着

Attach the top and bottom cases, making sure that the USB port on the bottom case fits into the USB connector on the xiao ble.
<br>
ボトムケースにあるUSB挿入口と、xiao bleのUSBがはまるよう注意して、トップケースとボトムケースを装着してください。
<br>
<br>
There are five screw holes on the side, so please secure it in place using 3mm M2 screws.
<br>
側面に５箇所のネジ穴がありますので、そこからM2ネジ3mmで固定してください。
<br>


##  11　キーキャップの装着

Please attach your favorite keycap.
<br>
お好きなキーキャップを装着してください。
<br>


## 12 完成

After attaching non-slip rubber to the bottom of the bottom case, it's done.
<br>
Please enjoy a life with a better keyboard.
<br>
ボトムケースの底面に、滑り止めゴムを取り付けたら、完成です。
<br>
よりよいキーボードのある生活を楽しんでください。
<br>

![](img/img00013.jpg)



