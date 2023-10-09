# intern-dev-tex

インターンで使用したドキュメントをtexにして組版するためのリポジトリです。

## コピー時のコマンド

前提: ホームディレクトリ下にintern-dev-tutorialがcloneされていること

```zsh
for i in `ls ~/intern-dev-tutorial/**/*.md`; do cp -R $i `echo $i | sed -E "s/intern-dev-tutorial\/([a-zA-Z0-9-]*\/*)/intern-dev-tex\/\1/g" | sed -E "s/(.*intern-dev-tex)\/(.*)\/(.*\.md)/\1\/\2-\3/g"`; done
```

## TOC

- Git / Github 学習資料: git
  - [README.md](./git/README.md)
  - [DOCS.md](./git/docs.md)
- JavaScriptを始めよう: javascript
  - [README.md](./javascript/README.md)
  - [DOCS.md](./javascript/DOCS.md)
- HTML/CSSを始めよう: html-css
  - [README.md](./html-css/README.md)
  - [DOCS.md](./html-css/DOCS.md)
- Denoについて: deno
  - [README.md](./deno/README.md)
- クライアント・サーバの通信: transfer-protocol
  - [README.md](./transfer-protocol/README.md)
- APIハンズオン: api
  - [README.md](./api/README.md)
- データベース: MySQL: detabase
  - [README.md](./database/README.md)
  - [docs.md](./database/docs.md)
- ログインハンズオン: did-login
  - [README.md](./did-login/README.md)
- ChatGPT APIハンズオン: chat-gpt-api
  - [README>md](./chat-gpt-api/README.md)

![](./imgs/summary.jpg)

## 著者

- <https://github.com/nabe1005>
- <https://github.com/Futaba-Kosuke>
- <https://github.com/dicenull>
- <https://github.com/takerucam>
- <https://github.com/rough-github>
- <https://github.com/Ryo-7>
- <https://github.com/haruyuki-16278>

### スペシャルサンクス

Contributerの皆様 <https://github.com/jigintern/intern-dev-tutorial/graphs/contributors>

### Credits

#### octicons
- <https://github.com/primer/octicons/blob/main/LICENSE>
