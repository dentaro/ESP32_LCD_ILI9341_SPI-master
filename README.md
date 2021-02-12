mgo-tecさんのライブラリを改造して利用させていただいています。

主な改造点
・HSPIとVSPIの両方の接続に使えるように、自動切換えに対応していますので、同じライブラリが使えます。
シューティングゲームなんかだと、HSPI接続の方が処理が速いようです。

今後はゲーム制作に特化した関数を増やしていこうと考えています。お楽しみに。
でんたろう拝

--以下はmgo-tecさんの情報です。    
  
# 【更新履歴】(Japanese)  
(1.27)  
- 新型M5Stack IPSディスプレイ自動認識に対応しました。  
- Disp_Rotation関数のパターンを増やした。  
- dispInversionOn関数、dispInversionOff関数を追加  
  
(1.26)  
- Brightness関数で使っている LEDC 関連を修正しました。  
  
(1.25)  
- 8x16 又は 16x16ビットマップフォント表示の背景色を指定できるように、クラスの引数を追加しました。  
- Draw_Pixel_65k_DotColor 関数が microSD カードと併用できなかったので、Draw_Pixel_65k_DotColor_sd 関数を追加しました。  
- その他、グラフィック描画関数が SD カードと併用できなかったので、修正しました。  
  
(1.23)  
Disp_Rotation 関数を追加。  
ディスプレイの縦置きに対応しました。  
その他、軽微な修正。  
  
(1.2)  
Scrolle_Inc_HVsizeUp_8x16_Font_DisplayOut関数を追加。  
これはフォントを１文字づつ読み込んでスクロールする関数です（メモリ節約のため、）。  
  
(1.1)  
引数 uint8_t txt_length を uint16_t txt_length に修正。  
  
The MIT License (MIT)  
  
MITライセンス  
Copyright (c) 2018 Mgo-tec  
  
My Blog:  
https://www.mgo-tec.com  
