<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نصيم و تانیا کی شادی | Nasim & Tania's Nikaah</title>
    <link href="https://fonts.googleapis.com/css2?family=Amiri&family=Poppins:wght@300;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --islamic-green: #0d5d0d;
            --gold: #d4af37;
        }

        body {
            background: #f7f3e9 url('islamic-pattern.png');
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }

        .header {
            text-align: center;
            border-bottom: 2px solid var(--islamic-green);
            padding-bottom: 1rem;
            margin-bottom: 2rem;
        }

        .arabic {
            font-family: 'Amiri', serif;
            font-size: 2rem;
            color: var(--islamic-green);
        }

        .couple-container {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin: 3rem 0;
        }

        .groom, .bride {
            width: 200px;
            height: 300px;
            background-size: contain;
            background-repeat: no-repeat;
        }

        .groom {
            background-image: url('nasim-kurta.png');
        }

        .bride {
            background-image: url('tania-hijab.png');
        }

        .details {
            text-align: center;
            padding: 2rem;
            background: #f8f8f8;
            border-radius: 10px;
            margin: 2rem 0;
        }

        .quran-verse {
            font-family: 'Amiri', serif;
            font-size: 1.5rem;
            color: var(--islamic-green);
            margin: 2rem 0;
        }

        .map-btn {
            background: var(--islamic-green);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: transform 0.3s;
        }

        .map-btn:hover {
            transform: scale(1.05);
        }

        .event-time {
            color: var(--gold);
            font-weight: 500;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="arabic">بِسْمِ ٱللَّٰهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ</div>
            <h1>نصيم و تانیا کی شادی</h1>
        </div>

        <div class="quran-verse">
            "وَمِنْ آيَاتِهِ أَنْ خَلَقَ لَكُم مِّنْ أَنفُسِكُمْ أَزْوَاجًا لِّتَسْكُنُوا إِلَيْهَا..."
            <br>(سورة الروم 21)
        </div>

        <div class="couple-container">
            <div class="groom"></div>
            <div class="bride"></div>
        </div>

        <div class="details">
            <h2>نصيم আহমেদ & تانیا بیگم</h2>
            <p>آپ کو اور آپ کے خاندان کو ہماری شادی میں شرکت کی دعوت دیتے ہیں</p>
            
            <h3>نکاح کی تقریب</h3>
            <p class="event-time">🗓 12th Rabi' al-Awwal 1446 AH<br>
            📅 12th November 2024<br>
            ⏰ 7:30 PM Onwards</p>

            <h3>وینو</h3>
            <p>کرونامئی کانفرنس ہال<br>
            کارونامئی، کولکاتا - 700091<br>
            مغربی بنگال، بھارت</p>

            <button class="map-btn" onclick="window.open('https://maps.app.goo.gl/EXAMPLELINK')">
                📍 Get Directions
            </button>
        </div>

        <div class="quran-verse">
            "بارك الله لكما وجمع بينكما في خير"
            <br>(اللہ تم دونوں کو برکت دے اور تمہیں اچھائی میں جمع کرے)
        </div>
    </div>
</body>
</html>
