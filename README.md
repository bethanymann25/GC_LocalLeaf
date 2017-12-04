<!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css?family=Oswald|PT+Sans" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Catamaran|Fjalla+One" rel="stylesheet">
<title>Local Leaf Nyc</title>
<link rel="stylesheet" type="text/css" href="LocalLeaf.css">
</head>
<!-- item 26-->
        <link rel="icon"
          type="image/png"
          href=""
          />
<!--slide area-->

  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="LocalLeaf1.jpeg" style="width:100%">
    <div class="text">Local Leaf</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="LocalLeaf2.jpg" style="width:100%">
    <div class="text">Local Leaf</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="LocalLeaf3.jpg" style="width:100%">
    <div class="text">Local Leaf</div>
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
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

<h1>Local Leaf Restaurant in NYC</h1>

<body>
    <p>Local Leaf is committed to providing fresh, chef-crafted food made from responsibly sourced ingredients. Focusing on reimagining common menu items and offering a healthy and delicious approach to all-day dining. From signature and customizable lettuce wraps, to platters, hydrating drinks, and breakfast crepes, this is delicious gourmet fare in a fast casual environment.</p>

<P>Learn more about Local Leaf with their NowThis Video</p>
   
<video width="320" height="240" controls>
  <source src="NowThis.mp4" type="video/mp4">
  <source src="NowThis.mp4" type="video/ogg">
  Your browser does not support the video tag.
</video>


<!--item 8-->
<h2>Things to Take Away From Local Leaf</h2>
<ul>
  <li>Always Provide Fresh Food</li>
  <li>Fast Paced Environment</li>
  <li>Breakfast is Available</li>
</ul>
    
    
<p>For more information<a href="https://www.eatlocalleaf.com/">Visit the Local Leaf website</a></p>
    <p>&copy; Local Leaf</p>
</body>
</html>
