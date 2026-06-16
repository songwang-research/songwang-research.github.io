---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-page {
  color: #2f3437;
}

.cv-hero {
  margin: 10px 0 34px 0;
  padding: 30px 34px;
  border-radius: 24px;
  background: linear-gradient(135deg, #f8fafc 0%, #eef7fb 48%, #ffffff 100%);
  border: 1px solid #e6eef3;
  box-shadow: 0 12px 34px rgba(15, 23, 42, 0.10);
}

.cv-kicker {
  color: #2f80a0;
  font-weight: 800;
  font-size: 13px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-bottom: 8px;
}

.cv-hero h1 {
  font-size: 36px;
  line-height: 1.2;
  margin: 0 0 12px 0;
  color: #2f3437;
}

.cv-hero p {
  font-size: 16px;
  line-height: 1.75;
  color: #4b5563;
  margin: 0;
}

.cv-nav {
  position: sticky;
  top: 0;
  z-index: 10;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0 0 32px 0;
  padding: 12px;
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.92);
  border: 1px solid #e5e7eb;
  box-shadow: 0 8px 20px rgba(15, 23, 42, 0.06);
  backdrop-filter: blur(8px);
}

.cv-nav a {
  display: inline-block;
  padding: 8px 13px;
  border-radius: 999px;
  color: #2f80a0;
  background: #eef7fb;
  text-decoration: none;
  font-size: 13px;
  font-weight: 800;
}

.cv-nav a:hover {
  background: #2f80a0;
  color: #ffffff;
}

.cv-section-title {
  margin-top: 42px;
  margin-bottom: 18px;
  font-size: 25px;
  color: #2f3437;
  border-bottom: 1px solid #e5e7eb;
  padding-bottom: 8px;
}

.cv-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
  margin-top: 16px;
}

.cv-card,
.cv-pub-card,
.cv-activity-card {
  padding: 20px 22px;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #edf2f7;
  box-shadow: 0 6px 20px rgba(15, 23, 42, 0.07);
}

.cv-card h3,
.cv-pub-card h3,
.cv-activity-card h3 {
  margin: 0 0 8px 0;
  color: #2f3437;
  font-size: 18px;
}

.cv-card p,
.cv-pub-card p,
.cv-activity-card p {
  margin: 6px 0;
  color: #4b5563;
  line-height: 1.65;
}

.cv-pub-card {
  margin-bottom: 16px;
  border-left: 5px solid #2f80a0;
}

.cv-pub-meta {
  color: #6b7280;
  font-size: 14px;
}

.cv-badge {
  display: inline-block;
  padding: 6px 11px;
  margin: 4px 6px 4px 0;
  border-radius: 999px;
  background: #eef7fb;
  color: #2f80a0;
  font-size: 13px;
  font-weight: 800;
}

.cv-list-card {
  padding: 20px 22px;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #edf2f7;
  box-shadow: 0 6px 20px rgba(15, 23, 42, 0.07);
}

.cv-list-card ul {
  margin: 0;
  padding-left: 20px;
}

.cv-list-card li {
  margin: 9px 0;
  color: #4b5563;
  line-height: 1.65;
}

.cv-link-group {
  padding: 19px 21px;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #edf2f7;
  box-shadow: 0 6px 20px rgba(15, 23, 42, 0.07);
}

.cv-link-group h3 {
  margin: 0 0 10px 0;
  color: #2f80a0;
  font-size: 18px;
}

.cv-link-group a,
.cv-pub-card a,
.cv-activity-card a {
  color: #2f80a0;
  font-weight: 700;
  text-decoration: none;
}

.cv-link-group a:hover,
.cv-pub-card a:hover,
.cv-activity-card a:hover {
  text-decoration: underline;
}

.cv-floating {
  position: fixed;
  right: 22px;
  bottom: 22px;
  display: flex;
  flex-direction: column;
  gap: 8px;
  z-index: 50;
}

.cv-floating a {
  width: 42px;
  height: 42px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: #2f80a0;
  color: #ffffff;
  text-decoration: none;
  font-weight: 900;
  box-shadow: 0 8px 18px rgba(47, 128, 160, 0.28);
}

@media (max-width: 768px) {
  .cv-hero {
    padding: 24px;
  }

  .cv-hero h1 {
    font-size: 30px;
  }

  .cv-grid {
    grid-template-columns: 1fr;
  }

  .cv-floating {
    right: 14px;
    bottom: 14px;
  }
}
</style>

<div class="cv-page" id="top">

  <div class="cv-hero">
    <div class="cv-kicker">Curriculum Vitae · Publications · Academic Activities</div>
    <h1>Song Wang</h1>
    <p>
      Ph.D. student at Chiba University, Japan. My research focuses on dependable computing,
      soft-error-tolerant sequential circuits, and reliability-aware VLSI design.
    </p>
  </div>

  <div class="cv-nav">
    <a href="#education">Education</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#publications">Publications</a>
    <a href="#activities">Activities</a>
    <a href="#service">Service</a>
    <a href="#academic-links">Academic Links</a>
  </div>

  <h2 class="cv-section-title" id="education">Education</h2>
  <div class="cv-grid">
    <div class="cv-card">
      <h3>Doctor of Engineering in Informatics</h3>
      <p><strong>Chiba University, Japan</strong></p>
      <p>Oct. 2025–present</p>
    </div>
    <div class="cv-card">
      <h3>Master of Engineering in Applied and Cognitive Informatics</h3>
      <p><strong>Chiba University, Japan</strong></p>
      <p>Oct. 2023–Sep. 2025</p>
    </div>
  </div>

  <h2 class="cv-section-title" id="experience">Research & Work Experience</h2>
  <div class="cv-grid">
    <div class="cv-card">
      <h3>Research Assistant</h3>
      <p><strong>Informatics, Chiba University, Japan</strong></p>
      <p>Oct. 2025–Mar. 2026</p>
    </div>
    <div class="cv-card">
      <h3>Research Student</h3>
      <p><strong>Information Engineering, Chiba University, Japan</strong></p>
      <p>Apr. 2023–Sep. 2023</p>
    </div>
  </div>

  <h2 class="cv-section-title" id="skills">Skills</h2>
  <div class="cv-grid">
    <div class="cv-list-card">
      <h3>Languages</h3>
      <ul>
        <li>English: TOEIC 755, Jul. 2022</li>
        <li>Japanese: JLPT N2, Jan. 2020</li>
      </ul>
    </div>
    <div class="cv-list-card">
      <h3>Programming</h3>
      <p>
        <span class="cv-badge">C/C++</span>
        <span class="cv-badge">Python</span>
        <span class="cv-badge">Verilog HDL</span>
        <span class="cv-badge">Shell</span>
        <span class="cv-badge">Makefile</span>
      </p>
    </div>
    <div class="cv-list-card">
      <h3>EDA & Design Tools</h3>
      <p>
        <span class="cv-badge">Synopsys HSPICE</span>
        <span class="cv-badge">Cadence Virtuoso</span>
        <span class="cv-badge">Siemens Calibre</span>
        <span class="cv-badge">AMD Vivado</span>
        <span class="cv-badge">KiCad</span>
      </p>
    </div>
    <div class="cv-list-card">
      <h3>Platforms</h3>
      <p><span class="cv-badge">Linux</span></p>
    </div>
  </div>

  <h2 class="cv-section-title" id="publications">Publications</h2>

  <h3>Journal Articles</h3>
  <div class="cv-pub-card">
    <h3>Analysis of a Delay-Element-Based Technique for Enhancing Soft Error Tolerance at Input Nodes Around Clock Edges</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba</p>
    <p><em>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</em>, vol. 34, no. 3, pp. 1017–1028, Mar. 2026.</p>
    <p class="cv-pub-meta">DOI: <a href="https://doi.org/10.1109/TVLSI.2025.3643939">10.1109/TVLSI.2025.3643939</a></p>
  </div>

  <div class="cv-pub-card">
    <h3>C-Element-Based Latch with DNU Tolerance and SET Resilience Around Clock Edges</h3>
    <p><strong>Song Wang</strong>, Xiangqing Wei, Ji Wu, and Kazuteru Namba</p>
    <p><em>Nonlinear Theory and Its Applications, IEICE</em>, to appear.</p>
  </div>

  <div class="cv-pub-card">
    <h3>Structure-Aware Tile-Level Scheduling for Irregular CNNs on PE-Array Accelerators</h3>
    <p>Xiangqing Wei, Ji Wu, <strong>Song Wang</strong>, Yun-Ju Baek, and Kazuteru Namba</p>
    <p><em>Nonlinear Theory and Its Applications, IEICE</em>, to appear.</p>
  </div>

  <h3>International Conference Papers</h3>
  <div class="cv-pub-card">
    <h3>A Delay-Elements-Centric Multi-Path Temporal Dispersion Structure for MNU-Tolerant Latch Design</h3>
    <p><strong>Song Wang</strong>, Ji Wu, Xiangqing Wei, and Kazuteru Namba</p>
    <p><em>2026 IEEE 15th International Conference on Communications, Circuits and Systems (ICCCAS)</em>, accepted.</p>
  </div>

  <div class="cv-pub-card">
    <h3>XAI-Driven Semantic Decoupling for NPU Fault Injection</h3>
    <p>Ji Wu, Xiangqing Wei, <strong>Song Wang</strong>, and Kazuteru Namba</p>
    <p><em>2026 IEEE 15th International Conference on Communications, Circuits and Systems (ICCCAS)</em>, accepted.</p>
  </div>

  <div class="cv-pub-card">
    <h3>A Double-Node-Upset Self-Recoverable Latch with Soft Error Tolerance to Soft Errors Around Clock Edges</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba</p>
    <p><em>2026 IEEE 2nd International Conference on Consumer Technology – Pacific (ICCT-Pacific)</em>, Yoshida, Yamaguchi-shi, Japan, Mar. 2026, pp. 239–242.</p>
    <p class="cv-pub-meta">DOI: <a href="https://doi.org/10.1109/ICCT-Pacific69083.2026.11518797">10.1109/ICCT-Pacific69083.2026.11518797</a></p>
  </div>

  <div class="cv-pub-card">
    <h3>C-Element-Based Latch for Flip-Flops: Complete SNU and Partial DNU Tolerance and Resilience to Soft Errors Around Clock Edges</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba</p>
    <p><em>2025 1st International Conference on Consumer Technology – Pacific (ICCT-Pacific)</em>, Matsue, Japan, Mar. 2025.</p>
    <p class="cv-pub-meta">DOI: <a href="https://doi.org/10.1109/ICCT-Pacific63901.2025.11012884">10.1109/ICCT-Pacific63901.2025.11012884</a></p>
  </div>

  <div class="cv-pub-card">
    <h3>A Master-Slave Flip-Flop with Double-Node-Upset Self-Recovery and Soft Error Tolerance Around Clock Edges</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba</p>
    <p><em>2024 International Conference on Consumer Electronics – Taiwan (ICCE-Taiwan)</em>, Taichung, Taiwan, Jul. 2024.</p>
    <p class="cv-pub-meta">DOI: <a href="https://doi.org/10.1109/ICCE-Taiwan62264.2024.10674496">10.1109/ICCE-Taiwan62264.2024.10674496</a></p>
  </div>

  <h3>Domestic Workshops and Technical Reports</h3>
  <div class="cv-pub-card">
    <h3>A C-Element-Based Latch Design for Flip-Flops with Complete SNU and Partial DNU Tolerance and Enhanced Soft Error Resilience Around Clock Edges</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba</p>
    <p><em>IEICE Technical Report</em>, DC2024-113, Tokyo, Japan, Feb. 2025.</p>
  </div>

  <div class="cv-pub-card">
    <h3>Critical Charge Measurements Around Falling Edge of Clock Signal for D Flip-Flops</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba</p>
    <p><em>FTC Workshop</em>, Hiroshima, Japan, Jan. 2024.</p>
  </div>

  <h2 class="cv-section-title" id="activities">Academic Activities and Presentations</h2>

  <div class="cv-activity-card">
    <h3>Asia Student Workshop on Information and Image Science</h3>
    <p>Teaching Assistant, “Let’s Try Simulating Computations Performed in Image Processing FPGA,” Chiba, Japan, Mar. 2026.</p>
  </div>

  <div class="cv-activity-card">
    <h3>IEEE CAS Chiba Workshop</h3>
    <p><strong>Song Wang</strong>, “Delay-Element-Based Soft-Error-Tolerant Latch with SET Tolerance at Input Nodes Around Clock Edges,” Chiba, Japan, Dec. 2025.</p>
  </div>

  <div class="cv-activity-card">
    <h3>SEMICON Japan Academia Area</h3>
    <p>Exhibitor, Computer Systems Laboratory, Chiba University, Tokyo, Japan, Dec. 2025.</p>
  </div>

  <div class="cv-activity-card">
    <h3>The 11th Soft Error Workshop: Radiation Effects in Semiconductors</h3>
    <p><strong>Song Wang</strong> and Kazuteru Namba, “A Delay-Element-Based Latch for Flip-Flops with Recovery from Double-Node Upsets and Tolerance to Soft Errors Around Clock Edges,” Fukuoka, Japan, Sep. 2025.</p>
  </div>

  <div class="cv-activity-card">
    <h3>Asia Student Workshop on Information and Image Science</h3>
    <p>Teaching Assistant, “Let’s Try Simulating Computations Performed in Image Processing FPGA,” Chiba, Japan, Mar. 2025.</p>
  </div>

  <div class="cv-activity-card">
    <h3>SEMICON Japan Academia Area</h3>
    <p>Exhibitor, Namba Laboratory, Chiba University, Tokyo, Japan, Dec. 2024.</p>
  </div>

  <div class="cv-activity-card">
    <h3>SEMICON Japan Academia Area</h3>
    <p>Exhibitor, Namba Laboratory, Chiba University, “Namba Laboratory and Chips,” Tokyo, Japan, Dec. 2023.</p>
  </div>

  <h2 class="cv-section-title" id="service">Professional Service and Memberships</h2>
  <div class="cv-grid">
    <div class="cv-card">
      <h3>Membership</h3>
      <p>Graduate Student Member, Institute of Electrical and Electronics Engineers (IEEE).</p>
    </div>
    <div class="cv-card">
      <h3>Reviewer</h3>
      <p><a href="https://mc.manuscriptcentral.com/tcas1">IEEE Transactions on Circuits and Systems I: Regular Papers</a></p>
      <p><a href="https://mc.manuscriptcentral.com/tvlsi-ieee">IEEE Transactions on Very Large Scale Integration (VLSI) Systems</a></p>
      <p><a href="https://link.springer.com/journal/10836">Journal of Electronic Testing: Theory and Applications</a></p>
    </div>
  </div>

  <h2 class="cv-section-title" id="academic-links">Academic Links</h2>
  <div class="cv-grid">
    <div class="cv-link-group">
      <h3>Author Profiles</h3>
      <p><a href="https://orcid.org/0009-0000-7572-7800">ORCID</a></p>
      <p><a href="https://www.scopus.com/authid/detail.uri?authorId=59358445800">Scopus Author Profile</a></p>
      <p><a href="https://www.webofscience.com/wos/author/record/PHO-3537-2026">Web of Science Researcher Profile</a></p>
      <p><a href="https://ieeexplore.ieee.org/author/704888443148980">IEEE Xplore Author Profile</a></p>
    </div>
    <div class="cv-link-group">
      <h3>Professional Societies</h3>
      <p><a href="https://www.ieee.org/">IEEE</a></p>
      <p><a href="https://www.computer.org/">IEEE Computer Society</a></p>
      <p><a href="https://ieee-cas.org/">IEEE Circuits and Systems Society</a></p>
      <p><a href="https://sscs.ieee.org/">IEEE Solid-State Circuits Society</a></p>
      <p><a href="https://ieee-ceda.org/">IEEE Council on Electronic Design Automation</a></p>
    </div>
    <div class="cv-link-group">
      <h3>IEICE</h3>
      <p><a href="https://www.ieice.org/">IEICE</a></p>
      <p><a href="https://www.ieice.org/iss/iss_r/eng/index.php">Information and Systems Society</a></p>
      <p><a href="https://www.ieice.org/nolta/index.php">NOLTA Society</a></p>
      <p><a href="https://www.ieice.org/iss/dc/jpn/">Dependable Computing Technical Committee</a></p>
      <p><a href="https://globals.ieice.org/">IEICE Digital Library</a></p>
      <p><a href="https://review.ieice.org/index_e.aspx">IEICE Information on Status of Each Paper</a></p>
    </div>
    <div class="cv-link-group">
      <h3>Chiba University and Research Infrastructure</h3>
      <p><a href="https://www.chiba-u.ac.jp/">Chiba University</a></p>
      <p><a href="https://informatics.chiba-u.jp/">Graduate School of Informatics</a></p>
      <p><a href="https://www.se.chiba-u.jp/">Graduate School of Science and Engineering</a></p>
      <p><a href="http://www.icsd2.tj.chiba-u.jp/">Kitakami & Namba Laboratory</a></p>
      <p><a href="http://www.vdec.u-tokyo.ac.jp/">VDEC</a></p>
    </div>
  </div>

  <div class="cv-floating">
    <a href="#top" aria-label="Back to top">↑</a>
    <a href="#bottom" aria-label="Go to bottom">↓</a>
  </div>

  <div id="bottom"></div>

</div>
