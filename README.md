# LUMEN — Drone Show

Three.jsによる、200個の光点で文字・絵文字を描くドローンショーです。

## 使い方

`index.html` をブラウザで開きます。サーバーやネット接続は不要です。

- 最大10文字の文字列を入力し「ショーを作成」で開始
- 各文字を順番に表示し、立体回転・移動・展開で切り替え
- 光点の位置・色・明るさが緩やかに変化
- 映像をクリックして全画面表示、再クリックまたはEscで終了
- BGMチェックボックスでオリジナルの72秒ループ曲をオン・オフ
- 「最初から」で映像とBGMを先頭に戻す

Three.js本体、スタイル、スクリプト、音楽生成処理はすべてHTMLに含まれています。絵文字の形は端末のフォントに依存します。WebGLとWeb Audioに対応したブラウザが必要です。

GitHub Pages: https://kagoya.github.io/droneshow/

## Third-party software

Three.js r170 is included under the MIT License. See `THIRD_PARTY_NOTICES.md`.
