# Dynamic One Piece Website

| Detail      | Keterangan      |
| ----------- | --------------- |
| Nama        | Carlos Louis Fernando   |
| Kelas       | TI.23.A5        |
| NIM         | 312310458       |
| Mata Kuliah | PEMROGRAMAN WEB |

## 📑 Deskripsi Project

Website dinamis dengan tema One Piece yang dibangun menggunakan PHP, Bootstrap, dan DataTables. Website ini menampilkan implementasi berbagai fitur web modern seperti responsive design, dynamic routing, dan interactive data tables.

## 🎯 Fitur Interaktif & Navigasi

### 🔝 Navigation Bar

1. **Logo & Brand**

   - Logo One Piece dengan animasi
   - Brand text "ONE PIECE" dengan styling custom

2. **Menu Utama**

   - Home (dengan ikon rumah)
   - About (dengan ikon info)
   - Contact (dengan ikon amplop)
   - Dropdown Menu "Belajar":
     - DataTables
     - Another Action
     - Something else

3. **Search Bar**
   - Input field dengan placeholder "Search..."
   - Tombol search dengan ikon
   - Animasi hover pada tombol

### 📱 Responsive Features

- Hamburger menu untuk tampilan mobile
- Collapsible navbar
- Responsive grid system
- Adaptive images

## 📄 Detail Halaman & Fitur

### 1. Home Page (home.php)

![alt text](<Cuplikan layar 2024-11-05 111033.png>)
![alt text](<Cuplikan layar 2024-11-05 144310-1.png>)

#### Hero Section

- Welcome message dengan typography custom
- Subtitle dengan efek gradient
- Background dengan overlay semi-transparan

#### Profile Card

- Foto profile dengan border circular
- Nama dan deskripsi
- Social media buttons:
  - GitHub
  - LinkedIn
  - Instagram
- Hover effect pada card

#### Feature Cards

1. **Responsive Design Card**

   - Ikon mobile
   - Deskripsi fitur
   - Hover animation

2. **Dynamic Tables Card**

   - Ikon table
   - Deskripsi DataTables
   - Interactive hover

3. **Modern UI Card**
   - Ikon brush
   - Deskripsi UI/UX
   - Transition effects

### 2. About Page (about.php)

![alt text](<Cuplikan layar 2024-11-05 111052.png>)

#### Profile Section

- Large profile image
- Nama dan title
- Deskripsi personal
- Background dengan efek blur

#### Skills Section

- Technical Skills dengan badges:
  - HTML5
  - CSS3
  - JavaScript
  - PHP
  - MySQL
  - Bootstrap
- Hover effects pada badges
- Responsive layout

### 3. Contact Page (contact.php)

![alt text](<Cuplikan layar 2024-11-05 144823.png>)

#### Contact Form

- Input fields:
  - Name (required)
  - Email (with validation)
  - Message (textarea)
- Submit button dengan hover effect
- Form validation

#### Contact Information

- Location dengan icon
- Email address dengan link
- Phone number
- Social media links dengan hover effects:
  - GitHub
  - LinkedIn
  - Instagram

### 4. DataTables Page (datatables.php)

![alt text](<Cuplikan layar 2024-11-05 111728.png>)

#### Table Features

- Sorting functionality:
  - Name
  - Position
  - Office
  - Age
  - Start date
  - Salary
- Search functionality
- Pagination controls
- Entries per page selector
- Responsive table layout

- # Web Pages Overview

Ini adalah penjelasan untuk dua halaman yang terdapat dalam proyek ini: halaman **Registration Form** dan halaman **404 Page**. Kedua halaman ini dibuat dengan HTML, CSS, dan menggunakan Bootstrap untuk menjaga tampilan yang responsif dan menarik.

---

## Registration Form Page

Halaman ini berfungsi sebagai form registrasi sederhana yang dirancang untuk mendapatkan data pengguna seperti email dan kata sandi.
![image](https://github.com/user-attachments/assets/fe89dd17-1997-4ac3-9d2c-cd98ca979fcb)


### Struktur Utama

- **Container**: Menggunakan `<div class="container py-5">` untuk memberi padding vertikal, sehingga form tetap berada di tengah dengan tampilan yang rapi.
- **Bootstrap Grid**: Kombinasi `<div class="row justify-content-center">` dan `<div class="col-md-8">` untuk memastikan form berada di tengah layar pada perangkat yang lebih besar.
- **Feature Card**: Bagian utama form yang membungkus semua elemen input, memberi struktur layout form.

### Elemen Form

- **Heading**: Menggunakan `<h2>` untuk menampilkan judul "Registration Form" dengan teks yang berwarna terang.
- **Input Email**: Field input email disertai label "Email address" dan bantuan teks yang memberi tahu bahwa email pengguna aman.
- **Input Password**: Field input untuk kata sandi dengan label "Password."
- **Checkbox**: Memberikan pilihan untuk pengguna menandai form dengan label "Check me out."
- **Tombol Submit**: Tombol berwarna kuning (`btn btn-warning`) yang digunakan untuk mengirimkan data form.

---

## 404 Page

Halaman ini muncul ketika halaman yang dicari tidak ditemukan. Halaman 404 ini memiliki tema petualangan yang terinspirasi dari Grand Line di dunia **One Piece**, memberikan pengalaman pengguna yang menarik dengan animasi dan pesan kreatif.
![image](https://github.com/user-attachments/assets/89fc94b2-a631-4086-92ac-84c4b271a0a6)


### Struktur Utama

- **Container Utama**: Menggunakan `min-vh-100 d-flex align-items-center justify-content-center` agar konten selalu berada di tengah layar dengan tinggi minimum yang sesuai.
- **Error Container**: Menyertakan `.error-container` dengan efek transparan, **blur**, dan rounded borders untuk tampilan yang halus dan menarik.

### Elemen Utama

- **Gambar Error**: Menampilkan logo One Piece dengan kelas `.error-image`, disertai animasi rotasi yang memberikan efek berputar secara terus-menerus.
- **Kode 404**: Teks besar "404" dengan animasi glitch, memberi efek pergerakan pada teks agar terlihat lebih hidup.
- **Pesan Error**: Menampilkan pesan "Oops! Looks like this page got lost in the Grand Line!" untuk memperjelas bahwa halaman yang dicari tidak ditemukan.
- **Tombol Kembali**: Tombol "Back to Safe Waters" yang membawa pengguna kembali ke halaman utama dengan animasi hover interaktif.

### CSS dan Animasi

- **Animasi Float**: `.float` memberi efek mengambang ke kontainer error untuk gerakan naik-turun.
- **Rotasi Gambar**: `.rotate` menambahkan efek rotasi terus-menerus pada logo untuk tampilan dinamis.
- **Efek Glitch**: `.glitch` memberikan efek glitch pada teks "404" dengan perubahan posisi untuk tampilan modern dan menarik.

---

## Teknologi yang Digunakan

- **HTML & CSS**: Digunakan untuk struktur dan styling halaman.
- **Bootstrap**: Untuk grid layout yang responsif dan komponen bergaya.
- **Font Awesome**: Digunakan untuk ikon kapal pada tombol kembali di halaman 404.

---

Ini adalah deskripsi singkat mengenai halaman **Registration Form** dan halaman **404 Page** dalam proyek ini. Kedua halaman dirancang untuk pengalaman pengguna yang menarik dengan tampilan visual yang unik.


### 🦶 Footer Section

#### About Column

- About One Piece description
- Social media icons:
  - Facebook
  - Twitter
  - Instagram
  - YouTube

#### Quick Links

- Home
- About
- Contact
- DataTables
- Hover effects pada links

#### Contact Info

- Location
- Phone
- Email
- Social media links

## 🎨 Styling Elements

### Color Scheme

```css
:root {
  --primary: #d32f2f; /* Red */
  --secondary: #fdd835; /* Yellow */
  --accent: #ff9800; /* Orange */
  --dark: #1a1a1a; /* Dark Gray */
  --light: #ffffff; /* White */
}
```

### Special Effects

1. **Glass Morphism**

   - Background blur
   - Transparent overlay
   - Border light effect

2. **Gradients**

   - Navbar gradient
   - Button gradients
   - Background effects

3. **Animations**
   - Hover transitions
   - Smooth scrolling
   - Loading effects
