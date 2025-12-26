# Tailwind CSS – Component Classes Overview

> **Important:** Tailwind CSS does **not** provide ready‑made component classes like Bootstrap (`.card`, `.navbar`, `.modal`).
>
> Tailwind is a **utility‑first CSS framework**. Components are built by combining utilities.

---

## ❓ So how many component classes are in Tailwind?

**Answer:** `0` predefined component classes ❌

Instead, Tailwind provides **utility class categories** that you use to build **any component** (cards, posters, navbars, modals, etc.).

---

## 🧩 Tailwind CSS Utility Categories (Official‑style Note)

### 1️⃣ Layout

Controls structure and positioning

* container
* box-sizing
* display
* float / clear
* isolation
* object-fit / object-position
* overflow / overscroll
* position
* visibility
* z-index

---

### 2️⃣ Flexbox & Grid

Used to build layouts and components

* flex / inline-flex
* flex-direction
* flex-wrap
* align-items
* align-content
* justify-content
* justify-items / justify-self
* place-content / place-items
* grid
* grid-template-columns / rows
* grid-auto-flow
* gap

---

### 3️⃣ Spacing

Controls space around and inside elements

* padding (`p`, `px`, `py`, `pt`, etc.)
* margin (`m`, `mx`, `my`, `mt`, etc.)
* space-between (`space-x`, `space-y`)

---

### 4️⃣ Sizing

Width & height utilities

* width (`w-*`)
* min-width / max-width
* height (`h-*`)
* min-height / max-height

---

### 5️⃣ Typography

Text and font styling

* font-family
* font-size
* font-weight
* line-height
* letter-spacing
* text-align
* text-color
* text-transform
* text-decoration
* text-overflow

---

### 6️⃣ Backgrounds

Background styling utilities

* background-color
* background-image
* background-size
* background-position
* background-repeat
* gradient utilities

---

### 7️⃣ Borders

Border and outline styling

* border-width
* border-color
* border-style
* border-radius
* divide-width / divide-color
* outline

---

### 8️⃣ Effects

Visual effects for UI components

* box-shadow
* opacity
* mix-blend-mode
* background-blend-mode

---

### 9️⃣ Filters

Image and backdrop effects

* blur
* brightness
* contrast
* grayscale
* hue-rotate
* invert
* saturate
* sepia
* backdrop-filter

---

### 🔟 Tables

Table‑specific utilities

* border-collapse
* border-spacing
* table-layout

---

### 1️⃣1️⃣ Transitions & Animation

Used for interactivity

* transition-property
* transition-duration
* transition-timing-function
* transition-delay
* animation

---

### 1️⃣2️⃣ Transforms

2D & 3D transforms

* scale
* rotate
* translate
* skew
* transform-origin

---

### 1️⃣3️⃣ Interactivity

User interaction behavior

* cursor
* pointer-events
* resize
* scroll-behavior
* scroll-snap
* user-select

---

### 1️⃣4️⃣ SVG

SVG styling utilities

* fill
* stroke
* stroke-width

---

### 1️⃣5️⃣ Accessibility

Accessibility helpers

* screen-readers (`sr-only`, `not-sr-only`)

---

## 🧱 How Components Are Made in Tailwind

Instead of predefined components:

```html
<div class="rounded-xl shadow-lg bg-white p-4">
  <h2 class="text-lg font-bold">Card Title</h2>
  <p class="text-gray-600">Card description</p>
</div>
```

➡️ This becomes a **Card Component**
