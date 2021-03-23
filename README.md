# wifiDeauth

* 需要使用兩張wifi 網卡
  * 第一張mlan0 用於 iwlist scan
  * 第二張 wlan0 用於 monitor
* 請先執行  airmon-ng start wlan0
* 再執行 python3 deauth.py