my-shopping-site/
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Shopping Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Shopping Site</h1>
    </header>
    <main>
        <section id="products">
            <h2>Products</h2>
            <div class="product">
                <h3>Product 1</h3>
                <p>Price: $10</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <h3>Product 2</h3>
                <p>Price: $20</p>
                <button>Add to Cart</button>
            </div>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

main {
    padding: 1em;
}

.product {
    background-color: white;
    border: 1px solid #ccc;
    margin: 1em 0;
    padding: 1em;
    border-radius: 5px;
}

button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 0.5em 1em;
    cursor: pointer;
    border-radius: 3px;
}

button:hover {
    background-color: #218838;
}
document.addEventListener('DOMContentLoaded', () => {
    const buttons = document.querySelectorAll('button');

    buttons.forEach(button => {
        button.addEventListener('click', () => {
            alert('Item added to cart!');
        });
    });
});
document.addEventListener('DOMContentLoaded', () => {
    const buttons = document.querySelectorAll('button');

    buttons.forEach(button => {
        button.addEventListener('click', () => {
            alert('Item added to cart!');
        });
    });
});
