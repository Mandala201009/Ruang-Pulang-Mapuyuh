# Ruang-Pulang-Mapuyuh
<html lang="id">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">

<title>Ruang Pulang Mapuyuh</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{

background:#f5f7fb;

color:#333;

}

.hero{

height:100vh;

background:linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),url("foto1.jpg");

background-size:cover;

background-position:center;

display:flex;

justify-content:center;

align-items:center;

text-align:center;

color:white;

padding:20px;

}

.hero h1{

font-size:55px;

}

.hero p{

margin-top:15px;

font-size:20px;

max-width:700px;

}

button{

margin-top:30px;

padding:15px 35px;

border:none;

border-radius:40px;

font-size:18px;

cursor:pointer;

background:white;

}

section{

padding:60px 10%;

}

.gallery{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

gap:15px;

}

.gallery img{

width:100%;

border-radius:15px;

transition:.3s;

}

.gallery img:hover{

transform:scale(1.03);

}

.card{

background:white;

padding:25px;

border-radius:20px;

box-shadow:0 5px 15px rgba(0,0,0,.08);

margin-bottom:25px;

}

h2{

margin-bottom:20px;

}

textarea{

width:100%;

min-height:150px;

padding:15px;

border-radius:12px;

border:1px solid #ddd;

margin-top:10px;

resize:vertical;

}

select{

width:100%;

padding:15px;

border-radius:12px;

margin-top:10px;

}

.submit{

background:#4f46e5;

color:white;

width:100%;

padding:18px;

border-radius:15px;

font-size:18px;

}

footer{

text-align:center;

padding:40px;

color:#777;

}

</style>

</head>

<body>

<div class="hero">

<div>

<h1>🕊 RUANG PULANG MAPUYUH</h1>

<p>

Kalau hari ini adalah kesempatan terakhir kita duduk bersama,

apa yang ingin kamu sampaikan kepada keluarga ini?

</p>

<button onclick="document.getElementById('mulai').scrollIntoView({behavior:'smooth'})">

Aku Siap Bercerita

</button>

</div>

</div>

<section>

<h2 align="center">📸 Perjalanan Kita</h2>

<br>

<div class="gallery">

<img src="foto1.jpg">

<img src="foto2.jpg">

<img src="foto3.jpg">

<img src="foto4.jpg">

<img src="foto5.jpg">

</div>

</section>

<section id="mulai">

<div class="card">

<h2>🤍 Cerita Pertama</h2>

<p>

Saat pertama kali menjadi bagian dari MAPUYUH,

apa yang kamu rasakan?

Apakah perasaan itu masih ada sampai sekarang?

</p>

<textarea></textarea>

</div>

<div class="card">

<h2>😔 Yang Tidak Pernah Kamu Ceritakan</h2>

<p>

Apakah kamu pernah menangis,

kecewa,

atau merasa sendirian selama perjalanan ini?

Jika iya,

ceritakan.

</p>

<textarea></textarea>

</div>

<div class="card">

<h2>🫂 Tentang Kita</h2>

<p>

Menurutmu,

kenapa kita tidak sedekat dulu?

</p>

<select>

<option>Pilih Jawaban</option>

<option>Kesibukan</option>

<option>Salah paham</option>

<option>Circle</option>

<option>Kurang komunikasi</option>

<option>Lainnya</option>

</select>

</div>

<div class="card">

<h2>🙏 Maaf dan Terima Kasih</h2>

<p>

Kalau hari ini kamu bisa meminta maaf

atau berterima kasih kepada seseorang di MAPUYUH,

kepada siapa dan kenapa?

</p>

<textarea></textarea>

</div>

<div class="card">

<h2>💌 Surat Untuk MAPUYUH</h2>

<p>

Bayangkan beberapa tahun lagi kita sudah sibuk dengan jalan masing-masing.

Tulis surat untuk keluarga ini.

Tidak ada batasan panjangnya.

</p>

<textarea style="min-height:300px;"></textarea>

</div>

<div class="card">

<h2>🌙 Pesan Terakhirmu</h2>

<p>

Jika ini adalah malam terakhir kita berkumpul,

apa yang ingin kamu katakan kepada seluruh MAPUYUH?

</p>

<textarea></textarea>

</div>

<button class="submit">

Kirim Ceritaku 🤍

</button>

</section>

<footer>

"Semoga suatu hari nanti,

ketika kita membuka halaman ini lagi,

yang tersisa bukan penyesalan,

tetapi rasa bangga pernah menjadi keluarga MAPUYUH."

</footer>

</body>

</html>
