<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Moja Strona</title>

  <!-- Google AdSense -->
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6205274330180483"
     crossorigin="anonymous"></script>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }
    header {
      background: #111;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
      background: white;
    }
    .ad {
      margin: 20px 0;
      text-align: center;
    }
    footer {
      margin-top: 30px;
      padding: 20px;
      background: #222;
      color: #ccc;
      font-size: 14px;
      text-align: center;
    }
    /* Baner cookies */
    #cookie-banner {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background: #333;
      color: white;
      padding: 15px;
      text-align: center;
      z-index: 1000;
      display: none;
    }
    #cookie-banner button {
      background: #4CAF50;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-left: 10px;
      cursor: pointer;
      font-weight: bold;
    }
  </style>
</head>
<body>

<header>
  <h1>Moja Strona</h1>
</header>

<nav>
  <a href="#home">Strona główna</a>
  <a href="#about">O nas</a>
  <a href="#contact">Kontakt</a>
  <a href="#privacy">Polityka prywatności</a>
</nav>

<main id="home">
  <h2>Witaj!</h2>
  <p>To jest moja strona z reklamami Google AdSense. Wszystkie reklamy są legalne i zgodne z zasadami Google.</p>

  <!-- REKLAMA 1 -->
  <div class="ad">
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-6205274330180483"
         data-ad-slot="8463707392"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </div>

  <p>Dodaj tutaj treści, artykuły lub newsy, żeby strona wyglądała profesjonalnie i była akceptowana przez AdSense.</p>

  <!-- REKLAMA 2 -->
  <div class="ad">
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-6205274330180483"
         data-ad-slot="8463707392"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </div>
</main>

<section id="about">
  <h2>O nas</h2>
  <p>Jesteśmy twórcami tej strony, oferującymi wartościowe treści i legalne reklamy AdSense. Naszym celem jest dostarczać informacje i rozrywkę w przyjaznej formie.</p>
</section>

<section id="contact">
  <h2>Kontakt</h2>
  <p>Masz pytania? Napisz do nas:</p>
  <p>Email: kontakt@mojastrona.pl</p>
  <p>Telefon: +48 123 456 789</p>
</section>

<section id="privacy">
  <h2>Polityka prywatności</h2>
  <p>Ta strona korzysta z usług reklamowych Google AdSense. Google może używać plików cookies do personalizacji reklam oraz analizy ruchu. AdSense może gromadzić informacje o użytkownikach, w tym adres IP, aby wyświetlać odpowiednie reklamy.</p>

  <p>Korzystając z tej strony, wyrażasz zgodę na przetwarzanie danych zgodnie z naszą polityką prywatności oraz regulacjami prawnymi (w tym GDPR).</p>

  <p>Więcej informacji o polityce prywatności Google znajdziesz na stronie <a href="https://policies.google.com/privacy" target="_blank">Google Privacy Policy</a>.</p>
</section>

<footer>
  © 2026 Moja Strona
</footer>

<!-- BANER COOKIES -->
<div id="cookie-banner">
  Ta strona używa plików cookies w celach reklamowych i analitycznych.  
  <button id="accept-cookies">Akceptuję</button>
</div>

<script>
  // Pokazanie banera jeśli nie zaakceptowano
  if (!localStorage.getItem('cookiesAccepted')) {
    document.getElementById('cookie-banner').style.display = 'block';
  }

  document.getElementById('accept-cookies').onclick = function() {
    localStorage.setItem('cookiesAccepted', 'true');
    document.getElementById('cookie-banner').style.display = 'none';
  };
</script>

</body>
</html>
