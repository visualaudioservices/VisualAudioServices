<!DOCTYPE html>
<html>
<head>
  <title>Visual Audio Services</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: #020008;
      color: white;
      font-family: 'Press Start 2P', monospace;
      font-size: 11px;
      line-height: 1.8;
      text-transform: uppercase;
      background-image:
        linear-gradient(rgba(0,255,255,0.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0,255,255,0.04) 1px, transparent 1px);
      background-size: 20px 20px;
    }

    .site {
      max-width: 1180px;
      margin: 20px auto;
      padding: 22px;
      border: 4px solid #00eaff;
      box-shadow: 0 0 25px #00eaff;
      background: #050008;
    }

    .top {
      text-align: center;
      border-bottom: 3px solid #ff3bd4;
      padding-bottom: 20px;
    }

    h1 {
      color: #00eaff;
      font-size: 48px;
      text-shadow: 4px 4px #ff3bd4;
      margin: 10px 0;
      line-height: 1.2;
    }

    .subtitle {
      color: #fff200;
    }

    .nav {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
      margin: 20px 0;
    }

    .nav a {
      color: #00eaff;
      border: 3px solid #00eaff;
      padding: 18px;
      text-decoration: none;
      text-align: center;
      background: #070019;
      box-shadow: inset 0 0 15px #001f33;
    }

    .nav a:hover {
      color: #ff3bd4;
      border-color: #ff3bd4;
    }

    .ticker {
      border: 3px solid #ff3bd4;
      color: #fff200;
      padding: 8px;
      margin-bottom: 18px;
      overflow: hidden;
      white-space: nowrap;
    }

    .ticker span {
      display: inline-block;
      animation: scroll 14s linear infinite;
    }

    @keyframes scroll {
      from { transform: translateX(100%); }
      to { transform: translateX(-100%); }
    }

    .hero {
      display: grid;
      grid-template-columns: 1fr 2fr;
      gap: 20px;
      border: 3px solid #7b2cff;
      padding: 25px;
      margin-bottom: 25px;
      background: radial-gradient(circle, #130033, #020008);
    }

    h2 {
      color: #00eaff;
      text-shadow: 2px 2px #7b2cff;
      font-size: 22px;
    }

    .stage {
      border: 2px solid #7b2cff;
      min-height: 230px;
      display: flex;
      align-items: end;
      justify-content: center;
      background:
        radial-gradient(circle at 30% 20%, #ff3bd4 0 3%, transparent 15%),
        radial-gradient(circle at 70% 20%, #00eaff 0 3%, transparent 15%),
        linear-gradient(#080010, #000);
      position: relative;
      overflow: hidden;
    }

    .stage::before {
      content: "♫";
      position: absolute;
      font-size: 90px;
      color: #ff3bd4;
      top: 35px;
      left: 45%;
      text-shadow: 0 0 20px #ff3bd4;
    }

    .crowd {
      width: 100%;
      height: 70px;
      background: repeating-linear-gradient(
        90deg,
        #000 0 12px,
        #7b2cff 12px 18px,
        #000 18px 28px
      );
      clip-path: polygon(0 60%, 100% 30%, 100% 100%, 0% 100%);
    }

    .button {
      display: inline-block;
      color: #ff3bd4;
      border: 3px solid #ff3bd4;
      padding: 12px 18px;
      text-decoration: none;
      margin-top: 12px;
      background: #120020;
      box-shadow: 4px 4px #7b2cff;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }

    .card {
      border: 3px solid #00eaff;
      padding: 18px;
      background: #030014;
      min-height: 150px;
    }

    .icon {
      font-size: 36px;
      color: #fff200;
      margin-bottom: 10px;
    }

    h3 {
      color: #ff3bd4;
      margin-top: 0;
      font-size: 13px;
    }

    .gear {
      text-align: center;
      border-top: 3px solid #fff200;
      border-bottom: 3px solid #fff200;
      padding: 20px;
      margin: 25px 0;
      color: #fff200;
    }

    .gear-list {
      color: white;
      margin-top: 10px;
    }

    .contact {
      border: 3px solid #ff3bd4;
      padding: 20px;
      display: grid;
      grid-template-columns: 1fr 2fr;
      gap: 20px;
    }

    input, textarea {
      width: 100%;
      margin-bottom: 10px;
      padding: 12px;
      background: #020008;
      border: 3px solid #00eaff;
      color: #00eaff;
      font-family: 'Press Start 2P', monospace;
      font-size: 9px;
    }

    .send {
      width: 100%;
      background: #ff3bd4;
      color: #020008;
      border: 3px solid #fff;
      padding: 15px;
      font-family: 'Press Start 2P', monospace;
      cursor: pointer;
    }

    .footer {
      text-align: center;
      color: #00eaff;
      font-size: 9px;
      margin-top: 20px;
    }

    @media (max-width: 800px) {
      .nav,
      .hero,
      .services,
      .contact {
        grid-template-columns: 1fr;
      }

      h1 {
        font-size: 28px;
      }

      .site {
        margin: 8px;
      }
    }
  </style>
</head>

<body>

  <div class="site">

    <div class="top">
      <h1>VISUAL AUDIO<br>SERVICES</h1>
      <div class="subtitle">Sound • Lighting • Event Support • AV Installation</div>
    </div>

    <div class="nav">
      <a href="#home">⌂ Home</a>
      <a href="#services">♫ Services</a>
      <a href="#gear">▣ Hire</a>
      <a href="#contact">✉ Contact</a>
    </div>

    <div class="ticker">
      <span>*** LIVE SOUND • LIGHTING • AV HIRE • MUSIC PRODUCTION • EVENT SUPPORT ***</span>
    </div>

    <section class="hero" id="home">
      <div>
        <h2>Welcome To Visual Audio</h2>
        <p>
          We bring venue-shaking sound and eye-burning visuals to gigs,
          parties, festivals, corporate events and weird little warehouse shows.
        </p>
        <a class="button" href="#contact">Book Now ▶</a>
      </div>

      <div class="stage">
        <div class="crowd"></div>
      </div>
    </section>

    <h2 id="services" style="text-align:center;">Our Services</h2>

    <section class="services">
      <div class="card">
        <div class="icon">▰</div>
        <h3>Live Sound</h3>
        <p>PA systems, mixing, stage setup and event audio.</p>
      </div>

      <div class="card">
        <div class="icon">☀</div>
        <h3>Lighting</h3>
        <p>Party lights, stage lighting and visual atmosphere.</p>
      </div>

      <div class="card">
        <div class="icon">▣</div>
        <h3>AV Hire</h3>
        <p>Speakers, mixers, mics, projectors and event gear.</p>
      </div>

      <div class="card">
        <div class="icon">♫</div>
        <h3>Music Production</h3>
        <p>Recording, mixing, editing and creative audio work.</p>
      </div>

      <div class="card">
        <div class="icon">☻</div>
        <h3>Corporate Events</h3>
        <p>Clean, reliable AV for meetings and presentations.</p>
      </div>

      <div class="card">
        <div class="icon">⌂</div>
        <h3>Festivals</h3>
        <p>Sound and lighting support for outdoor events.</p>
      </div>
    </section>

    <section class="gear" id="gear">
      <h2>Powered By Serious Gear</h2>
      <div class="gear-list">
        Mixers • Speakers • Wireless Mics • IEMs • Lighting • Cables • Stands
      </div>
      <p>Everything needed to make your event look loud and sound bright.</p>
    </section>

    <section class="contact" id="contact">
      <div>
        <h2>Contact The Crew</h2>
        <p>Hit us up and let’s make your event unforgettable.</p>
      </div>

      <form>
        <input type="text" placeholder="YOUR NAME">
        <input type="email" placeholder="EMAIL ADDRESS">
        <input type="text" placeholder="EVENT DATE / VENUE">
        <textarea rows="5" placeholder="TELL US ABOUT YOUR EVENT..."></textarea>
        <a href="mailto:youremail@example.com">
          <button class="send" type="button">SEND MESSAGE ▶</button>
        </a>
      </form>
    </section>

    <div class="footer">
      Best viewed at 1024x768<br>
      © 2004–2026 Visual Audio<br>
      Website powered by sound waves, caffeine and dodgy cables.
    </div>

  </div>

</body>
</html>
