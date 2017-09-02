# Arduiino Starter Kit
## Description 
* The Arduino Starter Kit（日本語版）の写経です.

## Issue
* `$ git checkout`すると`warning: unable to unlink`って言われる
  * checkoutしても変更分が残ってしまう
  * シリアルポート使うために`$ sudo ./arduino`でArduino Ideを起こしてるので作成したファイルの所有者がrootになるから
  * 自分でファイル作る or chownすれば問題ない？
