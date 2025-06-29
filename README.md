
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Undangan Pernikahan Qoribun & Nurul</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&family=Parisienne&display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #fffafc;
      color: #4a3b47;
      scroll-behavior: smooth;
    }
    h1, h2, h3 {
      font-family: 'Great Vibes', cursive;
      color: #b76e79;
    }
    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100vh;
      background: linear-gradient(to bottom right, #fbe9f2, #fff0f6);
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    .hero-content {
      animation: fadeOutUp 6s ease-in forwards;
    }
    @keyframes fadeOutUp {
      0% { opacity: 0; transform: translateY(30px); }
      30% { opacity: 1; transform: translateY(0); }
      80% { opacity: 1; }
      100% { opacity: 0; transform: translateY(-30px); }
    }
    .hero h1 {
      font-size: 4rem;
    }
    .hero p {
      font-size: 1.5rem;
    }
    .hero img {
      width: 180px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 4px solid #fff;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    }
    .hero button {
      margin-top: 30px;
      padding: 12px 28px;
      font-size: 1rem;
      background: #b76e79;
      color: #fff;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .hero button:hover {
      background: #a65e6d;
    }
    #mainContent {
      display: none;
    }
    .countdown {
      font-size: 1.2rem;
      background: #ffeef4;
      padding: 10px;
      border-radius: 8px;
      margin-top: 20px;
      color: #b76e79;
    }
    .flower {
      position: fixed;
      top: -50px;
      width: 30px;
      height: 30px;
      background: url('https://cdn-icons-png.flaticon.com/512/616/616408.png') no-repeat center/contain;
      animation: fall linear infinite;
      opacity: 0.8;
      z-index: 9999;
    }
    @keyframes fall {
      0% { transform: translateY(-50px); }
      100% { transform: translateY(110vh); }
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .mempelai h2 {
      font-family: 'Parisienne', cursive;
      font-size: 3rem;
      color: #c96a85;
    }
    .mempelai img {
      width: 150px;
      border-radius: 50%;
      margin: 10px;
      border: 4px solid #fff;
    }
    .slider {
      width: 100%;
      max-width: 800px;
      margin: 0 auto;
      overflow: hidden;
      border-radius: 16px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.2);
    }
    .slides {
      display: flex;
      width: 400%;
      animation: slide 20s infinite;
    }
    .slides img {
      width: 100%;
      height: auto;
    }
    @keyframes slide {
      0% { transform: translateX(0); }
      25% { transform: translateX(0); }
      30% { transform: translateX(-100%); }
      50% { transform: translateX(-100%); }
      55% { transform: translateX(-200%); }
      75% { transform: translateX(-200%); }
      80% { transform: translateX(-300%); }
      100% { transform: translateX(-300%); }
    }
    .mapouter { position:relative;text-align:right;height:400px;width:100%; }
    .gmap_canvas { overflow:hidden;background:none!important;height:400px;width:100%; }
    .btn {
      padding: 10px 20px;
      background: #b76e79;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
  </style>
</head>
<body>
<audio autoplay loop hidden>
  <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mpeg">
</audio>
<div class="hero" id="hero">
  <div class="hero-content">
    <img src="qoribun&lathifah/mempelai.jpg" alt="mempelai">
    <h1>Qoribun & Nurul</h1>
    <p>5 Agustus 2025</p>
    <p>Dengan segala hormat, kami mengundang Anda</p>
    <div class="countdown" id="countdown"></div>
    <button onclick="showMainContent()">Lihat Undangan</button>
  </div>
</div>
<div id="mainContent">
  <section class="section mempelai">
    <h2>Qoribun & Nurul Lathifah</h2>
    <img src="qoribun&lathifah/qoribun.jpg" alt="qoribun">
    <p>Putra ke-5 dari Bapak Hasanuddin & Ibu Siti Alimah</p>
    <img src="qoribun&lathifah/nurul.jpg" alt="nurul">
    <p>Putri pertama dari Bapak Ma'an Priyadi (Alm) & Ibu Tokhanah</p>
  </section>
  <section class="section">
    <h2>Ayat Al-Qur'an</h2>
    <p>"Dan di antara tanda-tanda kekuasaan-Nya ialah Dia menciptakan untukmu pasangan hidup dari jenismu sendiri supaya kamu merasa tentram di sampingnya dan dijadikan-Nya rasa kasih dan sayang di antara kamu. Sungguh, pada yang demikian itu benar-benar terdapat tanda-tanda bagi kaum yang berpikir."</p>
    <p><em>(QS. Ar-Rum: 21)</em></p>
  </section>
  <section class="section">
    <h2>Jadwal Akad</h2>
    <p>Selasa, 5 Agustus 2025</p>
    <p>Jam 09.00 WIB</p>
    <p>Tempat: Kediaman Mempelai Wanita</p>
  </section>
  <section class="section">
    <h2>Love Story</h2>
    <p>Kami pertama kali bertemu di bangku kuliah. Waktu berlalu dan rasa tumbuh. Kini kami siap mengikat janji suci dalam pernikahan. Terima kasih telah menjadi bagian dari cerita kami.</p>
  </section>
  <section class="section">
    <h2>Galeri</h2>
    <div class="slider">
      <div class="slides">
        <img src="undangan/mempelai.jpg" alt="mempelai">
        <img src="https://source.unsplash.com/800x500/?wedding-ring" alt="Galeri 2">
        <img src="https://source.unsplash.com/800x500/?wedding-flowers" alt="Galeri 3">
        <img src="https://source.unsplash.com/800x500/?wedding-decor" alt="Galeri 4">
      </div>
    </div>
  </section>
  <section class="section">
    <h2>Lokasi Akad</h2>
    <div class="mapouter">
      <div class="gmap_canvas">
        <iframe width="100%" height="400" id="gmap_canvas" src="https://maps.google.com/maps?q=purworejo&t=&z=15&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no"></iframe>
      </div>
    </div>
  </section>
  <section class="section">
    <h2>Konfirmasi Kehadiran</h2>
    <button class="btn" onclick="confirmRSVP()">RSVP Sekarang</button>
  </section>
  <section class="section">
    <h2>Bagikan Undangan</h2>
    <a class="btn" href="https://wa.me/?text=Hai%2C%20Saya%20mengundang%20Anda%20ke%20acara%20pernikahan%20kami%20pada%205%20Agustus%202025%20%0A%0Ahttps%3A%2F%2Fcontoh-link-undangan.com" target="_blank">Bagikan via WhatsApp</a>
  </section>
</div>
<footer class="section">
  <p>Terima kasih atas doa dan restunya</p>
  <p>Qoribun & Nurul Lathifah</p>
</footer>
<script>
  function showMainContent() {
    document.getElementById("hero").style.display = "none";
    document.getElementById("mainContent").style.display = "block";
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
  function confirmRSVP() {
    Swal.fire({
      title: 'RSVP Anda diterima!',
      text: 'Terima kasih telah mengkonfirmasi kehadiran Anda.',
      icon: 'success',
      confirmButtonText: 'OK'
    });
  }
  const countDownDate = new Date("August 5, 2025 09:00:00").getTime();
  const countdown = document.getElementById("countdown");
  setInterval(() => {
    const now = new Date().getTime();
    const distance = countDownDate - now;
    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);
    countdown.innerHTML = `Menuju Hari Bahagia: ${days} Hari ${hours} Jam ${minutes} Menit ${seconds} Detik`;
  }, 1000);
  function createFlower() {
    const flower = document.createElement("div");
    flower.classList.add("flower");
    flower.style.left = Math.random() * 100 + "vw";
    flower.style.animationDuration = 4 + Math.random() * 6 + "s";
    document.body.appendChild(flower);
    setTimeout(() => flower.remove(), 10000);
  }
  setInterval(createFlower, 500);
</script>
</body>
</html>
