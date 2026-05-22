<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Cá Nhân</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, sans-serif;
        }

        body{
            background: linear-gradient(to right, #0f172a, #1e293b);
            color:white;
        }

        header{
            height:100vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            padding:20px;
        }

        header h1{
            font-size:60px;
            color:#38bdf8;
            margin-bottom:20px;
        }

        header h2{
            font-size:30px;
            margin-bottom:20px;
        }

        header p{
            font-size:20px;
            max-width:700px;
            line-height:1.8;
        }

        .btn{
            margin-top:30px;
            padding:15px 30px;
            background:#38bdf8;
            color:black;
            text-decoration:none;
            border-radius:10px;
            font-weight:bold;
            transition:0.3s;
        }

        .btn:hover{
            background:white;
        }

        section{
            padding:80px 10%;
        }

        h3{
            font-size:40px;
            margin-bottom:30px;
            color:#38bdf8;
            text-align:center;
        }

        .card{
            background:#1e293b;
            padding:30px;
            border-radius:20px;
            margin-bottom:30px;
            box-shadow:0 0 15px rgba(0,0,0,0.3);
        }

        ul{
            list-style:none;
        }

        ul li{
            padding:10px 0;
            font-size:20px;
        }

        footer{
            text-align:center;
            padding:30px;
            background:#020617;
            font-size:18px;
        }
    </style>
</head>

<body>

    <header>
        <h1>TRỊNH HUỲNH MINH TRIẾT</h1>

        <h2>Học sinh lớp 12C4</h2>

        <p>
            Trường Trung Học Phổ Thông Nguyễn Thái Học <br>
            Năm nay tôi 18 tuổi. <br><br>

            Tôi yêu thích lập trình, nghe nhạc, đi phượt
            và dạo biển.
        </p>

        <a href="#about" class="btn">
            Khám phá thêm
        </a>
    </header>

    <section id="about">

        <h3>Giới Thiệu</h3>

        <div class="card">
            <p style="font-size:22px; line-height:1.8;">
                Xin chào 👋 <br><br>

                Tôi là <b>Trịnh Huỳnh Minh Triết</b>,
                hiện là học sinh lớp <b>12C4</b>
                tại trường <b>THPT Nguyễn Thái Học</b>.

                Tôi đam mê công nghệ và thích khám phá
                những điều mới mẻ trong cuộc sống.
            </p>
        </div>

        <h3>Sở Thích</h3>

        <div class="card">
            <ul>
                <li>🎵 Nghe nhạc</li>
                <li>🏍️ Đi phượt</li>
                <li>🌊 Dạo biển</li>
                <li>💻 Tìm hiểu công nghệ</li>
            </ul>
        </div>

        <h3>Mục Tiêu</h3>

        <div class="card">
            <p style="font-size:22px; line-height:1.8;">
                Cố gắng học tập tốt, phát triển kỹ năng lập trình
                và trở thành một người thành công trong tương lai.
            </p>
        </div>

    </section>

    <footer>
        © 2025 - Portfolio của Trịnh Huỳnh Minh Triết
    </footer>

</body>
</html>
