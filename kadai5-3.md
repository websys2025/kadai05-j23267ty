## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能：日本国内の郵便番号から住所情報（都道府県、市区町村、町域）を取得するAPI。
* リクエストとレスポンスのフォーマット：リクエスト：HTTP GETパラメータ：zipcode（必須）: 郵便番号（半角数字7桁、ハイフンなし）
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL：API名称：OpenWeatherMap API、参照URL：https://openweathermap.org/api
* エンドポイントと機能：エンドポイント：https://api.openweathermap.org/data/2.5/weather、機能：都市名や地理座標から現在の天気情報（温度、湿度、天気、風速など）を取得するAPI。
* リクエストとレスポンスのフォーマット
リクエスト：HTTP GET
パラメータ：q（必須）: 都市名（例：Tokyo）
appid（必須）: APIキー
units（任意）: 温度単位（例：metricで摂氏）
### Q3-3. 感想
* 今回の課題で苦労したこと：JSON形式のレスポンスから必要な情報を抽出する部分に手間取った。
* 演習を通して理解できたこと：APIの基本的な仕組みやリクエスト・レスポンスの形式について理解が深まった。
* Web APIの利便性や課題など：APIは他のシステムと連携するのに非常に便利であるが、トラフィック制限や認証が必要な場合も多く、効率的な設計が求められる。


