# What is this
ハッカソン用のサンプルアプリです。
Flickr APIを使用して、公開されている写真をキーワード検索しています。
Node.js + Express + EJSで構成されています。

# How to set up

1. モジュールインストール
```
$ npm install
```

2. Flickr APIに[登録](https://www.flickr.com/services/api/)し、app.jsを編集

```javascript
function getApiKeys(callback, errorcallback) {
  // CHANGE THE CREDENTIALS OF FLICKR API
  callback('Your Flickr API key', 'Your Flickr API secret');
}
```


3. サーバー起動
```
$ npm run dev
```

4. ブラウザから[アクセス](http://localhost:8080/)

# 参考
ゼロからはじめるExpress + Node.jsを使ったアプリ開発のサンプルコード
http://qiita.com/nkjm/items/723990c518acfee6e473 の記事のサンプルコードです。
