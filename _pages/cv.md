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
html {
  scroll-behavior: smooth;
}

.sw-page {
  max-width: 880px;
  margin: 0 auto;
  color: #2f3437;
}

.sw-page a {
  color: #2f80a0 !important;
  font-weight: 700;
  text-decoration: none;
}

.sw-page a:hover {
  text-decoration: underline;
}

.sw-hero {
  margin: 8px 0 26px 0;
  padding: 26px 28px;
  border-radius: 22px;
  background: linear-gradient(135deg, #f8fafc 0%, #eef7fb 48%, #ffffff 100%);
  border: 1px solid #e5edf3;
  box-shadow: 0 10px 28px rgba(15, 23, 42, 0.08);
}

.sw-kicker {
  color: #2f80a0;
  font-weight: 800;
  font-size: 13px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-bottom: 8px;
}

.sw-hero h1 {
  margin: 0 0 12px 0;
  color: #2f3437;
  font-size: 34px;
  line-height: 1.18;
}

.sw-hero p {
  color: #4b5563;
  line-height: 1.75;
  margin: 10px 0 0 0;
}

.sw-nav {
  position: sticky;
  top: 0;
  z-index: 20;
  margin: 18px 0 30px 0;
  padding: 10px 12px;
  border-radius: 16px;
  background: rgba(255, 255, 255, 0.92);
  border: 1px solid #e5e7eb;
  box-shadow: 0 6px 18px rgba(15, 23, 42, 0.06);
  backdrop-filter: blur(8px);
}

.sw-nav a {
  display: inline-block;
  margin: 4px 7px 4px 0;
  padding: 7px 12px;
  border-radius: 999px;
  background: #f8fafc;
  color: #2f80a0 !important;
  font-size: 13px;
  font-weight: 800;
  border: 1px solid #e5e7eb;
}

.sw-section-title {
  margin-top: 38px;
  margin-bottom: 16px;
  font-size: 24px;
  color: #2f3437;
  border-bottom: 1px solid #e5e7eb;
  padding-bottom: 8px;
}

.sw-subtitle {
  margin: 24px 0 10px 0;
  color: #2f80a0;
  font-size: 18px;
}

.sw-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
  margin-top: 16px;
}

.sw-card,
.sw-list-card {
  padding: 18px 20px;
  border-radius: 17px;
  background: #ffffff;
  border: 1px solid #edf2f7;
  box-shadow: 0 5px 18px rgba(15, 23, 42, 0.055);
}

.sw-card h3,
.sw-list-card h3 {
  margin: 0 0 9px 0;
  color: #2f3437;
  font-size: 17px;
}

.sw-card p,
.sw-list-card p {
  margin: 6px 0;
  color: #4b5563;
  line-height: 1.64;
}

.sw-badge {
  display: inline-block;
  padding: 6px 11px;
  margin: 4px 6px 4px 0;
  border-radius: 999px;
  background: #eef7fb;
  color: #2f80a0;
  font-size: 13px;
  font-weight: 800;
}

.sw-list-card ul {
  margin: 0;
  padding-left: 20px;
}

.sw-list-card li {
  margin: 8px 0;
  color: #4b5563;
  line-height: 1.62;
}

.pub-list {
  margin: 6px 0 0 0;
  padding-left: 22px;
}

.pub-list li {
  margin: 10px 0;
  padding-left: 4px;
  color: #4b5563;
  line-height: 1.62;
}

.pub-list em {
  color: #374151;
}

.pub-note {
  color: #6b7280;
  font-size: 14px;
}

.timeline {
  margin-top: 12px;
  border-left: 3px solid #dbeaf0;
  padding-left: 18px;
}

.timeline-item {
  position: relative;
  margin: 0 0 16px 0;
  padding: 14px 16px;
  border-radius: 16px;
  background: #ffffff;
  border: 1px solid #edf2f7;
  box-shadow: 0 5px 18px rgba(15, 23, 42, 0.055);
}

.timeline-item::before {
  content: "";
  position: absolute;
  left: -27px;
  top: 19px;
  width: 12px;
  height: 12px;
  border-radius: 999px;
  background: #2f80a0;
  border: 3px solid #eef7fb;
}

.timeline-date {
  color: #2f80a0;
  font-weight: 900;
  font-size: 14px;
  margin-bottom: 5px;
}

.timeline-item p {
  margin: 5px 0;
  color: #4b5563;
  line-height: 1.64;
}

.sw-floating {
  position: fixed;
  right: 22px;
  bottom: 22px;
  z-index: 999;
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.sw-floating a {
  width: 42px;
  height: 42px;
  border-radius: 999px;
  background: #2f80a0;
  color: #ffffff !important;
  text-align: center;
  line-height: 42px;
  font-weight: 900;
  box-shadow: 0 8px 18px rgba(15, 23, 42, 0.18);
}

.sw-floating a.secondary {
  background: #ffffff;
  color: #2f80a0 !important;
  border: 1px solid #2f80a0;
}

@media (max-width: 768px) {
  .sw-page {
    max-width: 100%;
  }

  .sw-hero {
    padding: 22px;
  }

  .sw-hero h1 {
    font-size: 28px;
  }

  .sw-nav {
    position: static;
  }

  .sw-grid {
    grid-template-columns: 1fr;
  }

  .sw-floating {
    right: 14px;
    bottom: 14px;
  }

  .sw-floating a {
    width: 38px;
    height: 38px;
    line-height: 38px;
  }
}
</style>

<div class="sw-page" id="top">

  <div class="sw-hero">
    <div class="sw-kicker">Curriculum Vitae · Publications · Academic Activities</div>
    <h1>Song Wang</h1>
    <p>
      Ph.D. student at Chiba University, Japan. My research focuses on dependable computing,
      soft-error-tolerant sequential circuits, and reliability-aware VLSI design.
    </p>
  </div>

  <div class="sw-nav">
    <a href="#education">Education</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#publications">Publications</a>
    <a href="#activities">Activities</a>
  </div>

  <h2 class="sw-section-title" id="education">Education</h2>
  <div class="sw-grid">
    <div class="sw-card">
      <h3>Doctor of Engineering in Informatics</h3>
      <p><strong>Chiba University, Japan</strong></p>
      <p>Oct. 2025–present</p>
    </div>
    <div class="sw-card">
      <h3>Master of Engineering in Applied and Cognitive Informatics</h3>
      <p><strong>Chiba University, Japan</strong></p>
      <p>Oct. 2023–Sep. 2025</p>
    </div>
  </div>

  <h2 class="sw-section-title" id="experience">Research &amp; Work Experience</h2>
  <div class="sw-grid">
    <div class="sw-card">
      <h3>Research Assistant</h3>
      <p><strong>Informatics, Chiba University, Japan</strong></p>
      <p>Oct. 2025–Mar. 2026</p>
    </div>
    <div class="sw-card">
      <h3>Research Student</h3>
      <p><strong>Information Engineering, Chiba University, Japan</strong></p>
      <p>Apr. 2023–Sep. 2023</p>
    </div>
  </div>

  <h2 class="sw-section-title" id="skills">Skills</h2>
  <div class="sw-grid">
    <div class="sw-list-card">
      <h3>Languages</h3>
      <ul>
        <li>English: TOEIC 755, Jul. 2022</li>
        <li>Japanese: JLPT N2, Jan. 2020</li>
      </ul>
    </div>
    <div class="sw-list-card">
      <h3>Programming</h3>
      <p>
        <span class="sw-badge">C/C++</span>
        <span class="sw-badge">Python</span>
        <span class="sw-badge">Verilog HDL</span>
        <span class="sw-badge">Shell</span>
        <span class="sw-badge">Makefile</span>
      </p>
    </div>
    <div class="sw-list-card">
      <h3>EDA &amp; Design Tools</h3>
      <p>
        <span class="sw-badge">Synopsys HSPICE</span>
        <span class="sw-badge">Cadence Virtuoso</span>
        <span class="sw-badge">Siemens Calibre</span>
        <span class="sw-badge">AMD Vivado</span>
        <span class="sw-badge">KiCad</span>
      </p>
    </div>
    <div class="sw-list-card">
      <h3>Platforms</h3>
      <p><span class="sw-badge">Linux</span></p>
    </div>
  </div>

  <h2 class="sw-section-title" id="publications">Publications</h2>

  <h3 class="sw-subtitle">Journal Articles</h3>
  <ol class="pub-list">
    <li>
      <strong>Song Wang</strong> and Kazuteru Namba, “Analysis of a Delay-Element-Based Technique for Enhancing Soft Error Tolerance at Input Nodes Around Clock Edges,”
      <em>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</em>, vol. 34, no. 3, pp. 1017–1028, Mar. 2026.
      DOI: <a href="https://doi.org/10.1109/TVLSI.2025.3643939">10.1109/TVLSI.2025.3643939</a>.
    </li>
    <li>
      <strong>Song Wang</strong>, Xiangqing Wei, Ji Wu, and Kazuteru Namba, “C-Element-Based Latch with DNU Tolerance and SET Resilience Around Clock Edges,”
      <em>Nonlinear Theory and Its Applications, IEICE</em>, vol. 17, no. 3, pp. 662–678, 2026.
      DOI: <a href="https://doi.org/10.1587/nolta.17.662">10.1587/nolta.17.662</a>.
    </li>
    <li>
      Xiangqing Wei, Ji Wu, <strong>Song Wang</strong>, YunJu Baek, and Kazuteru Namba, “Structure-Aware Tile-Level Scheduling for Irregular CNNs on PE-Array Accelerators,”
      <em>Nonlinear Theory and Its Applications, IEICE</em>, vol. 17, no. 3, pp. 822–840, 2026.
      DOI: <a href="https://doi.org/10.1587/nolta.17.822">10.1587/nolta.17.822</a>.
    </li>
  </ol>

  <h3 class="sw-subtitle">International Conference Papers</h3>
  <ol class="pub-list">
    <li>
      <strong>Song Wang</strong>, Ji Wu, Xiangqing Wei, and Kazuteru Namba, “A Delay-Elements-Centric Multi-Path Temporal Dispersion Structure for MNU-Tolerant Latch Design,”
      <em>2026 IEEE 15th International Conference on Communications, Circuits and Systems (ICCCAS)</em>, accepted.
    </li>
    <li>
      Ji Wu, Xiangqing Wei, <strong>Song Wang</strong>, and Kazuteru Namba, “XAI-Driven Semantic Decoupling for NPU Fault Injection,”
      <em>2026 IEEE 15th International Conference on Communications, Circuits and Systems (ICCCAS)</em>, accepted.
    </li>
    <li>
      <strong>Song Wang</strong> and Kazuteru Namba, “A Double-Node-Upset Self-Recoverable Latch with Soft Error Tolerance to Soft Errors Around Clock Edges,”
      <em>2026 IEEE 2nd International Conference on Consumer Technology – Pacific (ICCT-Pacific)</em>, Yoshida, Yamaguchi-shi, Japan, Mar. 2026, pp. 239–242.
      DOI: <a href="https://doi.org/10.1109/ICCT-Pacific69083.2026.11518797">10.1109/ICCT-Pacific69083.2026.11518797</a>.
    </li>
    <li>
      <strong>Song Wang</strong> and Kazuteru Namba, “C-Element-Based Latch for Flip-Flops: Complete SNU and Partial DNU Tolerance and Resilience to Soft Errors Around Clock Edges,”
      <em>2025 1st International Conference on Consumer Technology – Pacific (ICCT-Pacific)</em>, Matsue, Japan, Mar. 2025.
      DOI: <a href="https://doi.org/10.1109/ICCT-Pacific63901.2025.11012884">10.1109/ICCT-Pacific63901.2025.11012884</a>.
    </li>
    <li>
      <strong>Song Wang</strong> and Kazuteru Namba, “A Master-Slave Flip-Flop with Double-Node-Upset Self-Recovery and Soft Error Tolerance Around Clock Edges,”
      <em>2024 International Conference on Consumer Electronics – Taiwan (ICCE-Taiwan)</em>, Taichung, Taiwan, Jul. 2024.
      DOI: <a href="https://doi.org/10.1109/ICCE-Taiwan62264.2024.10674496">10.1109/ICCE-Taiwan62264.2024.10674496</a>.
    </li>
  </ol>

  <h3 class="sw-subtitle">Domestic Workshops and Technical Reports</h3>
  <ol class="pub-list">
    <li>
      <strong>Song Wang</strong> and Kazuteru Namba, “A C-Element-Based Latch Design for Flip-Flops with Complete SNU and Partial DNU Tolerance and Enhanced Soft Error Resilience Around Clock Edges,”
      <em>IEICE Technical Report</em>, vol. 124, no. 374, DC2024-113, pp. 43–46, Tokyo, Japan, Feb. 2025.
    </li>
    <li>
      <strong>Song Wang</strong> and Kazuteru Namba, “Critical Charge Measurements Around Falling Edge of Clock Signal for D Flip-Flops,”
      <em>FTC Workshop</em>, Hiroshima, Japan, Jan. 2024.
    </li>
  </ol>

  <p class="pub-note">
    Professional service, memberships, author profiles, and frequently used academic links are summarized on the homepage.
  </p>

  <h2 class="sw-section-title" id="activities">Academic Activities and Presentations</h2>

  <div class="timeline">
    <div class="timeline-item">
      <div class="timeline-date">Mar. 2026</div>
      <p>
        Teaching Assistant, “Let’s Try Simulating Computations Performed in Image Processing FPGA,”
        <em>Asia Student Workshop (ASW) on Information and Image Science</em>, Chiba, Japan.
      </p>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">Dec. 2025</div>
      <p>
        <strong>Song Wang</strong>, “Delay-Element-Based Soft-Error-Tolerant Latch with SET Tolerance at Input Nodes Around Clock Edges,”
        <em>IEEE CAS Chiba Workshop</em>, Chiba, Japan.
      </p>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">Dec. 2025</div>
      <p>
        Exhibitor, Computer Systems Laboratory, Chiba University,
        <em>SEMICON Japan Academia Area</em>, Tokyo, Japan.
      </p>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">Sep. 2025</div>
      <p>
        <strong>Song Wang</strong> and Kazuteru Namba, “A Delay-Element-Based Latch for Flip-Flops with Recovery from Double-Node Upsets and Tolerance to Soft Errors Around Clock Edges,”
        <em>The 11th Soft Error Workshop: Radiation Effects in Semiconductors</em>, Fukuoka, Japan.
      </p>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">Mar. 2025</div>
      <p>
        Teaching Assistant, “Let’s Try Simulating Computations Performed in Image Processing FPGA,”
        <em>Asia Student Workshop (ASW) on Information and Image Science</em>, Chiba, Japan.
      </p>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">Dec. 2024</div>
      <p>
        Exhibitor, Namba Laboratory, Chiba University,
        <em>SEMICON Japan Academia Area</em>, Tokyo, Japan.
      </p>
    </div>

    <div class="timeline-item">
      <div class="timeline-date">Dec. 2023</div>
      <p>
        Exhibitor, Namba Laboratory, Chiba University, “Namba Laboratory and Chips,”
        <em>SEMICON Japan Academia Area</em>, Tokyo, Japan.
      </p>
    </div>
  </div>

  <div id="bottom"></div>

  <div class="sw-floating">
    <a href="#top" title="Back to top">↑</a>
    <a class="secondary" href="#bottom" title="Go to bottom">↓</a>
  </div>

</div>
