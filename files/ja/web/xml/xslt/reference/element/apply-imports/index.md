---
title: <xsl:apply-imports>
slug: Web/XML/XSLT/Reference/Element/apply-imports
l10n:
  sourceCommit: 3e1b5277c6451e7d27ab628f23fb9702947a7a7b
---

`<xsl:apply-imports>` 要素は非常に秘密で、複雑なスタイルシートで主に使用されます。インポートの優先順位では、メインスタイルシートのテンプレートルールは、インポートされたスタイルシートのテンプレートルールより優先される必要があります。しかし、メインスタイルシート内の同等のルールではなく、（優先順位の低い）インポートされたスタイルシートからのテンプレートルールを使用するようにプロセッサーに強制できることが有益な場合もあります。

### 構文

```xml
<xsl:apply-imports/>
```

### 必須属性

なし。

### 任意属性

なし。

### 種類

命令で、テンプレート内に現れます。

## 仕様書

XSLT, section 5.6.

## Gecko の対応

サポート済み。
