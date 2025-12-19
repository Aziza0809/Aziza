# Aziza
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>Aziza Komilovna | Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

    <!-- ICONS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f5f7fa;
            color: #1f2933;
        }

        /* CLICKABLE HEADER */
        .click-header {
            background: #0a2540;
            color: white;
            padding: 50px 20px;
            text-align: center;
            cursor: pointer;
        }

        .profile-img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #fff;
            box-shadow: 0 6px 15px rgba(0,0,0,0.25);
            margin-bottom: 15px;
        }

        h1 {
            margin: 0;
            font-size: 32px;
        }

        .hint {
            margin-top: 8px;
            opacity: 0.9;
        }

        section {
            max-width: 900px;
            margin: 30px auto;
            padding: 0 20px;
            display: none;
        }

        section.show {
            display: block;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        h2 {
            color: #0a2540;
        }

        h2 i {
            margin-right: 8px;
        }

        .contact a {
            display: block;
            color: #0a2540;
            text-decoration: none;
            margin-bottom: 8px;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #e5e7eb;
        }
    </style>
</head>
<body>

<div class="click-header" id="toggleBtn">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeMnWuCBvsVgqWNRGqGRAXjv93-_-2nnTjmw&s" class="profile-img">
    <h1>Aziza Komilovna</h1>
    <p class="hint"><i class="fa-solid fa-chevron-down"></i> Bosib ma’lumotlarni ko‘ring</p>
</div>

<section id="content">
    <div class="card">
        <h2><i class="fa-solid fa-user"></i> Men haqimda</h2>
        <p>IT yo‘nalishida tahsil olayotgan talabaman. Bank IT sohasiga qiziqaman.</p>
    </div>

    <div class="card">
        <h2><i class="fa-solid fa-graduation-cap"></i> Ta’lim</h2>
        <p>Toshkent xalqaro moliyaviy boshqaruv va texnologiyalari Universiteti</p>
    </div>

    <div class="card">
        <h2><i class="fa-solid fa-laptop-code"></i> Ko‘nikmalar</h2>
        <ul>
            <li>IT asoslari</li>
            <li>Kompyuter savodxonligi</li>
            <li>Bank tizimlariga qiziqish</li>
        </ul>
    </div>

    <div class="card contact">
        <h2><i class="fa-solid fa-address-book"></i> Aloqa</h2>
        <a href="mailto:yuldoshevaaziza077@gmail.com"><i class="fa-solid fa-envelope"></i> Email</a>
        <a href="tel:+998996240809"><i class="fa-solid fa-phone"></i> Telefon</a>
    </div>
</section>

<footer>© 2025 Aziza Komilovna</footer>

<script>
    const btn = document.getElementById("toggleBtn");
    const content = document.getElementById("content");

    btn.addEventListener("click", () => {
        content.classList.toggle("show");
    });
</script>

</body>
</html>
