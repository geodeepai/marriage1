<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>নাসিম এবং তানিয়ার বিবাহের আমন্ত্রণ</title>
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;600&family=Lateef&display=swap" rel="stylesheet">
    <style>
        :root {
            --islamic-green: #228B22;
            --gold: #FFD700;
        }

        body {
            background: #f0f5e9 url('islamic-pattern.png');
            font-family: 'Hind Siliguri', sans-serif;
            line-height: 1.8;
            color: #333;
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.97);
            border-radius: 10px;
            box-shadow: 0 0 25px rgba(0,0,0,0.1);
        }

        .header {
            text-align: center;
            border-bottom: 3px solid var(--islamic-green);
            padding-bottom: 1rem;
            margin-bottom: 2rem;
        }

        .arabic {
            font-family: 'Lateef', serif;
            font-size: 2.5rem;
            color: var(--islamic-green);
        }

        .couple-container {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin: 3rem 0;
        }

        .groom, .bride {
            width: 250px;
            height: 350px;
            background-size: contain;
            background-repeat: no-repeat;
            animation: float 3s ease-in-out infinite;
        }

        .groom {
            background-image: url('nasim-panjabi.png');
        }

        .bride {
            background-image: url('tania-lehenga.png');
        }

        .bengali-text {
            font-size: 1.2rem;
            text-align: justify;
        }

        .details-box {
            background: #f8f8f8;
            border-radius: 10px;
            padding: 2rem;
            margin: 2rem 0;
            border: 2px solid var(--gold);
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .map-btn {
            background: var(--islamic-green);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s;
            margin: 1rem 0;
        }

        .map-btn:hover {
            background: #1A701A;
            transform: scale(1.05);
        }

        .highlight {
            color: var(--islamic-green);
            font-weight: 600;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="arabic">بِسْمِ ٱللَّٰهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ</div>
            <h1>নাসিম ও তানিয়ার বিবাহের আমন্ত্রণ</h1>
        </div>

        <div class="couple-container">
            <div class="groom"></div>
            <div class="bride"></div>
        </div>

        <div class="details-box">
            <p class="bengali-text">
                আসসালামু আলাইকুম ওয়া রহমাতুল্লাহ,<br><br>
                মহান আল্লাহর রহমতে আপনাকে ও আপনার পরিবারকে সাদর আমন্ত্রণ জানাচ্ছি...
            </p>

            <h2 class="highlight">বিবাহের তারিখ</h2>
            <p class="bengali-text">
                📅 ১৬ই জুন, ২০২৫<br>
                🕒 সন্ধ্যা ৭:৩০টা থেকে<br>
                (২০ই জিলহজ্জ ১৪৪৬ হিজরি)
            </p>

            <h2 class="highlight">স্থান</h2>
            <p class="bengali-text">
                কর্ণাময়ী ম্যারেজ হল<br>
                সিএল-১২৪, সেক্টর-১, কর্ণাময়ী<br>
                কলকাতা - ৭০০০৯১<br>
                পশ্চিমবঙ্গ
            </p>

            <button class="map-btn" onclick="window.open('https://maps.app.goo.gl/EXAMPLE')">
                🗺️ গুগল ম্যাপে অবস্থান দেখুন
            </button>

            <h2 class="highlight">যোগাযোগ</h2>
            <p class="bengali-text">
                নাসিম : +৯১ ৯৮৩১২ ৩৪৫৬৭<br>
                তানিয়া : +৯১ ৯০৭৬৫ ৪৩২১০
            </p>
        </div>

        <div class="arabic" style="text-align: center; margin-top: 2rem;">
            بارك الله لكما وجمع بينكما في خير
        </div>
    </div>
</body>
</html>

