# Ruang-Pulang-Mapuyuh
<!DOCTYPE html>
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
