---
# try also 'default' to start simple
theme: seriph
themeConfig:
  primary: '#8b471c'
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /bookshelf.webp
backgroudSize: contain
# some information about your slides (markdown enabled)
title: Daten im Privaten
info: |
  ## Daten aufschreiben im privaten Bereich

  Erstellt mit [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 10min
addons: 
  - slidev-addon-rabbit
rabbit:
  slideNum: true   # Show current/total slide numbers next to a rabbit icon
---

<h1 style="-webkit-text-stroke: 0.5px grey;">
  Daten im Privaten
</h1>
<h2 v-click style="-webkit-text-stroke: 0.5px grey;">
  Mein Jahr im Rückblick
</h2>

---
src: ./pages/start.md
---

---
src: ./pages/tv.md
---

---
src: ./pages/board_games.md
---

---
src: ./pages/books.md
---

---
src: ./pages/obsidian.md
---

---
src: ./pages/cool_software.md
---