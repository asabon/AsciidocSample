# AsciidocSample

## 目的

ASCIIDOC を使ったドキュメントの記述とビルドについてサンプルを示す。

## 構成

以下のように、ドキュメントごとに「生成用yml」「成果物」「ソース」を分けて置く。

```sh
+ .github/
  + workflows/
    + doc1.yml : doc1 生成用の yml
+ docs/
  + doc1/      : doc1 ビルド成果物
+ sources/
  + doc1/      : doc1 ソース
```

---

### doc1 (ASCIIDOC)

#### 目的

* ファイル分割の確認
* Mermaid を使った図の表現
  * GitHub の AsciiDoctor では描画できている
  * GitHub Actions による生成ではうまくいってない(調査中)

#### 成果物

* main ブランチから GitHub Actions で生成したドキュメント
  * https://asabon.github.io/DocumentSamples/docs/doc1/build/index.html

---
