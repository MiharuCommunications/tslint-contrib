# tslint-contrib

[![npm version](https://badge.fury.io/js/%40miharu%2Ftslint-contrib.svg)](https://badge.fury.io/js/%40miharu%2Ftslint-contrib)

TSLint のルールセット

## 概要

[tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) のルールセットの設定です。


## 利用方法

`@miharu/tslint-contrib` をプロジェクトに追加する。

```
yarn add @miharu/tslint-contrib --dev
```

プロジェクトの `tslint.json` を設定する。

```json
{
  "rulesDirectory": [
  ],
  "extends": [
    "@miharu/tslint-contrib"
  ],
  "rules": {
  }
}
```


## 参考資料

+ [TSLint core rules](https://palantir.github.io/tslint/rules/)
+ [microsoft/tslint-microsoft-contrib: A set of TSLint rules used on some Microsoft projects.](https://github.com/Microsoft/tslint-microsoft-contrib)
