<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>FYSIOMAS</title>
  <meta name="description" content="Krótki opis strony pod Google." />
  <style>
    body{font-family:system-ui,Arial,sans-serif;max-width:820px;margin:40px auto;padding:0 16px;line-height:1.6}
    header{padding:18px 0;border-bottom:1px solid #ddd}
    nav a{margin-right:12px}
    .box{background:#f6f6f6;padding:16px;border-radius:12px}
    footer{margin-top:40px;padding-top:16px;border-top:1px solid #ddd;font-size:14px;color:#555}
    button,a.button{display:inline-block;padding:10px 14px;border-radius:10px;border:1px solid #222;background:#222;color:#fff;text-decoration:none}
  </style>
</head>
<body>
  <header>
    <h1>Twoja Nazwa / Firma</h1>
    <p>Jedno zdanie: co robisz i dla kogo.</p>
    <nav>
      <a href="#oferta">Oferta</a>
      <a href="#cennik">Cennik</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </header>

  <main>
    <section class="box">
      <h2>Najważniejsze</h2>
      <ul>
        <li>Kursy</li>
        <li>Miejsce i dojazd</li>
        <li>Terminy</li>
      </ul>
      <a class="button" href="#kontakt">Umów wizytę</a>
    </section>

    <section id="oferta">
      <h2>Oferta</h2>
      <p>Opisz krótko usługi (2–5 zdań). Możesz dodać listę:</p>
      <ul>
        <li>Usługa 1</li>
        <li>Usługa 2</li>
        <li>Usługa 3</li>
      </ul>
    </section>

    <section id="cennik">
      <h2>Cennik</h2>
      <ul>
        <li>Konsultacja: 150 zł</li>
        <li>Wizyta: 200 zł</li>
        <li>Pakiet 5 wizyt: 900 zł</li>
      </ul>
      <p><small>*Wstaw swoje ceny lub usuń sekcję.</small></p>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>
        📞 Telefon: <a href="tel:+4748632958">+47 486 32 958</a><br>
        ✉️ Email: <a href="mailto:slyngemas@gmail.com">slyngemas@gmail.com</a><br>
        📍 Miejscowość: Gdansk
      </p>
    </section>
  </main>

  <footer>
    © <span id="y"></span> FYSIOMAS. Wszelkie prawa zastrzeżone.
  </footer>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>
