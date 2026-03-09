<style>

body{
    margin:0;
    font-family: Arial, Helvetica, sans-serif;
    background:white;
}

.header{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    background:white;
    border-bottom:1px solid #ddd;
    z-index:1000;
}

.container{
    max-width:900px;
    margin:auto;
}

.topbar{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:15px 10px;
}
@media (max-width:700px){

.topbar{
flex-direction:column;
align-items:center;
text-align:center;
}

.site-title{
font-size:28px;
margin-bottom:10px;
white-space:nowrap;
}

.menu{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:10px;
}

.menu a{
margin:0;
font-size:15px;
}

.hero{
margin-top:120px;
}

.site-title{
    font-size:28px;
    font-weight:600;
}

.menu a{
    margin-left:20px;
    text-decoration:none;
    color:#333;
}

.menu a:hover{
    color:#0077cc;
}

.hero{
    margin-top:100px;
}

.hero img{
    width:100%;
    border-radius:6px;
    box-shadow:0 25px 45px rgba(0,0,0,0.35);
}

</style>

<div class="header">
<div class="container">

<div class="topbar">

<div class="site-title">
Nagihan Saka
</div>

<div class="menu">
<a href="/">Nagihan'ca</a>
<a href="/strateji">Strateji</a>
<a href="/sistem-dinamikleri">Sistem Dinamikleri</a>
<a href="/iletisim">İletişim</a>
</div>

</div>
</div>
</div>

<div class="container hero">

<img src="/assets/hero.png">

</div>
