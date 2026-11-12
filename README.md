
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Baytul Hikmah - ইসলামি জ্ঞান, কুরআন, হাদিস, ইতিহাস ও গবেষণার ডিজিটাল পাঠাগার।">
  <title>Baytul Hikmah | بيت الحكمة</title>

  <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;500;600;700&family=Amiri:wght@400;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --green: #075b42;
      --dark: #064632;
      --gold: #c69b45;
      --cream: #f8f7f0;
      --white: #ffffff;
      --text: #26352e;
    }

    body {
      font-family: 'Hind Siliguri', sans-serif;
      background: var(--cream);
      color: var(--text);
      line-height: 1.7;
    }

    header {
      background: var(--white);
      padding: 15px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 12px #0000000c;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .logo {
      color: var(--green);
      font-size: 25px;
      font-weight: 700;
    }

    .logo span {
      color: var(--gold);
    }

    nav {
      display: flex;
      gap: 22px;
    }

    nav a {
      text-decoration: none;
      color: var(--text);
      font-weight: 600;
    }

    nav a:hover {
      color: var(--gold);
    }

    .hero {
      background: linear-gradient(130deg, #064632, #0b7655);
      color: white;
      text-align: center;
      padding: 85px 20px;
    }

    .arabic {
      font-family: 'Amiri', serif;
      font-size: 48px;
      color: #e6c477;
      margin-bottom: 8px;
    }

    .hero h1 {
      font-size: 38px;
      margin-bottom: 12px;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      font-size: 17px;
      color: #e5eee9;
    }

    .hero-btn {
      display: inline-block;
      margin-top: 28px;
      padding: 12px 30px;
      background: var(--gold);
      color: #172d23;
      text-decoration: none;
      border-radius: 6px;
      font-weight: 700;
    }

    .section {
      padding: 65px 7%;
      text-align: center;
    }

    .section-title {
      color: var(--green);
      font-size: 30px;
      margin-bottom: 8px;
    }

    .section-subtitle {
      color: #68756d;
      margin-bottom: 35px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 22px;
    }

    .card {
      background: white;
      padding: 30px 20px;
      border-radius: 12px;
      border: 1px solid #eee8d8;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px #00000012;
    }

    .card .icon {
      font-size: 38px;
      margin-bottom: 12px;
    }

    .card h3 {
      color: var(--green);
      font-size: 21px;
      margin-bottom: 8px;
    }

    .card p {
      color: #68756d;
      font-size: 14px;
    }

    .about {
      background: #eef3ed;
      padding: 55px 8%;
      text-align: center;
    }

    .about h2 {
      color: var(--green);
      margin-bottom: 15px;
      font-size: 28px;
    }

    .about p {
      max-width: 750px;
      margin: auto;
    }

    footer {
      background: #063e2e;
      color: white;
      text-align: center;
      padding: 30px 15px;
    }

    footer strong {
      color: #e6c477;
    }

    @media (max-width: 650px) {
      header {
        flex-direction: column;
        gap: 10px;
      }

      nav {
        gap: 13px;
        flex-wrap: wrap;
        justify-content: center;
        font-size: 13px;
      }

      .hero {
        padding: 65px 18px;
      }

      .hero h1 {
        font-size: 29px;
      }

      .arabic {
        font-size: 40px;
      }

      .section {
        padding: 48px 5%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">Baytul <span>Hikmah</span></div>

    <nav>
      <a href="#home">হোম</a>
      <a href="#library">গ্রন্থাগার</a>
      <a href="#about">আমাদের সম্পর্কে</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="arabic">بيت الحكمة</div>
    <h1>বাইতুল হিকমাহ</h1>
    <p>
      কুরআন, হাদিস, ইসলামি ইতিহাস, গবেষণা ও
      জ্ঞানচর্চার এক সমৃদ্ধ ডিজিটাল পাঠাগার।
    </p>
    <a href="#library" class="hero-btn">জ্ঞানভান্ডারে প্রবেশ করুন</a>
  </section>

  <section class="section" id="library">
    <h2 class="section-title">আমাদের জ্ঞানভান্ডার</h2>
    <p class="section-subtitle">
      জ্ঞান অন্বেষণের জন্য প্রবেশ করুন আপনার পছন্দের বিভাগে।
    </p>

    <div class="cards">

      <div class="card">
        <div class="icon">📖</div>
        <h3>আল-কুরআন</h3>
        <p>পবিত্র কুরআন, সূরা, অনুবাদ ও তাফসির।</p>
      </div>

      <div class="card">
        <div class="icon">📚</div>
        <h3>হাদিস</h3>
        <p>হাদিসের সংকলন, ব্যাখ্যা ও উসুলে হাদিস।</p>
      </div>

      <div class="card">
        <div class="icon">🕌</div>
        <h3>ইসলামি ইতিহাস</h3>
        <p>নবী-রাসুল, সাহাবি ও মুসলিম সভ্যতার ইতিহাস।</p>
      </div>

      <div class="card">
        <div class="icon">📜</div>
        <h3>ইসলামি বই</h3>
        <p>বিভিন্ন বিষয়ের বই ও PDF সংগ্রহ।</p>
      </div>

      <div class="card">
        <div class="icon">✍️</div>
        <h3>প্রবন্ধ ও গবেষণা</h3>
        <p>ইসলামি চিন্তা, বিশ্লেষণ ও গবেষণামূলক লেখা।</p>
      </div>

      <div class="card">
        <div class="icon">🌙</div>
        <h3>ইসলামি জ্ঞান</h3>
        <p>আকিদা, ফিকহ, সিরাত ও অন্যান্য বিষয়।</p>
      </div>

    </div>
  </section>

  <section class="about" id="about">
    <h2>বাইতুল হিকমাহ সম্পর্কে</h2>
    <p>
      বাইতুল হিকমাহ একটি ইসলামি ডিজিটাল জ্ঞানভান্ডার।
      আমাদের লক্ষ্য হলো ইসলামি জ্ঞান, ঐতিহ্য,
      গবেষণা ও পাঠ্যসামগ্রীকে সবার কাছে সহজে পৌঁছে দেওয়া।
    </p>
  </section>

  <footer>
    <strong>Baytul Hikmah | بيت الحكمة</strong>
    <p>জ্ঞান হোক আলোর পথ</p>
    <p>© 2026 Baytul Hikmah. All Rights Reserved.</p>
  </footer>

</body>
</html>
