
<style>
  @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Syne:wght@700;800&display=swap');
  .gh-root {
    font-family: 'Fira Code', monospace;
    background: #0d1117;
    color: #c9d1d9;
    border-radius: 12px;
    padding: 2rem;
    min-height: 480px;
  }
  .gh-header {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid #21262d;
  }
  .avatar-ring {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    background: linear-gradient(135deg, #58a6ff, #bc8cff, #56d364);
    padding: 3px;
    flex-shrink: 0;
  }
  .avatar-inner {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background: #161b22;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Syne', sans-serif;
    font-size: 22px;
    font-weight: 800;
    color: #fff;
    letter-spacing: -1px;
  }
  .org-name {
    font-family: 'Syne', sans-serif;
    font-size: 26px;
    font-weight: 800;
    color: #ffffff;
    margin: 0 0 4px;
    letter-spacing: -0.5px;
  }
  .org-handle {
    color: #58a6ff;
    font-size: 13px;
    margin: 0 0 8px;
  }
  .org-bio {
    color: #8b949e;
    font-size: 12px;
    margin: 0;
    line-height: 1.6;
  }
  .stats-row {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 12px;
    margin-bottom: 1.5rem;
  }
  .stat-card {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 8px;
    padding: 12px;
    text-align: center;
  }
  .stat-num {
    font-size: 20px;
    font-weight: 600;
    color: #ffffff;
    display: block;
    margin-bottom: 3px;
  }
  .stat-label {
    font-size: 10px;
    color: #6e7681;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
  .section-title {
    font-size: 11px;
    color: #6e7681;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin: 0 0 10px;
  }
  .repos-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
    margin-bottom: 1.5rem;
  }
  .repo-card {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 8px;
    padding: 14px;
    transition: border-color 0.2s;
    cursor: pointer;
  }
  .repo-card:hover {
    border-color: #388bfd;
  }
  .repo-name {
    color: #58a6ff;
    font-size: 13px;
    font-weight: 600;
    margin: 0 0 5px;
  }
  .repo-desc {
    color: #8b949e;
    font-size: 11px;
    margin: 0 0 10px;
    line-height: 1.5;
  }
  .repo-meta {
    display: flex;
    align-items: center;
    gap: 12px;
    font-size: 11px;
    color: #6e7681;
  }
  .lang-dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    display: inline-block;
    margin-right: 4px;
  }
  .members-row {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }
  .member-chip {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 20px;
    padding: 5px 12px 5px 8px;
    display: flex;
    align-items: center;
    gap: 7px;
    font-size: 12px;
    color: #c9d1d9;
  }
  .member-avatar {
    width: 22px;
    height: 22px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 9px;
    font-weight: 600;
    color: #fff;
  }
  .badge {
    display: inline-block;
    background: #1f6feb;
    color: #79c0ff;
    font-size: 10px;
    padding: 2px 8px;
    border-radius: 20px;
    margin-left: 6px;
  }
  .contrib-bar {
    height: 8px;
    background: #21262d;
    border-radius: 4px;
    margin-bottom: 1.5rem;
    overflow: hidden;
    display: flex;
  }
  .contrib-seg {
    height: 100%;
    transition: width 0.5s;
  }
  .top-bar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 6px;
  }
  .topics {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
    margin-top: 8px;
  }
  .topic-tag {
    background: #1c2d3e;
    color: #79c0ff;
    border: 1px solid #1f4a6f;
    border-radius: 20px;
    font-size: 10px;
    padding: 2px 10px;
  }
</style>

<div class="gh-root">
  <div class="gh-header">
    <div class="avatar-ring">
      <div class="avatar-inner">P·F</div>
    </div>
    <div style="flex:1">
      <p class="org-name">The Pro-Fessors <span class="badge">org</span></p>
      <p class="org-handle">@the-pro-fessors</p>
      <p class="org-bio">🎓 Professors who actually ship code. Research-grade quality, production-grade attitude.<br>Building the future of academic software, one commit at a time.</p>
      <div class="topics">
        <span class="topic-tag">research</span>
        <span class="topic-tag">open-source</span>
        <span class="topic-tag">education</span>
        <span class="topic-tag">ai</span>
        <span class="topic-tag">full-stack</span>
      </div>
    </div>
  </div>

  <div class="stats-row">
    <div class="stat-card">
      <span class="stat-num">42</span>
      <span class="stat-label">Repositories</span>
    </div>
    <div class="stat-card">
      <span class="stat-num">12</span>
      <span class="stat-label">Members</span>
    </div>
    <div class="stat-card">
      <span class="stat-num">3.1k</span>
      <span class="stat-label">Stars</span>
    </div>
    <div class="stat-card">
      <span class="stat-num">847</span>
      <span class="stat-label">Commits</span>
    </div>
  </div>

  <p class="section-title">Language breakdown</p>
  <div class="top-bar">
    <span style="font-size:11px; color:#6e7681;">Python · TypeScript · Java · Rust · Other</span>
  </div>
  <div class="contrib-bar">
    <div class="contrib-seg" style="width:38%; background:#3572A5;"></div>
    <div class="contrib-seg" style="width:27%; background:#3178c6;"></div>
    <div class="contrib-seg" style="width:18%; background:#b07219;"></div>
    <div class="contrib-seg" style="width:10%; background:#dea584;"></div>
    <div class="contrib-seg" style="width:7%; background:#333;"></div>
  </div>

  <p class="section-title">Pinned repositories</p>
  <div class="repos-grid">
    <div class="repo-card">
      <p class="repo-name">📚 lecture-gpt</p>
      <p class="repo-desc">AI-powered lecture note summarizer with RAG pipeline and citation tracking</p>
      <div class="repo-meta">
        <span><span class="lang-dot" style="background:#3572A5;"></span>Python</span>
        <span>⭐ 912</span>
        <span>🍴 103</span>
      </div>
    </div>
    <div class="repo-card">
      <p class="repo-name">🔬 research-graph</p>
      <p class="repo-desc">Knowledge graph builder for academic papers — connects concepts across citations</p>
      <div class="repo-meta">
        <span><span class="lang-dot" style="background:#3178c6;"></span>TypeScript</span>
        <span>⭐ 674</span>
        <span>🍴 88</span>
      </div>
    </div>
    <div class="repo-card">
      <p class="repo-name">🎯 gradeflow</p>
      <p class="repo-desc">Automated grading system with rubric engine and plagiarism detection</p>
      <div class="repo-meta">
        <span><span class="lang-dot" style="background:#b07219;"></span>Java</span>
        <span>⭐ 541</span>
        <span>🍴 67</span>
      </div>
    </div>
    <div class="repo-card">
      <p class="repo-name">⚡ syllabus-cli</p>
      <p class="repo-desc">Blazing fast CLI tool to generate and validate course syllabi from YAML configs</p>
      <div class="repo-meta">
        <span><span class="lang-dot" style="background:#dea584;"></span>Rust</span>
        <span>⭐ 389</span>
        <span>🍴 41</span>
      </div>
    </div>
  </div>

  <p class="section-title">Members</p>
  <div class="members-row">
    <div class="member-chip"><div class="member-avatar" style="background:#1f6feb;">김</div>prof-kim</div>
    <div class="member-chip"><div class="member-avatar" style="background:#388bfd;">이</div>dr-lee</div>
    <div class="member-chip"><div class="member-avatar" style="background:#56d364;">박</div>park-phd</div>
    <div class="member-chip"><div class="member-avatar" style="background:#bc8cff;">최</div>choi-labs</div>
    <div class="member-chip"><div class="member-avatar" style="background:#58a6ff;">정</div>j-research</div>
    <div class="member-chip"><div class="member-avatar" style="background:#f78166;">+7</div>and more</div>
  </div>
</div>
