<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Mohamed Slama – GitHub Profile</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Sora:wght@300;400;600;700&display=swap');
  *{box-sizing:border-box;margin:0;padding:0;}
  body{background:#010409;display:flex;justify-content:center;padding:2rem;font-family:'Sora',sans-serif;}
  .wrap{background:#0d1117;max-width:720px;width:100%;min-height:500px;padding:2rem;border-radius:12px;color:#e6edf3;position:relative;overflow:hidden;}
  .grid-bg{position:absolute;inset:0;background-image:linear-gradient(rgba(30,215,96,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(30,215,96,.04) 1px,transparent 1px);background-size:40px 40px;pointer-events:none;}
  .accent{color:#1ed760;}
  .muted{color:#8b949e;font-size:13px;}
  .header{display:flex;align-items:center;gap:1.5rem;margin-bottom:2rem;position:relative;}
  .avatar{width:72px;height:72px;border-radius:50%;background:linear-gradient(135deg,#1ed760,#0d6e35);display:flex;align-items:center;justify-content:center;font-family:'Space Mono',monospace;font-size:22px;font-weight:700;color:#0d1117;flex-shrink:0;box-shadow:0 0 0 3px rgba(30,215,96,.2);}
  .name{font-size:1.5rem;font-weight:700;letter-spacing:-.5px;}
  .role{font-size:13px;color:#8b949e;margin-top:4px;font-family:'Space Mono',monospace;}
  .badge{display:inline-flex;align-items:center;gap:6px;background:rgba(30,215,96,.08);border:1px solid rgba(30,215,96,.25);border-radius:999px;padding:4px 12px;font-size:12px;font-family:'Space Mono',monospace;color:#1ed760;margin-top:8px;}
  .dot{width:7px;height:7px;border-radius:50%;background:#1ed760;animation:pulse 2s infinite;}
  @keyframes pulse{0%,100%{opacity:1;}50%{opacity:.3;}}
  .divider{border:none;border-top:1px solid #21262d;margin:1.5rem 0;}
  .section-label{font-family:'Space Mono',monospace;font-size:11px;color:#8b949e;letter-spacing:2px;text-transform:uppercase;margin-bottom:.75rem;}
  .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px;margin-bottom:1.5rem;}
  .card{background:#161b22;border:1px solid #21262d;border-radius:8px;padding:.85rem 1rem;transition:border-color .2s;}
  .card:hover{border-color:rgba(30,215,96,.3);}
  .card-icon{font-size:18px;margin-bottom:6px;}
  .card-title{font-size:12px;color:#8b949e;margin-bottom:2px;}
  .card-value{font-size:15px;font-weight:600;font-family:'Space Mono',monospace;color:#e6edf3;}
  .skills{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:1.5rem;}
  .skill-pill{background:#161b22;border:1px solid #21262d;border-radius:6px;padding:5px 12px;font-size:12px;font-family:'Space Mono',monospace;color:#e6edf3;display:flex;align-items:center;gap:6px;}
  .skill-pill span{color:#1ed760;}
  .contact-row{display:flex;gap:10px;flex-wrap:wrap;}
  .contact-btn{display:inline-flex;align-items:center;gap:8px;background:#161b22;border:1px solid #21262d;border-radius:8px;padding:8px 16px;font-size:13px;color:#e6edf3;text-decoration:none;font-family:'Sora',sans-serif;cursor:pointer;transition:all .2s;}
  .contact-btn:hover{border-color:rgba(30,215,96,.4);color:#1ed760;}
  .stats-row{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:1.5rem;}
  .stat-bar-wrap{background:#161b22;border:1px solid #21262d;border-radius:8px;padding:.85rem 1rem;}
  .bar-label{display:flex;justify-content:space-between;font-size:12px;margin-bottom:6px;}
  .bar-label span:first-child{color:#8b949e;}
  .bar-label span:last-child{color:#1ed760;font-family:'Space Mono',monospace;}
  .bar-track{background:#21262d;border-radius:999px;height:5px;overflow:hidden;}
  .bar-fill{height:100%;border-radius:999px;background:linear-gradient(90deg,#1ed760,#0d8a45);}
</style>
</head>
<body>
<div class="wrap">
  <div class="grid-bg"></div>
  <div class="header">
    <div class="avatar">MS</div>
    <div>
      <div class="name">Mohamed Slama</div>
      <div class="role">// flutter developer</div>
      <div class="badge"><span class="dot"></span> open to internships</div>
    </div>
    <div style="margin-left:auto;text-align:right;">
      <img src="https://komarev.com/ghpvc/?username=slama-mohamed&color=1ed760&style=flat&label=views" alt="views" style="border-radius:4px;opacity:.8;" />
    </div>
  </div>

  <hr class="divider"/>

  <div class="section-label">Tech stack</div>
  <div class="skills">
    <div class="skill-pill"><span>■</span> Flutter</div>
    <div class="skill-pill"><span>■</span> Dart</div>
    <div class="skill-pill"><span>■</span> Firebase</div>
    <div class="skill-pill"><span>■</span> REST APIs</div>
    <div class="skill-pill"><span>■</span> Git</div>
    <div class="skill-pill"><span>■</span> BLoC / Riverpod</div>
  </div>

  <div class="section-label">Language breakdown</div>
  <div class="stats-row">
    <div class="stat-bar-wrap">
      <div class="bar-label"><span>Dart</span><span>68%</span></div>
      <div class="bar-track"><div class="bar-fill" style="width:68%;"></div></div>
    </div>
    <div class="stat-bar-wrap">
      <div class="bar-label"><span>Flutter</span><span>20%</span></div>
      <div class="bar-track"><div class="bar-fill" style="width:20%;opacity:.75;"></div></div>
    </div>
    <div class="stat-bar-wrap">
      <div class="bar-label"><span>Python</span><span>8%</span></div>
      <div class="bar-track"><div class="bar-fill" style="width:8%;opacity:.5;"></div></div>
    </div>
    <div class="stat-bar-wrap">
      <div class="bar-label"><span>Other</span><span>4%</span></div>
      <div class="bar-track"><div class="bar-fill" style="width:4%;opacity:.35;"></div></div>
    </div>
  </div>

  <div class="section-label">Currently</div>
  <div class="cards">
    <div class="card">
      <div class="card-icon">📱</div>
      <div class="card-title">learning</div>
      <div class="card-value" style="color:#1ed760;">Flutter</div>
    </div>
    <div class="card">
      <div class="card-icon">🌍</div>
      <div class="card-title">based in</div>
      <div class="card-value">Tunisia</div>
    </div>
    <div class="card">
      <div class="card-icon">🎯</div>
      <div class="card-title">goal</div>
      <div class="card-value">Internship</div>
    </div>
  </div>

  <hr class="divider"/>

  <div class="section-label">Get in touch</div>
  <div class="contact-row">
    <a class="contact-btn" href="mailto:mohamed.slama.dev@gmail.com">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="4" width="20" height="16" rx="2"/><polyline points="2,4 12,13 22,4"/></svg>
      mohamed.slama.dev@gmail.com
    </a>
    <a class="contact-btn" href="https://www.linkedin.com/in/mohamed-slama-4677a5323" target="_blank">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
      LinkedIn
    </a>
  </div>
</div>
</body>
</html>
