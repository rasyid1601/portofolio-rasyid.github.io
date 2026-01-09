# Portfolio Website - Struktur File

## 📁 Folder Structure

```
portofolio-rasyid/
├── index.html                    # Main HTML file
├── styles.css                    # Global styles & shared components
├── script.js                     # Global JavaScript functionality
│
├── navbar.css                    # Navigation bar styles
├── navbar.js                     # Navigation bar functionality
│
├── foto profil.jpg              # Profile photo
│
└── sections/                     # Section-specific files
    ├── tentang.html             # About section HTML
    ├── tentang.css              # About section styles
    │
    ├── portofolio.html          # Portfolio section HTML
    ├── portofolio.css           # Portfolio section styles
    │
    ├── kontak.html              # Contact section HTML
    └── kontak.css               # Contact section styles
```

## 📄 File Descriptions

### Main Files
- **index.html** - Halaman utama yang menggabungkan semua section
- **styles.css** - CSS global untuk layout umum, animasi, dan hero section
- **script.js** - JavaScript untuk fungsionalitas umum (scroll, form handling, dll)

### Navigation
- **navbar.css** - Styling khusus untuk navigation bar
- **navbar.js** - Fungsionalitas hamburger menu dan active link

### Sections (dalam folder `sections/`)
1. **Tentang Saya**
   - `tentang.html` - Struktur HTML untuk section "Tentang Saya"
   - `tentang.css` - Styling khusus untuk section "Tentang Saya"

2. **Portofolio**
   - `portofolio.html` - Struktur HTML untuk section "Portofolio"
   - `portofolio.css` - Styling khusus untuk section "Portofolio"

3. **Kontak**
   - `kontak.html` - Struktur HTML untuk section "Kontak"
   - `kontak.css` - Styling khusus untuk section "Kontak"

## 🎨 CSS Organization

Setiap file CSS terpisah memiliki:
- Komentar header yang jelas
- Logical grouping dari styles
- Mobile responsive design
- Konsistensi dengan CSS variables dari styles.css

## 🔧 How to Use

1. Semua file CSS sudah di-link di `index.html` `<head>`
2. Jika ingin mengedit sebuah section tertentu, edit file HTML dan CSS yang sesuai
3. JavaScript functionality tetap bersatu di `script.js` dan `navbar.js`
4. Global variables dan animasi ada di `styles.css`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px max-width container
- **Tablet**: 768px media query
- **Mobile**: 600px media query

## 🎯 Maintenance Tips

- Edit HTML section-specific di folder `sections/`
- Edit styling section-specific di CSS file yang sesuai
- Edit global styling di `styles.css`
- Jangan hapus CSS variables di root selector
