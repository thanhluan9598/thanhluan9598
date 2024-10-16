-<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cửa Hàng Của Tôi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Cửa Hàng Trực Tuyến</h1>
        <nav>
            <a href="#products">Sản Phẩm</a>
            <a href="#admin">Quản Trị</a>
        </nav>
    </header>
    <main>
        <section id="products">
            <h2>Sản Phẩm</h2>
            <div class="product">
                <h3>Sản Phẩm 1</h3>
                <p>Giá: 100.000 VNĐ</p>
                <button onclick="addToCart('Sản Phẩm 1')">Thêm Vào Giỏ</button>
            </div>
            <!-- Thêm sản phẩm khác ở đây -->
        </section>
        <section id="admin">
            <h2>Quản Trị</h2>
            <form id="adminForm">
                <label for="username">Tên Đăng Nhập:</label>
                <input type="text" id="username" required>
                <label for="password">Mật Khẩu:</label>
                <input type="password" id="password" required>
                <button type="submit">Đăng Nhập</button>
            </form>
            <div id="adminMessage"></div>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
