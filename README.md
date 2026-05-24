# VisualAudioServices
Prototype - Website
<!DOCTYPE html>
<html>
<head>
  <title>Visual Audio - Music & AV Services</title>
  <style>
    body {
      background: #000033;
      color: #ffffff;
      font-family: Verdana, Arial, sans-serif;
      margin: 0;
      text-align: center;
    }

    .page {
      width: 900px;
      margin: auto;
      background: #000000;
      border: 4px ridge #00ccff;
    }

    .header {
      background: linear-gradient(#333399, #000000);
      padding: 30px;
      border-bottom: 3px solid #00ccff;
    }

    .logo {
      font-size: 48px;
      color: #00ffff;
      text-shadow: 3px 3px #ff00ff;
      letter-spacing: 3px;
    }

    .tagline {
      color: #ffff00;
      font-size: 18px;
      margin-top: 10px;
    }

    .nav {
      background: #111111;
      padding: 12px;
      border-bottom: 2px solid #666666;
    }

    .nav a {
      color: #ffffff;
      background: linear-gradient(#666666, #222222);
      padding: 8px 16px;
      margin: 4px;
      border: 2px outset #aaaaaa;
      text-decoration: none;
      font-weight: bold;
    }

    .nav a:hover {
      color: #00ffff;
      border: 2px inset #aaaaaa;
    }

    .marquee {
      background: #ff00ff;
      color: #ffffff;
      padding: 8px;
      font-weight: bold;
    }

    .section {
      margin: 20px;
      padding: 20px;
      background: #111144;
      border: 3px groove #00ccff;
    }

    h2 {
      color: #00ffff;
      text-shadow: 2px 2px #ff00ff;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 15px;
    }

    .box {
      background: #000000;
      border: 2px solid #ffff00;
      padding: 15px;
      color: #ffffff;
    }

    .button {
      display: inline-block;
      margin-top: 20px;
      background: linear-gradient(#ff00ff, #660066);
      color: white;
      padding: 12px 25px;
      border: 3px outset #ff99ff;
      text-decoration: none;
      font-weight: bold;
    }

    .button:hover {
      border: 3px inset #ff99ff;
    }

    .footer {
      background: #000000;
      color: #999999;
      padding: 15px;
      font-size: 12px;
      border-top: 2px solid #00ccff;
    }

    input, textarea {
      width: 80%;
      padding: 8px;
      margin: 8px;
      background: #000000;
      color: #00ffff;
      border: 2px solid #00ccff;
    }
  </style>
</head>

<body>

  <div class="page">

    <div class="header">
      <div class="logo">VISUAL AUDIO</div>
      <div class="tagline">Sound • Lighting • Vision • Events</div>
    </div>

    <div class="nav">
      <a href="#home">ENTER SITE</a>
      <a href="#services">SERVICES</a>
      <a href="#gear">GEAR</a>
      <a href="#contact">CONTACT</a>
    </div>

    <div class="marquee">
      <marquee>*** LIVE SOUND • LIGHTING • AV HIRE • MUSIC PRODUCTION • EVENT SUPPORT ***</marquee>
    </div>

    <div class="section" id="home">
      <h2>Welcome to Visual Audio</h2>
      <p>
        We bring venue-shaking sound and eye-burning visuals to gigs,
        parties, festivals, corporate events and weird little warehouse shows.
      </p>
      <a class="button" href="#contact">BOOK NOW</a>
    </div>

    <div class="section" id="services">
      <h2>Our Services</h2>

      <div class="services">
        <div class="box">
          <h3>Live Sound</h3>
          <p>PA systems, mixing, stage setup and event audio.</p>
        </div>

        <div class="box">
          <h3>Lighting</h3>
          <p>Party lights, stage lighting and visual atmosphere.</p>
        </div>

        <div class="box">
          <h3>AV Hire</h3>
          <p>Speakers, mixers, mics, projectors and event gear.</p>
        </div>

        <div class="box">
          <h3>Music Production</h3>
          <p>Recording, mixing, editing and creative audio work.</p>
        </div>

        <div class="box">
          <h3>Corporate Events</h3>
          <p>Clean, reliable AV for meetings and presentations.</p>
        </div>

        <div class="box">
          <h3>Festivals</h3>
          <p>Sound and lighting support for outdoor events.</p>
        </div>
      </div>
    </div>

    <div class="section" id="gear">
      <h2>Powered By Serious Gear</h2>
      <p>
        Mixers • Speakers • Wireless Mics • IEMs • Lighting Fixtures • Cables • Stands
      </p>
      <p>
        Everything needed to make your event look loud and sound bright.
      </p>
    </div>

    <div class="section" id="contact">
      <h2>Contact The Crew</h2>

      <form>
        <input type="text" placeholder="Your Name"><br>
        <input type="email" placeholder="Email Address"><br>
        <input type="text" placeholder="Event Date / Venue"><br>
        <textarea rows="6" placeholder="Tell us about your event"></textarea><br>
        <a class="button" href="mailto:youremail@example.com">SEND MESSAGE</a>
      </form>
    </div>

    <div class="footer">
      Best viewed at 1024x768<br>
      © 2004–2026 Visual Audio<br>
      Website powered by sound waves, caffeine and dodgy cables.
    </div>

  </div>

</body>
</html>