---
title: Neo-Brutalist Theme Demo
aliases:
  - Theme Kitchen Sink
tags:
  - theme-demo
  - neo-brutalist
status: in-progress
rating: 10
featured: true
created: 2026-07-15
---

# Neo-Brutalist Theme Demo

This note is a kitchen-sink preview for `theme.css`. Open it in **Reading view** and **Live Preview** to check both rendered and editor styles.

## Typography & Links

### A Loud Third-Level Heading

#### Heading level four

##### Heading level five

###### Heading level six

Regular text can include **bold**, *italic*, ***bold italic***, ~~strikethrough~~, ==highlighted text==, and `inline code`.

Here is an [external link](https://obsidian.md), an internal [[Theme Notes]] link, and a link to a [[Theme Notes#Specific heading|specific heading]].

Visible tags: #theme-demo #neobrutalism #electric-lime

---

## Lists & Tasks

### Unordered list

- A square-marker item
- Another item
  - A nested item
  - A second nested item
- A final item

### Ordered list

1. Design the feature
2. Build the feature
   1. Test the edge cases
   2. Polish the details
3. Ship the feature

### Task list

- [x] Merge the base stylesheet
- [x] Integrate links, lists, tags, and properties
- [ ] Open this note in Obsidian
- [ ] Test hover states

## Blockquote

> Good tools should feel opinionated, legible, and slightly impossible to ignore.
>
> — A very loud design principle

## Table

| Token | Color | Purpose |
|---|---:|---|
| Pink | `#ff2bd6` | Primary impact |
| Lime | `#39ff14` | Links and positive states |
| Purple | `#7a00ff` | Secondary impact |
| Cyan | `#00e5ff` | Hover accents |
| Yellow | `#ffe600` | Warnings and code properties |

## Code

Inline code looks like `const loud = true;`.

```css
/* Syntax-highlighted CSS block */
.feature-card {
  color: #000;
  background: #39ff14;
  border: 4px solid #000;
  box-shadow: 8px 8px 0 #ff2bd6;
}
```

```javascript
const palette = ["pink", "lime", "purple", "cyan", "yellow"];

function announce(feature) {
  // Comments should remain readable.
  return `NEW: ${feature.toUpperCase()}`;
}
```

## Callouts

> [!note] Note
> Purple is used for general information.

> [!tip] Tip
> Lime calls attention to useful or positive information.

> [!warning] Warning
> Yellow signals caution without overpowering the page.

> [!danger] Danger
> Pink makes urgent information impossible to miss.

## Image Styles

Standard Markdown images receive a heavy black border and purple offset shadow.

![Obsidian logo](https://obsidian.md/images/obsidian-logo-gradient.svg)

For a local Obsidian image, the alt text can trigger wrapping:

```markdown
![[example-image.png|float-left|240]]
![[example-image.png|float-right|240]]
```

## Embeds

The following becomes a bordered embed when `Theme Notes.md` exists in the vault:

![[Theme Notes]]

---

## Final Visual Check

Select this sentence to test the hot-pink selection color. Hover over links, tags, property rows, and the active file in the sidebar. The active workspace tab and active file should also use the integrated neo-brutalist treatment.
