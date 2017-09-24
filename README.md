# Arduiino Starter Kit
## Description 
* The Arduino Starter Kit（日本語版）の写経です.

## Projects
### Project 2
* Lチカ

### Project 3
* 温度センサ
* ADコンバータ

### Project 4
* CDSセル
* パルス幅変調（PWM）

### Project 6
* 圧音スピーカ

### Project 11
* LCD(Liquid Crystal Display)

## Issue
* `$ git checkout`すると`warning: unable to unlink`って言われる
  * checkoutしても変更分が残ってしまう
  * シリアルポート使うために`$ sudo ./arduino`でArduino Ideを起こしてるので作成したファイルの所有者がrootになるから
  * `$ sudo usermod -a -G dialout $USER` でグループに追加すればよし
