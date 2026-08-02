<div align="center">

  <!-- Tech Badge Header -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">

  <br><br>

  <!-- Project Title -->
  <h1>🚀 Portofoli0</h1>

  <p><strong>Portofolio ZeroBug Team — Versi Pertama</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square">
    <img src="https://img.shields.io/badge/Status-Stable-green?style=flat-square">
    <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square">
  </p>

</div>

---

## 🚀 Tentang Project

**Portofoli0** adalah website portofolio resmi **ZeroBug Team** — versi ketiga yang menampilkan kumpulan proyek, referensi, dan showcase karya pengembangan web & aplikasi. Dibangun dengan pendekatan sederhana namun fungsional, portofolio ini menjadi fondasi identitas digital tim kami di dunia teknologi.

Meski kini telah tersedia [versi kedua (Porto-Redesign)](https://github.com/zerobugteam-zekkk/Porto-Redesign), repository ini tetap menjadi dokumentasi perjalanan dan evolusi desain ZeroBug Team.

Cocok untuk:
- 💼 Showcase proyek & pengalaman developer
- 🌐 Personal branding & online presence
- 📄 CV / resume digital
- 🎯 Landing page portofolio sederhana

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 🏠 **Landing Page** | Halaman utama dengan hero section yang menarik |
| 📂 **Project Showcase** | Daftar proyek yang pernah dikerjakan dengan deskripsi |
| 👤 **Tentang Kami** | Section profil tim dan visi ZeroBug Team |
| 🛠️ **Tech Stack Display** | Badge dan ikon teknologi yang dikuasai |
| 📱 **Responsive Design** | Tampilan yang menyesuaikan di berbagai ukuran layar |
| 🔗 **Social Links** | Integrasi link ke GitHub, LinkedIn, dan kontak |
| ⚡ **Lightweight** | Kode ringan, loading cepat tanpa framework berat |
| 🎨 **Custom Styling** | Desain kustom dengan CSS murni + Bootstrap |

---

## 🛠️ Tech Stack

| Layer | Teknologi |
|-------|-----------|
| **Markup** | HTML5 Semantic |
| **Styling** | CSS3 + Bootstrap |
| **Interactivity** | Vanilla JavaScript |
| **Icons** | Bootstrap Icons / Font Awesome |
| **Fonts** | Google Fonts |
| **Deploy** | GitHub Pages / Static Host |

---

## 📂 Struktur Folder

```
Portofoli0/
├── 📁 assets/
│   ├── 📁 css/
│   │   ├── style.css           # 🎨 Custom stylesheet utama
│   │   └── bootstrap.min.css   # 📦 Bootstrap framework
│   ├── 📁 js/
│   │   ├── main.js             # ⚡ Logika interaktif
│   │   └── bootstrap.bundle.min.js
│   ├── 📁 images/
│   │   ├── profile.png         # 👤 Foto profil tim
│   │   ├── projects/           # 🖼️ Thumbnail proyek
│   │   └── icons/              # 🎯 Icon tambahan
│   └── 📁 fonts/               # 🔤 Font lokal (opsional)
├── index.html                  # 🚪 Entry point / Landing page
├── about.html                  # 👤 Halaman tentang tim
├── projects.html               # 📂 Halaman daftar proyek
├── contact.html                # 📧 Halaman kontak
├── README.md                   # 📄 Dokumentasi proyek
└── LICENSE                     # 📜 File lisensi MIT
```

---

## ⚙️ Alur Kerja Sistem

```
┌─────────────┐     ┌──────────────┐     ┌─────────────┐
│   🧑 User   │────▶│  Buka Browser │────▶│  index.html  │
│  (Visitor)  │     │   (GitHub/Local)│     │   (Landing)  │
└─────────────┘     └──────────────┘     └──────┬──────┘
                                                  │
                              ┌───────────────────┼───────────────────┐
                              │                   │                   │
                              ▼                   ▼                   ▼
                         ┌─────────┐      ┌─────────────┐      ┌──────────┐
                         │ 🏠 Home │      │ 👤 About     │      │ 📂 Projects│
                         │ Section │      │  Section     │      │  Section   │
                         └─────────┘      └─────────────┘      └──────────┘
                              │                   │                   │
                              └───────────────────┼───────────────────┘
                                                  │
                                                  ▼
                                          ┌─────────────┐
                                          │ 🎨 CSS + JS  │
                                          │  (Render UI) │
                                          └──────┬──────┘
                                                 │
                                                 ▼
                                          ┌─────────────┐
                                          │ 📱 Responsive│
                                          │  (All Devices)│
                                          └─────────────┘
```

1. **Akses Website** → User/visitor membuka link portofolio di browser
2. **Load Landing Page** → `index.html` dimuat sebagai halaman utama
3. **Navigasi Section** → User menjelajahi Home, About, Projects, dan Contact
4. **Apply Styling** → CSS & Bootstrap mengatur layout, warna, dan typography
5. **Interactivity** → JavaScript menangani animasi sederhana dan efek hover
6. **Responsive** → Layout menyesuaikan otomatis sesuai ukuran layar device

---

## 🚀 Cara Install

### 1. Clone Repository
```bash
git clone https://github.com/zerobugteam-zekkk/Portofoli0.git
cd Portofoli0
```

### 2. Buka di Browser

**Opsi A — Langsung buka file:**
```bash
# Buka file index.html di browser favorit
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

**Opsi B — Menggunakan Live Server (VS Code):**
1. Install ekstensi **Live Server** di VS Code
2. Klik kanan pada `index.html` → **Open with Live Server**
3. Browser akan terbuka otomatis di `http://127.0.0.1:5500`

**Opsi C — Menggunakan Python HTTP Server:**
```bash
# Python 3
python -m http.server 8000

# Akses via browser:
http://localhost:8000
```

### 3. Deploy ke GitHub Pages (Opsional)

1. Push repository ke GitHub
2. Masuk ke **Settings** → **Pages**
3. Pilih branch `main` dan folder `/ (root)`
4. Klik **Save** — website akan live dalam beberapa menit

---

## 📸 Screenshot

> **Tambahkan screenshot preview di sini**
>
> Contoh:
> - 🖥️ Desktop View (Full HD)
> - 📱 Mobile View (iPhone/Android)
> - 🏠 Hero Section
> - 📂 Projects Showcase

---

## ✨ Evolusi ke Versi 2.0

| Aspek | Portofoli0 (v1) | Porto-Redesign (v2) |
|-------|-----------------|---------------------|
| **Desain** | Klasik & Sederhana | Modern & Minimalis |
| **Responsif** | Parsial | Fully Responsive |
| **Performa** | Standar | Optimized & Cepat |
| **Animasi** | Dasar | Smooth Transitions |
| **Struktur Kode** | Flat | Modular & Terorganisir |
| **Bootstrap** | v4 / Dasar | v5 (Latest) |
| **SEO** | Dasar | Semantic HTML5 + Meta Tags |

> 📌 **Lihat versi terbaru:** [Porto-Redesign v2.0](https://github.com/zerobugteam-zekkk/Porto-Redesign)

---

## 🔗 Link Terkait

| Platform | Link |
|----------|------|
| 🌐 **Live Demo** | [zerobug.site.je] |
| 🎨 **Versi Kedua** | [Porto-Redesign](https://github.com/zerobugteam-zekkk/Porto-Redesign) |
| 📧 **Email** | [zerobugteam@gmail.com] |

---

## 🤝 Kontribusi

Kontribusi sangat diterima! Jika ingin menambahkan fitur atau memperbaiki bug:

1. **Fork** repository ini
2. Buat **branch** baru: `git checkout -b fitur/nama-fitur`
3. **Commit** perubahan: `git commit -m "feat: tambahkan fitur X"`
4. **Push** ke branch: `git push origin fitur/nama-fitur`
5. Buat **Pull Request** ke branch `main`

---

## 📄 Lisensi

Project ini dilisensikan di bawah [MIT License](LICENSE).

---

<div align="center">
  <sub>Dibuat oleh <a href="https://github.com/zerobugteam-zekkk">@zerobugteam-zekkk</a> — ZeroBug Team</sub>
  <br>
  <sub>Full-Stack Developer | Clean Code | Modern Web Solutions</sub>
</div>
