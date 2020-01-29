# Miladin-doktor<html>
<head>
<title>Nasa prva web stranica</title>
<style>
body {

  background-image: url('https://cvecarstvo.com/wp-content/uploads/2016/02/Cvecara-Fragola-9-620x315.jpg'); }
  
#tekst { color: white;
		 text-decoration: none;
		 font-family: Verdana; }
#deo { background-color: black;
       padding: 15px; }

</style>
</head>
<body>
<div id='deo'>
<h1 id='tekst'>Ovo je nasa prva stranica</h1>
<p id='tekst'>Nadam se da samo uspeli kreirati naslov i tekst</p>
<hr>
<p id='tekst'>Ovo je popis stvari koje volimo raditi:</p>
<ul>
<li id='tekst'>uciti web programiranje kod najboljeg  profesora Vladimira</li>
<li id='tekst'>govoriti sa prijateljima na facebooku</li>
<li id='tekst'>biti u prirodi</li>
<li id='tekst'>voziti motocikl</li>
</ul>
<p id='tekst'><a href="https://cvecarakazablanka.com/" title="Povratak">Ovo je link prema sajtu kazablanke</p>
<p id='tekst'>Ovo su osnovne izrade web stranica</p>
</div>
<a href='https://cvecarakazablanka.com/'><img src='https://www.klikdovencanja.com/wp-content/uploads/2015/03/cvecara-kazablanka1-320x160.jpg'></a>
<a href='https://drvotehnika.info/adresar/javorac-bogise'><img src='https://www.pttimenik.com/sites/default/files/imagecache/logo_firme/131969.jpg' height='160px'></a>
<br>
<div>
      <div class="slajd">
      
        <img src="https://drvotehnika.info/media/images/biznisklub/038_Javorac.jpg" style="width:50%">
        
      </div>
      <div class="slajd">
  
        <img src="https://www.cvecarakazablanka.com/data/products/1317/feature/1/Cvetni_aranzman_691.JPG" style="width:50%;">
        
      </div>
      <div class="slajd">
   
        <img src="https://i.pinimg.com/originals/f7/f6/24/f7f62453abc07427a42f3b66cfcd4183.jpg" style="width:50%">
       
      </div>
      <button class="prev" onclick="menjanje(-1)">prosla</button>
      <button class="next" onclick="menjanje(1)">sledeca</button>

</body>
<script>
var slajdIndex = 1;
      pokaziSlajd(slajdIndex);
      
      function menjanje(n) {
        pokaziSlajd(slajdIndex += n);
      }
      
      function sadasnjiSlajd(n) {
        pokaziSlajd(slajdIndex = n);
      }
      
      function pokaziSlajd(n) {
        var i;
        var slajdovi = document.getElementsByClassName("slajd");
        
        if (n > slajdovi.length) {slajdIndex = 1}    
        if (n < 1) {slajdIndex = slajdovi.length}
        for (i = 0; i < slajdovi.length; i++) {
            slajdovi[i].style.display = "none";  
        }
        
        slajdovi[slajdIndex-1].style.display = "block";  
        
      }



</script>
</html>



