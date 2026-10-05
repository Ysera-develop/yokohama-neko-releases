# ヨコハマ ねこ便り — Android試用版

横浜のお出かけ候補を探す「ヨコハマ ねこ便り」の配布用リポジトリです。

## インストール

1. [v1.8の配布ページ](https://github.com/Ysera-develop/yokohama-neko-releases/releases/tag/v1.8)を開き、`yokohama-neko-v1.8-debug.apk`をダウンロードしてください。
2. Android 7.0以降の端末でAPKを開き、Androidの確認画面に従ってインストールします。配布元とハッシュを確認してください。端末のセキュリティ警告を無視しないでください。
3. 既存版を使っている場合は、同じアプリID・署名のAPKで上書き更新してください。アンインストールすると端末内のお気に入りや保存情報が消える場合があります。

Google Play公開版ではなく、デバッグ署名付きの試用版です。第三者ライセンス通知は[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)をご確認ください。

## アプリからの更新確認

v1.7には更新画面がないため、v1.8への初回更新は上の配布ページから手動で行ってください。v1.8以降はアプリの「更新情報を確認」で公開版のビルド番号と比較します。新しい版がある場合だけAPKをブラウザーへ開きます。保存とインストールはブラウザーとAndroidの確認画面で行います。自動インストールはしません。

Android WebViewでの通信、Custom Tabsからのダウンロード、実機インストールは未検証です。

## 配布情報

- アプリID: `jp.yseradevelop.yokohamaneko`
- v1.8 / versionCode 9 / Android API 24以降
- APK: 6,311,139 bytes
- APK SHA-256: `1d5f5b2e438b03ffb41ec31fee0861a5ae01edcc44805cc9537c95fd748f0406`
- 署名証明書 SHA-256: `9613cd742136fb6bcf9b954913a57959eeccec5a983d26dedd3ae8949c089666`

更新情報は、配布APKの公開と取得確認を終えた版だけを掲載します。APKには実行に必要なプログラムと同梱データが含まれます。

## 試用上の注意

- 実機へのインストール、画面操作、ネイティブHTTP動作、画像ベースUIの確認は未実施です。
- iOS配布はありません。
- 公式情報の収集は全イベントを網羅せず、リアルタイムの中止通知を保証しません。公式条件と会場からの推定を区別して表示します。屋内の推定は雨天開催を保証しません。
- 休館日などを確定できない会期は「開催日要確認」と表示します。お出かけ前は必ず主催者の公式案内をご確認ください。
- 検索条件・お気に入り・取得情報は端末内に保存します。

変更内容は[CHANGELOG.md](CHANGELOG.md)、機械可読の更新情報は[update.json](https://raw.githubusercontent.com/Ysera-develop/yokohama-neko-releases/refs/heads/main/update.json)をご覧ください。
