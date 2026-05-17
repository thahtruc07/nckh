<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>ResearchHub</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f6fa;
        }

        /* Topbar */
        .topbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 24px;
            background: white;
            border-bottom: 1px solid #ddd;
        }

        .logo {
            font-weight: bold;
            color: #5a67d8;
        }

        .top-menu {
            display: flex;
            gap: 20px;
            align-items: center;
        }

        .top-menu a {
            text-decoration: none;
            color: #333;
            font-size: 14px;
        }

        .top-menu a:hover {
            color: #5a67d8;
        }

        .search-box {
            padding: 6px 10px;
            border: 1px solid #ccc;
            border-radius: 6px;
        }

        /* Layout */
        .container {
            display: flex;
        }

        /* Sidebar */
        .sidebar {
            width: 220px;
            background: white;
            height: 100vh;
            padding: 20px;
            border-right: 1px solid #ddd;
        }

        .sidebar h4 {
            margin-top: 20px;
            font-size: 13px;
            color: #999;
        }

        .sidebar a {
            display: block;
            margin: 10px 0;
            text-decoration: none;
            color: #333;
            font-size: 14px;
        }

        .sidebar a:hover {
            color: #5a67d8;
        }

        /* Main */
        .main {
            flex: 1;
            padding: 20px;
        }

        .banner {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 30px;
            border-radius: 12px;
            margin-bottom: 20px;
        }

        .banner input {
            width: 60%;
            padding: 10px;
            border: none;
            border-radius: 6px;
            margin-top: 10px;
        }

        /* Cards */
        .card {
            background: white;
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .card h3 {
            margin-top: 0;
        }

        .paper {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }

        .paper:last-child {
            border-bottom: none;
        }

        /* Right panel */
        .right {
            width: 280px;
            padding: 20px;
        }

    </style>
</head>
<body>

<!-- TOPBAR -->
<div class="topbar">
    <div class="logo">ResearchHub</div>

    <input class="search-box" placeholder="Tìm tài liệu..." />

    <div class="top-menu">
        <a href="#">Chủ đề hot</a>
        <a href="#">Trợ lý AI</a>
        <a href="#">Tải tài liệu</a>
        <a href="#">🔔</a>
    </div>
</div>

<div class="container">

    <!-- SIDEBAR -->
    <div class="sidebar">
        <a href="#"><b>Trang chủ</b></a>
        <a href="#">Tìm kiếm nghiên cứu</a>
        <a href="#">Công cụ AI</a>
        <a href="#">Thư viện</a>
        <a href="#">Cộng đồng</a>

        <h4>Nâng cao</h4>
        <a href="#">Trích nguồn APA</a>
        <a href="#">Tạo outline</a>
        <a href="#">Gợi ý câu hỏi</a>
    </div>

    <!-- MAIN -->
    <div class="main">

        <!-- Banner -->
        <div class="banner">
            <h2>Hành trình nghiên cứu thông minh hơn</h2>
            <p>Tìm kiếm, lưu trữ và tóm tắt tài liệu với AI</p>
            <input placeholder="Nhập chủ đề nghiên cứu..." />
        </div>

        <!-- Saved Papers -->
        <div class="card">
            <h3>Tài liệu của bạn</h3>

            <div class="paper">
                <b>AI trong giáo dục</b><br>
                <small>2024 • Nguyễn Văn A</small>
            </div>

            <div class="paper">
                <b>Blockchain và tài chính</b><br>
                <small>2023 • Trần Văn B</small>
            </div>

            <div class="paper">
                <b>Machine Learning cơ bản</b><br>
                <small>2025 • Lê Minh C</small>
            </div>
        </div>

    </div>

    <!-- RIGHT PANEL -->
    <div class="right">
        <div class="card">
            <h3>Thảo luận nổi bật</h3>
            <p>AI có thay thế nghiên cứu truyền thống?</p>
            <p>Ứng dụng SEM trong marketing</p>
        </div>

        <div class="card">
            <h3>Khảo sát</h3>
            <p>Bạn dùng AI bao nhiêu lần/ngày?</p>
        </div>
    </div>

</div>

</body>
</html>
