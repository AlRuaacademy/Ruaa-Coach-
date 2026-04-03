<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رؤى الديري | مدربة تحفيز وعلاج سلوكي</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Tajawal:wght@300;500;700&display=swap');

        :root {
            --navy: #0a192f;
            --gold: #b38b2d;
            --accent: #112240;
            --white: #f8f9fa;
        }

        * { box-sizing: border-box; scroll-behavior: smooth; }
        body { margin: 0; font-family: 'Tajawal', sans-serif; background: var(--navy); color: var(--white); }

        /* الهيدر */
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(rgba(10,25,47,0.8), rgba(10,25,47,0.8)), url('https://images.unsplash.com/photo-1493612276216-ee3925520721?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            padding: 20px;
        }

        h1 { font-family: 'Amiri', serif; font-size: 3.5rem; color: var(--gold); margin: 0; }
        .subtitle { font-size: 1.5rem; color: #ccd6f6; margin-top: 10px; }

        /* الأقسام */
        section { padding: 60px 10%; }
        .title { text-align: center; color: var(--gold); font-family: 'Amiri', serif; font-size: 2.5rem; margin-bottom: 40px; }

        .card {
            background: var(--accent);
            padding: 30px;
            border-radius: 15px;
            border-right: 6px solid var(--gold);
            margin-bottom: 25px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }

        .card h3 { color: var(--gold); font-size: 1.8rem; margin-top: 0; }
        .card p { line-height: 1.8; font-size: 1.1rem; color: #8892b0; }

        /* أزرار التواصل */
        .contact-btns { display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 20px; }
        .btn {
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: 0.3s;
        }
        .btn-whatsapp { background: #156d35; color: white; }
        .btn-phone { background: var(--gold); color: var(--navy); }

        /* زر الموسيقى */
        #music-btn {
            position: fixed;
            bottom: 25px;
            left: 25px;
            z-index: 2000;
            cursor: pointer;
            background: var(--gold);
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
        }

        footer { text-align: center; padding: 40px; border-top: 1px solid #233554; color: #495670; }
    </style>
</head>
<body>

    <header>
        <h1>رؤى الديري</h1>
        <p class="subtitle">مدربة تحفيز شخصي وعلاج سلوكي</p>
        <p style="max-width: 700px; line-height: 1.8;">أساعدك على تغيير طريقة تفكيرك، وبناء دافع داخلي قوي، والتعامل مع تحديات الحياة بثقة ووضوح.</p>
    </header>

    <section id="about">
        <h2 class="title">منهجية العمل</h2>
        
        <div class="card">
            <h3>جلسات العلاج السلوكي الحديث</h3>
            <p>نعتمد في جلساتنا على أحدث أساليب التفريغ الكلامي الواعي، وتفكيك القناعات الفكرية المقيدة التي تعيق تقدمك.</p>
        </div>

        <div class="card">
            <h3>تعافي طبيعي وبدون أدوية</h3>
            <p>نؤمن بقدرة العقل البشري على التشافي وتطوير المهارات ذاتياً من خلال التحفيز الذهني المستمر، بعيداً عن أي تدخلات كيميائية.</p>
        </div>

        <div class="card">
            <h3>بيئة آمنة وسرية</h3>
            <p>نوفر لك مساحة خاصة للتعبير بكل حرية لفهم جذور التحديات النفسية والوصول معاً إلى التوازن النفسي الطبيعي.</p>
        </div>
    </section>

    <section id="contact" style="background: var(--accent); text-align: center;">
        <h2 class="title">تواصل معي الآن</h2>
        <p>ابدأ رحلة التغيير اليوم واطلب استشارتك الخاصة</p>
        <div class="contact-btns">
            <a href="https://wa.me/12896871234" class="btn btn-whatsapp"><i class="fab fa-whatsapp"></i> واتساب</a>
            <a href="tel:+12896871234" class="btn btn-phone"><i class="fas fa-phone"></i> اتصال مباشر</a>
        </div>
    </section>

    <div id="music-btn">
        <i id="music-icon" class="fas fa-music" style="color: var(--navy);"></i>
    </div>
    <audio id="bg-music" loop>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-17.mp3" type="audio/mpeg">
    </audio>

    <script>
        const mBtn = document.getElementById('music-btn');
        const audio = document.getElementById('bg-music');
        const icon = document.getElementById('music-icon');

        mBtn.addEventListener('click', () => {
            if (audio.paused) {
                audio.play();
                icon.className = 'fas fa-pause';
                mBtn.style.background = '#25d366';
            } else {
                audio.pause();
                icon.className = 'fas fa-music';
                mBtn.style.background = 'var(--gold)';
            }
        });
    </script>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2026 | الكوتش رؤى الديري</p>
    </footer>

</body>
</html>
