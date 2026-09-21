# amp-catalog-cloudera-jpn

Cloudera AI の AMP カタログに、日本向けのカスタム AMP をタイル表示するためのリポジトリです。

## ファイル

| ファイル / ディレクトリ | 説明 |
|---|---|
| `amp-catalog-cloudera-jpn.yaml` | AMP カタログ定義ファイル |
| `images/` | AMP タイル用画像（`image_path` から raw URL で参照） |

## AMP の追加方法

`amp-catalog-cloudera-jpn.yaml` の `entries` 配列に、新しいエントリを追記してください。  
ファイル先頭のコメントにフィールド定義のテンプレートがあります。

## Cloudera AI への登録

1. このリポジトリを GitHub に Public で作成・Push する
2. **Site Administration → AMPs → Add Source**
3. 次のいずれかを指定する

**Catalog File URL（推奨）:**

```
https://raw.githubusercontent.com/eyo-shi/amp-catalog-cloudera-jpn/main/amp-catalog-cloudera-jpn.yaml
```

**Git Repository URL:**

```
https://github.com/eyo-shi/amp-catalog-cloudera-jpn
```

カタログファイル名: `amp-catalog-cloudera-jpn.yaml`

## 参考

- [Catalog File Specification](https://docs.cloudera.com/machine-learning/cloud/manage-amp/topics/ml-amp-catalog-spec.html)
- [Adding a catalog](https://docs.cloudera.com/machine-learning/cloud/manage-amp/topics/ml-amp-add-catalog.html)
