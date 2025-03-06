# 📝 **Markdown Cheat Sheet (Basic & Extended)**  

**Markdown** adalah bahasa markup ringan yang digunakan untuk memformat teks dengan sintaks yang mudah dibaca dan ditulis. Markdown sering digunakan untuk dokumentasi, blogging, dan README di GitHub, GitLab, serta Bitbucket.  

Panduan ini mencakup:  
1. **Basic Syntax (Sintaks Dasar)**  
2. **Extended Syntax (Sintaks Tambahan)**

---

> **Referensi utama:**  
> - [The Markdown Guide](https://www.markdownguide.org)  
> - [Basic Syntax](https://www.markdownguide.org/basic-syntax/)  
> - [Extended Syntax](https://www.markdownguide.org/extended-syntax/)  

---

# 📌 **1. Basic Syntax**  
Elemen-elemen berikut merupakan bagian dari desain asli Markdown oleh **John Gruber** dan didukung oleh hampir semua aplikasi Markdown.  

---

## 🔠 **1.1 Heading (Judul)**  
Gunakan tanda `#` di awal baris untuk membuat heading.  

### **Contoh Kode:**
```markdown
# H1 Heading 😎
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading
```

### **Hasil Render:**  
# H1 Heading 😎  
## H2 Heading  
### H3 Heading  
#### H4 Heading  
##### H5 Heading  
###### H6 Heading  

---

## 🔻 **1.2 Horizontal Rule (Garis Horizontal)**  
Gunakan `---`, `___`, atau `***` untuk membuat garis horizontal.  

### **Contoh Kode:**
```markdown
---
___
***
```

### **Hasil Render:**  
---  
___  
***  

---

## ✍ **1.3 Typographic Replacements**  
Beberapa simbol secara otomatis dikonversi menjadi bentuk typographic yang lebih baik.  

### **Contoh Kode:**
```markdown
(c) (C) (r) (R) (tm) (TM) (p) (P) +-  
"Smartypants, double quotes" and 'single quotes'
```

### **Hasil Render:**  
© © ® ® ™ ™ ℗ ℗ ±  
“Smartypants, double quotes” and ‘single quotes’  

---

## 🖥 **1.4 Code & Syntax Highlighting**  

### 🔹 **1.4.1 Inline Code**  
Gunakan backticks `` ` `` untuk menyisipkan kode di dalam teks.  

### **Contoh Kode:**
```markdown
Inline `code`
```

### **Hasil Render:**  
Inline `code`  

---

### 🔹 **1.4.2 Indented Code Block**  
Gunakan indentasi 4 spasi atau tab untuk membuat blok kode.  

### **Contoh Kode:**
```markdown
    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code
```

### **Hasil Render:**
```
    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code  
```  

### Contoh Lainnya
```js
var foo = function(bar) {
  return bar++;
};

console.log(foo(5));
```

---

### 🔹 **1.4.3 Fenced Code Block**  
Gunakan tiga backticks (` ``` `) untuk membuat blok kode, tambahkan bahasa untuk syntax highlighting.  

### **Contoh Kode:**
```markdown
```js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```
```

### **Hasil Render:**
```js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

---

### 🏷 **1.5 List of Supported Languages**  
Berikut adalah beberapa bahasa pemrograman yang umum didukung dalam syntax highlighting:

```markdown
- bash
- bat
- sh
- c
- cpp
- json
- java
- js
- php
- git
- markdown
- dockerfile
- sql
- xml
- yaml
- python
- html
- css
```

**Hasil Render:**  
- bash  
- bat  
- sh  
- c  
- cpp  
- json  
- java  
- js  
- php  
- git  
- markdown  
- dockerfile  
- sql  
- xml  
- yaml  
- python  
- html  
- css  

---

## 🔠 **1.6 Text Formatting (Emphasis & Styling)**  

### 🔹 **1.6.1 Bold**  
Gunakan `**` atau `__` untuk menebalkan teks.  

### **Contoh Kode:**
```markdown
**bold text**  
__bold text__
```

### **Hasil Render:**  
**bold text**  
__bold text__  

---

### 🔹 **1.6.2 Italic**  
Gunakan `*` atau `_` untuk membuat teks miring.  

### **Contoh Kode:**
```markdown
*italicized text*  
_italicized text_
```

### **Hasil Render:**  
*italicized text*  
_italicized text_  

---

### 🔹 **1.6.3 Strikethrough**  
Gunakan `~~` di awal dan akhir teks untuk mencoret teks.  

### **Contoh Kode:**
```markdown
~~Strikethrough~~
```

### **Hasil Render:**  
~~Strikethrough~~  

---

### 🔹 **1.6.4 Highlight**  
Gunakan `==` untuk menyoroti teks.  

### **Contoh Kode:**
```markdown
I need to highlight these ==very important words==.
```

### **Hasil Render:**  
I need to highlight these ==very important words==.  

---

## 🔢 **1.7 Lists**  

### 🔹 **1.7.1 Ordered List**  
Gunakan angka `1.` diikuti oleh spasi.  

### **Contoh Kode:**
```markdown
1. First item
2. Second item
3. Third item
```

### **Hasil Render:**  
1. First item  
2. Second item  
3. Third item  

### Nested List
- Item 1
  - Sub-item 1
  - Sub-item 2
- Item 2

---

### 🔹 **1.7.2 Unordered List**  
Gunakan `-`, `+`, atau `*` untuk membuat daftar tidak berurutan.  

### **Contoh Kode:**
```markdown
- First item
- Second item
- Third item
```

### **Hasil Render:**  
- First item  
- Second item  
- Third item  

---

## 📌 **1.8 Blockquote**  
Gunakan `>` untuk membuat kutipan.  

### **Contoh Kode:**
```markdown
> This is a blockquote.
```

### **Hasil Render:**  
> This is a blockquote.  

---

## 🔗 **1.9 Links & Images**  

### 🔹 **1.9.1 Link**  

### **Contoh Kode:**
```markdown
[Markdown Guide](https://www.markdownguide.org)
```

### **Hasil Render:**  
[Markdown Guide](https://www.markdownguide.org)  

---

### 🔹 **1.9.2 Image**  

### **Contoh Kode:**
```markdown
![alt text](https://www.markdownguide.org/assets/images/tux.png)
```

### **Hasil Render:**  
![alt text](https://www.markdownguide.org/assets/images/tux.png)

---

Baik, saya akan lanjutkan dengan **Bagian 2: Extended Syntax** secara lengkap dan menyeluruh.  

---

# 📌 **2. Extended Syntax**  
Fitur-fitur ini tidak ada dalam desain asli Markdown oleh John Gruber, tetapi didukung oleh banyak implementasi modern seperti **GitHub Flavored Markdown (GFM)**.

---

## 📊 **2.1 Tables (Tabel)**  
Gunakan `|` untuk membuat tabel, dan `---` untuk memisahkan header.  

### **Contoh Kode:**
```markdown
| Name     | Age | City      |
|----------|----|-----------|
| Alice    | 24 | New York  |
| Bob      | 30 | London    |
| Charlie  | 27 | Tokyo     |
```

### **Hasil Render:**  
| Name    | Age | City     |
|---------|-----|---------|
| Alice   | 24  | New York |
| Bob     | 30  | London   |
| Charlie | 27  | Tokyo    |

---

### 🔹 **2.1.1 Aligning Text in Tables**  
Tambahkan `:` sebelum atau sesudah `---` untuk mengatur posisi teks.  

### **Contoh Kode:**
```markdown
| Left-Aligned | Center-Aligned | Right-Aligned |
|:------------|:--------------:|-------------:|
| Text 1      | Text 2         | Text 3      |
| Text 4      | Text 5         | Text 6      |
```

### **Hasil Render:**  
| Left-Aligned | Center-Aligned | Right-Aligned |
|:------------|:--------------:|-------------:|
| Text 1      | Text 2         | Text 3      |
| Text 4      | Text 5         | Text 6      |

---

## 🎨 **2.2 Task List (Daftar Tugas)**  
Gunakan `- [ ]` untuk item belum selesai dan `- [x]` untuk item yang sudah selesai.  

### **Contoh Kode:**
```markdown
- [x] Task 1 (Selesai)
- [ ] Task 2 (Belum selesai)
- [ ] Task 3 (Belum selesai)
```

### **Hasil Render:**  
- [x] Task 1 (Selesai)  
- [ ] Task 2 (Belum selesai)  
- [ ] Task 3 (Belum selesai)  

---

## ⬇️ **2.3 Collapsible Section (Bagian yang Bisa Diperluas/Sembunyikan)**  
Gunakan `<details>` dan `<summary>` untuk membuat bagian yang bisa diklik untuk diperluas.  

### **Contoh Kode:**
```markdown
<details>
  <summary>Klik untuk melihat isi</summary>
  Ini adalah teks tersembunyi yang muncul saat diklik.
</details>
```

### **Hasil Render:**  
<details>
  <summary>Klik untuk melihat isi</summary>
  Ini adalah teks tersembunyi yang muncul saat diklik.
</details>

---

## 🎯 **2.4 Footnotes (Catatan Kaki)**  
Gunakan `[^1]` dalam teks dan buat definisi di bagian bawah dengan `[^1]:`.  

### **Contoh Kode:**
```markdown
Markdown memiliki fitur catatan kaki[^1].

[^1]: Ini adalah catatan kaki.
```

### **Hasil Render:**  
Markdown memiliki fitur catatan kaki[^1].  

[^1]: Ini adalah catatan kaki.  

---

## ⏩ **2.5 Automatic URL Linking**  
Tautan yang tidak diberi format `[teks](URL)` tetap bisa diklik secara otomatis.  

### **Contoh Kode:**
```markdown
https://www.github.com
```

### **Hasil Render:**  
https://www.github.com  

---

## 🏗 **2.6 Definition Lists (Daftar Definisi)**  
Gunakan `:` untuk mendefinisikan istilah.  

### **Contoh Kode:**
```markdown
Markdown
: Sebuah format teks ringan.

GitHub
: Platform pengembangan perangkat lunak.
```

### **Hasil Render:**  
**Markdown**  
: Sebuah format teks ringan.  

**GitHub**  
: Platform pengembangan perangkat lunak.  

---

## 📜 **2.7 Subscript & Superscript**  

### **Subscript (Teks Bawah)**  
Gunakan `~` di awal dan akhir teks.  

### **Contoh Kode:**
```markdown
H~2~O adalah rumus kimia air.
```

### **Hasil Render:**  
H~2~O adalah rumus kimia air.  

---

### **Superscript (Teks Atas)**  
Gunakan `^` di awal dan akhir teks.  

### **Contoh Kode:**
```markdown
E = mc^2^ adalah rumus relativitas Einstein.
```

### **Hasil Render:**  
E = mc^2^ adalah rumus relativitas Einstein.  

---

## 🏷 **2.8 Emoji (Emoticon)**  
Gunakan format `:emoji_name:` sesuai daftar emoji di [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet).  

### **Contoh Kode:**
```markdown
:wink: :cry: :laughing: :yum: :fire: :heart: :rocket: :100: :man_technologist: :woman_technologist: :white_check_mark: :one: :pushpin: &rarr; 
```

### **Hasil Render:**  
😉 😢 😆 😋 🔥 ❤️ 🚀 💯  

:man_technologist: :woman_technologist: :white_check_mark: :one: :pushpin: &rarr; 

---

## 🎶 **2.9 Adding Music in Markdown**  
Markdown sendiri tidak mendukung pemutaran musik, tetapi kita bisa menyisipkan embed dari SoundCloud atau YouTube menggunakan HTML.  

### **Contoh Kode:**
```markdown
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zi_XLOBDo_Y" frameborder="0" allowfullscreen></iframe>
```

### **Hasil Render:**  
*(Tampilkan video jika di-render dalam HTML, tidak ditampilkan di Markdown biasa.)*  

---

## 🖼 **2.10 Adding GIFs**  
Markdown mendukung **GIF** sama seperti gambar biasa.  

### **Contoh Kode:**
```markdown
![Funny GIF](https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif)
```

### **Hasil Render:**  
![Funny GIF](https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif)  

---

## 🔍 **2.11 Adding Checkboxes (Checkbox Input Form)**  
Jika menggunakan Markdown dalam HTML (misalnya di GitHub Issues atau README), kita bisa menambahkan checkbox yang bisa diubah statusnya.  

### **Contoh Kode:**
```markdown
- [ ] Task belum selesai
- [x] Task selesai
```

### **Hasil Render:**  
- [ ] Task belum selesai  
- [x] Task selesai  

---

# 🎯 **Kesimpulan**  
Markdown adalah format yang sangat fleksibel dan berguna untuk berbagai keperluan, seperti:  
✅ **Dokumentasi proyek**  
✅ **Blogging (dengan Jekyll atau Hugo)**  
✅ **README di GitHub, GitLab, Bitbucket**  
✅ **Penulisan artikel dan presentasi**  

Dengan memahami **Basic Syntax** dan **Extended Syntax**, kita bisa membuat dokumen yang lebih kaya dan lebih menarik secara visual. 🚀🔥  

