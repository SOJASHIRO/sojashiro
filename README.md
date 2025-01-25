<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - SOJA SHIRO</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-image: url('https://images.unsplash.com/photo-1557683316-973673baf926');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            min-height: 100vh;
            font-family: 'Arial', sans-serif;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            padding: 2rem 6rem;
            align-items: center;
        }

        .nav-menu {
            display: flex;
            gap: 4rem;
        }

        .nav-link {
            text-decoration: none;
            font-size: 0.8rem;
            font-weight: 300;
            letter-spacing: 1px;
            transition: opacity 0.3s;
            color: black;
            mix-blend-mode: difference;
            filter: invert(1);
        }

        .brand-name {
            font-size: 1.2rem;
            font-weight: 400;
            text-decoration: none;
            margin-left: 4rem;
            color: black;
            mix-blend-mode: difference;
            filter: invert(1);
        }

        .about-container {
            max-width: 800px;
            margin: 100px auto;
            padding: 0 20px;
        }

        .about-title {
            font-size: 1.5rem;
            font-weight: 300;
            margin-bottom: 40px;
            letter-spacing: 2px;
            color: black;
            mix-blend-mode: difference;
            filter: invert(1);
        }

        .about-content {
            font-size: 0.9rem;
            line-height: 1.8;
            font-weight: 300;
            margin-bottom: 60px;
            color: black;
            mix-blend-mode: difference;
            filter: invert(1);
        }

        .about-image {
            width: 100%;
            max-width: 1000px;
            height: auto;
            margin: 40px auto;
            display: block;
        }
    </style>
</head>
<body style="background: white;">
    <nav class="navbar">
        <div class="nav-menu">
            <a href="index.html" class="nav-link">NEW ARRIVALS</a>
            <a href="about.html" class="nav-link">ABOUT</a>
            <a href="#" class="nav-link">STORIES</a>
            <a href="#" class="nav-link">CONTACT</a>
        </div>
        <a href="index.html" class="brand-name">SOJA SHIRO</a>
    </nav>

    <div class="about-container">
        <h1 class="about-title">ABOUT THE SOJA SHIRO</h1>
        <p class="about-content">
            SOJA SHIRO represents a harmonious blend of traditional craftsmanship and contemporary design. Our philosophy centers on creating timeless pieces that transcend seasonal trends, focusing on quality materials and sustainable practices. Each creation tells a story of dedication to excellence and respect for artistic heritage.
        </p>
        
        <img src="https://images.unsplash.com/photo-1493606278519-11aa9f86e40a" alt="About Image" class="about-image">
    </div>
</body>
