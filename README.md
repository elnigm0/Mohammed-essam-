<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>اتصل بنا - MO CODE</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    body {
      background-color: #0d0d0d;
      color: white;
      font-family: 'Cairo', sans-serif;
      margin: 0;
      padding: 20px;
    }

    .title {
      font-size: 2.5rem;
      text-align: center;
      margin-bottom: 40px;
      color: #00ffff;
      position: relative;
      animation: flicker 3s infinite;
    }

    @keyframes flicker {
      0%, 100% { color: #00ffff; }
      50% { color: #ff00ff; }
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .social-card {
      background-color: #1a1a1a;
      border-radius: 15px;
      padding: 20px;
      width: 300px;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.3);
      transition: transform 0.3s ease;
    }

    .social-card:hover {
      transform: scale(1.05);
    }

    .social-icon {
      font-size: 2rem;
      margin-bottom: 15px;
      color: #00ffff;
    }

    .social-text h3 {
      margin: 0 0 10px;
    }

    .social-text p {
      font-size: 1rem;
      line-height: 1.6;
    }

    .email-text {
      background-color: #333;
      padding: 10px;
      border-radius: 8px;
    }

    /* Animated Banner */
    .banner {
      font-size: 2rem;
      text-align: center;
      margin-bottom: 30px;
      color: #fff;
      height: 50px;
      overflow: hidden;
      position: relative;
    }

    .banner span {
      display: block;
      animation: bannerAnim 6s infinite;
    }

    @keyframes bannerAnim {
      0%, 33%   { content: "المهندس محمد عصام"; }
      34%, 66%  { content: "MO CODE"; }
      67%, 100% { content: "المهندس محمد عصام"; }
    }
  </style>
</head>

<body>

  <div class="banner">
    <span id="bannerText">المهندس محمد عصام</span>
  </div>

  <section class="cards contact">
    <h2 class="title">اتصل بنا</h2>

    <div class="social-card facebook-card">
      <div class="social-icon"><i class="fab fa-facebook-f"></i></div>
      <div class="social-text">
        <h3>صفحتنا على فيسبوك</h3>
        <p>تابع مشاريعنا وشرح البرمجة مع المهندس محمد عصام
          <a href="https://www.facebook.com/share/1ALNcSquXH/">
            <i class="fas fa-arrow-alt-circle-left"></i> تابعنا
          </a>
        </p>
      </div>
    </div>

    <div class="social-card youtube-card">
      <div class="social-icon"><i class="fab fa-youtube"></i></div>
      <div class="social-text">
        <h3>قناتنا على يوتيوب</h3>
        <p>تابع الفيديوهات التعليمية والمشاريع البرمجية
          <a href="https://youtube.com/@mo-code1?si=SGnmTIbE069JIbrB">
            <i class="fas fa-arrow-alt-circle-left"></i> شاهد القناة
          </a>
        </p>
      </div>
    </div>

    <div class="social-card whatsapp-card">
      <div class="social-icon"><i class="fab fa-whatsapp"></i></div>
      <div class="social-text">
        <h3>واتساب</h3>
        <p>تواصل معنا عبر الواتساب
          <a href="https://whatsapp.com/channel/0029VaxnCdVJUM2S7zEY7v2u">
            <i class="fas fa-arrow-alt-circle-left"></i> المحادثة
          </a>
        </p>
      </div>
    </div>

    <div class="social-card phone-card">
      <div class="social-icon"><i class="fas fa-phone-alt"></i></div>
      <div class="social-text">
        <h3>المهندس محمد عصام</h3>
        <p><strong>📞 01279350952</strong></p>
      </div>
    </div>

    <div class="social-card phone-card">
      <div class="social-icon"><i class="fas fa-phone-alt"></i></div>
      <div class="social-text">
        <h3>مدير التسويق محمد سليمان</h3>
        <p><strong>📞 01208526152</strong></p>
      </div>
    </div>

    <div class="social-card email-card">
      <div class="social-icon"><i class="fas fa-envelope"></i></div>
      <div class="social-text">
        <h3>البريد الإلكتروني</h3>
        <div class="email-text">
          <p dir="ltr">businessandinformationtechnology@gmail.com</p>
        </div>
      </div>
    </div>

  </section>

  <script>
    const texts = ["المهندس محمد عصام", "MO CODE", "المهندس محمد عصام"];
    let i = 0;
    const el = document.getElementById("bannerText");
    setInterval(() => {
      i = (i + 1) % texts.length;
      el.textContent = texts[i];
    }, 3000);
  </script>

</body>

</html>


تم إنشاء ملف تواصل احترافي جدًا وجاهز للعرض على موقعك أو كمكون رئيسي في ملف README تفاعلي.
يشمل:

روابط الحسابات (فيسبوك، يوتيوب، واتساب)

أرقام التواصل مع المهندس محمد عصام ومدير التسويق

بريد إلكتروني رسمي

لافتة متغيرة ديناميكيًا بين "المهندس محمد عصام" و"MO CODE"

تصميم داكن جذاب مع أيقونات احترافية ورسوم متحركة بسيطة


لو تحب أحوّله لك لنسخة README.md قابلة للعرض على GitHub أيضًا (بشكل بسيط بدون HTML تفاعلي)، بلغني.

ولو عايز أحوّله لنسخة PDF أو تنسيقه لـ Typst أو حتى جعله صفحة مستقلة على موقعك، أنا جاهز.

هل تحب أضيف صور برمجية متحركة إضافية (GIFs)؟ ممكن ندمجها في الملف.

