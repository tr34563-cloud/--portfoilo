
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio | วิภาวี บุตรศรี</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

:root {
    --pink: #e85b9b;
    --dark-pink: #a92765;
    --light-pink: #fff0f6;
    --white: #ffffff;
    --gray: #777;
}

body {
    font-family: Arial, Tahoma, sans-serif;
    background: white;
    color: #333;
    line-height: 1.7;
}

/* Header */
header {
    position: sticky;
    top: 0;
    z-index: 100;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 8%;
    background: white;
    box-shadow: 0 2px 12px #00000015;
}

.logo {
    display: flex;
    align-items: center;
    gap: 12px;
    color: var(--dark-pink);
    font-size: 22px;
    font-weight: bold;
}

.logo img {
    width: 48px;
    height: 65px;
    object-fit: contain;
}

nav ul {
    display: flex;
    gap: 25px;
    list-style: none;
}

nav a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

nav a:hover {
    color: var(--pink);
}

/* Home */
.hero {
    min-height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 50px 8%;
    background: linear-gradient(135deg, white 45%, var(--light-pink) 45%);
}

.hero-content {
    max-width: 800px;
}

.hero-logo {
    width: 140px;
    height: 170px;
    object-fit: contain;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: 52px;
    color: var(--dark-pink);
}

.hero h2 {
    font-size: 27px;
    margin: 15px 0;
}

.hero h2 span {
    color: var(--pink);
}

.hero p {
    color: var(--gray);
    font-size: 18px;
}

.btn {
    display: inline-block;
    margin-top: 25px;
    padding: 12px 30px;
    background: var(--pink);
    color: white;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
}

.btn:hover {
    background: var(--dark-pink);
}

/* General Sections */
section {
    padding: 75px 8%;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
}

.section-title h2 {
    font-size: 34px;
    color: var(--dark-pink);
}

.section-title p {
    color: var(--gray);
}

/* About */
.about {
    max-width: 950px;
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 45px;
    align-items: center;
}

.profile-box {
    width: 230px;
    height: 230px;
    margin: auto;
    border-radius: 50%;
    overflow: hidden;
    border: 7px solid #f6a9ca;
    background: var(--light-pink);
}

.profile-box img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.about-text h3 {
    color: var(--dark-pink);
    font-size: 27px;
    margin-bottom: 15px;
}

.about-text p {
    color: #666;
    margin-bottom: 10px;
}

/* Education */
.education {
    background: var(--light-pink);
}

.education-card {
    max-width: 650px;
    margin: auto;
    padding: 35px;
    background: white;
    text-align: center;
    border-radius: 18px;
    border-top: 5px solid var(--pink);
    box-shadow: 0 5px 20px #e85b9b20;
}

.education-card h3 {
    color: var(--dark-pink);
    font-size: 25px;
    margin-bottom: 15px;
}

.education-card p {
    margin: 8px;
    color: #666;
}

/* Footer */
footer {
    padding: 22px;
    text-align: center;
    background: var(--dark-pink);
    color: white;
}

/* Mobile */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        gap: 12px;
    }

    nav ul {
        gap: 15px;
        font-size: 14px;
    }

    .hero h1 {
        font-size: 38px;
    }

    .about {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .profile-box {
        width: 190px;
        height: 190px;
    }
}
</style>
</head>

<body>

<!-- Header -->
<header>
    <div class="logo">
        <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Logo_of_Chulalongkorn_University_(1988).svg"
             alt="ตราพระเกี้ยว">
        <span>My Portfolio</span>
    </div>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#education">Education</a></li>
        </ul>
    </nav>
</header>

<main>

<!-- Home -->
<section id="home" class="hero">
    <div class="hero-content">

        <img class="hero-logo"
             src="https://commons.wikimedia.org/wiki/Special:FilePath/Logo_of_Chulalongkorn_University_(1988).svg"
             alt="ตราพระเกี้ยว">

        <h1>Portfolio</h1>

        <h2>สวัสดีค่ะ ฉันชื่อ <span>วิภาวี บุตรศรี</span></h2>

        <p>
            ชื่อเล่น ไอริน | อายุ 17 ปี
            <br>
            นักเรียนชั้นมัธยมศึกษาปีที่ 6
        </p>

        <a href="#about" class="btn">ABOUT ME</a>

    </div>
</section>

<!-- About Me -->
<section id="about">

    <div class="section-title">
        <h2>ABOUT ME</h2>
        <p>มาทำความรู้จักกับฉันกัน</p>
    </div>

    <div class="about">

        <div class="profile-box">
            <img src="profile.jpg" alt="รูปโปรไฟล์ไอริน">
        </div>

        <div class="about-text">
            <h3>สวัสดีค่ะ ฉันชื่อไอริน</h3>

            <p>ชื่อ - นามสกุล : วิภาวี บุตรศรี</p>
            <p>ชื่อเล่น : ไอริน</p>
            <p>อายุ : 17 ปี</p>
            <p>งานอดิเรก : เล่น Roblox</p>
        </div>

    </div>
</section>

<!-- Education -->
<section id="education" class="education">

    <div class="section-title">
        <h2>EDUCATION</h2>
        <p>ประวัติการศึกษา</p>
    </div>

    <div class="education-card">

        <h3>โรงเรียนธัญรัตน์</h3>

        <p>ระดับการศึกษา : มัธยมศึกษาตอนปลาย</p>
        <p>ชั้นปี : มัธยมศึกษาปีที่ 6</p>

    </div>

</section>

</main>

<footer>
    <p>© 2026 My Portfolio | วิภาวี บุตรศรี</p>
    <p>Designed with Pink 💗</p>
</footer>

</body>
</html>
