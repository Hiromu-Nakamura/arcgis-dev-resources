バージョン 4.x の API は、新しい機能（例えば、3D サポート、マップの回転、ポータル連携の強化等）が追加されています。しかし、バージョン 4.x の最初のリリースには、バージョン 3.x の全ての機能が含まれていません。今後のリリースでは、バージョン 3.x と同等の機能、また、3.x を上回る多くの機能が追加される予定です。開発者はアプリケーションの要件を考慮して、必要な機能が現在のバージョン 4.x もしくは 3.x に実装されているかどうかを判断する必要があります。

本トピックでは 3.x の API で作成した既存のアプリケーションを 4.x に移行するために必要な情報を解説します。API で更新された仕様はいくつかありますが、その中でも重要な項目について紹介します。

* アプリケーションで、3D 表示が必要な場合は、バージョン 4.x を使用してください
* アプリケーションで、編集のようなバージョン 4.x でまだ利用できない機能が必要な場合は、バージョン 3.x を使用してください

|機能|3.20|4.3|
|:--|:--|:--|
|3D 表示|×|○|
|2D 表示|○|○（部分的なサポート）|
|ベクター タイル レイヤー|○|○|
|ラスター タイル レイヤー|○|○|
|イメージ レイヤー|○|○|
|マップ イメージ レイヤー（ダイナミック レイヤー）|○|○|
|フィーチャ レイヤー|○|○（現バージョンでは表示とクエリのみ対応）|
|ジオメトリ エンジン|○|○|
|Web シーン|×|○|
|Web マップ|○|○（部分的なサポート）|
|ポータル アイテムのレイヤーの直接参照|×|○（部分的なサポート）|
|編集と図形描画|○|○（部分的なサポート）|
|時系列データ|○|×（今後のバージョンで対応予定）|
|OGC レイヤー（WMS、WMTS、WFS、KML）|○|×（今後のバージョンで対応予定）|
|印刷|○|○|
|GIS 機能ウィジェット（解析、ルート案内、計測）|○|×（今後のバージョンで対応予定）|

全機能の比較は <a href="https://developers.arcgis.com/javascript/latest/guide/functionality-matrix/index.html" target="_blank">3.x/4.x 機能比較表（英語）</a>を参照してください。