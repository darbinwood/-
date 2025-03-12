# -<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>داربین</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">خانه</a></li>
                <li><a href="#">محصولات</a></li>
                <li><a href="#">درباره ما</a></li>
                <li><a href="#">تماس با ما</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>خوش آمدید به داربین!</h1>
            <p>محصولات و خدمات ما را بررسی کنید.</p>
        </section>
        <section class="categories">
            <h2>دسته‌بندی محصولات</h2>
            <!-- اینجا می‌توانید دسته‌بندی‌های مختلف محصولات را اضافه کنید -->
        </section>
    </main>
    <footer>
        <p>&copy; 2025 داربین</p>
    </footer>
</body>
</html>
2. CSS برای طراحی صفحه اصلی (styles.css)
css
Copy
Edit
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1a1a1a; /* پس‌زمینه مشکی */
    color: white;
}

header {
    background-color: #333;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: #ff6600; /* نارنجی */
    text-decoration: none;
    font-size: 18px;
}

.hero {
    background-color: #1a1a1a;
    text-align: center;
    padding: 50px 0;
}

.hero h1 {
    color: #ff6600;
    font-size: 36px;
}

.hero p {
    font-size: 20px;
}

.categories {
    padding: 30px 0;
    text-align: center;
}

footer {
    background-color: #333;
    text-align: center;
    padding: 20px 0;
    color: #999;
}
3. صفحه محصول (Product Page)
html
Copy
Edit
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محصولات داربین</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">خانه</a></li>
                <li><a href="#">محصولات</a></li>
                <li><a href="#">درباره ما</a></li>
                <li><a href="#">تماس با ما</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="product">
            <h2>محصول 1</h2>
            <img src="product-image.jpg" alt="محصول">
            <p>توضیحات محصول</p>
            <button>افزودن به سبد خرید</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 داربین</p>
    </footer>
</body>
</html>
4. JavaScript برای تعامل
javascript
Copy
Edit
// این کد می‌تواند برای تعاملات مثل تغییر رنگ و چیدمان خانه استفاده شود
document.querySelector("#changeColorButton").addEventListener("click", function() {
    document.body.style.backgroundColor = "orange";
});
وود
