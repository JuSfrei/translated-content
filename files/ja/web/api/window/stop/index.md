---
title: window.stop
slug: Web/API/Window/stop
---

{{ApiRef}}

## 概要

このメソッドは、ウィンドウの読み込みを停止します。

## 構文

```
window.stop()
```

## 例

```html
<script>
  stop();
</script>

<p>このパラグラフは読み込まれないでしょう。</p>
```

## 注記

`stop()` メソッドは、ブラウザーの停止ボタンをクリックすることと全く同じです。スクリプトが読み込まれる順番のために、`stop()` メソッドは文書の読み込みを停止できない可能性がありますが、巨大な画像、新しいウィンドウなど、読み込みを遅延させるオブジェクトの読み込みを停止することはできるでしょう。

## 仕様書

{{Specifications}}

## 互換性

stop() メソッドは、Internet Explorer でサポートされません。
