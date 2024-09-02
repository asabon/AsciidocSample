# AsciidocSample

## 目的

ASCIIDOC を使ったドキュメントの記述とビルドについてサンプルを示す。

## 構成

以下のように、ドキュメントごとに「生成用yml」「成果物」「ソース」を分けて置く。

```sh
+ .github/
  + workflows/
    + doc1.yml : doc1 生成用の yml
+ build/
  + doc1/      : doc1 ビルド後 HTML 置き場(予定)
+ doc/
  + doc1/      : doc1 ソース
```
