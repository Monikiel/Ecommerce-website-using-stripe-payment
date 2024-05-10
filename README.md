# Ecommerce-website-using-stripe-payment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ecommerce Website With Payment</title>
    <!-- Link to CSS -->
    <link rel="stylesheet" href="CSS/style.css">
    <!-- Box Icons -->
    <link 
    href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css'
     rel='stylesheet'
    />
</head>
<body>
<!-- Navbar -->  
<header>
    <!-- Nav -->
    <div class="nav container">
   <!-- Logo -->   
   <a href="#" class="logo">Ecommerce</a>   
    <!-- Cart Icon -->
    <i class='bx bxs-shopping-bag' id="Cart-icon" data-quantitiy="0"></i>
    <!-- cart -->
    <div class="cart">
        <h2 class="cart-title">Your Cart</h2>
        <!-- Content -->
<div class="cart-content">
    <div class="cart-box">
        <img src="img/product1.jpeg" alt="" class="cart-img" />
        <div class="detail-box">
            <div class="cart-product-title">Product Shirt</div>
            <div class="cart-price">$50</div>
            <input type="number" name="" id="" value="1" class="cart-quantity"
            />
        </div>
        <!-- Remove item -->
        <i class='bx bx-trash-alt cart-remove' ></i>
    </div>
</div>
<!-- Total -->
<div class="total">
    <div class="total-title">Total</div>
    <div class="total-price">$0</div>
</div>
<!-- Buy Button -->
<button type="button" class="btn-buy">Pay Now</button>
<!-- Close Cart -->
<i class='bx bx-x' id="close-cart"></i>
    </div>
    </div>
</header>  
</body>
</html>



cursor: pointer;
}
