# Benkyo-kai
二つの目的がある。
1. 以下のリソースをいじることを通じてReactについて学ぶための壊していいレポジトリ。
2. 構成のラフ案をプルリクしながら作っていくことを通じて分散開発に慣れるためのレポジトリ。

## リソース
[React公式](https://ja.react.dev/learn) reactの8割を理解する

[Material UI](https://mui.com/material-ui/react-autocomplete/)　現場でも使われているUIコンポーネントを利用して画面を構成する

## 使い方
### MUI
コンポーネントを一つ取り上げる

![Screenshot 2023-07-10 at 9 39 21](https://github.com/Escher-js/benkyo-kai/assets/94701070/67b019df-db41-4422-bf2a-1fc13fcfbdb8)

`show the full source`を押すと全体が見える

![Screenshot 2023-07-10 at 9 40 36](https://github.com/Escher-js/benkyo-kai/assets/94701070/644b996e-cfd1-4614-b70b-72e2c2d29e9c)


`components/<yourcomponentsname>.tsx` を作成しコピペする

![Screenshot 2023-07-10 at 9 41 09](https://github.com/Escher-js/benkyo-kai/assets/94701070/9d863b17-e784-4868-ad2a-95c5f9ee3e9c)

App.tsxで読み込む

![Screenshot 2023-07-10 at 9 50 03](https://github.com/Escher-js/benkyo-kai/assets/94701070/0e95f537-18fc-460c-8bd0-9f29015f0ced)

![Screenshot 2023-07-10 at 9 49 50](https://github.com/Escher-js/benkyo-kai/assets/94701070/9890cf96-a73a-4975-b3bd-92dc10c7ac8d)

`npm start`をターミナルで実行
![Screenshot 2023-07-10 at 9 50 44](https://github.com/Escher-js/benkyo-kai/assets/94701070/3fa41d5b-543e-4d7d-b956-aaec1046e6dd)

以降は動かしっぱなしで変更を加えると反映される

### 動かないときは
- エラーは何が出ているか？
- `npm install`は忘れていないか？
- 動くが、変更が反映されていない
  - `npm run build`を試してみよ

## 自分で同じようなレポジトリを作る場合
あとで加筆
