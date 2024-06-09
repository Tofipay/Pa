 سلا.
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عرض الأفلام والحلقات</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            display: flex;
            overflow-x: auto;
            scroll-behavior: smooth;
            gap: 5px;
            padding: 10px;
            max-width: 100%;
            margin-bottom: 20px; /* إضافة مسافة بين الصفوف */
        }

        .movie-card, .episode-card {
            background-color: #003366; /* لون أزرق غامق */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            min-width: 160px;
            transition: transform 0.2s;
            color: white; /* لون النص أبيض */
        }

        .movie-card:hover, .episode-card:hover {
            transform: scale(1.05);
        }

        .movie-poster, .episode-poster {
            width: 100%;
            height: 200px; /* تعديل ارتفاع الصورة */
            object-fit: cover; /* للحفاظ على نسبة العرض إلى الارتفاع */
        }

        .movie-info, .episode-info {
            padding: 10px;
        }

        .movie-title, .episode-title {
            font-size: 16px;
            margin: 0;
        }

        .title-wrapper {
            background-color: #003366;
            color: white;
            padding: 0px 0px;
            border-radius: 20px;
            margin: -5px 0 5px; /* مسافة بين العنوان وصف الحلقات */
            text-align: center;
            width: 100%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

    </style>
</head>
<body>
    <!-- عنوان الأفلام -->
    <div class="title-wrapper">
        <h2 class="title">أفلام</h2>
    </div>
    
    <div class="container" id="movie-container">
        <!-- فيلم 1 -->
        <div class="movie-card">
            <a href="go:S1">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/05/MV5BMzkwODZjYjAtZDQ0Yy00YWM0LThmZTMtM2FiMzE1OWU2OGViXkEyXkFqcGdeQXVyMjQzNzIzMTA@.jpg_V1_SX700.jpg" alt="Movie Poster 1" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Movie Title 1</h2>
                </div>
            </a>
        </div>
        
        <!-- فيلم 2 -->
        <div class="movie-card">
            <a href="go:S2">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/06/MV5BN2I3NjEzZjctY2ViZS00Zjg5LWEzYjMtMGEyYTM0MzNkY2RlXkEyXkFqcGdeQXVyODU0MTM0OTU@._V1_-scaled.jpg" alt="Movie Poster 2" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Movie Title 2</h2>
                </div>
            </a>
        </div>

        <!-- فيلم 3 -->
        <div class="movie-card">
            <a href="go:S3">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2019/11/MV5BZGZjYTY4MzMtOTc1ZC00NWM2LTkxMzEtOTA2MTc5YmZhYzhlXkEyXkFqcGdeQXVyOTg4MDYyNw@@-.jpg" alt="Movie Poster 3" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Movie Title 3</h2>
                </div>
            </a>
        </div>

        <!-- فيلم 4 -->
        <div class="movie-card">
            <a href="go:S4">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2019/02/MV5BMTM4OGJmNWMtOTM4Ni00NTE3LTg3MDItZmQxYjc4N2JhNmUxXkEyXkFqcGdeQXVyNTgzMDMzMTg@._V1_SY1000_SX675_AL_.jpg" alt="Movie Poster 4" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Movie Title 4</h2>
                </div>
            </a>
        </div>

        <!-- فيلم 5 -->
        <div class="movie-card">
            <a href="go:S5">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/03/MV5BNWYxMWFmNmUtYzgzNy00NWYzLThlZDktN2I1ODAyMDhkMWI4XkEyXkFqcGdeQXVyODE5NzE3OTE@.jpg_V1_SX700.jpg" alt="Movie Poster 5" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Movie Title 5</h2>
                </div>
            </a>
        </div>

        <!-- فيلم 6 -->
        <div class="movie-card">
            <a href="go:S6">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/03/MV5BNWYxMWFmNmUtYzgzNy00NWYzLThlZDktN2I1ODAyMDhkMWI4XkEyXkFqcGdeQXVyODE5NzE3OTE@.jpg_V1_SX700.jpg" alt="Movie Poster 6" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Movie Title 6</h2>
                </div>
            </a>
        </div>
    </div>

    <!-- عنوان المسلسلات -->
    <div class="title-wrapper">
        <h2 class="title">مسلسلات تركية</h2>
    </div>
    
    <!-- صف الحلقات -->
    <div class="container" id="episode-container">
        <!-- حلقة 1 -->
        <div class="episode-card">
            <a href="go:E1">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2023/10/f7hfgnexkaas0bn-medium.jpg" alt="Episode 1" class="episode-poster">
                <div class="episode-info">
                    <h2 class="episode-title">Episode Title 1</h2>
                </div>
            </a>
        </div>

        <!-- حلقة 2 -->
        <div class="episode-card">
            <a href="go:E2">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2023/11/MV5BM2JiZmNhNDctZmViMC00ZDYwLWE3MTQtZTQyNWY1NjkxNjZiXkEyXkFqcGdeQXVyMTMxODEzNzgz._V1_SX700.jpg" alt="Episode 2" class="episode-poster">
<HTML لانغ = "EN">            <div class="episode-info">
<<الرأس>.>.<h2 class="episode-title">Episode Title 2</h2>
 <ميتا charset="UTF-8"> </div>
 <meta name="viewport" content="width=عرض الجهاز، المقياس الأولي=1.0"> </a>
 <title>عرض الأفلام والحلقات</title> </div>

 الجسم {     <!-- حلقة 3 -->
 الخط الأسرة: Arial، sans-serif. <div class="episode-card">
 الخلفية اللون: #ffffff; <a href="go:E3">
 عرض: المرن. <img src="https://www.tuktukcima.com/wp-content/uploads/2024/03/MV5BYjQ2ODViODktN2Y0NC00MGMzLWI0YzEtMmMwZTRhZWIzMzQyXkEyXkFqcGdeQXVyNzg5NTE1MzE@.jpg_V1_SX700.jpg" alt="Episode 3" class="episode-poster">
 فليكس الاتجاه: العمود؛ <div class="episode-info">
 محاذاة البنود: مركز; <h2 class="episode-title">Episode Title 3</h2>
 الارتفاع: 100vh; </div>
 الهامش: 0؛ </a>
 } </div>

 .الحاوية {     <!-- حلقة 4 -->
 عرض: المرن. <div class="episode-card">
 تجاوز-x: السيارات؛ <a href="go:E4">
 التمرير السلوك: على نحو سلس. <img src="https://via.placeholder.com/160x200.png?text=Episode+4" alt="Episode 4" class="episode-poster">
 الفجوة: 5px؛ <div class="episode-info">
 الحشو: 10px.                 <h2 class="episode-title">Episode
