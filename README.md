<!doctype html>
<html lang="en">
<head>
	<style>
		*{
margin:0;
padding:0;
box-sizing:border-box;
}
body{
font-family: 'Poppins', sans-serif;
}
.navbar{
display:flex;
align-items:center;
padding;20px;
}
nav{
flex:1;
text-align:right;
}
nav ul{
display:inline-block;
list-style-type:none;
}
nav ul li{
display:inline-block;
margin-right:20px;

}
a{
text-decoration:none;
color:#555;
}
p{
color:#555;
}
.container{
max-width:1300px;
margin:auto;
padding-left:25px;
padding-right:25px;
}
.row{
display:flex;
align-items:center;
flex-wrap:wrap;
justipy-content:space-around;
}
.col2{
flex-basis:50%;
min-width:300px;
}
.col2 img{
max-width:100%;
padding:50px 0;
}
.col2 h1{
font-size:50px;
line-height:60px;
margin:25px 0;
}
.btn{
display:inline-block;
background:#ff523b;
color:#fff;
padding:8px 30px;
margin:30px 0;
border-radius:30px;
transition:background 0.5s;
}
.btn:hover{
background:#563434;
}

.header{
background:radial-gradient(#fff,#ffd6d6);
}
.header .row{
margin-top:70px;
}
.categories{
margin:70px 0;

}


.col-3{
flex-basis:30%;
min-width:250px;
margin-bottom:30px;

}
.col-3 img{
width:100%;

}
.small-container{
max-width:1080px;
margin:auto;
padding-left:25px;
padding-right:25px;
}
.col-4{
flex-basis:25%;
padding:10px;
min-width:200px;
margin-bottom:50px;
transition:transform 0.5s;
}
.col-4 img{
width:100%;
}
.title{
text-align: center;
margin: 0 auto 80px;
position:relative;
line-height:60px;
color:#555;
}
.title::after{
content:'';
background:#ff523b;
width:80px;
height:5px;
border-radius:5px;
position:absolute;
bottom:0;
left:50%;
transform:translateX(-50%);
}
h4{
color:#555;
font-weight:normal;

}
.col-4 p{
fon-size:14px;

}
.rating .fa{
color:#ff523b;
}

.col-4:hover{
transform:translateY(-5px);
}

	/*--------offer--------*/
.offer{
background:radial-gradient(#fff,#ffd6d6);
margin-top:80px;
padding:30px 0;
}
.col-2 .offer-img{
padding:50px;
width:400px;
}
small{
color:#555;
}
	/*--------testimonial--------*/
.testimonial{
padding-top:100px;

}
.testimonial .col-3{
text-align:center;
padding:40px 20px;
box-shadow:0 0 20px 0px rgba(0,0,0,0.3);
cursor:pointer;
transition:transform 0.5s;
}
.testimonial .col-3 img{
width:50px;
margin-top:20px;
border-radius:50%;
}
.testimonial .col-3:hover{
transform:translateY(-10px);
}
.fa.fa-quote-left{
font-size:34px;
color:#ff523b
}
.col-3 p{
font-size:12px;
margin:12px 0;
color:#777;
}
.testimonial .col-3 h3{
font-weight:600;
color:#555;
font-size:16px;

}
/*------brands------*/
.brands{
margin:100px auto;
}
.col-5{
width:160px;
}
.col-5 img{
width:100px;
cursor:pointer;
filter:grayscale(100%);
}
.col-5 img:hover{
filter:grayscale(0);
}
/*-------footer------*/

.footer{
background:#000;
color:#8a8a8a;
font-size:14px;
padding:60px 0 20px;
}

.footer p{
color:#8a8a8a;
}


.footer h3{
color:#fff;
margin-bottom:20px;
}
.footer-col-1,.footer-col-2,.footer-col-3,.footer-col-4{
min-width:250px;
margin-bottom:20px;

}
.footer-col-1{
flex-basis: 30%;
}
.footer-col-2{
flex:1;
text-align:center;
}
.footer-col-2 img{
width:180px;
margin-bottom:20px;
}
.footer-col-3,.footer-col-4{
flex-basis:12%;
text-align:center;
}

ul{
list-style-type:none;
}
.app-logo{
margin-top:20px;
}

.app-logo img{
width:140px;
}
.footer hr{
border:none;
background:#b5b5b5;
height:1px;
margin:20px 0;
}
.copyright{
text-align:center;
}

.menu-icon{
width:28px;
margin-left:20px;
display:none;
}

/*-------media query for menu------*/

@media only screen and (max-width:800px){
	
	nav ul{
position:absolute;
top:70px;
left:0;
background:#333;
width:100%;
overflow:hidden;
transition:max-height 0.5s;

     }
	  nav ul li{
		display:block;
		margin-right:50px;
		margin-top:10px;
		margin-bottom:10px;

	  }
   nav ul li a{
    color:#fff;

   }
.menu-icon{
display:block;
cursor:pointer;
}
 
}
/*----------all products page---------*/

.row-2{
justify-content:space-between;
margin:100px auto 50px;

}

select{
border:1px solid #ff523b;
padding:5px;
}
select:focus{
outline:none;
}

.page-btn{
margin:0 auto 80px;

}

.page-btn span{
display:inline-block;
border:1px solid #ff523b;
margin-left:10px;
width:40px;
height:40px;
text-align:center;
line-height:40px;
cursor:pointer;
}

.page-btn span:hover{
background:#ff523b;
color:#fff;
}

/*-------sibgle product details-----*/

.single-product{
margin-top:80px;

}

.single-product .col-2 img{
padding:0px;
}


.single-product .col-2{
padding:20px;

}

#hy{
   margin:20px 0;
   font-size:22px;
   font-weight:bold;
}





/*-------media query for less than 600 screen size------*/

@media only screen and (max-width:600px){
	.row{
		text-align:center;
	}
	
	.col-2,.col-3,.col-4{
		flex-basis:100%;
	}
}



	</style>
   <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="style.css">
 
<title>M.R.Lights|welcome</title>
 
<link rel="icon" href="img/favicon.png">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet"href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
<div class="header">
<div class="container">

<div class="navbar">
<div class="logo">
<img src="images/logo.png" width="125px">
</div>
<nav>
<ul id ="menuitems">
	<li><a href="index-1.html">HOME</a></li>
	<li><a href="products-1.html">PRODUCTS</a></li>
	<li><a href="#">ABOUT</a></li>
	<li><a href="#">CONTACT</a></li> 	
	<li><a href="#">ACCOUNT</a></li>
</ul>
</nav>

<img src="images/cart.png" width="30px" height="30px">
<img src="images/menu.png" class="menu-icon" onclick="menutoggle()">

</div>

<div class="row">
<div class="col2">
	<h1>mama tanki wala <br>A New Style!</h1>
	<p> success ist't always about greatness.it's about 
	consistency.consistent<br> hard work gains success.greatness
	 will ccome</p>
	<a href="#" class="btn">Explore Now &#8594;</a>
</div>
<div class="col2">
<img src="images/image1.png">
 </div>
</div>

</div>

</div>
<!-----featured categories----->
<div class=categories>
<div class="small-container">
<div class="row">
<div class="col-3">
<img src="images/category-1.jpg">
</div>
<div class="col-3">
<img src="images/category-2.jpg">
</div>
<div class="col-3">
<img src="images/category-3.jpg">
</div>
  </div>
</div>

</div>

<!-----featured products----->
<div class="small-container">
<h2 class="title">Featured Products</h2>
<div class="row">

<div class="col-4">
<a href="product-detail.html">
<img src="images/product-1.jpg">
<h4>Red Printed T-Shirt</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div></a>
<div class="col-4">
<img src="images/product-2.jpg">
<h4>black-color-shoes/footwear</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-half-o"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-3.jpg">
<h4>black color-nightwear/nighty</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-half-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-4.jpg">
<h4>blue Printed T-Shirt</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>

</div>
<h2 class="title">Latest Products</h2>
<div class="row">
<div class="col-4">
<img src="images/product-5.jpg">
<h4>shoes for boys</h4>

<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-6.jpg">
<h4>Black Printed T-Shirt</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-half-o"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-7.jpg">
<h4>combo of three-color shocks</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-half-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-8
.jpg">
<h4>fossil black color watch</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>

</div>
<div class="row">
<div class="col-4">
<img src="images/product-9.jpg">
<h4>roadstar black color watch</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-10.jpg">
<h4>black color-shoes for mens/footwear</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-half-o"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-11.jpg">
<h4>dockstreet shoes for boys</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-half-o"></i>
</div>
<p>$50.00</p>
</div>
<div class="col-4">
<img src="images/product-12.jpg">
<h4>nike black colored nightwear</h4>
<div class="rating">
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star"></i>
<i class="fa fa-star-o"></i>
</div>
<p>$50.00</p>
</div>

</div>
</div>
	<!--------offer-------->
<div class="offer">
<div class="small-conainer">
<div class="row">
<div class="col-2">
<img src="images/exclusive.png" class="offer-img">
</div>
<div class="col-2">
	<p>Exclusively Available on RedStore</p>
	<h1>Smart Band 4</h1>
	<small>The Mi Smart Band 4 features a 39.9% larger
	(than Mi band 3)AMOLED color<br> full-touch display with
	 adjustable brightnes,so everything is clear as can
	 be.</small>
	<br>
		<a href="#" CLASS="btn">Buy Now &#8594;</a>
</div>
		</div>
	</div>
</div>

	<!--------testimonial-------->
<div class="testimonial">
<div class="small-container">
<div class="row">
	<div class="col-3">
		   <i class="fa fa-quote-left"></i>
		<p>lorem ipsum is siply dummy text of the printing
		and typesetting industry.lorem Ipsum has been the
		industry's standerd dummy text ever</p>
		<div class="rating">
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star-o"></i>
		 </div>
		<img src="images/user-1.png">
		<h3>Sean Parker</h3>
	</div>
	<div class="col-3">
		   <i class="fa fa-quote-left"></i>
		<p>lorem ipsum is siply dummy text of the printing
		and typesetting industry.lorem Ipsum has been the
		industry's standerd dummy text ever</p>
		<div class="rating">
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star-o"></i>
		 </div>
		<img src="images/user-2.png">
		<h3>mike abroe</h3>
	</div>
	<div class="col-3">
		   <i class="fa fa-quote-left"></i>
		<p>lorem ipsum is siply dummy text of the printing
		and typesetting industry.lorem Ipsum has been the
		industry's standerd dummy text ever</p>
		<div class="rating">
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star"></i>
		   <i class="fa fa-star-o"></i>
		 </div>
		<img src="images/user-3.png">
		<h3>jenny farnandez</h3>
	</div>
	
    </div>
 </div>
</div>

	<!---------brands-------->
	<div class="brands">
	    <div class="small-container">
	    <div class="row">
		<div class="col-5">
		   <img src="images/logo-godrej.png">
		</div>
		<div class="col-5">
		   <img src="images/logo-oppo.png">
		</div>
		<div class="col-5">
		   <img src="images/logo-coca-cola.png">
		</div>
		<div class="col-5">
		   <img src="images/logo-paypal.png">
		</div>
		<div class="col-5">
		   <img src="images/logo-philips.png">
		</div>
	    </div>
	</div>
</div>

<!------footer----->
<div class="footer">
<div class="container">
	<div class="row">
    	    <div class="footer-col-1">
		<h3>Downlod Our App</h3>
		<p> Downlod App for Android and ios mobil phone.</p>
		<div class="app-logo">
			<img src="images/play-store.png">
			<img src="images/app-store.png">
		</div>
	    </div>
	    <div class="footer-col-2">
		<img src="images/logo-white.png">
		<p>Our Purpose Is To Sustainably Make the Pleasure and
		Benifits of Sports Accessible to the Many. </p>
	    </div>
	    <div class="footer-col-3">
		<h3>useful Links</h3>
		<ul>
			<li>Coupons</li>
			<li>Blog Post</li>
			<li>Return Policy</li>
			<li>Join Affiliate</li>
		</ul>
	    </div>
	    <div class="footer-col-4">
		<h3>FOOLOW Us</h3>
		<ul>
			<li>facebook</li>
			<li>twitter</li>
			<li>instagram</li>
			<li>youtube</li>
		</ul>
	    </div>
	</div>
		<hr>
	     <p class="copyright">copyright 2020-M.R.Light</p>
</div>
</div>

<!-------js for toggle-------->
<script> 
	var menuitems=document.getElementById("menuitems");
	
	menuitems.style.maxHeight="0px";
	
	function menutoggle(){
	    if(menuitems.style.maxHeight=="0px")
		{
			menuitems.style.maxHeight="200px"
		}
	    else
		{
			menuitems.style.maxHeight="0px"
		}
	}
</script>
</body>
</html>
