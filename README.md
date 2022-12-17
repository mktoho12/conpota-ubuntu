## こんぽたUbuntu修正版
`localedef`というコマンドを実行すると日本語が入力できるようになるらしい…

```
localedef -i ja_JP -c -f UTF-8 -A /usr/share/locale/locale.alias ja_JP.UTF-8
```

ので、Dockerfileを作ってビルド手順に追加しました。ついでに環境変数も追加しました
