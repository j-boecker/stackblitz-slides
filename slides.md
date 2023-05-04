---
# try also 'default' to start simple
theme: dracula
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Stackblitz
  Online Code Editor - German Presentation
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# Stackblitz VVV

Entwickeln mit Node.js im Browser

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Los geht's <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# VVV Stackblitz - Inhalte

StackBlitz ist eine Web IDE für das Javascript Ecosystem.

-  **Features** - was kann man alles mit Stackblitz machen?
-  **Technologie** - wie funktioniert Stackblitz (grob)?
-  **Templates** - welche Frameworks gibt es als Templates?
-  **Tricks** - welche Funktionen sind gut zu kennen?
-  **Kritik** - welche Probleme gibt es?
-  **Glaskugel** - was wird es demnächst geben?


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
class: px-20
---

# Features

Instant Bug Reports - Auschecken von Branches auf Github

Coding Sandbox für Beispiele

<div grid="~ cols-2 gap-2" m="-t-2">


<img border="rounded" src="https://c.staticblitz.com/assets/vite/bug_reports-62f54590.png">


</div>
---
class: px-20
---

# Features

Schnelles Prototyping - Hot Loading - Schnelle Installation von Abhängigkeiten

Zusammenarbeiten an gleichem Code - Code Preview - Verschiedene Devices

<div grid="~ cols-2 gap-2" m="-t-2">


<img border="rounded" src="https://c.staticblitz.com/assets/vite/interactive_documentation-0fa61953.png">

<img border="rounded" src="https://c.staticblitz.com/assets/vite/rapid_prototyping-35780526.png">

</div>
---
class: px-20
---

# Technologie

Wie funktioniert Stackblitz? Haben die einen Docker Container in der Cloud laufen? Wie finanzieren die sich?
---
class: px-20
---
# Technologie

Alles läuft im Browser! Stackblitz verwendet WebAssembly um Node.js im Browser zu starten. Kein Streaming wie bei Code Sandbox [Oficial Site](https://blog.stackblitz.com/posts/introducing-webcontainers//)

<div grid="~ cols-1 gap-2" m="-t-2">


<img border="rounded" src="https://blog.stackblitz.com/img/posts/introducing-webcontainers.png">

</div>

---

# Templates

Eigentlich alles was mit Javascript/ Typescript geschrieben ist

### Keyboard Shortcuts

|     |     |
| --- | --- |
| <kbd>Frontend</kbd>| Angular, Vue, React, Solid, Svelte |
| <kbd>Backend</kbd> | NestJs, Express, GraphQL, Json Server |
| <kbd>Fullstack</kbd> | Next.js,  Nuxt, WebContainer API |
| <kbd>Docs, Blogs, Slides</kbd> | Slidev, Astro Docs, Vue Press |
| <kbd>Mobile</kbd> | Native Script |
| <kbd>Vanilla</kbd> | Javascript, NodeJs, RxJS, Vanilla HTML |

---
layout: iframe
url: "https://stackblitz.com/edit/angular-rhaycc?ctl=1&embed=1&file=src/main.ts"
---
# Templates - Angular

Angular

---
layout: center
class: text-center
---

# Links

[Oficial Site](https://stackblitz.com/) · [Docs](https://developer.stackblitz.com/) · [StackBlitz GitHub](https://github.com/stackblitz/core)
