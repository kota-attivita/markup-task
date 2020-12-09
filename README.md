# Markup Task

マークアップの課題です。

## Rule
マークアップする上で下記のルールにしたがって開発をしてください。

- レスポンシブ対応。
- cssはBEMの思想で書いてください。
- アニメーションは特につけなくていいです。
- stylelint、puglintといったコードチェックを走らせているので、エラーが出た場合必ずなおしてからpushしてください。
- 色々ファイルがありますが、`src`の`index`フォルダのみ触って開発をしてください。
- zipで渡す時は必ず `node_modules`は削除してからzipにしてください。


## Overview

下記の技術を使って開発をします。

html -> pug

css -> Scss

JavaScript -> TypeScript


それぞれのドキュメントは下記でご確認ください。

- [PUGのドキュメント](https://qiita.com/takeshisakuma/items/fdcf456d8250e6dafc7b)
- [Scssのドキュメント](https://qiita.com/nchhujimiyama/items/8a6aad5abead39d1352a)
- [TypeScriptのドキュメント](https://qiita.com/ringtail003/items/7ccf992f18b768e0e633)


`Node.js`と`yarn`は下記のバージョン下記でお願いします。

| 名前    | バージョン |
| ------- | ---------- |
| Node.js | v15.2.0   |
| Yarn    | v1.22.10    |

## Install

### Node Install

node.js を使うので下記の記事に従い node をインストールしてください。（既にnodeが入っていればスキップ）

**for mac**

[https://qiita.com/kyosuke5_20/items/c5f68fc9d89b84c0df09](https://qiita.com/kyosuke5_20/items/c5f68fc9d89b84c0df09)

**for windows**

[https://qiita.com/maecho/items/ae71da38c88418b806ff](https://qiita.com/maecho/items/ae71da38c88418b806ff)



### Yarn Install

yarn を使うので下記のコマンドで yarn をインストールしてください。（既にyarnが入っていればスキップ）

**for mac**

```bash
$ brew install yarn
```
​
**for windows**
​
```sh
# for Windows (with Chocolatey)
$ choco install yarn
```

[Use installer](https://yarnpkg.com/lang/en/docs/install/#windows-tab)

## Commands

開発で使うコマンドは下記になります。
​
### Add package

プロジェクトをクローンしたら、ルートディレクトリから下記のコマンドを叩いてください。

```bash
yarn install
```

### Start Development

下記のコマンドで開発サーバーが立ち上あがり開発ができるようになります。

```
yarn start
```

http://localhost:8080
