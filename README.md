# On the 17 ビルドガイド
- [キット内容](#キット内容)
- [組み立て](#組み立て)
- [キーのカスタマイズ](#キーのカスタマイズ)
- [その他](#その他)

## キット内容

![画像を添付](img/) 
||部品名|数| |
|-|-|-|-|
|1|メインボード|1||
||スイッチプレート|1||
||アクリルケース|1||
||色付きプレート|1||
||M2トラスねじ|26|6mm|
||M2スペーサー（長）|13|13mm|
|2|M2スペーサー（短）|7|3mm|
|3|アクリルプレート（小）|2||
|4|34mmトラックボール支柱|6|
|5|25mmトラックボール支柱|6|
||M2なべねじ（短）|2|4mm|
||M2なべねじ（長）|9|10mm|
||M2ワッシャー|21||
||M2スプリングワッシャー|9||
||M2ナット|9||
||M3角ナット|3||
||M3なべねじ|3|10mm|
||MXスイッチソケット|60||
||LED|75|SK6812MINI-E|
||センサー&レンズ|1|PMW3360|
||リセットスイッチ||
||Poronスポンジシート（白）|6|2mm|
||Poronスポンジシート（黒）|7|3mm|
||ゴム足|6||

### キット以外に必要なもの
![画像を添付](img/) 
|部品名|数| |
|-|-|-|
|キースイッチ|62～64||
|キーキャップ|62～64||
|2Uスタビライザー|0～2|必要数|
|トラックボール用ボール|1|34mmか25mm|
|Type-C|USBケーブル|1||

### 初期不良のチェック
アクリルケースからねじを外してスイッチプレートとメインボードを取り出します。  
![画像を添付](img/) 

アクリルケースは色付きプレートを取り除いて順番通り戻します。
![画像を添付](img/) 

こちらのuf2ファイルをダウンロードしてください。  
- !URL!

メインボードをPCと接続するとRPI-RP2というドライブとして認識されるのでダウンロードしたuf2ファイルをドラッグアンドドロップするとキーボードとして使用できるようになります。
![画像を添付](img/) 

ソケット用のパッドやキースイッチ用のホールをピンセット等で導通し、01～64が入力されることを確認してください。  
![画像を添付](img/) 

> [!IMPORTANT] 
> 全数テスト後に発送しておりますがはんだ付けの前に必ず一度確認し、入力されないキーがある場合はご連絡ください。
> はんだ付け作業後の交換は有償での対応になります。

## 組み立て
### リセットスイッチのはんだ付け
リセットスイッチを乗せてはんだ付けします。  
> [!IMPORTANT] 
> 全ての組み立て作業はPCと接続していない状態で行ってください。

![画像を添付](img/) 

リセットスイッチを押しながらメインボードをPCと接続しRPI-RP2ドライブとして認識されることを確認したら、そのまま接続を解除してください。  

> [!NOTE]
> うまくはんだ付けされない場合は飛ばしても使用には差支えありません。  

![画像を添付](img/) 

### 1Uと2Uを選ぶ
この2か所は1Uキーか2Uキーかを選んで組み立てることができます。  
![画像を添付](img/) 
今回はすべて1Uキーで組み立てます。取り付けるキーに合わせて2か所のジャンパーを短絡してください。  
![画像を添付](img/) 

### （オプション）LEDのはんだ付け
LEDの足の角とシルク印刷を合わせてはんだ付けします。      
![画像を添付](img/) 

選んだ1Uと2UどちらかのLEDのみ取り付けてください。  
![画像を添付](img/) 

半田付けが終わったら発光を確認します。  

### MXスイッチソケットのはんだ付け
スイッチソケットをはんだ付けします。  
![画像を添付](img/) 

### センサーのはんだ付け
センサーの丸印とシルク印刷を合わせて表ではんだ付けします。  
![画像を添付](img/) 

保護フィルムをはがし、レンズを乗せた状態でPCと接続します。  
![画像を添付](img/) 
手をかざす等してマウスカーソルが動くことを確認してください。  

センサーの動作を確認したらレンズを取り付けて裏面でレンズの足をはんだごてで押しつぶして固定します。  
![画像を添付](img/) 

### （オプション）スタビライザーの取り付け
2Uキーを使う場合は2Uスタビライザーを使うことができます。
![画像を添付](img/) 

### キースイッチの取り付け
メインボードにスイッチプレートを重ねてキースイッチを付けます。
![画像を添付](img/) 

はんだ付けをしていないキー以外が反応することを確認したら、残ったキーをはんだ付けして動作を確認します。
![画像を添付](img/) 

### Poronスポンジシートの貼り付け
スイッチプレートの表面にPoronスポンジシート（白）、裏面にPoronスポンジシート（黒）を貼ります。
![画像を添付](img/) 
センサーの横にも1枚Poronスポンジシート（黒）を貼るところがあります。
![画像を添付](img/) 

### トラックボール支柱の組み立て
34mm用と25mm用を選んで組み立てます。
![画像を添付](img/) 
今回は34mmボールを使います。

M2なべねじ（長）9本にM2ワッシャーを通します。
![画像を添付](img/) 

M2なべねじ（長）でトラックボール支柱にM2スペーサー（短）を取り付けます。
![画像を添付](img/) 

反対側にもトラックボール支柱を付けてM2ワッシャー、M2スプリングワッシャー、M2ナットの順で止めます。
![画像を添付](img/) 

3本のネジにベアリングを通し切れ込みに引っ掛け、M2ワッシャー、M2スプリングワッシャー、M2ナットの順で止めます。
![画像を添付](img/) 

### トラックボール支柱の取り付け
M3角ナットをトラックボール支柱のスリットに入れてメインボードに立てます。
![画像を添付](img/) 

M3角ナットがずれないように気を付けながら裏からM3なべねじで止めます。
![画像を添付](img/) 

ボールを入れてトラックボールの動きを確認したらPCに接続して動作も確認します。
![画像を添付](img/) 

> [!NOTE] 
> ボールにガタ付きがある場合はベアリングの隣に1枚ワッシャーを挟むと改善することがあります。
> ![画像を添付](img/)
> この場合ねじを締めすぎるとベアリングが回転しないので調節してください。 


### ファームウェアの更新
こちらのuf2ファイルをダウンロードしてください。
-  !URL!

一度USBケーブルを外し、画像に示したキーを押しながらPCに接続してしばらく待つとRPI-RP2ドライブが出てきます。  
![画像を添付](img/) 
うまくいかない場合はリセットスイッチを押しながらUSBケーブルを差しこんでください。  

RPI-RP2ドライブにダウンロードしたuf2ファイルをドラッグアンドドロップしたらファームウェアの更新完了です。  


### ケースの組み立て
前面のねじは外した状態でケースを裏返します。
![画像を添付](img/) 

底になるプレートをスペーサーごと引き抜き、スペーサーを取り除いて保護フィルムをはがします。
![画像を添付](img/) 

スペーサーを付けなおしゴム足を貼ります。
![画像を添付](img/) 

ここにM2スペーサー（小）をM2なべねじ（短）で取り付けます。
![画像を添付](img/) 

アクリルプレート（小）を乗せてM2なべねじ（短）で止めます。
![画像を添付](img/) 

1枚ずつ保護フィルムをはがして載せていきます。2枚は同じ形状が続きます。
![画像を添付](img/) 
![画像を添付](img/) 
2枚の大きくくり抜かれたプレートは同じ形状で、どちらかを色付きプレートと交換することが可能です。
![画像を添付](img/) 
![画像を添付](img/) 
ここまで乗せたらメインボードを乗せます。
![画像を添付](img/) 
スペーサー用の穴が開いたプレートと、ねじ用の小さい穴が開いたプレートを乗せます。
![画像を添付](img/) 
![画像を添付](img/) 
M2トラスねじで止めたら完成です。お好みで中央付近にゴム足を増やしてください。
![画像を添付](img/) 

USBケーブルを差し込んで全体的に動作を確認してみてください。

## キーのカスタマイズ
### Remapへの接続
Google Chrome（もしくはChromiumベースのブラウザ）でRemapにアクセスしてください。
- !URL!

青いボタンを押してUndertowを選ぶと接続できます。
![画像を添付](img/) 

### 保存と復元

### 形の変更

### キーの割り当て
下の一覧からを上のキーにドラッグアンドドロップするとキー設定を変更することができます。
![画像を添付](img/)

### 特殊なキーの割り当て
FUNCTIONSタブのVIA USER KEYにOSに関わらず使えるショートカットやトラックボール、OLEDなどの設定をするキーがあります。

### LEDの調整




















