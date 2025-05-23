---
title: :only-of-type
slug: Web/CSS/:only-of-type
l10n:
  sourceCommit: 62681c2ef134407009c5c11fa679db1f485e016d
---

{{CSSRef}}

La [pseudo-classe](/fr/docs/Web/CSS/Pseudo-classes) [CSS](/fr/docs/Web/CSS) **`:only-of-type`** permet de cibler un élément qui ne possède aucun nœud frère du même type.

{{InteractiveExample("CSS Demo: :only-of-type", "tabbed-shorter")}}

```css interactive-example
a:only-of-type {
  color: fuchsia;
}

dd:only-of-type {
  background-color: bisque;
}
```

```html interactive-example
<p>
  To find out more about <b>QUIC</b>, check <a href="#">RFC 9000</a> and
  <a href="#">RFC 9114</a>.
</p>

<dl>
  <dt>Published</dt>
  <dd>2021</dd>
  <dd>2022</dd>
</dl>

<p>Details about <b>QPACK</b> can be found in <a href="#">RFC 9204</a>.</p>

<dl>
  <dt>Published</dt>
  <dd>2022</dd>
</dl>
```

> [!NOTE]
> Dans la version initiale de la spécification (CSS3), l'élément ciblé devait avoir un parent, ce n'est plus nécessaire depuis (spécification pour les sélecteurs de niveau 4).

## Syntaxe

```css
:only-of-type {
  /* ... */
}
```

## Exemples

### Mettre en forme des éléments sans voisins du même type

#### HTML

```html
<main>
  <div>Je suis l'élément `div` n°1.</div>
  <p>Je suis le seul élément `p` parmi mes voisins.</p>
  <div>Je suis l'élément `div` n°2.</div>
  <div>
    Je suis l'élément `div` n°3.
    <i>Je suis le seul enfant `i`.</i>
    <em>Je suis l'élément `em` n°1.</em>
    <em>Je suis l'élément `em` n°2.</em>
  </div>
</main>
```

#### CSS

```css
main :only-of-type {
  color: red;
}
```

#### Résultat

{{EmbedLiveSample('','100%',180)}}

## Spécifications

{{Specifications}}

## Compatibilité des navigateurs

{{Compat}}

## Voir aussi

- [`:only-child`](/fr/docs/Web/CSS/:only-child)
- [`:first-of-type`](/fr/docs/Web/CSS/:first-of-type)
- [`:last-of-type`](/fr/docs/Web/CSS/:last-of-type)
- [`:nth-of-type`](/fr/docs/Web/CSS/:nth-of-type)
