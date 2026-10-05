# TugasWeb-Pertemuan4-SCSS

**Tugas Rutin 4: Konversi CSS ke SCSS (7-1 pattern)**
**Nama:** Samuel Jacksen Brahmana | Pemrograman Web, UNIMED

Konversi CSS dari Tugas Pertemuan 2 (Portofolio) ke SCSS dengan struktur modular **7-1 pattern**, di-compile menggunakan **Vite + Dart Sass**.

## Requirements

| # | Requirement | Implementasi |
|---|---|---|
| 1 | Konversi CSS ke SCSS | `css/style.css` (Tugas 2) → `src/scss/` |
| 2 | Variables colors & spacing | `abstracts/_variables.scss` (palet light/dark, map `$spacing`) |
| 3 | Nesting maks 3 level | Pola BEM dengan `&__element`, `&--modifier`, `&:hover` |
| 4 | Min. 3 mixins | `flex`, `surface`, `respond-below`, `dark-mode`, `hover-focus`, `focus-ring`, `tokens` (`abstracts/_mixins.scss`) |
| 5 | Struktur 7-1 | `abstracts`, `vendors`, `base`, `layout`, `components`, `pages`, `themes` + `main.scss` |
| 6 | `@use` (bukan `@import`) | Semua partial memakai `@use` / `@forward` |
| 7 | Min. 1 `@each` / `@for` | `@each` di `layout/_grid.scss` (grid-area) dan `abstracts/_mixins.scss` (`tokens`) |
| 8 | Compile Vite / Dart Sass | `npm run dev`, `npm run build`, `npm run sass:build` |

## Struktur Folder

```
src/scss/
├── abstracts/    _variables  _functions  _mixins  _index
├── vendors/      _index
├── base/         _reset      _index
├── layout/       _grid  _header  _aside  _footer  _index
├── components/   _card  _form  _button  _social-links  _index
├── pages/        _home       _index
├── themes/       _light  _dark  _index
└── main.scss
css/style.css    # hasil compile
```

## Cara Menjalankan

```bash
npm install
npm run dev          # server development (Vite) → http://localhost:5173
npm run sass:build   # compile SCSS → css/style.css
npm run build        # build produksi ke folder dist/
```

> Salin gambar dari Tugas 2 (`sketch_1.JPEG`, `ss1.png`, `ss2.png`, `HTTS-2026.png`) ke folder `public/images/`.

## Hasil Compile

File CSS hasil compile ada di [`css/style.css`](css/style.css).
