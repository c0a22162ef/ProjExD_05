# ゲーム のタイトル
逆襲！エイリアン！

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターコウカトンを操作しクリアを目指す

## ゲームの実装
###共通基本機能
* ex04を共通の基盤とする

### 担当追加機能
* ゲームの終わり方の追加
* クリアを表示
* クリア後の分岐制作

### ToDo

- [✓] エンターキーを押された時に終了する（強制終了）
- [✓] scoreを超えたあとのクリア画像表示
- [✓] クリア後にエンターキーを押すと終了する
- [✓] クリア後にスペースキーを押すと継続する

### メモ
* Continueクラスを追加
* Finishクラスを追加
* クリア前とクリア後の判定に iを用いて判別
* 