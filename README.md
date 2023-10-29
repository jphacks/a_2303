# Umap
<img width="746" alt="image" src="https://github.com/jphacks/SP_2303/assets/81278726/85c804bf-4fb7-4d0e-8d46-4f0253084cd9">


## APKファイル配布
Androidで実行可能なAPKファイルを配布しています。
以下のリンクからダウンロードしてください。

- ダウンロード期日：11/3 23:59まで
- 推奨動作環境：Android 7.0以上
https://62.gigafile.nu/1103-ce21b31a0add1f66dc6eb9c0c59baf4d5

## 製品概要
### 背景(製品開発のきっかけ、課題等）
外食をするときに、行きたいお店を忘れてしまったり、新しいお店に行きたいと思いながらも結局いつものお店を選択してしまっているときがあります。そんなときに、外食をサポートしてくれるアプリがあれば良いなと思いました。このような背景があって、外食 × Techの開発を始めました。


### 製品説明（具体的な製品の説明）
「外食をより楽しく、便利に！」をコンセプトとした 外食 × Tech のモバイルアプリケーションです。

### 特長
#### 1. ご飯マップ作成機能
白紙のマップに自分のピンが刺さって、広がっていく様子を楽しむことができます。


#### 2. Swipe UI
これまでは「お店を探す」という作業は文字ベースで展開されてきました。お店の名前で検索したり、地図上で店名をタップしてからでないとどんな料理かわかりません。その点に注目した私たちは、マッチングアプリのように画像ベースでお店を選択できるようなUIを考案、実装しました。


#### 3. キャラクター育成機能
Swipe UIの実現のためには画像の投稿をしてもらうことが必須になることから、その操作を実行してもらえるように他にモチベーションを用意する必要があり、育成機能を実装しました。キャラクターの画像には3DCGと特殊なテクスチャを用いており、アニメ調の見た目でありながら柔らかさを表現しています。

<p align="center">
<div style="display:flex">
  <img style="flex-grow:1" src="https://github.com/jphacks/SP_2303/assets/81278726/ea0954dd-4a6a-43c3-846e-d13cef94e300" width="30%">
  <img style="flex-grow:1" src="https://github.com/jphacks/SP_2303/assets/81278726/95c5bae0-3279-4157-9bad-22976b46561f" width="30%">
  <img style="flex-grow:1" src="https://github.com/jphacks/SP_2303/assets/81278726/b8849999-623c-4b1c-81de-1f9b389f51d4" width="30%">
</div>
</p>


### 解決出来ること
外食では、``「お店を探す」→「食べる」→「記録・共有する」→「振り返る」``という手順を踏んでいます。上記の機能を用いることで、このサイクルの中でも特に「お店を探す」「記録・共有する」「振り返る」をより楽しく便利にすることができます。


![](https://hackmd.io/_uploads/rkWbDwjMa.png)

### 今後の展望
- アプリ内での共有機能追加
- データを全てバックエンドで管理
- キャラクターの動きのレパートリーの追加

### 注力したこと（こだわり等）
* 地図上のピン、アイコンの自作
* 3DCGキャラクターのアニメ調の見た目の再現

### 開発技術
<img width="879" alt="image" src="https://github.com/jphacks/SP_2303/assets/63779824/e0926bff-bea7-48ce-87fd-3833a6457d8c">

### 活用した技術
- Flutter
- Python
- Firebase Authentication
- Blender

#### API・データ
* Google Map API

#### フレームワーク・ライブラリ・モジュール
* Fast API

#### デバイス
* iPhone, Android

### 独自技術
#### ハッカソンで開発した独自機能・技術
* 独自で開発したものの内容をこちらに記載してください
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください。
