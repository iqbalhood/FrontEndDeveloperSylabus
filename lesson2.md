
### LESSON 02: PENGENALAN HTML DAN CSS

---

### Objectives
1. Peserta mampu membuat **HTML** dasar dengan text editor.
    * Title
    * Heading
    * Image
    * Paragraph
    * Links
2. Peserta memahami cara menyisipkan **CSS** pada sebuah halaman **HTML**.
    * Inline
    * Internal
    * Eksternal

---

### Software yang harus dibutuhkan
  * [Sublime](https://www.sublimetext.com/3)
  * [Google Chrome](https://support.google.com/chrome/answer/95346?co=GENIE.Platform%3DDesktop&hl=id)

---

### Material

#### 1. HTML
* Title
  ```html
  <html>
    <head>
        <title>Belajar Membuat Title</title>
    </head>
  </html>
  ```
* Heading
  ```html
  <html>
    <head>
        <title>Belajar Membuat Heading</title>
    </head>
    <body>
      Hallo
      <h1>Heading 1</h1>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <h4>Heading 4</h4>
      <h5>Heading 5</h5>
      <h6>Heading 6</h6>
    </body>
  </html>
  ```
* Image
  ```html
  <html>
    <head>
        <title>Belajar Menyisipkan Gambar</title>
    </head>
    <body>
  <img src="images/doraemon.jpg" alt="Gambar Doraemon JPG" width="104" height="142">
  <img src="images/doraemon.gif" alt="Gambar Doraemon GIF" width="104" height="142">
  <img src="images/doraemon.png" alt="Gambar Doraemon PNG" width="104" height="142">
    </body>
  </html>
  ```
* Paragraph
  ```html
  <html>
    <head>
        <title>Belajar Membuat Paragraf</title>
    </head>
    <body>
  <p>Ini adalah paragraf satu.</p>
  <p>Ini adalah paragraf dua.</p>
    </body>
  </html>
  ```
* Anchor / Link
  ```html
  <html>
    <head>
        <title>Belajar Membuat Links</title>
    </head>
    <body>
        <!--Eksternal link-->
        <a href="https://www.facebook.com">Link ke facebook</a>
        <!--Internal link-->
        <a href="kontak.html">Halaman Kontak</a>
    </body>
  </html>
  ```

#### 2. CSS
* Inline CSS
  ```html
  <html>
    <head>
        <title>Belajar Membuat Links</title>
    </head>
    <body>
  <h1 style="color:blue;">Ini warna biru</h1>
  <h1 style="color:green;">Ini warna hijau</h1>
    </body>
  </html>
  ```

* Internal CSS
  ```html
  <html>
    <head>
        <title>Belajar Membuat Links</title>
        <style>
          body{
            background-color:powderblue;
          }
          h1{
            color:blue;
            text-align:center;
          }
          p{
            color:red;
          }
        </style>
    </head>
    <body>
    <h1>This is Heading</h1>
    <p>This is paragraph</p>
    </body>
  </html>
  ```

---

### Execises
1. Buat file HTML dengan:
    * Judul
    * Gambar
    * Paragraf
    * Link
2. Beri style pada website yang dibuat di latihan pertama.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 02** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 02** ini?

---

### References
1. [Intro to HTML and CSS](https://www.udacity.com/course/intro-to-html-and-css--ud304 "Intro to HTML and CSS")
2. [HTML & CSS for Beginners](https://www.codecademy.com/en/tracks/htmlcss "HTML & CSS for Beginners")
