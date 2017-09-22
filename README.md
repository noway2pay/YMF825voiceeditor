# YMF825voiceeditor

YMF825 voice editor arduino , VT100ターミナルで動作する YMF825用ボイスエディタ　スケッチです 
※2017/9/22 修正アップデートしました

YMF825 boardとArduino用に配線が必要です 下記を参照下さい

https://yamaha-webmusic.github.io/ymf825board/intro/

ScreenFMEdit.ino ymf825cont.ino 2つのファイルをArduino IDEで読み込んでスケッチを書き込んでください。

・使い方

TeraTerm等VT100対応の端末ソフトで接続して下さい。

2017/9/22 音色データのインポート/エクスポート機能を付けました。データ形式はカラム数30のcsv一行のデータになります

例: 

1,133,0,123,249,67,0,32,64,0,163,166,14,3,16,0,0,44,249,155,0,32,65,0,163,166,14,1,16,64,


キー操作

     '+'　　パラメータ値インクリメント

     '-'　　パラメータ値デクリメント
 
     CR　　再描画
 
     'p'　テスト演奏 (何かキーを押すと中断)

     's'　音色をEEPROMへ保存 保存数最大１６音

     'l'　音色をEEPROMから読込

     'd'　音色データをcsvダンプ
     
     'i' csv形式音色データをインポート
     
     
