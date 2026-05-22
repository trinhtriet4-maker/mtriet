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
            font-family:Arial;
        }

        body{
            background:#0f172a;
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
            margin-bottom:20px;
            color:#38bdf8;
        }

        header p{
            font-size:22px;
            max-width:700px;
            line-height:1.6;
        }

        .btn{
            margin-top:30px;
            padding:15px 30px;
            background:#38bdf8;
            color:black;
            text-decoration:none;
            border-radius:10px;
            font-weight:bold;
        }

        section{
            padding:80px 10%;
        }

        h2{
            font-size:40px;
            margin-bottom:30px;
            color:#38bdf8;
        }

        .about,
        .skills,
        .projects{
            margin-bottom:80px;
        }

        .skill-list{
            display:flex;
            flex-wrap:wrap;
            gap:15px;
        }

        .skill{
            background:#1e293b;
            padding:15px 25px;
            border-radius:10px;
        }

        .project-card{
            background:#1e293b;
            padding:25px;
            border-radius:15px;
            margin-bottom:20px;
        }

        footer{
            text-align:center;
            padding:30px;
            background:#020617;
        }
    </style>
</head>

<body>

    <header>
        <h1>Xin chào 👋</h1>
        <p>
            Mình là ABC — Web Developer / Student / Designer
        </p>

        <a href="#projects" class="btn">
            Xem dự án
        </a>
    </header>

    <section class="about">
        <h2>Giới thiệu</h2>

        <p>
            Mình thích lập trình website và thiết kế giao diện đẹp.
            Hiện đang học HTML, CSS và JavaScript.
        </p>
    </section>

    <section class="skills">
        <h2>Kỹ năng</h2>

        <div class="skill-list">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">GitHub</div>
        </div>
    </section>

    <section class="projects" id="projects">
        <h2>Dự án</h2>

        <div class="project-card">
            <h3>Website Cá Nhân</h3>
            <p>Trang portfolio đầu tiên bằng HTML/CSS.</p>
        </div>

        <div class="project-card">
            <h3>Landing Page</h3>
            <p>Thiết kế giao diện giới thiệu sản phẩm.</p>
        </div>
    </section>

    <footer>
        © 2025 - Portfolio của ABC
    </footer>

</body>
</html>
