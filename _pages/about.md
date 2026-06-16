---
permalink: /
title: "Hi, "
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
html {
  scroll-behavior: smooth;
}

.profile-intro-card {
  margin: 8px 0 28px 0;
  padding: 26px 28px;
  border-radius: 22px;
  background: linear-gradient(135deg, #f8fafc 0%, #eef7fb 48%, #ffffff 100%);
  border: 1px solid #e5edf3;
  box-shadow: 0 10px 28px rgba(15, 23, 42, 0.08);
}

.profile-kicker {
  color: #2f80a0;
  font-weight: 700;
  font-size: 13px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-bottom: 8px;
}

.profile-intro-card h1 {
  margin: 0 0 12px 0;
  color: #2f3437;
  font-size: 34px;
  line-height: 1.18;
}

.profile-intro-card p {
  color: #4b5563;
  line-height: 1.75;
  margin: 10px 0;
}

.profile-buttons {
  margin-top: 18px;
}

.profile-buttons a {
  display: inline-block;
  padding: 9px 16px;
  margin: 6px 8px 6px 0;
  border-radius: 999px;
  text-decoration: none;
  font-size: 14px;
  font-weight: 700;
  background: #2f80a0;
  color: #ffffff !important;
  box-shadow: 0 5px 12px rgba(47, 128, 160, 0.20);
}

.profile-buttons a.secondary {
  background: #ffffff;
  color: #2f80a0 !important;
  border: 1px solid #2f80a0;
  box-shadow: none;
}

.section-nav {
  position: sticky;
  top: 0;
  z-index: 20;
  margin: 20px 0 34px 0;
  padding: 12px 14px;
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.92);
  border: 1px solid #e5e7eb;
  box-shadow: 0 6px 18px rgba(15, 23, 42, 0.06);
  backdrop-filter: blur(8px);
}

.section-nav a {
  display: inline-block;
  margin: 4px 8px 4px 0;
  padding: 7px 12px;
  border-radius: 999px;
  background: #f8fafc;
  color: #2f80a0 !important;
  font-size: 13px;
  font-weight: 700;
  text-decoration: none;
  border: 1px solid #e5e7eb;
}

.section-title {
  margin-top: 42px;
  margin-bottom: 18px;
  font-size: 25px;
  color: #2f3437;
  border-bottom: 1px solid #e5e7eb;
  padding-bottom: 8px;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
  margin-top: 18px;
}

.info-card,
.news-card,
.activity-card,
.link-card {
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #edf2f7;
  box-shadow: 0 6px 20px rgba(15, 23, 42, 0.06);
}

.info-card,
.activity-card,
.link-card {
  padding: 20px 22px;
}

.news-card {
  padding: 18px 20px;
  border-left: 5px solid #2f80a0;
  margin-bottom: 14px;
}

.news-date {
  color: #2f80a0;
  font-weight: 800;
  font-size: 14px;
  margin-bottom: 8px;
}

.news-card p,
.activity-card p,
.info-card p,
.link-card p {
  color: #4b5563;
  line-height: 1.68;
  margin: 6px 0;
}

.activity-card h3,
.info-card h3,
.link-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
  color: #2f3437;
  font-size: 18px;
}

.activity-card a,
.link-card a,
.news-card a,
.info-card a {
  color: #2f80a0 !important;
  font-weight: 700;
}

.badge {
  display: inline-block;
  padding: 7px 12px;
  margin: 5px 7px 5px 0;
  border-radius: 999px;
  background: #eef7fb;
  color: #2f80a0;
  font-size: 13px;
  font-weight: 700;
}

.compact-list {
  margin: 8px 0 0 0;
  padding-left: 0;
  list-style: none;
}

.compact-list li {
  margin: 9px 0;
  line-height: 1.58;
  color: #4b5563;
}

.compact-list li::before {
  content: "•";
  color: #2f80a0;
  font-weight: 900;
  margin-right: 8px;
}

.highlight-box {
  margin-top: 18px;
  padding: 20px 24px;
  border-radius: 18px;
  background: #f8fafc;
  border: 1px solid #e5e7eb;
  color: #4b5563;
  line-height: 1.75;
}

.floating-jump {
  position: fixed;
  right: 22px;
  bottom: 22px;
  z-index: 999;
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.floating-jump a {
  width: 42px;
  height: 42px;
  border-radius: 999px;
  background: #2f80a0;
  color: #ffffff !important;
  text-align: center;
  line-height: 42px;
  font-weight: 900;
  text-decoration: none;
  box-shadow: 0 8px 18px rgba(15, 23, 42, 0.18);
}

.floating-jump a.secondary {
  background: #ffffff;
  color: #2f80a0 !important;
  border: 1px solid #2f80a0;
}

@media (max-width: 768px) {
  .profile-intro-card {
    padding: 22px;
  }

  .profile-intro-card h1 {
    font-size: 28px;
  }

  .section-nav {
    position: static;
  }

  .card-grid {
    grid-template-columns: 1fr;
  }

  .floating-jump {
    right: 14px;
    bottom: 14px;
  }

  .floating-jump a {
    width: 38px;
    height: 38px;
    line-height: 38px;
  }
}
</style>

<div id="top"></div>

<div class="profile-intro-card" id="about">
  <div class="profile-kicker">Dependable Computing · VLSI Reliability · Soft-Error-Tolerant Design</div>

  <h1>Song Wang</h1>

  <p>
    Thank you for visiting my homepage. I am a Ph.D. student in the
    <a href="http://www.icsd2.tj.chiba-u.jp/">Namba Laboratory</a> at
    <a href="https://www.chiba-u.ac.jp/">Chiba University</a>, supervised by Associate Professor
    <a href="https://researchmap.jp/nambakazuteru?lang=en">Kazuteru Namba</a>.
    My research focuses on dependable computing, with particular interests in
    soft-error-tolerant sequential circuits, radiation-hardened-by-design techniques,
    and reliable VLSI systems.
  </p>

  <p>
    At present, I am not affiliated with any external sponsorship. If you are interested in
    potential collaboration, please feel free to contact me.
  </p>

  <div class="profile-buttons">
    <a href="{{ site.baseurl }}/publications/">Publications</a>
    <a class="secondary" href="https://ieeexplore.ieee.org/author/704888443148980">IEEE Xplore</a>
    <a class="secondary" href="mailto:songwang@ieee.org">Email</a>
  </div>
</div>

<div class="section-nav">
  <a href="#about">About</a>
  <a href="#news">News</a>
  <a href="#activities">Academic Activities</a>
  <a href="#quick-links">Quick Links</a>
  <a href="#acknowledgements">Acknowledgements</a>
  <a href="#contact">Contact</a>
</div>

<h2 class="section-title" id="news">News</h2>

<div class="news-card">
  <div class="news-date">Jul. 7–10, 2026</div>
  <p>
    <strong>Wang</strong> will present “A Delay-Elements-Centric Multi-Path Temporal Dispersion Structure for MNU-Tolerant Latch Design”
    at the <a href="https://www.icccas.org/"><em>2026 IEEE 15th International Conference on Communications, Circuits and Systems (ICCCAS)</em></a>
    in Gunma, Japan.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Apr. 10, 2026</div>
  <p>
    <strong>Wang</strong>’s paper “C-Element-Based Latch with DNU Tolerance and SET Resilience Around Clock Edges”
    was accepted for publication in
    <a href="https://www.jstage.jst.go.jp/browse/nolta/-char/en"><em>Nonlinear Theory and Its Applications, IEICE</em></a>.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Mar. 28–30, 2026</div>
  <p>
    <strong>Wang</strong> presented “A Double-Node-Upset Self-Recoverable Latch with Soft Error Tolerance to Soft Errors Around Clock Edges”
    at <a href="https://2026.icct-pacific.org/"><em>IEEE International Conference on Consumer Technology - Pacific 2026</em></a>
    in Yamaguchi, Japan.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Mar. 9, 2026</div>
  <p>
    <strong>Wang</strong> served as a teaching assistant for the hands-on session
    “Let’s Try Simulating Computations Performed in Image Processing FPGA” at
    <a href="https://www.tp.chiba-u.jp/asw/html/html_en/index.html#3"><em>Asia Student Workshop (ASW) on Information and Image Science</em></a>,
    held at Chiba University.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Feb. 16–17, 2026</div>
  <p>
    <strong>Wang</strong> participated in the Synopsys ASIC Design Engineer Course at the Futako-Tamagawa Rise Office of
    <a href="https://www.synopsys.com/ja-jp/japan/company.html"><em>Synopsys Japan G.K.</em></a>
    in Tokyo, Japan.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Dec. 26–27, 2025</div>
  <p>
    <strong>Wang</strong> presented “Delay-Element-Based Soft-Error-Tolerant Latch with SET Tolerance at Input Nodes Around Clock Edges”
    at <a href="https://www.s-lab.nd.chiba-u.jp/chibaworkshop/2025/index.html"><em>2025 IEEE CASS Chiba Workshop</em></a>
    in Chiba, Japan.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Dec. 17–19, 2025</div>
  <p>
    <strong>Wang</strong> participated in the Academia Area of
    <a href="https://www.semiconjapan.org/jp/workforce/academia"><em>SEMICON Japan</em></a>
    at Tokyo Big Sight and presented a poster on behalf of the Computer Systems Laboratory, Chiba University.
  </p>
</div>

<div class="news-card">
  <div class="news-date">Dec. 8, 2025</div>
  <p>
    <strong>Wang</strong>’s paper “Analysis of a Delay-Element-Based Technique for Enhancing Soft Error Tolerance at Input Nodes Around Clock Edges”
    was accepted for publication in
    <a href="https://ieee-cas.org/publication/tvlsi"><em>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</em></a>.
  </p>
</div>

<div class="highlight-box">
  <strong>Earlier news will be updated soon.</strong>
</div>

<h2 class="section-title" id="activities">Academic Activities</h2>

<div class="card-grid">
  <div class="activity-card">
    <h3>Membership</h3>
    <ul class="compact-list">
      <li>Graduate Student Member, <a href="https://www.ieee.org/">Institute of Electrical and Electronics Engineers (IEEE)</a></li>
    </ul>
  </div>

  <div class="activity-card">
    <h3>Reviewer Service</h3>
    <ul class="compact-list">
      <li>Reviewer, <a href="https://mc.manuscriptcentral.com/tcas1"><em>IEEE Transactions on Circuits and Systems I: Regular Papers</em></a> (IEEE TCAS-I)</li>
      <li>Reviewer, <a href="https://mc.manuscriptcentral.com/tvlsi-ieee"><em>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</em></a> (IEEE TVLSI)</li>
      <li>Reviewer, <a href="https://link.springer.com/journal/10836"><em>Journal of Electronic Testing: Theory and Applications</em></a> (JETTA)</li>
    </ul>
  </div>
</div>

<h2 class="section-title" id="quick-links">Quick Links</h2>

<div class="card-grid">
  <div class="link-card">
    <h3>Professional Profiles</h3>
    <ul class="compact-list">
      <li><a href="https://ieeexplore.ieee.org/author/704888443148980">IEEE Xplore Author Profile</a></li>
    </ul>
  </div>

  <div class="link-card">
    <h3>IEEE</h3>
    <ul class="compact-list">
      <li><a href="https://www.ieee.org/">IEEE</a></li>
      <li><a href="https://www.computer.org/">IEEE Computer Society</a></li>
      <li><a href="https://ieee-cas.org/">IEEE Circuits and Systems Society</a></li>
      <li><a href="https://sscs.ieee.org/">IEEE Solid-State Circuits Society</a></li>
      <li><a href="https://ieee-ceda.org/">IEEE Council on Electronic Design Automation</a></li>
    </ul>
  </div>

  <div class="link-card">
    <h3>IEICE</h3>
    <ul class="compact-list">
      <li><a href="https://www.ieice.org/">IEICE</a></li>
      <li><a href="https://www.ieice.org/iss/iss_r/eng/index.php">Information and Systems Society</a></li>
      <li><a href="https://www.ieice.org/nolta/index.php">NOLTA Society</a></li>
      <li><a href="https://www.ieice.org/iss/dc/jpn/">Dependable Computing Technical Committee</a></li>
      <li><a href="https://globals.ieice.org/">IEICE Digital Library</a></li>
      <li><a href="https://review.ieice.org/index_e.aspx">IEICE Information on Status of Each Paper</a></li>
    </ul>
  </div>

  <div class="link-card">
    <h3>Chiba University</h3>
    <ul class="compact-list">
      <li><a href="https://www.chiba-u.ac.jp/">Chiba University</a></li>
      <li><a href="https://informatics.chiba-u.jp/">Graduate School of Informatics</a></li>
      <li><a href="https://www.se.chiba-u.jp/">Graduate School of Science and Engineering</a></li>
      <li><a href="http://www.icsd2.tj.chiba-u.jp/">Kitakami &amp; Namba Laboratory</a></li>
    </ul>
  </div>

  <div class="link-card">
    <h3>Research Infrastructure</h3>
    <ul class="compact-list">
      <li><a href="http://www.vdec.u-tokyo.ac.jp/">VDEC, The University of Tokyo</a></li>
    </ul>
  </div>
</div>

<h2 class="section-title" id="acknowledgements">Acknowledgements</h2>

<div class="info-card">
  <p>
    My research has been supported through the activities of VDEC, d.lab, The University of Tokyo,
    in collaboration with NIHON SYNOPSYS G.K., Cadence Design Systems, and Siemens Electronic Design Automation Japan K.K.
  </p>
</div>

<h2 class="section-title" id="contact">Contact Information</h2>

<div class="info-card">
  <p>
    <strong>Address:</strong> 4F, 1st Bldg., Faculty of Engineering, Nishi-Chiba Campus, Chiba University,
    1-33 Yayoi-cho, Inage-ku, Chiba-shi, Chiba 263-8522, Japan.
    408 (WANG), 411 (NAMBA, Supervisor)
  </p>
  <p>
    <strong>E-mail:</strong> <a href="mailto:songwang@ieee.org">songwang@ieee.org</a>
  </p>
</div>

<div id="bottom"></div>

<div class="floating-jump">
  <a href="#top" title="Back to top">↑</a>
  <a class="secondary" href="#bottom" title="Go to bottom">↓</a>
</div>
