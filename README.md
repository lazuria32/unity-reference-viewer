# unity-reference-viewer

[**English**](README_EN.md)

Unity上でアセットの参照を検索し、ウィンドウ上に表示するツールです。  
(例：テクスチャを使用しているマテリアルを調べる)  
  
詳しい解説は[**こちら**](https://amagamina.jp/reference-viewer/)

## セットアップ

Unity2019.3.4f1またはUnity2020.1a21以降ならUnityプロジェクトの`Packages/manifest.json`のdepdendenciesセクションに次の行を追加できます。

```json
{
  "dependencies": {
    "jp.amagamina.reference-viewer": "https://github.com/ina-amagami/unity-reference-viewer.git?path=/Assets/Plugins/ReferenceViewer"
  }
}
```

## ライセンス条項

MITライセンス
https://opensource.org/licenses/mit-license.php  

コード内のライセンス表記を残して頂ければ自由に使用可能です。

Copyright (c) 2019 ina-amagami (ina@amagamina.jp)
