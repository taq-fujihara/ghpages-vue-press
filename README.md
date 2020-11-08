# VuePressで作成したサイトをGithub Pagesで公開するサンプル

## Development

```text
npm run docs:dev
```

## Deploy

`.github/workflows/gh-pages.yaml`の則って`master`ブランチへのPush時にhtmlアセット生成 & `gh-pages`ブランチへのPushが行われます。
