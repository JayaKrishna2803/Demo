# Demo
This is my first Git repository

<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ecommerce Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer">
  
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap" rel="stylesheet">
<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    font-size: 7px;
    font-family: "Poppins", sans-serif;
}
body,html{
    overflow-x: hidden;
}
.navbar{
    display: flex;
    align-items: center; 
    padding: 20px;
}
nav{
    flex: 1;
    text-align: right;
}
nav ul{
    display: inline-block;
    list-style-type: none;
}
nav ul li{
    display: inline-block;
    margin: 20px;
    font-size: 9px;
    
}
a{
    text-decoration: none;
    color: #d01515;
}
p{
    color: #fd0303;
}
.container{
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: center;
    flex-wrap:wrap ;
    justify-content: space-around;
}
.col2{
    flex-basis: 50%;
    min-width: 300px;
}
.col2{
    max-width: 100%;
    padding: 50px 0;
}
.col2 h1{
    font-size: 30px;
    margin: 15px 0;
}
.btn{
    display: inline-block;
    background: #0bd86b;
    color: #fff;
    padding: 5px 20px;
    margin: 30px 0;
    border-radius: 30px;
}
.btn:hover{
    background: #563434;
}
.header{
    background: radial-gradient(#cf5423,#05ea08);
}
.header row{
    margin-top: 70px;
}
.row1{
    margin-top: 35px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
    flex-wrap: wrap;/

}
.col3 img{
    height: 100px;
    width: 100px;
}
.featured{
    margin-left:px;
    margin-top: 5px;
    flex-direction: column;
 
}
.row2{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}
.row10{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}
.col4{
    padding: 10px;
    margin-bottom: 30px;
    transition: transform 0.5s;
}
.col4 img{
    height: 100px;
    width: 100px;
}
.title{
    margin-top: 20px;
    text-align: center;
}
.rating .fa{
    color: #3bff65;
}
.col4 p{
    font-size: 10px;
}
/* .line{
    height: 4px;
    width: 50px;
    background: red;
    display: flex;
    justify-content: center;
} */
 .col4:hover{
    transform: translateY(-5px);
 }
 .row5{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 60px;
 }
 .small-container{
    display: flex;
    justify-content: center;
    align-items: center;
 }
 .offer{
    background: radial-gradient(#efeb0a,rgb(7, 235, 11));
    margin-top: 60px;
    padding: 30px 0;
 }
small{
    color: #555;
}
.row6{
    display: flex;
    align-items: center;
    flex-wrap:wrap ;
    justify-content: space-around;
    gap: 30px;
}
.testimonial{
    padding-top: 100px;
}
.testimonial .col4 img{
    width: 30px;
    height: 30px;
    margin-top: 20px;border-radius: 50%;
}
.testimonial .col4{
    text-align: center;
}
.col4 p{
    font-size: 7px;
}
.brand{
    margin: 100px auto;
}
.row7{
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    margin-top: 30px;
}
.row7 .col5 img{
    width: 70px;
    filter: grayscale(100%);
}
.col5 img:hover{
    filter: grayscale(0);
}
.footer{
    background:#0eeeb2 ;
    color: #8a8a8a;
    font-size: 10px;
    padding: 20px 0 20px;
}
.row8{
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content:space-evenly;
}
.row8 .footer-col2 img{
    width: 120px;
}
 .footer-col3 ul,.footer-col4  ul {
    list-style-type: none;
}
.footer-col1 p,.footer-col2 p{
    font-size: 7px;
    color: #1ae7f9;
}
.footer h3{
    color: #0570f3;
    margin-bottom: 20px;
}
.footer-col2{
    text-align: center;
} 
.footer-col3 li,.footer-col4 li{
    font-size: 7px;
}
.applogo{
    margin-top: 5px;
}
.applogo img{
    width: 100px;
    height:30px ;
}
.footer hr{
    border: none;
    background: #ef2978;
    height: 1px;
    margin: 20px;
}
.copyright{
    text-align: center;
    color: #8a8a8a;
    font-size: 8px;
}

    </style>

  </head>
  <body><div>
    <div class="header">
    <div id="a1" class="container">
      <div class="navbar">
        <div class="logo">
          <img width="100px" height="100px" src="https://t3.ftcdn.net/jpg/02/47/48/00/360_F_247480017_ST4hotATsrcErAja0VzdUsrrVBMIcE4u.jpg" alt="">
        </div>
        <nav>
          <ul>
            <li><a href="#a1">Home</a></li>
            <li><a href="#a2">Products</a></li>
            <li><a href="#a3">About</a></li>
            <li><a href="#a4">Contact</a></li>
            <li><a href="">Account</a></li>
          </ul>
        </nav>
        <img width="50px" height="50px" src="https://static.vecteezy.com/system/resources/thumbnails/004/798/846/small/shopping-cart-logo-or-icon-design-vector.jpg" alt="">
      </div>
      <div class="row">
        <div class="col2">
          <h1>
            Make Your Style<br>
            By Your Choice!
          </h1>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit
            eligendi quia <br> voluptatum consequatur unde, alias a labore quasi
            accusamus.
          </p>
          <a href="" class="btn">Explore Now →</a>
        </div>
        <div class="col2">
            <img width="300px" src="https://m.media-amazon.com/images/I/71Rtv5Uso5L._AC_UF350,350_QL80_.jpg" alt="">
        </div>
      </div>
    </div>
</div>
<div style="background-color: cornflowerblue;">

<div id="a2" class="categories">
    <div class="row1">
        <div class="col3">
            <img src="https://vasanthandco.in/images/productimages/1903__product__Mobiles__apple-mobile-iphone-13-blue-128gb-1.png" alt="">
            
        </div>
        <div class="col3">
            <img src="https://akm-img-a-in.tosshub.com/indiatoday/images/device/1683285701Pixel6-800x800_one_to_one.png?VersionId=ZuqwtLKGvUIAtfotExGbrmy2EmtqItdy" alt="">
        </div>
        <div class="col3">
            <img src="https://img.etimg.com/photo/msid-98945112,imgsize-13860/SamsungGalaxyS23Ultra.jpg" alt="">
        </div>
    </div>
</div>



<div class="feature1">
  <h2 class="title">Feature Products</h2>
<div class="featured">
  <div class="row2">
    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/41037bXz-GL._SY445_SX342_QL70_FMwebp_.jpg" alt="">
      <h4>Apple iPhone 15 Pro Max (256 GB) <br> Natural Titanium</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹1,500,000.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/71goZuIha-L._SL1500_.jpg" alt="">
      <h4>Samsung Galaxy S23 Ultra 5G AI Smartphone <br>(Phantom Black, 12GB, 256GB Storage)</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹84,000.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/51mzSYOPNGL._SX569_.jpg" alt="">
      <h4>Pixel 9 Pro XL 5G <br>(Obsidian, 16 RAM, 256GB Storage)</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹80,000.00</p>
    </div>

    <div class="col4">
      <img src="https://media.rolex.com/image/upload/q_auto:eco/f_auto/c_limit,w_1920/v1720523263/rolexcom/collection/family-pages/professional-watches/explorer/explorer-family-page/professional-watches-explorer-a-tool-watch-for-exploration-M124273-0001_2403jva_002" alt="">
      <h4>Rolex</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹1,00,000.00</p>
    </div>
 
  </div>    
  </div>
</div>

<div class="feature1">
  <h2 class="title">Latest Product</h2>
<div class="featured">
  <div class="row2">
    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/71pzB-Rhc9L._SY879_.jpg" alt="">
      <h4>Red Plain Formal-shirt</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹645.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/71jfMhZZLQL._SY879_.jpg" alt="">
      <h4>Men's Slim Fit Flexi <br> Waist Casual Pants</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹1,899.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/71EoGntO5bL._AC_UL480_QL65_.jpg" alt="">
      <h4>Apple Watch Series 3 (GPS, 42mm) <br>Space Grey Aluminium Case <br>with Black Sport Band</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>$50.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/615nnoTis0S._SX679_.jpg" alt="">
      <h4>OLEVS Stainless Steel Luxury Analogue <br>Men'S Watch(Green-Gold Dial &amp; <br>Silver &amp; Gold Colored Strap)-Ol85G</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹2790.00</p>
    </div>
      <div class="row10">
    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/71y45xLzgHL._SX679_.jpg" alt="">
      <h4>HP-Laptop</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹40,990.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/31tKtKPIkWL._SX300_SY300_QL70_FMwebp_.jpg" alt="">
      <h4>boAt Airdopes 311 Pro</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹1,199.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/41B+MCOnmkL._SY300_SX300_.jpg" alt="">
      <h4>Boult x Mustang Torq</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹1,199.00</p>
    </div>

    <div class="col4">
      <img src="https://m.media-amazon.com/images/I/61r7rylEOWL._SX522_.jpg" alt="">
      <h4>Bajaj Dominar D 400 UG 2 Bike</h4>
      <div class="rating">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-regular fa-star"></i>
      </div>
      <p>₹2,32,040.00</p>
    </div> 
  </div>
  </div>    
  </div>
</div>
</div>
</div>
<div id="a3" class="offer">
  <div class="small-container">
    <div class="row5">
      <div class="col5">
        <img height="130px" src="./images/exclusive.png" alt="" class="offer-image">
      </div>
      <div class="col5">
        <p>Exclusively Available on Redstore</p>
        <h1>smart Brand</h1>
        <small>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Labore cupiditate <br> explicabo aliquam illo nulla ratione harum sequi obcaecati minus quis.</small>
        <br>
        <a class="btn" href="">Buy Now →</a>
      </div>
    </div>
  </div>
</div>
<div style="background-color: gold;">
<div class="testimonial">
  <div class="small-container">
    <div class="row6">
      <div class="col4">
        <i class="fa-solid fa-quote-left"></i>
        <p>Lorem ipsum dolor sit amet consecte <br> elit. Culpa porro veniam revhhjfdgtt<br>  eaque numquam cumque asperiores.</p>
        <div class="rating">
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-regular fa-star"></i>
        </div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlhY-Ch_e4DvmsHzhyEwGvVSlUM2ICyjs5pA&amp;s" alt="">
        <h3>Sruti Rout</h3>
      </div>

      <div class="col4">
        <i class="fa-solid fa-quote-left"></i>
        <p>Lorem ipsum dolor sit amet consectetur <br> elit. Culpa porro veniam rem nam modi,<br>  eaque numquam cumque asperiores.</p>
        <div class="rating">
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-regular fa-star"></i>
        </div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTTwccCf56-gpPjKYk-XilNTtqxytxUvV6INDDLgd98-BAxGLlbpX4Y5r5Peu1_Ar3yYmM&amp;usqp=CAU" alt="">
        <h3>Sruti Rout</h3>
      </div>

      <div class="col4">
        <i class="fa-solid fa-quote-left"></i>
        <p>Lorem ipsum dolor sit amet consectetu <br> elit. Culpa porro veniam rem nam mo,<br>  eaque numquam cumque asperiores.</p>
        <div class="rating">
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-solid fa-star"></i>
          <i class="fa-regular fa-star"></i>
        </div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJ9TEU0Up6DJnC0jpJw6D0jqrv1mdk3tPU7x88dZYFIQUvF9vmR-UTRElgpP5_BwXqbAw&amp;usqp=CAU" alt="">
        <h3>Ram Rout</h3>
      </div>
    </div>
  </div>
</div>
</div>

<div class="brands">
  <div class="small-container">
    <div class="row7">
      <div class="col5">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbI5GEjTBEwDs4_fSL9xvTAR004HOizjMhzw&amp;s" alt="">
      </div>
      <div class="col5">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/OPPO_Logo_wiki.png" alt="">
      </div>
      <div class="col5">
        <img src="https://1000logos.net/wp-content/uploads/2017/06/Samsung-logo.jpg" alt="">
      </div>
      <div class="col5">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNrEJyc4sONe680_ShobD5LmKwKl31QB1opQ&amp;s" alt="">
      </div>
      <div class="col5">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvpQr7jRfGRZXz54j5HdGf6MDP8w5l53a3UQ&amp;s" alt="">
      </div>
    </div>
  </div>
</div>

<div id="a4" class="footer">
  <div class="footer1">
    <div class="row8">
      <div class="footer-col1">
        <h3>Download Our App</h3>
        <p>Lorem ipsum dolor sit amet consectetur</p>
        <div class="applogo">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_lSkUx4UgyHmXeNi1x2kGGiyTeG6bpC9R6Q&amp;s" alt="">
          <img src="https://w7.pngwing.com/pngs/314/368/png-transparent-itunes-app-store-apple-logo-apple-text-rectangle-logo.png" alt="">
        </div>
      </div>
      <div class="footer-col2">
        <img src="https://t3.ftcdn.net/jpg/02/47/48/00/360_F_247480017_ST4hotATsrcErAja0VzdUsrrVBMIcE4u.jpg" alt="">
        <p>Lorem ipsum dolor sit amet consectetu asd fjcj dbknkjn <br>hsbnjc bhjdsbhdsbk dbhj hjjsbdchb s </p>
      </div>
      <div class="footer-col3">
       <h3>Useful links</h3>
       <ul>
        <li>Coupons</li>
        <li>Blogpost</li>
        <li>Return policy</li>
        <li>Join Affliate</li>
       </ul>
       
      </div>
      <div class="footer-col4">
        <h3>Follow Us</h3>
        <ul>
         <li>Facebook</li>
         <li>Twittter</li>
         <li>Instagram</li>
         <li>YouTube</li>
        </ul>
        
       </div>
    </div>
    <hr>
    <p class="copyright"> Copyright 2024</p>
  </div>
</div>

  

</body></html>
Author: Jaya Krishna
