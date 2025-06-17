## 📝 **README.md**
# 🚀 About Me — HTML Basic Learning

Halo! 👋  
Ini adalah proyek **About Me** sederhana menggunakan _HTML dasar_ — cocok banget buat kamu yang baru mulai belajar HTML. Di sini kamu akan belajar membuat halaman web sederhana dengan elemen-elemen seperti: **heading**, **paragraf**, **gambar**, **list**, dan **link**.

---

## 📌 Apa yang ada di proyek ini?
✅ Halaman HTML sederhana (index.html)  
✅ CSS terpisah untuk latihan styling  
✅ Gambar profil (bisa pakai gambar sendiri!)  
✅ List hobi atau minat  
✅ Link ke profil GitHub  

---

## ⚡ Contoh kode `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>About Me - HTML Basic Learning</title>
  <link rel="stylesheet" href="./style.css">
</head>
<body>
  <div class="container">
    <h1>About Me</h1>
    <img src="assets/images/profile.jpg" alt="Profile Photo">
    <p>Hi! I'm RH. I love coding and sharing knowledge about HTML for beginners.</p>

    <h2>My Hobbies</h2>
    <ul>
      <li>Coding</li>
      <li>Reading</li>
      <li>Gaming</li>
    </ul>

    <p>Check out my <a href="https://github.com/Rh-dt" target="_blank">GitHub Profile</a>!</p>
  </div>
</body>
</html>
````

---

## ⚡ Contoh kode `style.css`

```css
body {
  font-family: sans-serif;
  background-color: #f9f9f9;
  padding: 20px;
}

.container {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  max-width: 600px;
  margin: auto;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

img {
  width: 150px;
  border-radius: 50%;
}
```

---

## 🌟 Cara menjalankan

1️⃣ Salin kode di atas ke file bernama `index.html` dan `style.css`
2️⃣ Buka file `index.html` di browser (Chrome, Edge, Firefox, dll)
3️⃣ Tadaaa! Lihat hasilnya!

> 🎨 **Tips:**
>
> * Ganti foto jadi foto kamu sendiri (taruh di `assets/images/`)
> * Ubah warna atau font di `style.css`
> * Tambahkan elemen baru: tombol, video, dsb

---

## 🙌 Siapa yang buat?

👤 [RH](https://github.com/Rh-dt)

Aku bikin ini untuk berbagi ke teman-teman yang baru mulai belajar HTML. Semangat ngoding yaa! 💻

---

## 💡 License

Proyek ini bebas dipakai untuk belajar dan latihan! 🚀

---

## 📂 **Struktur folder**
```
about-me/
├── index.html
└── assets/
      └── style.css
└── images/
      └── profile.jpg
