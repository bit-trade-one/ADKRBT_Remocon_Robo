# よくある質問

----

### Q:Arduino IDEから直接ソースコードを編集したい場合はどうしたらいいですか？

#### A:つくるっちに内蔵されているArduino IDEを起動してください。

つくるっち上の[ロボット] - [pc modeプログラムを開く] を選択すると "PC通信モード" のソースコードがArduinoIDEで開かれ、ArduinoIDEよりロボットに書き込むことができます。  

また、[ロボット] - [最初のプログラムを開く]を選択すると最初のプログラムがArduinoIDEより開かれ、ArduinoIDEよりロボットに書き込むことが可能です。

----

### Q:つくるっちからロボットへの接続ができません / プログラムを書き込めません

#### A:ロボットのCOMポート番号を確認してください。

PC上にUARTポートが複数認識されている場合、つくるっちはすべてのポートを列挙します。

つくるっちより確認する場合、以下の手順を試してください。  
1.つくるっち上の[接続] - [ロボットに接続(COMxx)] を選択し、チェックマークが付いた状態にする。  
``[ロボットに接続(COMxx)] が複数表示される場合はお手数ですが、一つづつ手順１と２を試して下さい。``    
2. [接続] - [ロボットをPC通信モードに設定] を選択してください。  

----

### Q:ロボットが認識されていますが、Arduino IDEからプログラムを書き込めません

#### A:Arduino IDEの"ボード"と"プロセッサ"を確認してください。

ADKRBT リモコンロボにはArduino Nano互換ボードが搭載されています。  
このボードにはブートローダが2バージョンあり、それに合わせて書き込み時の設定を変更する必要があります。  

Arduino IDEの上部ツールバーより、[ツール]→[ボード]で"Arduino Nano"を選択、  
[ツール]→[プロセッサ]で"ATmega328P"もしくは"ATmega328P (Old bootloader)"のどちらかを選択いただき、  
書込めるか試してください。

----

[参考資料：SWITCHSCIENCE様Arduino Nano販売ページ](https://www.switch-science.com/catalog/2554/)

----

----

#### Q.WINDOWSに接続しても認識されない  
A. 搭載部品のドライババージョンダウンで治る可能性があります。  
リンク先のPDFを参考に行ってください。  
[ArdunoNANOドライババージョンダウン方法.pdf](https://github.com/bit-trade-one/ADKRBT_Remocon_Robo/blob/master/Documents/ArdunoNANO%E3%83%89%E3%83%A9%E3%82%A4%E3%83%90%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E3%83%80%E3%82%A6%E3%83%B3%E6%96%B9%E6%B3%95.pdf)  

----

#### Q.ArduinoNanoのシリアルICドライバのバージョンを下げたい。  
A. 手順を公開しています。  
リンク先のPDFを参考に行ってください。  
[ArdunoNANOドライババージョンダウン方法.pdf](https://github.com/bit-trade-one/ADKRBT_Remocon_Robo/blob/master/Documents/ArdunoNANO%E3%83%89%E3%83%A9%E3%82%A4%E3%83%90%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E3%83%80%E3%82%A6%E3%83%B3%E6%96%B9%E6%B3%95.pdf)    

----

