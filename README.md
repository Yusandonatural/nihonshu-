# 自然日本酒 ― Peace「以和為貴」純米吟醸

自然栽培米「初霜」100% を原料に、奈良・都祁の酒蔵「倉本酒造」で醸した純米吟醸酒のランディングページ。

株式会社悠三堂 (YUSANDO)

## 公開URL

https://sake.yusando.com/

GitHub Pages（`main` ブランチ / ルート）で公開。カスタムドメインは `CNAME` で指定。

## 構成

```
index.html    ページ本体（HTML / CSS すべて内包・自己完結）
CNAME         カスタムドメイン指定
.nojekyll     GitHub Pages の Jekyll 処理を無効化
```

JavaScript は使用していません。読み物タブは CSS のみ（隠しラジオボタン + 兄弟セレクタ）で動作します。

## 画像について

写真は Shopify CDN 上のファイルを参照しています。完全に自己完結させたい場合は、画像を `images/` に置いて `index.html` 内の `https://cdn.shopify.com/...` を相対パスに置き換えてください。

## 編集方法

`index.html` を直接編集して push すれば、数分で公開ページに反映されます。

## 関連

同じ内容を Shopify の固定ページとしても公開しています。
https://yusando.com/pages/shizen-nihonshu
