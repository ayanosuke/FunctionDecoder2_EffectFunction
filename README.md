# Arduino_SmileFunctionDecoder2 for Effect Function<br>
SmileFunctionDecoder2 (AYA002-2)用のエフェクトファンクッションデコーダスケッチです。
多種点灯パターンを用意しました。
<br>
デフォルトのアドレス3
O1:F1 でON/OFF
O2:F2 でON/OFF
O3:F3 でON/OFF
O4:ヘッドライト F0でON/OFF F4でFX 効果切り替え

LightMes()関数搭載(^^;
ATtiny85デコーダはシリアルピンが無いため、Atiny85 PB0(5pin):O1を使って、
変数の値を光で確認できます。
※出力ポートはO1,O2,O3,O4のいづれかに変更できます。
※アドレス書きかえ時に影響あるところに入れるとアドレス変更に失敗します。
※CV49の書き換えでFX効果を切り替えたいのですが、なぜかうまく動かない。