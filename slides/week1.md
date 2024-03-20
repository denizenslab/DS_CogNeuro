---
theme: academic
layout: cover
class: text-center
# coverBackgroundUrl: /test.jpg
coverBackgroundUrl: "https://drive.google.com/file/d/18YLxJVdvbiCwi7P8ZgsPbaFIjW3WBIe7/view?usp=sharing"
# coverBackgroundSource: unsplash
# coverBackgroundSourceUrl: https://images.unsplash.com/photo-1594122230689-45899d9e6f69?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80
# https://drive.google.com/file/d/18YLxJVdvbiCwi7P8ZgsPbaFIjW3WBIe7/view?usp=sharing
coverDate: "18.04.2024"
themeConfig:
  paginationX: r
  paginationY: t
  paginationPagesDisabled: [1]
title: Welcome to Data Science for Cognitive Neuroscience
info: |
  Week 1 - Introduction to Cognitive Neuroscience
download: true
---

# Welcome to Data Science for Cognitive Neuroscience
## Anuja Negi
## Fatma Deniz

---
layout: table-of-contents
hideInToc: false
---

# Overview

---
layout: index
indexEntries:
  - { title: "Curated cover image for Slidev", uri: 4 }
  - { title: "Curated cover image for Slidev", uri: 5 }
---

# index

`index` used as list of figures

---
layout: figure
figureCaption: Curated cover image for Slidev
figureFootnoteNumber: 1
figureUrl: ./test.jpg
---

# figure

<Footnotes separator>
  <Footnote :number=1><a href="https://unsplash.com/collections/94734566/slidev" rel="noreferrer" target="_blank">Anthony Fu</a></Footnote>
</Footnotes>

---
layout: figure-side
figureCaption: Curated cover image for Slidev
figureFootnoteNumber: 1
figureUrl: https://source.unsplash.com/collection/94734566/1024x768
---

# figure-side

- Ensures figures are displayed nicely out of the box
- Allows placing the figure on the left or right
- Features an optional figure caption

<Footnotes separator>
  <Footnote :number=1><a href="https://unsplash.com/collections/94734566/slidev" rel="noreferrer" target="_blank">Anthony Fu</a></Footnote>
</Footnotes>

---
layout: center
class: "text-center"
---

# Footnotes & Footnote

<span class="font-extralight">
  <q>Give credit where credit is due</q>
  <sup>1</sup>
</span>

<Footnotes separator>
  <Footnote :number=1>Smart person</Footnote>
</Footnotes>

---
layout: center
class: "text-center"
---

# Pagination

<span class="font-extralight">Enabled by default</span>

<img
  class="absolute transform rotate-z-180 -top-0.9 -right-21.5 w-36"
  src="/box.svg"
/>

<p class="absolute font-extralight right-14 transform rotate-8 top-4">Here!</p>

---
layout: index
indexEntries:
  - { title: "GitHub", uri: "https://github.com/alexanderdavide/slidev-theme-academic" }
  - { title: "npm", uri: "https://www.npmjs.com/package/slidev-theme-academic" }
  - { title: "Slidev", uri: "https://sli.dev" }
indexRedirectType: external
---

# index

`index` used as a list of references