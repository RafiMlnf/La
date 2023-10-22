# Lab4Web

### Menjawab pertanyaan dan tugas.
![tugas](https://github.com/RafiMlnf/Lab4Web/assets/115614668/e1121cc1-81e5-45a1-81a1-fe6fee537503)

-----------------------------------------

### 1. Jawaban no 1 (About) - Isi HTML
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container-about">

        <header class="header-about">
            <h1>&lt;h1&gt; <span class="blue-text">About Me</span> &lt;/h1&gt;</h1>
        </header>

        <nav class="nav-about">
            <a href="home.html">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html" class="active">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>

        <section class="about-section">
            <img src="me.png" alt="" class="image-about">
        </section>

        <section id="main-about">
            <div class="box-about">
                <h3>Rafi Maulana Firdaus</h3>
                <p> Let me share a little story. I have a deep interest in digital visuals, and I thoroughly enjoy exploring my imagination and creativity. 
                    I'm skilled in using Adobe Photoshop and often find myself editing things in my spare time. 
                    Lately, I've been learning the basics of web programming.</p>

                <ul>I take great pleasure in collecting and creating memories to cherish in the future. 
                    I love exploring different areas, such as beaches, mountains, and some events in various cities. 
                    I'm usually the one who hosts and designs a holiday semester event on class.</ul>
            </div>
        </section>

        <footer>
            <p>&copy; 2023 - Rafi Maulana Firdaus</p>
        </footer>
    </div>
</body>
</html>
```
--------------------------------------

### Melakukan styling about.html pada CSS

```CSS
/* ---------------------- about.css ----------------------*/
.main-about {
    background-color: #131313;
    height: auto;
    width: auto;
    text-align: center;
}

.about-section {
    background-color: #131313;
    height: max-content;
    width: 80vh;
    text-align: left;
}

.container-about {
    background-color: #131313;
}

/* ---------------------- navigasi ----------------------*/
.nav-about {
    background-color: #131313;
    padding-left: 50px;

}
.nav-about a {
    padding: 15px 25px;
    color: #7c7c7c;
    font-size: 17px;
}

.nav-about a.active,
.nav-about a:hover {
  background-color: #131313;
}
/* ---------------------- navigasi ----------------------*/

/* ---------------------- header ----------------------*/
.header-about {
    background-color: #131313;
    height: 7vh;
    font-family: 'Mermaid';
    padding-left: 60px;
}

.header-about h1 {
    color: #2e2e2e;
    font-size: 25px;
    
}
/* ---------------------- header ----------------------*/

/* ---------------------- box ----------------------*/
.box-about {
    background-color: #131313;
    padding: 100px 0;
    text-align: left;
    padding-left: 60px;
}

.box-about h3 {
    color: #ffffff;
    font-family: 'Mermaid';
    font-size: 50px;
    padding-bottom: 20px;
}

.box-about p {
    margin-right: 100vh;
    font-family: 'Open Sans';
    font-size: 20px;
    text-align: justify;
    padding-bottom: 25px;
}

.box-about ul {
    margin-right: 100vh;
    font-family: 'Open Sans';
    font-size: 20px;
    text-align: justify;
}
/* ---------------------- box ----------------------*/

.image-about {
    width: 1343px;
    height: initial;
    display: block;
}
.blue-text {
    color: #7c7c7c;
    font-size: 35px;
}
```

--------------------------------------

### Ini adalah tampilan akhir about.html setelah dilakukan styling

![abouthtml](https://github.com/RafiMlnf/Lab4Web/assets/115614668/732322f8-2ef6-49fd-b974-4f73b5898dd0)

--------------------------------------

### 2. Jawaban no 2 (Kontak) - Isi HTML

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Layout Sederhana</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>

        <section id="kontak">
            <h2>Kontak</h2>
            <p>Silakan hubungi saya melalui salah satu cara di bawah ini:</p>
            <ul>
                <ul>Alamat: JL. Asep Gaming - No.70</li>
                <ul>Nomor Telepon: 0888888888</li>
                <ul>Email: <a href="mailto:kontak@example.com">asepgaming@gmail.com</a></li>
            </ul>

            <h3>Formulir Kontak</h3>
            <form action="proses_kontak.php" method="post">
                <label for="nama">Nama:</label>
                <input type="text" id="nama" name="nama" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="pesan">Pesan:</label>
                <textarea id="pesan" name="pesan" required></textarea>

                <input type="submit" value="Kirim">
            </form>
        </section>

        <footer>
            <p>&copy; 2021 - Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

### 2. Ini adalah tampilan web-nya
![kontak](https://github.com/RafiMlnf/Lab4Web/assets/115614668/083e5229-833f-4b6e-b96a-2e99b1a02ccb)


