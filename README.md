
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="style.css" rel="stylesheet" type="text/css" media="all" />
</head>

<body>

    <div id="container">
    <div id="content" class="animate1">
    <h1 id="header">Bicubic Shader</h1>

    <p>Bicubic Shader adalah addon atau sebuah sumber daya untuk minecraft edisi bedrock shader ini akan menambahkan efek fisual yang sangat berbeda
    dari shader lainnya.<br> Seperti penambahan efek pada pencahayaan yang diatur sedemikian rupa sehingga warna pada pencahayaan dapat berganti seiring waktu
    pewarnaan yang lebih kuat dan vibrant juga menjadikan ciri khas dari shader ini, karena saya atur lagi pengkoreksian warna cahaya menggunakan 
    ACES film tonemap dan juga color saturation(grading) agar membuatnya terlihat lebih segar dan berwarna.</br>
        <br>
    hal tersebut bukan tanpa alasan, dikarenakan saya sebagai pembuat tentu sangat suka dengan pencahayaan yang seperti itu dan juga tak lepas dari
    saran para pengikut saya, sehinnga saya membuat shader dengan konsep dan keinginan saya sendiri.</br>
        <br>
    Dan tentu saja saya membuat shader ini membutuhkan waktu yang lama dan tak lepas dari kesalahan. makadari itu saya sangat
    berterimakasih kepada para develover shader mcbe lainnya yang telah menyempatkan diri untuk membantu saya. Shader ini saya buat
    dengan sedikit mengkombinasi code dari shader mcbe yang lain dan tentu saja saya juga meminta izin untuk menggunakannya.</p>

    <br>
    <p>
        <li>Download dan pasanglah shader ini pada minecraft anda, jangan mengcopi atau mengambil code tanpa sepengetahuan dari Dev.</li>
        <li>jangan upload ulang shader menggunaka link berbeda</li>
        <li>jika ingin membagikan, bagikan saja link dari situs ini</li>
        <li>bila ditemukan bug, crash atau kesalaha code harap laporkan saya ke saya</li>
        <br>
        <h3>Bicubic Shader Download</h3>
          <div class="slideshow-container">

            <div class="Slides">
              <img src="picture/hh.jpg" style="max-width: 100%">
            </div>
            
            <div class="Slides">
              <img src="picture/jap.jpg" style="max-width: 100%">
            </div>

            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
          </div>
            
            <div id="right">
                Fitur:
                <li>realistic cloud with semi volumetic of 3D noise fbm</li>
                <li>2D water wave with fake reflect of clouds</li>
                <li>realistic, vibrance and fresh coloring</li>
                <li>realistic rain effect with fake wet on top the block</li>
            </div>
    </div>
    </div>

    <script>
        var slideIndex = 1;
        showSlides(slideIndex);
        
        function plusSlides(n) {
          showSlides(slideIndex += n);
        }
        
        function showSlides(n) {
          var i;
          var slides = document.getElementsByClassName("Slides");
          
          if (n > slides.length) {slideIndex = 1}    
          if (n < 1) {slideIndex = slides.length}
          for (i = 0; i < slides.length; i++) {
              slides[i].style.display = "none";  
          }
          
          slides[slideIndex-1].style.display = "block";  
        }
</script>

</body>
</html>
