<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clothing Display</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Clothing Display</h1>
    </header>
    <main>
        <div class="product">
            <img src="shirt.jpg" alt="Shirt">
            <h2>Stylish Shirt</h2>
            <p>$25.00</p>
        </div>
        <div class="product">
            <img src="pants.jpg" alt="Pants">
            <h2>Comfy Pants</h2>
            <p>$30.00</p>
        </div>
        <div class="product">
            <img src="jacket.jpg" alt="Jacket">
            <h2>Cool Jacket</h2>
            <p>$50.00</p>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

main {
    display: flex;
    justify-content: space-around;
    padding: 2em;
}

.product {
    background-color: #fff;
    padding: 1em;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.product img {
    max-width: 100%;
    border-radius: 5px;
}

.product h2 {
    margin: 0.5em 0;
    color: #333;
}

.product p {
    color: #777;
}
// script.js
document.addEventListener('DOMContentLoaded', () => {
    console.log('Clothing Display Website Loaded');
});
