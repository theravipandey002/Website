# Website
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pandey Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: rgb(204, 241, 125);
        }
        header {
            background-color: #333;
            color: rgb(204, 241, 125);
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product {
            background-color: white;
            margin: 15px;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 350px;
        }
        .product img data:{
            width: 10%;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: green;
            font-size: 18px;
        }
        .product button {
            background-color: #061d0b;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background-color: #842188;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        My Pandey Store
    </header>
    <div class="container">
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71v2jVh6nIL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 1">
            <h3>IPhone 18</h3>
            <p>₹699</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/615O-NFQKdL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 2">
            <h3>Iphone 19</h3>
            <p>₹799</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71657TiFeHL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 3">
            <h3>IPhone 20</h3>
            <p>₹899</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/713SsA7gftL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 1">
            <h3>IPhone 21</h3>
            <p>₹999</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/61DjMd76QnL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 1">
            <h3>IPhone 22</h3>
            <p>₹1099</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71d7rfSl0wL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 1">
            <h3>IPhone 23</h3>
            <p>₹1199</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/71nvkHnPpZL._AC_UY327_FMwebp_QL65_.jpg" alt="Product 1">
            <h3>IPhone 24</h3>
            <p>₹1299</p>
            <button>Add to Cart</button>
        </div>
    </div>
    <footer>
        &copy; 2025 My E-Commerce Store
    </footer>
</body>
</html>
