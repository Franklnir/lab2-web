# lab2-web
<h1 langkah 1 membuat dokumen html

## Deklarasi HTML
- <!DOCTYPE html>: Menandakan bahwa ini adalah dokumen HTML5.
## Bagian <head>
- <meta charset="UTF-8">`**: Mengatur pengkodean karakter ke UTF-8.
- <meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Membuat tampilan responsif di perangkat seluler.
- <title>CSS Dasar</title>`: Menetapkan judul halaman sebagai "CSS Dasar".
## Bagian <body>
- Header: <h1>CSS Internal dan <i>Inline CSS</i></h1> menampilkan judul dengan teks miring.
- Navigasi (<nav>): Tiga tautan untuk menuju halaman "CSS Dasar", "CSS Eksternal", dan "HTML Dasar".
- ID Selector (#intro): <div id="intro"> digunakan untuk mengatur gaya khusus
- Class Selector (.button .btn-primary): Tombol bertuliskan "Informasi selengkapnya" dengan gaya yang ditetapkan melalui kelas CSS.
  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>
  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>
  <div id="intro">
    <h1>Hello World</h1>
    <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
    <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
    Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
  </div>
</body>
</html>

![image](https://github.com/user-attachments/assets/addbc723-ab8d-4566-8b59-ecd47e44c6af)







### langkah 2 Mendeklarasikan CSS Internal
#<style>: Menyertakan CSS internal yang mengatur gaya elemen pada halaman.
#body: Menentukan font untuk seluruh halaman dengan menggunakan 'Open Sans', dan memilih jenis sans-serif sebagai alternatif.
#header: Mengatur tinggi minimum elemen header menjadi 80px dan menambahkan border di bagian bawah dengan warna #77CCEF.
#h1: Mengatur ukuran font menjadi 24px, memberikan warna teks biru (#0F189F).
#h1 i: Mengubah warna teks miring di dalam elemen <h1> menjadi abu-abu (#6d6a6b).

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>
  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>
  <div id="intro">
    <h1>Hello World</h1>
    <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
    <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
    Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
  </div>
</body>
</html>
<head>
    <title>CSS Dasar</title>
    <style>
      body {
        font-family: 'Open Sans', sans-serif;
      }
      header {
        min-height: 80px;
        border-bottom: 1px solid #77CCEF;
      }
      h1 {
        font-size: 24px;
        color: #0F189F;
        text-align: center;
        padding: 20px 10px;
      }
      h1 i {
        color: #6d6a6b;
      }
    </style>
  </head>
  
![image](https://github.com/user-attachments/assets/9e813819-67b8-41b2-a77e-08ee437241e3)









###langkah 3 Menambahkan Inline CSS
#text-align: center;: Mengatur teks dalam paragraf agar terletak di tengah.
#color: #ccd8e4;: Mengatur warna teks menjadi abu-abu muda (#ccd8e4).

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>
  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>
  <div id="intro">
    <h1>Hello World</h1>
    <p style="text-align: center; color: #ccd8e4;">
     Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
    <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
    Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
  </div>
</body>
</html>
<head>
    <title>CSS Dasar</title>
    <style>
      body {
        font-family: 'Open Sans', sans-serif;
      }
      header {
        min-height: 80px;
        border-bottom: 1px solid #77CCEF;
      }
      h1 {
        font-size: 24px;
        color: #0F189F;
        text-align: center;
        padding: 20px 10px;
      }
      h1 i {
        color: #6d6a6b;
      }
    </style>
  </head>
  
![image](https://github.com/user-attachments/assets/5f6c4764-3a7b-457e-80b4-ebc0df128d87)








###langkah 4 Membuat CSS Eksternal
#background: #20A759;: Menetapkan warna latar belakang hijau.
#color: #fff;: Mengatur warna teks menjadi putih.
#padding: 10px;: Memberikan ruang di dalam elemen navigasi.
#nav a: Mengatur gaya untuk semua tautan (<a>) di dalam elemen navigasi.
#color: #fff;: Menetapkan warna teks tautan menjadi putih.
#text-decoration: none;: Menghilangkan garis bawah pada tautan.
#padding: 10px 20px;: Memberikan ruang di sekitar teks tautan (10px vertikal, 20px horizontal).

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Dasar</title>
</head>
<body>
  <header>
    <h1>CSS Internal dan <i>Inline CSS</i></h1>
  </header>
  <nav>
    <a href="lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_eksternal.html">CSS Eksternal</a>
    <a href="lab1_tag_dasar.html">HTML Dasar</a>
  </nav>
  <div id="intro">
    <h1>Hello World</h1>
    <p style="text-align: center; color: #ccd8e4;">
     Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
    <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
    Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
  </div>
</body>
</html>
<head>
    <title>CSS Dasar</title>
    <style>
      body {
        font-family: 'Open Sans', sans-serif;
      }
      header {
        min-height: 80px;
        border-bottom: 1px solid #77CCEF;
      }
      h1 {
        font-size: 24px;
        color: #0F189F;
        text-align: center;
        padding: 20px 10px;
      }
      h1 i {
        color: #6d6a6b;
      }
    </style>
  </head>
  <link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>
  
![image](https://github.com/user-attachments/assets/3031cbfc-904f-4d37-80a3-30cdda93f82c)










###langkah 5 Menambahkan CSS Selector dan semua style yang ada pada style_ekstenal.css
# ID selector Mengatur gaya pada elemen HTML dengan atribut id, yang bersifat unik.
# selector mengatur gaya pada satu atau lebih elemen HTML dengan atribut class, yang dapat digunakan berkali-kali.

nav {
    background: #20A759; 
    color: #fff;        
    padding: 10px;      
  }
  
  nav a {
    color: #fff;         
    text-decoration: none; 
    padding: 10px 20px;  
  }
  
  nav .active,
  nav a:hover {
    background: #0B6B3A; 
  }
  #intro {
    background: #418fb1; 
    border: 1px solid #099249; 
    min-height: 100px; 
    padding: 10px; 
  }
  #intro h1 {
    text-align: left; 
    border: 0; 
    color: #fff; 
  }
.button {
  padding: 15px 20px; 
  background: #bebcbd; 
  color: #fff; 
  display: inline-block; 
  margin: 10px; 
  text-decoration: none; 
}
.btn-primary {
  background: #E42A42; 
}
  
![image](https://github.com/user-attachments/assets/e86598d3-23b6-48db-adfc-705286973ef1)




