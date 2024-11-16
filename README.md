# Semantic--HTML
Latihan Praktikum 2 Semantic HTML


### 1. Tag `<html>` dan `<body>`
- **Codingan 1**: Tidak menyertakan tag `<html>` dan `<body>`. Struktur halaman langsung dimulai dengan `<header>`, sehingga tidak memenuhi standar HTML5.
- **Codingan 2**: Menggunakan tag `<html>` dengan atribut `lang="en"` untuk menunjukkan bahasa halaman adalah bahasa Inggris, serta membungkus seluruh elemen (seperti `<header>`, `<nav>`, `<section>`, dan `<footer>`) di dalam tag `<body>`.

### 2. Tag `<head>`
- **Codingan 1**: Tidak memiliki tag `<head>`, sehingga elemen penting seperti metadata dan tautan ke file CSS eksternal tidak ada.
- **Codingan 2**: Menyertakan tag `<head>` yang lengkap dengan elemen-elemen berikut:
  - `<meta charset="UTF-8">` untuk menentukan encoding karakter,
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` untuk mendukung tampilan responsif di perangkat seluler,
  - `<title>HTML5 Semantic</title>` sebagai judul halaman, dan
  - `<link rel="stylesheet" href="./assets/styles/styles.css">` untuk menghubungkan file CSS eksternal.

### 3. Penutupan Tag
- **Codingan 1**: Tidak memiliki tag penutup `</html>` atau `</body>`, membuat struktur HTML tidak lengkap dan tidak sesuai standar HTML5.
- **Codingan 2**: Menyertakan penutupan tag yang benar untuk `</html>` dan `</body>`, sehingga sesuai dengan standar HTML5.

### 4. Atribut `lang="en"` pada Tag `<html>`
- **Codingan 1**: Tidak menambahkan atribut `lang` pada tag `<html>`.
- **Codingan 2**: Menambahkan atribut `lang="en"` pada tag `<html>`, memberikan informasi kepada mesin pencari dan pembaca layar bahwa halaman menggunakan bahasa Inggris.

### 5. Penyusunan Struktur Halaman
- **Codingan 1**: Struktur halaman hanya terdiri dari elemen dasar seperti `<header>`, `<nav>`, `<section>`, dan `<footer>`, tetapi tidak menyertakan tag `<head>` dan `<body>`.
- **Codingan 2**: Struktur halaman lebih lengkap dengan menyertakan tag `<head>` dan `<body>`, sesuai dengan praktik terbaik pengkodean HTML5.

### 6. Properti CSS `grid-template-columns`
- **Codingan 1**:  
  ```css
  grid-template-columns: 20% 1fr 18;
  ```
  Pengaturan kolom grid menggunakan nilai `18` tanpa satuan, sehingga tidak valid dan berpotensi menyebabkan tata letak yang salah.
- **Codingan 2**:  
  ```css
  grid-template-columns: 20% 1fr 18%;
  ```
  Lebar kolom ketiga ditulis dengan satuan yang benar, yaitu `18%`, sehingga menghasilkan tata letak yang valid.

### 7. Margin pada Elemen `<body>`
- **Codingan 1**: Tidak memberikan margin pada elemen `<body>`.
- **Codingan 2**: Menyertakan aturan `margin: 10px;` pada elemen `<body>`, memberikan jarak antara konten dan tepi jendela browser.

### 8. Kesalahan Penulisan Selector Footer di Codingan 1
- **Codingan 1**: Selector CSS ditulis salah sebagai `I footer { ... }`. Huruf `I` yang tidak diperlukan menyebabkan aturan CSS tidak diterapkan pada elemen `<footer>`.
- **Codingan 2**: Selector ditulis dengan benar sebagai `footer { ... }`, sehingga gaya CSS diterapkan dengan benar pada elemen `<footer>`.
