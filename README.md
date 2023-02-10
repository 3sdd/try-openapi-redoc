

# ReDocを使ってOpen APIのファイルからドキュメントサイトを作る


前提として、Node.jsはインストール済み。

以下コマンドを実行

```bash
npx redoc-cli build petstore.yaml --output=docs/index.html
```




readoclyでも可能


```bash
npx @redocly/cli build-docs <api>
```

ドキュメントのhtml生成。
```bash
npx @redocly/cli build-docs api-with-examples.yaml --output=index.html
```