

## 20160516

Safari ではブラウザ組み込みのカラーピッキングが仮に最新バージョンでもできないようで、パラレルコーディネートに使っている density 用のカラーピッカーが役に立たなくなるので、以下のライブラリを使って拡張する

http://jscolor.com/download/

こちらはふつうに IE などでも使えるようになっているみたいで、機能的にも十分に使える。


## 20160517

firefox でテスト。
minmax 指定した場合の選択レイヤの挙動がおかしい。


## 20160620

新しい実装

### 動画
https://www.youtube.com/watch?v=VK9YbphYg4I

### インタラクション
必要となるインタラクション、PDF で言及されているインタラクションの全てというのが何を指しているか。

### 外見
これそもそも WebGL 使う必要がないのではないか疑惑
Canvas2D で行えるのなら、それでもいいのではないか

### キーワードについて調べておく

* 回帰分析
* クラスタリング ← データをまとめて大きな塊にする
* 分散メモリ

ベジェ曲線的なもので曲線を描いているのか、アルゴリズムを利用することで自然とこういうフォルムになるのかわからない。


### 要件

* WebGL 必須ではないが、エフェクトにシェーダとかあったほうが便利っぽいからひとまず WebGL でやる
* クラスタリングしたデータが、どのようなパラメータを持っていればいいのか、そのインタフェースを設計する
* 恐らく JSON などでデータが流れてくるのでそれを描画する仕組みを考える
* データ構造を検討する







