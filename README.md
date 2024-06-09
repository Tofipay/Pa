<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تصميم الصفحة</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #003366;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #003366;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .video-player {
            margin-bottom: 20px;
            text-align: center;
        }

        .episode-list {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .episode-item {
            margin: 5px;
            padding: 10px;
            background-color: #111;
            border-radius: 8px;
            cursor: pointer;
            width: 60px;
            text-align: center;
        }

        .episode-item:hover {
            background-color: #003366;
        }

        #episode-title {
            text-align: center;
            font-size: 20px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="video-player">
            <iframe allow="fullscreen" allowfullscreen height="315" src="" width="100%" style="border:none;"></iframe>
            <div id="episode-title"></div>
        </div>
        <ul class="episode-list">
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/jyent0', 'مسلسل عثمان حلقة 1')">1</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/gc2jqw', 'مسلسل عثمان حلقة 2')">2</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/rr6681', 'مسلسل عثمان حلقة 3')">3</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/taf4ci', 'مسلسل عثمان حلقة 4')">4</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/w1rkc6', 'مسلسل عثمان حلقة 5')">5</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/0u8w2l', 'مسلسل عثمان حلقة 6')">6</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/9ixtwk', 'مسلسل عثمان حلقة 7')">7</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/7544vq', 'مسلسل عثمان حلقة 8')">8</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/gkqfjy', 'مسلسل عثمان حلقة 9')">9</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/3sn137', 'مسلسل عثمان حلقة 10')">10</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/cvetfr', 'مسلسل عثمان حلقة 11')">11</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/95qap8', 'مسلسل عثمان حلقة 12')">12</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/slvn5s', 'مسلسل عثمان حلقة 13')">13</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/opsr0q', 'مسلسل عثمان حلقة 14')">14</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/jd4vfh', 'مسلسل عثمان حلقة 15')">15</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/h6pb0t', 'مسلسل عثمان حلقة 16')">16</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/m5e8u1', 'مسلسل عثمان حلقة 17')">17</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/ckns9n', 'مسلسل عثمان حلقة 18')">18</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/keh02y', 'مسلسل عثمان حلقة 19')">19</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/j8lthb', 'مسلسل عثمان حلقة 20')">20</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/wddp1b', 'مسلسل عثمان حلقة 21')">21</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/niipwz', 'مسلسل عثمان حلقة 22')">22</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/7ia38w', 'مسلسل عثمان حلقة 23')">23</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/dc8enr', 'مسلسل عثمان حلقة 24')">24</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/j3u82e', 'مسلسل عثمان حلقة 25')">25</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/7a5sml', 'مسلسل عثمان حلقة 26')">26</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/l3b8lh', 'مسلسل عثمان حلقة 27')">27</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/udi8vg', 'مسلسل عثمان حلقة 28')">28</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/lwaup1', 'مسلسل عثمان حلقة 29')">29</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/7mofid', 'مسلسل عثمان حلقة 30')">30</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/ltwnat', 'مسلسل عثمان حلقة 31')">31</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/a6153q', 'مسلسل عثمان حلقة 32')">32</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/6m5nc6', 'مسلسل عثمان حلقة 33')">33</li>
            <li class="episode-item" onclick="playVideo('https://streamable.com/e/6m5nc6', 'مسلسل عثمان حلقة 34')">34</li>
        </ul>
    </div>

    <script>
        function playVideo(videoUrl, episodeTitle) {
            const iframe = document.querySelector('.video-player iframe');
            iframe.src = videoUrl;
            document.getElementById('episode-title').textContent = episodeTitle;
        }
    </script>
</body>
</html>
