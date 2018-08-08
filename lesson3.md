---

### LESSON 03: PEMBAHASAN RINCI HTML

---

### Objectives
1. Peserta mengerti perintah untuk menyisipkan icon, meta data, video, list, dan line break.
2. Peserta mengerti struktur website dibentuk dari **HTML** `div`.
3. Peserta mampu memahami box model pada **CSS**.

---

### Material

#### 1. HTML
* Icon
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
      <link rel="icon" type="image/png" href="images/icon.png">
     </head>
     <body>
        This is body...
     </body>
  </html>
  ```
* Meta
  ```html
    <html>
      <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web
        tutorial">
        <meta name="author" content="Alexander">
      </head>
      <body>
        This is body...
      </body>
    </html>
  ```  
* Line Break
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web tutorial">
        <meta name="author" content="Alexander">
     </head>
     <body>
        This is the first line sentece. <br/>
        This is the second line sentence.
     </body>
  </html>
  ```
* Unordered List
  ```html
  <html>
    <head>
      <title>TITLE OF WEBSITE</title>
      <meta charset="UTF-8">
      <meta name="description" content="CodingMum Web tutorial">
      <meta name="author" content="Alexander">
    </head>
    <body>
      <h2>Alat membuat mie goreng</h2>
      <ul>
        <li>Panci</li>
        <li>Piring</li>
        <li>Sendok</li>
        <li>Kompor Gas</li>
      </ul>
    </body>
  </html>
  ```
* Ordered List
  ```html
  <html>
    <head>
      <title>TITLE OF WEBSITE</title>
      <meta charset="UTF-8">
      <meta name="description" content="CodingMum Web tutorial">
      <meta name="author" content="Alexander">
    </head>
    <body>
      <h2>Langkah membuat mie:</h2>
      <ol>
        <li>Rebus air dalam panci</li>
        <li>Ambil mie instant</li>
        <li>Masukan dalam air yang sudah mendidih</li>
        <li>Setelah matang mie-nya, angkat dan tiriskan</li>
        <li>Masukan bumbu mie intant dalam piring</li>
        <li>Masukan mie yang sudah tiris</li>
        <li>Aduk rata mie dengan bumbu</li>
      </ol>
    </body>
  </html>
  ```
* Video
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web tutorial">
        <meta name="author" content="Alexander">
     </head>
     <body>
     This is video of CodingMum:<br/>
        <video id="video-1" width="320" height="240" controls>
           <source src="videos/CodingMum_Mancanegara.mp4" type="video/mp4" />
        </video>
     </body>
  </html>
  ```  
* Div
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web tutorial">
        <meta name="author" content="Alexander">
     </head>
     <body>
      <div style=“width:200px;height:400px;” >Ini adalah sebuah persegi</div>
      <div style=“width:400px;height:400px;” >Ini adalah sebuah kotak</div>
     </body>
  </html>
  ```

#### 2. CSS Box Model
* Border
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web tutorial">
        <meta name="author" content="Alexander">
     </head>
     <body>
      <div style=“width:200px;height:400px;border: 5px solid red;” >Ini adalah sebuah persegi</div>
      <div style=“width:400px;height:400px;border: 5px dotted blue;” >Ini adalah sebuah kotak</div>
     </body>
  </html>
  ```
* Margin
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web tutorial">
        <meta name="author" content="Alexander">
     </head>
     <body>
      <div style=“width:200px;height:400px;border: 5px solid red;margin:30px;” >Ini adalah sebuah persegi</div>
      <div style=“width:400px;height:400px;border: 5px dotted blue;margin:60px;” >Ini adalah sebuah kotak</div>
     </body>
  </html>
  ```
* Padding
  ```html
  <html>
     <head>
        <title>TITLE OF WEBSITE</title>
        <meta charset="UTF-8">
        <meta name="description" content="CodingMum Web tutorial">
        <meta name="author" content="Alexander">
     </head>
     <body>
      <div style=“width:200px;height:400px;border: 5px solid red;margin:30px;padding:60px;” >Ini adalah sebuah persegi</div>
      <div style=“width:400px;height:400px;border: 5px dotted blue;margin:60px;padding:30px;” >Ini adalah sebuah kotak</div>
     </body>
  </html>
  ```
---
