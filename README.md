# Basic_S AviUtl ExEdit2 スクリプト

汎用的な基本効果や基本図形などをまとめた AviUtl ExEdit2 用のスクリプト集です．丸角四角形の生成や斜め軸での回転，回転中心のマウス操作移動や傾斜変形，内側シャドウや内側縁取りなどができます．

[ダウンロードはこちら．](https://github.com/sigma-axis/aviutl2_script_Basic_S/releases) [紹介動画．](https://www.nicovideo.jp/watch/sm45523651
)

##  動作要件

- AviUtl ExEdit2

  http://spring-fragrance.mints.ne.jp/aviutl

  - `beta15` で動作確認済み．

## 導入方法

以下のフォルダのいずれかに `Basic_S.anm2` と `Basic_S.obj2` をコピーしてください．

1.  スクリプトフォルダ
    - AviUtl2 のメニューの「その他」 :arrow_right: 「アプリケーションデータ」 :arrow_right: 「スクリプトフォルダ」で表示されます．
1.  (1) のフォルダにある任意の名前のフォルダ

初期状態だと「オブジェクトを追加」や「フィルタ効果を追加」メニューの「Basic_S」以下に各種オブジェクトやフィルタ効果が追加されています．
- 「オブジェクト追加メニューの設定」の「ラベル」項目で分類を変更できます．

##  詳しい解説について

[Wiki](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki) に順次掲載していく予定です．

パラメタインジェクション (`PI`) 経由でのみ指定・調整できる項目もあります．

##  追加されるオブジェクト

### 角丸矩形

<img width="720" height="480" alt="Various corner shapes." src="https://github.com/user-attachments/assets/1f8760e0-90ce-4eb6-817d-6d0b51ee449a" />

長方形や丸角四角形を生成します．縦横をピクセル単位で指定でき，上下左右揃えの指定もできます．

丸角の形状も複数種類から選べ，半径や縦横比も角ごとに独立に指定することもできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/角丸矩形)

### 楕円

<img width="320" height="240" alt="Sample of an ellipse shape" src="https://github.com/user-attachments/assets/3a2ace4b-c95f-45e6-ae4d-2564f4d60006" />

標準図形の「円」を，縦横をピクセル単位で指定できるようにしたものです．上下左右揃えの指定もできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/楕円)

### 菱形

<img width="320" height="240" alt="Sample of a rhombus shape" src="https://github.com/user-attachments/assets/057750a3-5043-43c1-b9c6-6773f73c432f" />

菱形を生成します．縦横をピクセル単位で指定でき，上下左右揃えの指定もできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/菱形)

### スーパー楕円

<img width="720" height="480" alt="Samples of various superellipses" src="https://github.com/user-attachments/assets/b22c54bc-9a4e-41fa-9b16-039a0e2e055d" />

[スーパー楕円](https://ja.wikipedia.org/wiki/スーパー楕円)を生成します．[アステロイド](https://ja.wikipedia.org/wiki/アステロイド_(曲線))や菱形などもこの特殊形です．

縦横をピクセル単位で指定でき，上下左右揃えの指定もできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/スーパー楕円)

##  追加されるフィルタ効果

### 四隅丸め

<img width="640" height="240" alt="Two samples of rounded corners" src="https://github.com/user-attachments/assets/04ba5c33-7286-48ef-9431-c042d25abd50" />

オブジェクトの四隅を円などの図形で丸めます．

角の形状も複数種類から選べ，半径や縦横比も角ごとに独立に指定することもできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/四隅丸め)

### 背景角丸矩形

<img width="360" height="120" alt="Sample of a round rect background" src="https://github.com/user-attachments/assets/d80d9d36-268e-4a56-a00a-39596c80e577" />

オブジェクトの背景に角丸矩形を配置します．テロップバックや立ち絵の背景などに利用できます．

色を指定する代わりにパターン画像を指定することもできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/背景角丸矩形)

### 背景楕円

<img width="360" height="120" alt="Sample of an ellipse background" src="https://github.com/user-attachments/assets/1400898a-c474-41ac-862d-75fbf92fc9b1" />

オブジェクトの背景に楕円を配置します．吹き出しやアイコンの背景などに利用できます．

色を指定する代わりにパターン画像を指定することもできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/背景楕円)

### 背景菱形

<img width="560" height="120" alt="Sample of a rhombus background" src="https://github.com/user-attachments/assets/5e1999b9-dcd5-4751-8cec-c1d1712eae63" />

オブジェクトの背景に菱形を配置します．吹き出しやアイコンの背景などに利用できます．

色を指定する代わりにパターン画像を指定することもできます．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/背景菱形)

### 透明度適用

オブジェクトの各ピクセルを指定した分だけ半透明化します．標準のフィルタ効果の「透明度」とは異なり，後続のフィルタ効果に影響する形で透明度を指定します．

> [!NOTE]
> 標準のフィルタ効果の「透明度」の効果が適用されるのは最後にフレームバッファに描画されるタイミングで，全てのフィルタ効果が適用された後です．内部的な「後に適用される透明度の数値」を操作しているだけなので高速な反面，後続のフィルタ効果 (標準描画など以外) にはまず影響しません．
>
> 「縁取り」や「反転」の「透明度反転」など一部のフィルタ効果に対して，半透明化したピクセルを意図して処理させたい場合には「透明度適用」が効果的です．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/透明度適用)

### 透明度二値化

透明度を二値化します．ぼかしの境界を明確にしたい場合などに利用できます．

正確には二値化ではなく，「一定のしきい値よりも透明なら完全透明，また別のしきい値よりも不透明なら完全不透明，その間は線形に補間」という処理を行います．従って半透明になる「ぼかし幅」があります．

:arrow_right: [\[詳細\]](https://github.com/sigma-axis/aviutl2_script_Basic_S/wiki/透明度二値化)

### 色調補正

標準の「色調補正」の機能追加版です．標準で利用されている YUV ([BT.601](https://ja.wikipedia.org/wiki/YUV)) 以外に [HSV](https://ja.wikipedia.org/wiki/HSV色空間) や [HSL](https://ja.wikipedia.org/wiki/HLS色空間), XYZ ([sRGB 規準](https://ja.wikipedia.org/wiki/SRGB)) などでの色調補正ができます．

> [!NOTE]
> XYZ や YUV での「色相」はそれぞれ，XZ-平面と UV-平面の偏角を操作するものですが，これらには光学的，視覚心理学的に有意義な意味合いはありません．便宜上の実装と捉えてください．
>
> 特に XYZ 色空間に関しては偏角操作などの便宜上，白点を XZ-平面の原点に対応させるなど内部的な色変換行列にも手を加えていて，独自性が強いことを付記しておきます．

### 回転中心

オブジェクトの回転中心を変更します．標準のフィルタ効果の「座標」の回転中心版です．

### 回転中心アンカー指定

オブジェクトの回転中心を，アンカーによるマウス操作で移動できます．ここで変更した回転中心は，後続のフィルタ効果にのみ影響します．

### 上下左右揃え

オブジェクトの回転中心を，上下左右の端や中央に合わせます．後続フィルタで拡大縮小した場合，指定した中心を基準に拡大縮小するようになり，他オブジェクト間のレイアウトを揃えやすくなります．

### 直角回転

AviUtl (無印) にあったフィルタ効果の「ローテーション」の類似物です．90°単位に画像を開店します．標準のフィルタ効果の「回転」とは異なり，後続フィルタに影響します．

回転以外にも上下や左右に反転，斜め軸の反転など 8 種類 ($=\\#D_4$ [(二面体群)](https://ja.wikipedia.org/wiki/二面体群))の配置ができます．

> [!NOTE]
> 標準のフィルタ効果の「回転」の効果が適用されるのは最後にフレームバッファに描画されるタイミングで，全てのフィルタ効果が適用された後です．内部的な「後に適用される回転角度の数値」を操作しているだけなので高速な反面，後続のフィルタ効果 (標準描画など以外) にはまず影響しません．
>
> 「ドロップシャドウ」や「凸エッジ」など一部のフィルタ効果に対して，回転角度を影響させたい場合には「直角回転」が効果的です．

### XYZ追加回転

標準のフィルタ効果の「回転」とは異なり，常に画面を基準とした X, Y, Z 軸の回転をします．「描画する」でオブジェクトの回転結果を後続のフィルタ効果に影響させられるようにもなります．

> [!NOTE]
> 標準のフィルタ効果の「回転」は，それまでに適用された回転角度に加算する形で計算されているため，回転軸が現在の回転角度によって変わります．一方で「XYZ追加回転」は常に画面を基準とした X, Y, Z 軸で回転します．
>
> 加えて標準のフィルタ効果の「回転」の効果が適用されるのは最後にフレームバッファに描画されるタイミングで，全てのフィルタ効果が適用された後です．後続のフィルタ効果 (標準描画など以外) にはまず影響しません．「描画する」を ON にした場合，このフィルタ効果の時点で回転の効果が適用され，後続のフィルタ効果にも影響を与えられます．

### 任意軸追加回転

https://github.com/user-attachments/assets/8a0d6595-605f-49c5-9e05-739963d9c63a

アンカーで指定したラインに沿った軸でオブジェクトを立体回転させます．軸指定がアンカーな点以外は[XYZ追加回転](#xyz追加回転)と同様です．

### 傾斜

![Demo of slant effect](https://github.com/user-attachments/assets/a9b55ccf-0dc7-4404-9624-cb3085424d21)

アンカーで指定した軸に沿った傾斜変形をします．傾斜量は角度と傾き (角度の $\tan$ 値) で指定できます (両方指定した場合は，傾きとしての和を適用).

### XY軸変形

https://github.com/user-attachments/assets/146133cf-f82f-4bc9-82ff-5dfc1b7d86d8

X, Y 軸方向に伸びたアンカーをマウス操作することで変形します．

### 領域サイズ変更

標準のフィルタ効果の「クリッピング」と「領域拡張」を併せたフィルタ効果です．正の指定値で領域拡張，負の指定値でクリッピングの効果になります．

「領域拡張」にはない「中心の位置を変更」のオプションもあります．

- [領域サイズ指定](#領域サイズ指定)と名前が似ているので注意．

### 領域割合サイズ変更

[領域サイズ変更](#領域サイズ変更)の割合指定版です．ピクセル数単位ではなく，左右の値はオブジェクトの幅からの割合で，上下の値はオブジェクトの高さからの割合でそれぞれ指定します．

### 領域サイズ指定

指定した位置とサイズでオブジェクトをクリッピング，必要なら領域拡張をします．

予め切り取りたいサイズがわかっている場合に，アンカー操作で位置を指定して切り抜きするなどに便利です．

- [領域サイズ変更](#領域サイズ変更)と名前が似ているので注意．

### カットずらし

https://github.com/user-attachments/assets/6fc13047-fde8-4ec9-8984-2083661129f2

アンカーで指定したラインでオブジェクトを切り取って，ずらして配置します．ずらす移動量や方向もアンカーで操作できます．

### 中抜きクリッピング

<img width="520" height="360" alt="Sample of midrange crop" src="https://github.com/user-attachments/assets/bce76075-2c82-40cc-919b-3a3442f09c8b" />

「クリッピング」や「領域拡張」に相当する操作を，オブジェクトの端ではなく中間部分で行います．大きな図表の中間部分を切り取って詰めたい場合に利用できます．

### 小数ぼかし

標準の「ぼかし」とは異なり，小数点以下のピクセル数の精度で画像をぼかします．AviUtl 標準の「ぼかし」にあった，小さい奇数ピクセルでの不具合も修正しています．

> [!NOTE]
> 標準の「ぼかし」には，奇数ピクセルを指定した場合の重み分布が正確な三角分布にはならない不具合があります．AviUtl (無印) でも同様の挙動です．
>
> 例えば 1 ピクセルのぼかしの場合，正確な三角分布は “25%, 50%, 25%” ですが，AviUtl 標準の「ぼかし」だと “33.3%, 33.3%, 33.3%” という分布になっています．3 ピクセルの場合だと，正確な分布 “6.25%, 12.5%, 18.75%, 25%, 18.75%, 12.5%, 6.25%” に対して “6.67%, 13.3%, 20%, 20%, 20%, 13.3%, 6.67%”.

### 縁取りα

標準の「縁取り」に透明度を指定したり，中をくり抜いて縁だけにしたり，内側縁取りもできるようになります．縁部分にパターン画像の指定も可能．

### 四角縁取り

<img width="480" height="240" alt="Comparison of ordinary borders and rectangle borders" src="https://github.com/user-attachments/assets/b11ad429-a8b2-4d9f-89bb-e71ae4044974" />

AviUtl (無印) の「縁取り」と同様，角が四角になる縁取りです．特に長方形に対して縁取りをする場合などは，こちらのほうがいい場面もあると思います．

[縁取りα](#縁取りα)と同様，透明度の指定や内側縁取りなども可能です．

### 内側シャドウ

<img width="280" height="280" alt="Sample of inner shadow effect" src="https://github.com/user-attachments/assets/e93b5e4f-a43e-416c-9341-db0b2df02950" />

オブジェクト自身に外側から影が落ちているような効果を描画します．パターン画像や合成モードの指定もできます．

##  既知の問題

1.  [スーパー楕円](#スーパー楕円)のライン幅には標準の「縁取り」を利用していますが，これは 500 ピクセルサイズが限界のため，スーパー楕円のライン幅も最大で 500 ピクセルしか描画されません．

1.  [スーパー楕円](#スーパー楕円)で「膨らみ」が小さい ($\approx -150$ 以下) の場合，サイズが偶数ピクセルか奇数ピクセルかで尖点部分の見え方が大きく変わります．サイズを連続して動かす場合は，ちらつきの原因となるので注意．

1.  [小数ぼかし](#小数ぼかし)の「光の強さ」の影響は，標準の「ぼかし」のものとは異なります．このスクリプトでは AviUtl (無印) のフィルタ効果の「ぼかし」での計算式を使用していますが，AviUtl2 での計算式とは異なるらしく，それが不明なため完全再現とはなっていません．


## 改版履歴

- **v1.00 (for beta15)** (2025-10-16)

  - 初版．


## ライセンス

このプログラムの利用・改変・再頒布等に関しては MIT ライセンスに従うものとします．

---

The MIT License (MIT)

Copyright (C) 2025 sigma-axis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

https://mit-license.org/


#  連絡・バグ報告

- GitHub: https://github.com/sigma-axis
- Twitter: https://x.com/sigma_axis
- nicovideo: https://www.nicovideo.jp/user/51492481
- Misskey.io: https://misskey.io/@sigma_axis
- Bluesky: https://bsky.app/profile/sigma-axis.bsky.social
