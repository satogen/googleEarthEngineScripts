## Google Earth Engine Python APIを用いたスクリプト

### グリッド状のものから画像をダウンロード
- grid_img_downloader.ipynb

### 月ごとに温度データをCSVファイルとしてダウンロード
- GEE_temp_downloader.ipynb

下記を任意のポリゴンデータにすれば、実行できます
```
world_data = ee.FeatureCollection("users/halogen322/world_countries")
```
### ポイントを中心としてポリゴンを作成し画像をダウンロード

#### 画像をダウンロード
- data_export.ipynb

#### ダウンロードした画像を描画
- datashow.ipynb
