# check-ng-word-from-text

テキストの中に NG ワードが含まれているかをチェックするのを textlint で試してみました。

## Usage

```
$ npm run textlint
```

## .textlintrc

ルールは以下のように words に配列として追加していきます。

```
{
  "rules": {
    "textlint-rule-ng-word": {
      "words": ["ほげ"]
    }
  }
}
```

## 参考記事

[textlintを設定してライターに自動校正を提供する - ねこせんせいのノート](https://prokou.caitsith.info/tool/textlint.html#NG%E3%83%AF%E3%83%BC%E3%83%89)
