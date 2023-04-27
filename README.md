# D-MIN
Communication robot capable of wireless remote control.

##初期コンセプト
安価なESP32-C3をマイコンとして用い、手くらいのサイズの室内用ロボット

##すでにできること
- ESP32-c3への書き込み


##開発中の機能
- I2CでのSSD1306への表示
- I2Cでの音声構成ＬＳＩを用いた発生
- I2Cでのセンサ(温湿度、9軸センサを予定)
- 三輪オムニの制御
- WebSocketを用いたスマホ上ブラウザからの遠隔操作


##将来的に
- ESP-CAMとミックス
- 外部Wifi接続でのネット経由の遠隔操作
- 大量生産用に基盤等設計
