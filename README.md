# Slicing Project

Proyek ini merupakan setup dasar untuk melakukan slicing HTML/CSS menggunakan **Tailwind CSS**, lengkap dengan fitur live reload dan plugin ikon dari **Material Symbols**.

## 🚀 Fitur Utama

- ✅ **Tailwind CSS** versi 3
- 🔁 **Live reload** dengan BrowserSync
- 🎨 **Custom color & font**
- 💅 **Prettier + plugin Tailwind CSS**
- 📦 **Ikon Material Symbols** via `@egoist/tailwindcss-icons`

## 📁 Struktur Folder

```
slicing/
├── src/
│   └── input.css         # File input utama Tailwind
├── dist/
│   ├── index.html        # Output HTML
│   └── assets/css/
│       └── main.css      # Output CSS dari Tailwind
├── tailwind.config.js    # Konfigurasi Tailwind
├── .prettierrc           # Konfigurasi Prettier
├── .gitignore
├── package.json
```

## 📦 Instalasi

1. Clone repo ini
2. Jalankan perintah:

```bash
npm install
```

## 🛠️ Perintah Pengembangan

### Mode Development (auto reload + tailwind watch)

```bash
npm run dev
```

Akan membuka [http://localhost:3000](http://localhost:3000) secara otomatis dengan hot reload.

### Build CSS untuk Production

```bash
npm run build
```

Hasil minify Tailwind CSS akan tersimpan di:

```
dist/assets/css/main.css
```

## 🎨 Custom di Tailwind

- Warna:
  - `brands.dark-green`: `#118871`
  - `brands.light-green`: `#15AB8E`
- Font:
  - `sans`: Inter
  - `brand`: Red Rose
- Ukuran ikon (`fontSize`):
  - `icon-sm`: 20px
  - `icon-md`: 24px
  - `icon-lg`: 28px
  - `icon-xl`: 32px
- Animasi:
  - `slide-top`
  - `slide-bottom`

## 🧩 Plugin Digunakan

- `@egoist/tailwindcss-icons`
- `@iconify-json/material-symbols`
- `prettier-plugin-tailwindcss`

---

Dibuat dengan ❤️ untuk kebutuhan slicing yang cepat dan rapi.
