<!DOCTYPE html>
<html>
<head>
	<title>Trang web mẫu </title>
	<style>
		body {
			background-color: #f1f1f1;
		}
		
		.header {
			background-color: #333;
			color: #fff;
			padding: 20px;
			text-align: center;
		}
		
		.navbar {
			overflow: hidden;
			background-color: #333;
		}
		
		.navbar a {
			float: left;
			display: block;
			color: #f2f2f2;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
		}
		
		.navbar a:hover {
			background-color: #ddd;
			color: black;
		}
		
		.content {
			display: grid;
			grid-template-columns: repeat(16, 1fr);
			grid-gap: 20px;
			padding: 20px;
		}
		
		.product {
			background-color: #fff;
			padding: 20px;
			box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
			text-align: center;
		}
		
		.product img {
			max-width: 100%;
			height: auto;
		}
		
		.footer {
			background-color: #333;
			color: #fff;
			padding: 20px;
			text-align: center;
		}
	</style>
</head>
<body>
	<div class="header">
		<h1>Trang web mẫu</h1>
		<p>Một trang web đơn giản</p>
	</div>
	
	<div class="navbar">
		<a href="#">Trang chủ</a>
		<a href="#">Giới thiệu</a>
		<a href="#">Liên hệ</a>
	</div>
	
	<div class="content">
		<div class="product">
			<img src="https://via.placeholder.com/400x400.png" alt="Sản phẩm 1">
			<p>Sản phẩm 1</p>
		</div>
		<div class="product">
			<img src="https://via.placeholder.com/400x400.png" alt="Sản phẩm 2">
			<p>Sản phẩm 2</p>
		</div>
		<div class="product">
			<img src="https://via.placeholder.com/400x400.png" alt="Sản phẩm 3">
			<p>Sản phẩm 3</p>
		</div>
		<!-- Thêm các sản phẩm khác tại đây -->
	</div>
	
	<div class="footer">
		<p>Trang web mẫu - &copy; 2023</p>
	</div>
	
	<script>
		// Thêm hiệu ứng động cho navbar
		window.onscroll = function() {scrollFunction()};

		function scrollFunction() {
		  if (document.body.scrollTop > 50 || document.documentElement.scrollTop > 50) {
			document.querySelector(".navbar").style.padding = "10px 10px";
			document.querySelector(".navbar a").style.fontSize = "18px";
		  } else {
			document.querySelector(".navbar").style.padding = "20px";
			document.querySelector(".navbar a").style.fontSize = "22px";
		  }
		}
	</script>
</body>
</html>

