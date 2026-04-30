# <!DOCTYPE html>

<html lang="th">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Shoe Store</title>

<style>

body {

    font-family: Arial, sans-serif;

    margin: 0;

    background: #f5f5f5;

}

header {

    background: black;

    color: white;

    padding: 15px;

    text-align: center;

}

nav {

    display: flex;

    justify-content: center;

    background: #333;

}

nav a {

    color: white;

    padding: 14px 20px;

    text-decoration: none;

}

nav a:hover {

    background: #555;

}

.hero {

    background: url('https://images.unsplash.com/photo-1528701800489-20be9c62a36d') no-repeat center/cover;

    height: 300px;

    display: flex;

    align-items: center;

    justify-content: center;

    color: white;

    font-size: 30px;

    font-weight: bold;

}

.container {

    padding: 20px;

}

.products {

    display: grid;

    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));

    gap: 20px;

}

.card {

    background: white;

    padding: 15px;

    border-radius: 10px;

    text-align: center;

}

.card img {

    width: 100%;

    border-radius: 10px;

}

button {

    background: black;

    color: white;

    border: none;

    padding: 10px;

    cursor: pointer;

}

button:hover {

    background: #444;

}

footer {

    text-align: center;

    padding: 10px;

    background: black;

    color: white;

}

</style>

</head>

<body>

<header>

    <h1>👟 Shoe Store</h1>

    <p>ร้านรองเท้าแฟชั่น</p>

</header>

<nav>

    <a href="#">หน้าแรก</a>

    <a href="#">สินค้า</a>

    <a href="#">เกี่ยวกับ</a>

    <a href="#">ติดต่อ</a>

</nav>

<div class="hero">

    รองเท้าที่ใช่ สำหรับคุณ

</div>

<div class="container">

    <h2>สินค้าแนะนำ</h2>

    <div class="products">

        <div class="card">

            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff">

            <h3>Nike Air</h3>

            <p>฿3,500</p>

            <button>สั่งซื้อ</button>

        </div>

        <div class="card">

            <img src="https://images.unsplash.com/photo-1519741497674-611481863552">

            <h3>Adidas Run</h3>

            <p>฿2,900</p>

            <button>สั่งซื้อ</button>

        </div>

        <div class="card">

            <img src="https://images.unsplash.com/photo-1525966222134-fcfa99b8ae77">

            <h3>Converse Classic</h3>

            <p>฿2,200</p>

            <button>สั่งซื้อ</button>

        </div>

    </div>

</div>

<footer>

    <p>© 2025 Shoe Store</p>
