<!DOCTYPE html>
<html>
<head>
  <title>Visual Audio Services</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      background: #000;
      color: #fff;
      font-family: 'Press Start 2P', monospace;
      font-size: 10px;
      line-height: 1.7;
      text-transform: uppercase;
    }

    body::before {
      content: "";
      position: fixed;
      inset: 0;
      pointer-events: none;
      background: repeating-linear-gradient(
        to bottom,
        rgba(255,255,255,0.04) 0px,
        rgba(255,255,255,0.04) 1px,
        transparent 2px,
        transparent 5px
      );
      z-index: 99;
    }

    .site {
      max-width: 1180px;
      margin: 12px auto;
      padding: 24px;
      background: #020205;
      border: 4px solid #00eaff;
      box-shadow: 0 0 0 3px #003f55, 0 0 25px #00eaff;
    }

    .top-grid {
      display: grid;
      grid-template-columns: 150px 1fr 150px;
      align-items: center;
      gap: 20px;
      text-align: center;
    }

    h1 {
      color: #00eaff;
      font-size: 52px;
      line-height: 0.95;
      margin: 0;
      text-shadow:
        4px 4px 0 #006d8c,
        8px 8px 0 #001f33;
    }

    .pink {
      color: #ff4bd8;
      font-size: 26px;
      letter-spacing: 12px;
      text-shadow: 4px 4px 0 #501050;
      margin-top: 10px;
    }

    .tagline {
      color: #fff200;
      margin-top: 15px;
      font-size: 10px;
    }

    .eq {
      height: 110px;
      display: flex;
      gap: 8px;
      align-items: end;
      justify-content: center;
    }

    .eq span {
      width: 14px;
      background: linear-gradient(#ff4bd8, #00eaff);
      box-shadow: 0 0 8px #00eaff;
    }

    .eq span:nth-child(1) { height: 35px; }
    .eq span:nth-child(2) { height: 70px; }
    .eq span:nth-child(3) { height: 45px; }
    .eq span:nth-child(4) { height: 95px; }
    .eq span:nth-child(5) { height: 55px; }

    .speaker-stack {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
    }

    .speaker {
      width: 72px;
      height: 86px;
      border: 4px solid #7b2cff;
      background: #111;
      box-shadow: 5px 5px 0 #201040;
      position: relative;
    }

    .speaker::before,
    .speaker::after {
      content: "";
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      border-radius: 50%;
      border: 4px solid #777;
      background: #000;
    }

    .speaker::before {
      width: 22px;
      height: 22px;
      top: 10px;
    }

    .speaker::after {
      width: 42px;
      height: 42px;
      bottom: 10px;
    }

    .nav {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
      margin: 25px 0 14px;
    }

    .nav a {
      color: #00eaff;
      border: 3px solid #00eaff;
      padding: 18px;
      text-decoration: none;
      background: #050510;
      text-align: center;
      box-shadow: inset 0 0 0 2px #003f55;
      font-size: 12px;
    }

    .nav a:nth-child(2) { color: #ff4bd8; }
    .nav a:nth-child(3) { color: #fff200; }
    .nav a:nth-child(4) { color: #68ff68; }

    .nav a:hover {
      background: #111133;
      transform: translateY(-2px);
    }

    .ticker {
      border: 3px solid #ff4bd8;
      color: #fff200;
      padding: 8px;
      overflow: hidden;
      white-space: nowrap;
      margin-bottom: 18px;
    }

    .ticker span {
      display: inline-block;
      animation: scroll 16s linear infinite;
    }

    @keyframes scroll {
      from { transform: translateX(100%); }
      to { transform: translateX(-100%); }
    }

    .hero {
      border: 3px solid #7b2cff;
      min-height: 240px;
      padding: 22px;
      display: grid;
      grid-template-columns: 310px 1fr;
      gap: 25px;
      background: radial-gradient(circle at center, #12001f, #000);
      margin-bottom: 24px;
    }

    h2 {
      color: #00eaff;
      font-size: 20px;
      line-height: 1.2;
      margin: 0 0 16px;
    }

    .button {
      display: inline-block;
      color: #ff4bd8;
      border: 3px solid #ff4bd8;
      padding: 10px 18px;
      text-decoration: none;
      background: #120010;
      box-shadow: 4px 4px 0 #7b2cff;
      margin-top: 8px;
    }

    .stage {
      position: relative;
      border: 2px solid #2b1245;
      overflow: hidden;
      min-height: 210px;
      background:
        radial-gradient(circle at 35% 10%, rgba(255,75,216,.8) 0 4%, transparent 18%),
        radial-gradient(circle at 50% 10%, rgba(0,234,255,.8) 0 4%, transparent 18%),
        radial-gradient(circle at 65% 10%, rgba(255,75,216,.8) 0 4%, transparent 18%),
        linear-gradient(#050010, #000);
    }

    .truss {
      position: absolute;
      top: 12px;
      left: 16%;
      right: 16%;
      height: 25px;
      border: 3px solid #7b2cff;
      background: repeating-linear-gradient(45deg, transparent 0 10px, #7b2cff 10px 13px);
    }

    .beam {
      position: absolute;
      top: 35px;
      width: 75px;
      height: 150px;
      opacity: .75;
      clip-path: polygon(40% 0, 60% 0, 100% 100%, 0 100%);
    }

    .beam.one { left: 32%; background: #ff4bd8; }
    .beam.two { left: 43%; background: #00eaff; }
    .beam.three { left: 54%; background: #ff4bd8; }

    .performer {
      position: absolute;
      bottom: 55px;
      left: 50%;
      transform: translateX(-50%);
      color: #fff;
      font-size: 40px;
      z-index: 3;
    }

    .crowd {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 75px;
      background:
        radial-gradient(circle, #7b2cff 0 6px, transparent 7px) 0 0 / 28px 28px,
        linear-gradient(to top, #000 0 55%, transparent 55%);
    }

    .section-title {
      display: flex;
      align-items: center;
      gap: 20px;
      color: #00eaff;
      text-align: center;
      justify-content: center;
      margin: 20px 0 12px;
    }

    .section-title::before,
    .section-title::after {
      content: "";
      height: 3px;
      flex: 1;
      background: #7b2cff;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
    }

    .card {
      border: 2px solid #00eaff;
      display: grid;
      grid-template-columns: 90px 1fr;
      gap: 14px;
      padding: 14px;
      min-height: 110px;
      background: #030309;
    }

    .icon {
      font-size: 42px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .cyan { color: #00eaff; }
    .pink-icon { color: #ff4bd8; }
    .yellow { color: #fff200; }
    .green { color: #68ff68; }
    .purple { color: #7b2cff; }

    h3 {
      margin: 0 0 5px;
      font-size: 12px;
      color: #00eaff;
    }

    .card:nth-child(2) h3 { color: #ff4bd8; }
    .card:nth-child(3) h3 { color: #fff200; }
    .card:nth-child(4) h3 { color: #68ff68; }
    .card:nth-child(5) h3 { color: #7b2cff; }

    .gear {
      margin: 18px 0;
      text-align: center;
    }

    .gear h2 {
      color: #fff200;
      text-align: center;
      margin-bottom: 15px;
    }

    .gear-icons {
      display: grid;
      grid-template-columns: repeat(7, 1fr);
      gap: 12px;
      align-items: start;
    }

    .gear-item {
      color: #fff;
      font-size: 8px;
    }

    .gear-pic {
      font-size: 34px;
      margin-bottom: 8px;
      color: #aaa;
    }

    .gear-line {
      color: #fff;
      font-size: 10px;
      margin-top: 10px;
    }

    .contact-title {
      color: #ff4bd8;
      text-align: center;
      font-size: 18px;
      margin: 10px 0;
    }

    .contact {
      border: 3px solid #7b2cff;
      display: grid;
      grid-template-columns: 330px 1fr 180px;
      gap: 20px;
      padding: 18px;
      align-items: center;
    }

    .mailbox {
      font-size: 54px;
      color: #ff4bd8;
      text-align: center;
    }

    input, textarea {
      width: 100%;
      background: #020205;
      border: 2px solid #00eaff;
      color: #00eaff;
      padding: 10px;
      margin-bottom: 8px;
      font-family: 'Press Start 2P', monospace;
      font-size: 8px;
    }

    .send {
      display: block;
      text-align: center;
      background: #ff4bd8;
      color: #140014;
      border: 4px solid #ff9bea;
      padding: 18px 10px;
      text-decoration: none;
      font-size: 14px;
      box-shadow: 5px 5px 0 #7b2cff;
    }

    .footer {
      text-align: center;
      color: #00eaff;
      font-size: 8px;
      margin-top: 18px;
    }

    @media (max-width: 900px) {
      .top-grid,
      .hero,
      .services,
      .contact,
      .gear-icons {
        grid-template-columns: 1fr;
      }

      .nav {
        grid-template-columns: 1fr 1fr;
      }

      h1 {
        font-size: 32px;
      }

      .pink {
        font-size: 18px;
        letter-spacing: 5px;
      }

      .eq,
      .speaker-stack {
        display: none;
      }

      .site {
        margin: 6px;
        padding: 14px;
      }

      .card {
        grid-template-columns: 70px 1fr;
      }
    }
  </style>
</head>

<body>

  <div class="site">

    <header class="top-grid">
      <div class="eq">
        <span></span><span></span><span></span><span></span><span></span>
      </div>

      <div>
        <h1>VISUAL AUDIO</h1>
        <div class="pink">SERVICES</div>
        <div class="tagline">Sound ✦ Lighting ✦ Event Support ✦ AV Installation</div>
      </div>

      <div class="speaker-stack">
        <div class="speaker"></div>
      </div>
    </header>

    <nav class="nav">
      <a href="#home">⌂ Home</a>
      <a href="#services">♫ Services</a>
      <a href="#gear">▣ Hire</a>
      <a href="#contact">✉ Contact</a>
    </nav>

    <div class="ticker">
      <span>&lt;&lt;&lt; *** Live Sound ✦ Lighting ✦ AV Hire ✦ Music Production ✦ Event Support *** &gt;&gt;&gt;</span>
    </div>

    <section class="hero" id="home">
      <div>
        <h2>Welcome To<br>Visual Audio</h2>
        <p>
          We bring venue-shaking sound and eye-burning visuals to gigs,
          parties, festivals, corporate events and weird little warehouse shows.
        </p>
        <a class="button" href="#contact">Book Now ▶</a>
      </div>

      <div class="stage">
        <div class="truss"></div>
        <div class="beam one"></div>
        <div class="beam two"></div>
        <div class="beam three"></div>
        <div class="performer">♬</div>
        <div class="crowd"></div>
      </div>
    </section>

    <h2 class="section-title" id="services">Our Services</h2>

    <section class="services">
      <div class="card">
        <div class="icon cyan">▣</div>
        <div>
          <h3>Live Sound</h3>
          <p>PA systems, mixing, stage setup and event audio.</p>
        </div>
      </div>

      <div class="card">
        <div class="icon pink-icon">☀</div>
        <div>
          <h3>Lighting</h3>
          <p>Party lights, stage lighting and visual atmosphere.</p>
        </div>
      </div>

      <div class="card">
        <div class="icon yellow">▰</div>
        <div>
          <h3>AV Hire</h3>
          <p>Speakers, mixers, mics, projectors and event gear.</p>
        </div>
      </div>

      <div class="card">
        <div class="icon green">♫</div>
        <div>
          <h3>Music Production</h3>
          <p>Recording, mixing, editing and creative audio work.</p>
        </div>
      </div>

      <div class="card">
        <div class="icon purple">♟</div>
        <div>
          <h3>Corporate Events</h3>
          <p>Clean, reliable AV for meetings and presentations.</p>
        </div>
      </div>

      <div class="card">
        <div class="icon cyan">⌂</div>
        <div>
          <h3>Festivals</h3>
          <p>Sound and lighting support for outdoor events.</p>
        </div>
      </div>
    </section>

    <section class="gear" id="gear">
      <h2>Powered By Serious Gear</h2>

      <div class="gear-icons">
        <div class="gear-item"><div class="gear-pic">▦</div>Mixers</div>
        <div class="gear-item"><div class="gear-pic">▣</div>Speakers</div>
        <div class="gear-item"><div class="gear-pic">♬</div>Wireless Mics</div>
        <div class="gear-item"><div class="gear-pic">◉</div>IEMs</div>
        <div class="gear-item"><div class="gear-pic">◌</div>Lighting</div>
        <div class="gear-item"><div class="gear-pic">◎</div>Cables</div>
        <div class="gear-item"><div class="gear-pic">⌐</div>Stands</div>
      </div>

      <div class="gear-line">
        Everything needed to make your event look loud and sound bright.
      </div>
    </section>

    <h2 class="contact-title" id="contact">Contact The Crew</h2>

    <section class="contact">
      <div>
        <div class="mailbox">✉</div>
        <p>Hit us up and let’s make your event unforgettable.</p>
      </div>

      <form>
        <input type="text" placeholder="YOUR NAME">
        <input type="email" placeholder="EMAIL ADDRESS">
        <input type="text" placeholder="EVENT DATE / VENUE">
        <textarea rows="4" placeholder="TELL US ABOUT YOUR EVENT..."></textarea>
      </form>

      <a class="send" href="mailto:youremail@example.com">
        Send<br>Message ▶
      </a>
    </section>

    <footer class="footer">
      Best viewed at 1024x768<br>
      © 2004–2026 Visual Audio<br>
      Website powered by sound waves, caffeine and dodgy cables.
    </footer>

  </div>

</body>
</html>
