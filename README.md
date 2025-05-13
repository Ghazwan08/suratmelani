<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Surat Buat MELANI PRIATNA 💌</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Open+Sans&display=swap');

    body {
      background: linear-gradient(to right, #0a0f3d, #1b1b2f);
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      height: 100vh;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }

    h1 {
      font-family: 'Pacifico', cursive;
      color: #ff4d4d;
      font-size: 36px;
      margin-bottom: 10px;
    }

    .slide {
      display: none;
      background-color: #ff0000;
      color: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      max-width: 600px;
      line-height: 1.8;
      animation: fadeIn 0.5s ease-in-out;
    }

    .slide.active {
      display: block;
    }

    .buttons {
      margin-top: 20px;
    }

    .buttons button {
      background-color: #8b0000;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      border-radius: 10px;
      margin: 0 10px;
      cursor: pointer;
    }

    .buttons button:hover {
      background-color: #a30000;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .logo {
      margin-top: 20px;
    }

    /* Animasi detak jantung */
    .heartbeat {
      font-size: 50px;
      color: #ff4d4d;
      animation: heartbeat 1.5s ease-in-out infinite;
    }

    @keyframes heartbeat {
      0% {
        transform: scale(1);
      }
      25% {
        transform: scale(1.2);
      }
      50% {
        transform: scale(1);
      }
      75% {
        transform: scale(1.2);
      }
      100% {
        transform: scale(1);
      }
    }
  </style>
</head>
<body>

  <h1>Surat Buat MELANI PRIATNA 💌</h1>

  <!-- Slide 1 -->
  <div class="slide active" id="slide-1">
    <h2>Selamat datang di suratku, Seng!</h2>
    <p>Ini adalah awal dari perjalanan yang akan kita lalui bersama. 💌</p>
  </div>

  <!-- Slide 2 -->
  <div class="slide" id="slide-2">
    <h2>Kenangan pertama kita</h2>
    <p>Waktu pertama kali kita berbicara, aku merasa ada yang spesial dalam percakapan itu. Kamu membuat aku merasa nyaman, dan aku tahu ini bukan sekadar kebetulan. 😊</p>
  </div>

  <!-- Slide 3 -->
  <div class="slide" id="slide-3">
    <h2>Waktu berlalu begitu cepat!</h2>
    <p>Setiap detik yang kita lewati bersama selalu menjadi kenangan yang tak terlupakan. Kamu mengisi hidupku dengan kebahagiaan, dan aku merasa beruntung bisa mengenalmu lebih dekat. 🕰️</p>
  </div>

  <!-- Slide 4 -->
  <div class="slide" id="slide-4">
    <h2>Musik yang menghubungkan kita</h2>
    <p>Setiap lagu yang kita dengar bersama selalu mengingatkanku pada momen indah kita. Semoga kita terus menemukan kenangan manis dalam setiap alunan musik. 🎶</p>
  </div>

  <!-- Slide 5 -->
  <div class="slide" id="slide-5">
    <h2>Hal-hal kecil yang berarti</h2>
    <p>Kadang yang paling sederhana bisa menjadi kenangan terindah. Seperti senyumanmu, atau cara kamu memandang dunia. Itu adalah hal-hal kecil yang selalu aku ingat. ❤️</p>
  </div>

  <!-- Slide 6 -->
  <div class="slide" id="slide-6">
    <h2>Janji kita untuk masa depan</h2>
    <p>Semoga kita bisa terus saling mendukung, berjuang, dan tumbuh bersama. Aku percaya bahwa perjalanan kita baru saja dimulai, dan masih banyak hal indah yang menanti. ✨</p>
  </div>

  <!-- Slide 7 -->
  <div class="slide" id="slide-7">
    <h2>Untuk selalu bersama</h2>
    <p>Tak ada yang lebih aku inginkan selain bisa bersama kamu, melalui setiap langkah hidup ini dengan penuh kebahagiaan. Kamu adalah bagian dari impianku, dan aku akan selalu ada untukmu. 💖</p>
  </div>

  <!-- Navigation Buttons -->
  <div class="buttons">
    <button onclick="prevSlide()">Sebelumnya</button>
    <button onclick="nextSlide()">Selanjutnya</button>
  </div>

  <script>
    let currentSlide = 1;
    const totalSlides = 7;

    function showSlide(n) {
      for (let i = 1; i <= totalSlides; i++) {
        document.getElementById(`slide-${i}`).classList.remove('active');
      }
      document.getElementById(`slide-${n}`).classList.add('active');
    }

    function nextSlide() {
      currentSlide = currentSlide < totalSlides ? currentSlide + 1 : 1;
      showSlide(currentSlide);
    }

    function prevSlide() {
      currentSlide = currentSlide > 1 ? currentSlide - 1 : totalSlides;
      showSlide(currentSlide);
    }
  </script>

</body>
</html>
# suratmelani
