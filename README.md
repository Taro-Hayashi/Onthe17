# On the 17 ビルドガイド
- [キット内容](#キット内容)
- [組み立て](#組み立て)
- [キーのカスタマイズ](#キーのカスタマイズ)
- [その他](#その他)

## キット内容

![](img/IMG_1330.jpg) 
||部品名|数| |
|-|-|-|-|
|1|メインボード|1||
||スイッチプレート|1||
||アクリルケース|1||
||色付きプレート|1||
||M2トラスねじ|13|6mm|
||M2なべねじ|5|8mm|
||M2スペーサー（長）|13|13mm|
|2|アクリルプレート（小）|2||
|3|34mmトラックボール支柱|6|
|4|25mmトラックボール支柱|6|
|5|センサー&レンズ|1|PMW3360|
|6|M2トラスねじ|13|6mm|
|7|M2なべねじ（短）|2|4mm|
|8|M2なべねじ（長）|9|10mm|
|9|M3なべねじ|3|10mm|
|10|M2スペーサー（短）|7|3mm|
|11|ベアリング|3|
|12|M2ワッシャー|21||
|13|M2ナット|9||
|14|M2スプリングワッシャー|9||
|15|M3角ナット|3||
|16|Poronスポンジシート（白）|6|2mm|
|17|Poronスポンジシート（黒）|7|3mm|
|18|ゴム足|6||
|19|MXスイッチソケット|60||
|20|LED|75|SK6812MINI-E|

### キット以外に必要なもの
|部品名|数| |
|-|-|-|
|キースイッチ|62～64||
|キーキャップ|62～64||
|2Uスタビライザー|0～2|必要数|
|トラックボール用ボール|1|34mmか25mm|
|Type-C USBケーブル|1||

### 動作確認
アクリルケースの表からねじを外してスイッチプレートとメインボードを取り出します。  
![](img/IMG_1351.jpg)  

アクリルケースは色付きプレートを取り除いて順番通り戻します。  
![](img/IMG_1356.jpg)  

こちらのuf2ファイルをダウンロードしてください。  
- https://github.com/Taro-Hayashi/Onthe17/releases/latest/download/tarohayashi_onthe17_default.uf2

メインボードをPCと接続するとRPI-RP2というドライブとして認識されるのでダウンロードしたuf2ファイルをドラッグアンドドロップするとキーボードとして使用できるようになります。  
![](img/rpi.jpg)  
> [!NOTE] 
> ドライブが出てこない場合はリセットボタンを押しながら接続してみてください。  
> ![](img/IMG_1367.jpg)  

ソケット用のパッドやキースイッチ用のホールをピンセット等で導通し、01～64が入力されることを確認してください。   
![](img/IMG_1371.jpg)  

> [!IMPORTANT] 
> はんだ付けの前に必ず一度確認してください。

### 1Uと2Uを選ぶ
この2か所は1Uキーか2Uキーかを選んで組み立てることができます。  
![](img/IMG_1381.jpg)  
今回はすべて1Uキーで組み立てます。取り付けるキーに合わせて2か所のジャンパーを短絡してください。  
![](img/IMG_1392.jpg)  

### （オプション）LEDのはんだ付け  
LEDの足の角とシルク印刷を合わせてはんだ付けします。      
![](img/IMG_1398.jpg)  

選んだ1Uと2UどちらかのLEDのみ取り付けてください。  
![](img/IMG_1405.jpg)  

半田付けが終わったら発光を確認します。  
![](img/IMG_1413.jpg)  

### MXスイッチソケットのはんだ付け
スイッチソケットをはんだ付けします。  
![](img/IMG_1418.jpg)   

### センサーのはんだ付け
センサーの丸印とシルク印刷を合わせて表ではんだ付けします。  
![](img/IMG_1429.jpg)  
![](img/IMG_1434.jpg)  

保護フィルムをはがし、レンズを乗せた状態でPCと接続します。  
![](img/IMG_1445.jpg)  
手をかざす等してマウスカーソルが動くことを確認してください。  

センサーの動作を確認したらレンズを取り付けて裏面でレンズの足をはんだごてで押しつぶして固定します。  
![](img/IMG_1457.jpg)  

### （オプション）スタビライザーの取り付け
2Uキーを使う場合は2Uスタビライザーを使うことができます。  
![](img/IMG_1461.jpg)  

### キースイッチの取り付け
メインボードにスイッチプレートを重ねてキースイッチを付けます。  
![](img/IMG_1471.jpg)  

はんだ付けをしていないキー以外が反応することを確認したら、残ったキーをはんだ付けして動作を確認します。  
![](img/IMG_1476.jpg)  

### Poronスポンジシートの貼り付け
スイッチプレートの表面にPoronスポンジシート（白）、裏面にPoronスポンジシート（黒）を貼ります。  
![](img/IMG_1483.jpg)   
センサーの横にも1枚Poronスポンジシート（黒）を貼るところがあります。  
![](img/IMG_1490.jpg)   

### トラックボール支柱の組み立て
34mm用と25mm用を選んで組み立てます。  
![](img/IMG_1494.jpg)   
今回は34mmボールを使います。  

M2なべねじ（長）9本にM2ワッシャーを通します。  
![](img/IMG_1499.jpg)   

M2なべねじ（長）でトラックボール支柱にM2スペーサー（短）を取り付けます。  
![](img/IMG_1504.jpg)   

反対側にもトラックボール支柱を付けてM2ワッシャー、M2スプリングワッシャー、M2ナットの順で止めます。  
![](img/IMG_1510.jpg)   

3本のネジにベアリングを通し切れ込みに引っ掛け、M2ワッシャー、M2スプリングワッシャー、M2ナットの順で止めます。  
![](img/IMG_1514.jpg)   

### トラックボール支柱の取り付け
M3角ナットをトラックボール支柱のスリットに入れてメインボードに立てます。  
![](img/IMG_1530.jpg)   
M3角ナットがずれないように気を付けながら裏からM3なべねじで止めます。  

3つ取り付けたらボールを入れてトラックボールの動きを確認したらPCに接続して動作も確認します。  
![](img/IMG_1533.jpg)   

> [!NOTE] 
> ボールにガタ付きがある場合はベアリングの隣に1枚ワッシャーを挟むと改善することがあります。  
> ![](img/IMG_1523.jpg)  
> この場合ねじを締めすぎるとベアリングが回転しないので調節してください。   


### ファームウェアの更新
こちらのuf2ファイルをダウンロードしてください。  
-  https://github.com/Taro-Hayashi/Onthe17/releases/latest/download/tarohayashi_onthe17_via.uf2  

一度USBケーブルを外し、USBコネクタに一番近いキーを押しながらPCに接続してしばらく待つとRPI-RP2ドライブが出てきます。  
![](img/IMG_15332.jpg)   
うまくいかない場合はリセットスイッチを押しながらUSBケーブルを差しこんでください。    

RPI-RP2ドライブにダウンロードしたuf2ファイルをドラッグアンドドロップしたらファームウェアの更新完了です。    


### ケースの組み立て
前面のねじは外した状態でケースを裏返します。  
![](img/IMG_1544.jpg)   

底になるプレートをスペーサーごと引き抜き、スペーサーを取り除いて保護フィルムをはがします。  
![](img/IMG_1554.jpg)   
スペーサーを付けなおしゴム足を貼ります。  
  
ここにM2スペーサー（小）をM2なべねじ（短）で取り付けます。  
![](img/IMG_1557.jpg)   

アクリルプレート（小）2つを乗せてM2なべねじ（短）で止めます。  
![](img/IMG_1561.jpg)   

1枚ずつ保護フィルムをはがして載せていきます。2枚は同じ形状が続きます。  
![](img/IMG_1565.jpg)   
![](img/IMG_1568.jpg)   
2枚の大きくくり抜かれたプレートは同じ形状で、どちらかを色付きプレートと交換することが可能です。  
![](img/IMG_1579.jpg)   
![](img/IMG_1583.jpg)   
ここまで乗せたらメインボードを乗せます。  
![](img/IMG_1589.jpg)   
スペーサー用の穴が開いたプレートを乗せます。
![](img/IMG_1590.jpg)   
ねじ用の穴が開いた一番上のプレートをM2トラスねじで止めます。
![](img/IMG_1597.jpg)  
キーキャップを付けたら完成です。お好みで中央付近にゴム足を増やしてください。  
![](img/IMG_1936.jpg)   

USBケーブルを差し込んで全体的に動作を確認してみてください。  

## キーのカスタマイズ

### トラックボールの設定の変更
一番上の行の左から2番目のキーを押しながら操作するとトラックボールの設定を変更できるようになっています。
![](img/ball.jpg)   
オートマウス機能はトラックボールを使っている時だけレイヤー3に移動する機能です。  

### Remapへの接続
Google Chrome（もしくはChromiumベースのブラウザ）でRemapにアクセスしてください。  
- https://remap-keys.app

![](img/remap1.png)   
青いボタンを押してOn the 17を選ぶと接続できます。  
![](img/remap2.png)   

### 保存と復元
こちらからキーマップの保存と復元ができます。  
![](img/remaprestore.png)   
いくつかサンプルを用意していますので雛形としてご利用ください。  

### 2Uキーの設定
このボタンで2Uキーを設定できます。  
![](img/remaplayout.png)   

### LEDの調整
LEDの設定の変更ができます。  
![](img/remapled.png)   

### キーの割り当て
下の一覧からを上のキーにドラッグアンドドロップしてFLASHを押すとキー設定を変更することができます。  
![](img/remapflash.png)  
下のEnglish(US)のプルダウンをJapaneseに変更すると日本語キーボード（JIS）のキーに対応できます。OSの設定を確認して合わせてください。  

### 特殊なキー
#### スクロールのしかた
左上のキーはTAB/Scrollというキーが割り当てられていて、打鍵するとTABキーですが押しながらトラックボールを操作するとカーソル移動ではなくスクロールになります。  
![](img/scroll.jpg)   
同様にLang2/Scrollキーは長押しでスクロール、Lang2/Slowキーは長押しでカーソルの速度が遅くなります。  

#### 特殊なキーの割り当て
FUNCTIONSタブのVIA USER KEYにOSに関わらず使えるショートカットやトラックボールの設定をするキーがあります。  

|キー名|機能|
|-|-|
|Cmd/Ctl|WindowsではControlキー、MacではCmdキーになります。|
|Captcha|スクリーンショットを撮ります。Win/Mac/iOS対応|
|CPI+（-）|カーソルの移動速度を増やし/減らします。|
|Angle+（-）|カーソルの移動角度を変えます。|
|Invert X|センサーのX軸を反転させます。|
|Cursor / Scroll|トラックボールの動作を切り替えます。|
|Invert Scroll|スクロールの方向を反転します。|
|Scroll Mode|押している間はトラックボールでスクロールします。|
|Toggle Auto Mouse|オートマウス機能をオンオフします。|
|ESC（TAB、Lang1、Lang2）/Scroll|タップでESC（TAB、かな、英数）、押し続けるとスクロールモード。|
|Slow Mode|押している間はトラックボールの速度が減ります。|
|ESC（TAB、Lang1、Lang2、Mouse 1、Mouse2、Mouse3）/Slow|タップでESC（TAB、かな、英数、左クリック、右クリック、中クリック）、押し続けるとスローモード。|

## その他
### ファームウェアまとめ
- テスト用 https://github.com/Taro-Hayashi/Onthe17/releases/latest/download/tarohayashi_onthe17_default.uf2
- Remap用 https://github.com/Taro-Hayashi/Onthe17/releases/latest/download/tarohayashi_onthe17_via.uf2  

### ファームウェアのコード
- https://github.com/Taro-Hayashi/qmk_firmware/tree/tarohayashi/keyboards/tarohayashi/onthe17

### 販売サイト
- https://tarohayashi.booth.pm/items/5508084





















