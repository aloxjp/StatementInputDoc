# Document Template

## Overview

Markdownで技術文章を記載する際のテンプレートです。
textlintによる文章校正を導入しており、理解しやすい文章の作成を支援します。

## Requirement

- Node.js

VSCode等のエディタで使用する場合、拡張機能の利用を推奨します。

## Install

1. [このリンク](https://github.com/masokamoto/DocumentTemplate/generate)からリポジトリを作成する
1. npmパッケージをインストールする
   ```cmd
   npm install
   ```
1. Markdownファイルを追加し、ドキュメントを作成する

## textlint rules

<!-- textlint-disable -->
- [textlint-rule-ja-no-mixed-period](https://github.com/textlint-ja/textlint-rule-ja-no-mixed-period)
  文末の句点を"。"に統一する
- [textlint-rule-period-in-list-item](https://github.com/textlint-rule/textlint-rule-period-in-list-item)
  箇条書きの文末にある句点を検出する
- [textlint-rule-ja-no-redundant-expression](https://github.com/textlint-ja/textlint-rule-ja-no-redundant-expression)
  冗長な表現を検出する
  > 冗長な表現の一例
  > (×)することができない (○)できる
  > (×)であると言える (○)である
- [textlint-rule-ja-no-weak-phrase](https://github.com/textlint-ja/textlint-rule-ja-no-weak-phrase)
  弱い日本語表現を禁止する
  > 弱い日本語表現の一例
  > ～かもしれない ～と思う
- [textlint-rule-ja-unnatural-alphabet](https://github.com/textlint-ja/textlint-rule-ja-unnatural-alphabet)
  不自然なアルファベットを検出し、IMEの入力ミスによるtypoを発見しやすくする
- [textlint-rule-no-double-negative-ja](https://github.com/textlint-ja/textlint-rule-no-double-negative-ja)
  二重否定を検出する
- [textlint-rule-no-doubled-joshi](https://github.com/textlint-ja/textlint-rule-no-doubled-joshi)
  1つの文中に同じ助詞が連続して出てくるのを検出する
- [textlint-rule-no-dropping-the-ra](https://github.com/textlint-ja/textlint-rule-no-dropping-the-ra)
  ら抜き言葉を検出する
- [textlint-rule-no-hankaku-kana](https://github.com/textlint-ja/textlint-rule-no-hankaku-kana)
  半角カタカナの利用を禁止する
- [textlint-rule-no-mixed-zenkaku-and-hankaku-alphabet](https://github.com/textlint-ja/textlint-rule-no-mixed-zenkaku-and-hankaku-alphabet)
  全角アルファベットの使用を禁止する
- [textlint-rule-preset-ja-spacing](https://github.com/textlint-ja/textlint-rule-preset-ja-spacing)
  日本語におけるスペースの有無を決定する
  - 全角文字と半角文字の間にスペースを入れない
  - インラインコードの周りにスペースを入れない
  - 全角文字どうしの間にスペースを入れない
  - カタカナ語は中黒または半角スペースで区切る
  - かっこの内側、外側にスペースを入れない
- [textlint-rule-preset-ja-technical-writing](https://github.com/textlint-ja/textlint-rule-preset-ja-technical-writing)
  技術文章向けルールのプリセット
<!-- textlint-enable -->