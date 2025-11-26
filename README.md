# IPHONE

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Phone - متجر الهواتف</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="https://via.placeholder.com/32x32?text=MP" type="image/x-icon">
</head>
<body>
    <header>
        <div class="logo">
            <h1>My Phone</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#products">المنتجات</a></li>
                <li><a href="#cart">السلة</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
        <div class="search">
            <input type="text" placeholder="ابحث عن هاتف...">
            <button>بحث</button>
        </div>
    </header>

    <section id="home" class="hero">
        <h2>اكتشف أحدث الهواتف في السعودية</h2>
        <p>عروض خاصة على iPhone، Samsung، وغيرها!</p>
        <button>تسوق الآن</button>
    </section>

    <section id="products">
        <h2>الهواتف المتاحة</h2>
        <div class="categories">
            <button class="category-btn active" data-category="all">الكل</button>
            <button class="category-btn" data-category="iphone">iPhone</button>
            <button class="category-btn" data-category="samsung">Samsung</button>
            <button class="category-btn" data-category="accessories">إكسسوارات</button>
        </div>
        <div class="product-grid">
            <div class="product" data-category="iphone">
                <img src="https://via.placeholder.com/200x200?text=iPhone+15" alt="iPhone 15">
                <h3>iPhone 15</h3>
                <p>سعر: 3999 ريال</p>
                <button class="add-to-cart" data-name="iPhone 15" data-price="3999">أضف إلى السلة</button>
            </div>
            <div class="product" data-category="samsung">
                <img src="https://via.placeholder.com/200x200?text=Samsung+S24" alt="Samsung Galaxy S24">
                <h3>Samsung Galaxy S24</h3>
                <p>سعر: 2999 ريال</p>
                <button class="add-to-cart" data-name="Samsung Galaxy S24" data-price="2999">أضف إلى السلة</button>
            </div>
            <div class="product" data-category="accessories">
                <img src="https://via.placeholder.com/200x200?text=Case" alt="غطاء هاتف">
                <h3>غطاء هاتف</h3>
                <p>سعر: 99 ريال</p>
                <button class="add-to-cart" data-name="غطاء هاتف" data-price="99">أضف إلى السلة</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </section>

    <section id="cart">
        <h2>سلة التسوق</h2>
        <ul id="cart-items"></ul>
        <p>المجموع: <span id="total">0</span> ريال</p>
        <button id="checkout">الدفع</button>
    </section>

    <footer>
        <p>&copy; 2023 My Phone. جميع الحقوق محفوظة.</p>
        <div class="social">
            <a href="#">فيسبوك</a> | <a href="#">تويتر</a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
