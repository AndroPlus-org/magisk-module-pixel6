## Google Pixel 6 Pro 用パッチ

Google Pixel 6 Pro にて

* カメラシャッター音の強制を無効化
* USB ケーブル接続時に画面がオンにならないよう変更
* カラー調整にビビッドを追加 (※画面が乱れる場合あり)
* 電源メニューから緊急通報や機内モードを削除
* SoftBank SIM でのテザリング制限解除 (動作未確認)
* ステータスバーのバッテリーアイコンを非表示に変更
* ナビゲーションバーのバーを非表示に変更
* 壁紙のズームを無効化

をする Magisk モジュールです。  
必要ないものがあれば overlay フォルダにある apk を削除するかデコンパイルして編集してください。

Google Pixel 6 Pro で動作確認済みですが、Pixel 6でも動作すると思います。

## 更新履歴

#### v5
* Android 13 に対応

#### v4
* SystemUI の Overlay を機能毎に分割  
  (ナビバーの余白をなくしたければ optional フォルダの apk を system/product/overlay に入れてください)

#### v3
* ステータスバーのバッテリーアイコンを非表示に変更
* 誤反応が多くなるのでナビゲーションバーのスペースを広げてバーは非表示に変更

#### v2
* カラー調整にビビッドを追加

#### v1
* リリース

## ライセンス

- [WTFPL](http://www.wtfpl.net/)

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```