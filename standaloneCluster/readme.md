
## parallel

parallel.js


## about

parallel.js に機能を追加して、スタンドアロン版でも React on HIVE でも同じように動作するように調整する方針で実装。

SVG に当たるスタイルなど微妙にルールが違っている部分があるようだが、ソースコードは同じものを使えるように調整する。


## TODO

* ファイルの入力を受ける口を作って HIVE 版でノード経由でファイルを渡せるようにする
* 軸のスケーリング（これはビュー的なものなので not on store）
* 軸の入れ替え（入れ替え時は再度リクエストする）
* データを出力するインターフェースを作る
* HIVE 版ではこれを input へ、スタンドアロンの場合は JSON としてどこかに吐き出すようにする
* 

## 実装済み

* GLSL ベースでのベジェ曲線描画（TRIANGLE_STRIP）
* ベジェ曲線ポリゴンの幅を変更可能
* SVG による軸、軸タイトル、軸目盛、目盛のキャプションの描画
* 軸タイトル部分のドラッグで軸をドラッグすることが可能
* Canvas 内部の余白、フォントサイズなどを自由に調整可能


