## RPi-CM3MB2-PoE / RPi-CM3MB2L-PoEのハードウェア仕様
|||
|:-----|:-----|
|名称| Raspberry Pi CM3キャリアボード<br>※RPi-CM3MB2L-PoEは Raspberry Pi CM3 キャリアボード CM3Lite バンドル版|
|型番|RPi-CM3MB2-PoE<br>RPi-CM3MB2L-PoE（CM3Liteバンドル版）|
|対応 Raspberry Pi|Raspberry Pi Compute Module 3<br>Raspberry Pi Compute Module 3 Lite|
|LED|[電源LED]<br>　　緑点灯 電源ON<br>　　緑点滅 0.3秒間隔 / シャットダウン中<br>　　緑点滅 1.0秒間隔 / 充電中（電源ON時）<br>　　赤点灯 バッテリー要充電<br>　　赤点滅 1.0秒間隔 / 充電中（電源OFF時） <br>[ステータスLED]<br>　　緑点滅 システムアクセス中<br>[シャットダウンLED]<br>　　緑点灯 シャットダウンプロセス実行中|
|RTC|搭載（CR2032電池よりバックアップ）|
|電源スイッチ|電源 ON /OFF ボタン|
|電源電圧|DC +12V/3A ※DCジャックまたは2ピンXHコネクタより供給<br>適合プラグ：センタープラス 12V/3A<br>　　　　　　　　フォーク(音叉)型DCプラグ（径5.5mm 内径2.1mm） |
|消費電流|DC12V/ 220mA (スタンバイ時)、540ｍA ( 4コア100%負荷時)<br>(USB 2A負荷時は1000mA 加算、Li-ion電池充電中は最大530mA加算)|
|動作環境|温度：0～40℃、湿度：20～80%（ただし結露しないこと）|
|基板寸法|RPi-CM3MB2(L) 約 166mm x 112mm|
|重量|約208g ※CR2032電池、CM3Liteを含む。|
|適合ケース|CM3MB2シリーズ：タカチ電機工業<br>PF18-4-12、PF18-5-12（HAT拡張基板も組込可能）|
|I/O 端子|[microSDスロット]<br>　　※Compute Module Lite (eMMCなしモデル)使用時のみシステムドライブとして使用可能<br>[HDMI出力]<br>　　HDMI Std. Aコネクタ<br>　　※Raspberry Piの仕様により最大1080p/60Hzまで<br>[USBホスト]<br>　　USB Type A x3（フロント x1, リア x2）<br>　　ピンヘッダー x1（拡張GPIOコネクタ）<br>　　※USB2.0 HighSpeed対応<br>[イーサネット]<br>　　100BASE-TX対応 RJ45<br>　　PoE Class 4（48V/25.5W)対応<br>　　※PoE 給電対応ハブに接続する必要があります。<br>[GPIO]<br>　　HAT仕様準拠40ピン ピンヘッダー<br>　　拡張 8ピン ピンヘッダー|
|Li-ionバッテリー|18650タイプ（保護機能付き）<br> 3.7V 2600mAh (もしくは互換品)<br><br>■ 電池残量<br>約40%未満 -- 要充電(電源LEDが赤点灯)<br>約20%未満 -- シャットダウンを実行(電源ボタンを長押した場合と同じ)<br>※周囲温度が25℃の場合。<br><br>■ 使用時間(満充電状態から自動シャットダウンまでの時間<br>約2時間<br>※周囲温度が25℃で、動画を連続再生した場合。<br><br>■ 充電時間(電池切れ状態で充電し、自動起動から充電完了までの時間)<br>約2.5時間<br>※周囲温度が25℃で、動画を連続再生した場合。|
|パッケージ内容|RPi-CM3MB2-PoE 本体 x1<br>CR2032電池（RTCバックアップ用）<br>補足文書 x1<br>保証書 x1<br>Raspberry Pi Compute Module 3 Lite ※RPi-CM3MB2L-PoEのみ|
|生産|日本|
|保証期間|1年|
