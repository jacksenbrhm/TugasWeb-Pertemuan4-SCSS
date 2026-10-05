# TugasWeb-Pertemuan4-SCSS

## Requirements

| # | Requirement | Implementasi |
|---|---|---|
| 1 | Konversi CSS ke SCSS | `css/style.css` (Tugas 2) dipecah menjadi partial di `src/scss/` |
| 2 | Variables colors & spacing | `abstracts/_variables.scss` (palet light/dark dan map `$spacing`) |
| 3 | Nesting maks 3 level | Pola BEM dengan `&__element`, `&--modifier`, dan `&:hover` |
| 4 | Min. 3 mixins | `flex`, `surface`, `respond-below`, `dark-mode`, `hover-focus`, `focus-ring`, `tokens` (`abstracts/_mixins.scss`) |
| 5 | Struktur 7-1 pattern | `abstracts`, `vendors`, `base`, `layout`, `components`, `pages`, `themes` + `main.scss` |
| 6 | `@use` (bukan `@import`) | Semua partial memakai `@use` dan `@forward` |
| 7 | Min. 1 `@each` / `@for` | `@each` di `layout/_grid.scss` dan `abstracts/_mixins.scss` |
| 8 | Compile dengan Vite / Dart Sass | `npm run dev`, `npm run build`, `npm run sass:build` |