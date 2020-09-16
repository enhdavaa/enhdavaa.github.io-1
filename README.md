<<<<<<< HEAD
</doctype html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>my website</title>
    <link rel="stylesheet" href="css/website.css">
    <meta charset="utf-8">
</head>
<body>s
    <div class="menu">
        <div class="taniltsuulga right">
            <ul>
                <li><a href="website1.html">asdq</a></li>
                <li><a href="website.html">нүүр</a></li>
                <li><a href="website2.html">танилцуулга</a></li>
                <li><a href="website3.html">сургууль</a></li>
                <li><a href="website4.html">бүтээлүүд</a></li>
                <li><a href="#">утас 89948589</a></li>
            </ul>
        </div>
        <div class="clr"></div>
    </div>
    <div class="menu1">
        <div class="taniltsuulga">
            <div class="logo left">
                <img src="img/redfin.png">    
            </div>
            <diV class="search">
                <input type="text" placeholder="Search.." name="search">
                <button type="submit">go!</button>
            </diV>
            <div class="clr"></div>
        </div>
    </div>
    <div class="slideshow-container">
        <div class="mySlides fade">
          <div class="numbertext">1 / 4</div>
          <img src="img/indra1.jpg" style="width:100%">
          <div class="text">Caption Text</div>
        </div>
        <div class="mySlides fade">
          <div class="numbertext">2 / 4</div>
          <img src="img/indra2.jpg" style="width:100%">
          <div class="text">Caption Two</div>
        </div>      
        <div class="mySlides fade">
            <div class="numbertext">3 / 4</div>
            <img src="img/indra3.jpg" style="width:100%">
            <div class="text">Caption Three</div>
        </div>
        <div class="mySlides fade">
            <div class="numbertext">2 / 4</div>
            <img src="img/indra4.jpg" style="width:100%">
            <div class="text">Caption for</div>
        </div>        
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>       
    </div>
        <br>       
    <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span> 
        <span class="dot" onclick="currentSlide(2)"></span> 
        <span class="dot" onclick="currentSlide(3)"></span> 
        <span class="dot" onclick="currentSlide(4)"></span>
    </div>
    <div class="menu">
        <div class="s1 left">
            <h2>asd</h2>
        </div>
        <div class="s2 right">
            <h3>asfedtgGGes</h3>
        </div>
    </div>
    <script>
        var slideIndex = 1;
            showSlides(slideIndex);
        function plusSlides(n) {
        showSlides(slideIndex += n);
        }
        function currentSlide(n) {
        showSlides(slideIndex = n);
        }
        function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if (n > slides.length) {slideIndex = 1}    
        if (n < 1) {slideIndex = slides.length}
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";  
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex-1].style.display = "block";  
        dots[slideIndex-1].className += " active";
        }
    </script>   
</body>
</html>
=======
<DOCTYPE html>
>>>>>>> 18daf99dc173bbae49570e959d0e03662db742c4

