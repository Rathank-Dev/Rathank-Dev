<section class="about-container glass">
  <div class="header-content">
    <p class="about-tag">ABOUT ME</p>
    <h1 class="name-title">Rathank <span class="accent">Phoung</span></h1>
    <p class="bio-text">
      📍 Based in <strong>Phnom Penh, Cambodia</strong> 🇰🇭
    </p>
  </div>

  <p class="description">
    I am a passionate <strong>Cybersecurity Researcher</strong> and <strong>Web Dev</strong>. 
  </p>

  <div class="info-grid">
    <div class="info-card">
      <h3>🎓 Education</h3>
      <p><strong>Grade 12 Student</strong><br>High School in Cambodia (2025-Present)</p>
    </div>

    <div class="info-card">
      <h3>🛠️ Skills & Arsenal</h3>
      <div class="skill-tags">
        <span class="tag lang">PHP (Laravel)</span>
        <span class="tag lang">Node.js</span>
        <span class="tag lang">C#</span>
        <span class="tag sys">Kali Linux</span>
        <span class="tag sys">Hyprland</span>
        <span class="tag tool">Burp Suite</span>
        <span class="tag tool">sqlmap</span>
        <span class="tag tool">Metasploit</span>
      </div>
    </div>
  </div>
</section>

<style>
  :root {
    --accent-color: #ff5f5f;
    --bg-card: rgba(20, 20, 20, 0.7);
    --text-main: #e0e0e0;
    --glow: rgba(255, 95, 95, 0.3);
  }

  .glass {
    background: var(--bg-card);
    backdrop-filter: blur(20px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 30px;
    padding: 3rem;
    color: var(--text-main);
    max-width: 800px;
    margin: 2rem auto;
    box-shadow: 0 20px 50px rgba(0, 0, 0, 0.5);
    font-family: 'Inter', sans-serif;
  }

  .about-tag {
    color: var(--accent-color);
    font-weight: 800;
    letter-spacing: 3px;
    font-size: 0.8rem;
    margin-bottom: 0.5rem;
    text-transform: uppercase;
  }

  .name-title {
    font-size: 3rem;
    margin: 0;
    font-weight: 900;
    letter-spacing: -1px;
  }

  .accent { color: var(--accent-color); text-shadow: 0 0 15px var(--glow); }

  .bio-text { color: #888; margin-top: 0.5rem; font-size: 1.1rem; }

  .description {
    line-height: 1.8;
    font-size: 1.1rem;
    margin: 2rem 0;
    color: #bbb;
  }

  .brand {
    color: #fff;
    border-bottom: 2px solid var(--accent-color);
  }

  .info-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
    margin-top: 2rem;
  }

  .info-card h3 {
    font-size: 1.2rem;
    margin-bottom: 1rem;
    color: #fff;
  }

  .skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .tag {
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.1);
    padding: 5px 12px;
    border-radius: 12px;
    font-size: 0.85rem;
    transition: all 0.3s ease;
    cursor: default;
  }

  .tag:hover {
    background: var(--accent-color);
    color: #000;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px var(--glow);
  }

  @media (max-width: 600px) {
    .info-grid { grid-template-columns: 1fr; }
    .name-title { font-size: 2.2rem; }
  }
</style>
