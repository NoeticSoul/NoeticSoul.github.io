:root {
  --bg: #0b1020;
  --bg-soft: #11182d;
  --card: rgba(255, 255, 255, 0.06);
  --card-border: rgba(255, 255, 255, 0.12);
  --text: #eef3ff;
  --muted: #b6bfd9;
  --line: rgba(255, 255, 255, 0.08);
  --accent: #6f8cff;
  --accent-2: #53d3bf;
  --radius: 24px;
  --radius-sm: 18px;
  --shadow: 0 18px 40px rgba(0, 0, 0, 0.22);
  --max: 1180px;
}

* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  color: var(--text);
  line-height: 1.6;
  background:
    radial-gradient(circle at top left, rgba(111, 140, 255, 0.16), transparent 26%),
    radial-gradient(circle at top right, rgba(83, 211, 191, 0.14), transparent 22%),
    linear-gradient(180deg, #090e1b 0%, #0d1326 42%, #0f1730 100%);
}

a { color: inherit; text-decoration: none; }
img { max-width: 100%; display: block; }
.container { width: min(calc(100% - 2rem), var(--max)); margin: 0 auto; }
.muted { color: var(--muted); }
.section { padding: 4.5rem 0; }
.section-tight { padding: 2rem 0 4.5rem; }
.kicker {
  display: inline-flex;
  gap: 0.5rem;
  align-items: center;
  padding: 0.5rem 0.85rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,0.12);
  background: rgba(255,255,255,0.05);
  color: var(--muted);
  font-size: 0.92rem;
}
.grid-2, .grid-3 { display: grid; gap: 1.2rem; }
.grid-2 { grid-template-columns: repeat(2, minmax(0, 1fr)); }
.grid-3 { grid-template-columns: repeat(3, minmax(0, 1fr)); }
.card {
  background: var(--card);
  border: 1px solid var(--card-border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
}
.card-inner { padding: 1.5rem; }
.badge-list, .tag-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
}
.badge, .tag {
  padding: 0.45rem 0.78rem;
  border-radius: 999px;
  font-size: 0.92rem;
}
.badge {
  color: #dfe6ff;
  background: rgba(111, 140, 255, 0.12);
  border: 1px solid rgba(111, 140, 255, 0.26);
}
.tag {
  color: var(--muted);
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.1);
}
.btn-row { display: flex; flex-wrap: wrap; gap: 0.9rem; }
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.6rem;
  padding: 0.95rem 1.2rem;
  border-radius: 14px;
  font-weight: 700;
  border: 1px solid transparent;
  transition: transform 0.18s ease, background 0.18s ease, border-color 0.18s ease;
}
.btn:hover { transform: translateY(-1px); }
.btn-primary {
  color: white;
  background: linear-gradient(135deg, var(--accent), #6578ff);
}
.btn-secondary {
  color: var(--text);
  background: rgba(255,255,255,0.05);
  border-color: rgba(255,255,255,0.12);
}
header.site-header {
  position: sticky;
  top: 0;
  z-index: 40;
  border-bottom: 1px solid var(--line);
  background: rgba(9, 14, 27, 0.8);
  backdrop-filter: blur(14px);
}
.nav-wrap {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 0;
  gap: 1rem;
}
.brand {
  display: flex;
  flex-direction: column;
  gap: 0.1rem;
}
.brand strong { font-size: 1.02rem; }
.brand span { color: var(--muted); font-size: 0.88rem; }
.nav-toggle {
  display: none;
  border: 1px solid rgba(255,255,255,0.12);
  background: transparent;
  color: var(--text);
  border-radius: 12px;
  padding: 0.55rem 0.7rem;
}
.nav-links {
  display: flex;
  align-items: center;
  gap: 0.35rem;
  flex-wrap: wrap;
}
.nav-links a {
  padding: 0.65rem 0.85rem;
  border-radius: 12px;
  color: var(--muted);
  font-weight: 600;
  font-size: 0.96rem;
}
.nav-links a:hover,
.nav-links a.active {
  color: var(--text);
  background: rgba(255,255,255,0.06);
}
.hero {
  padding: 5rem 0 3rem;
}
.hero-grid {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 1.5rem;
  align-items: center;
}
.hero h1,
.page-hero h1 {
  margin: 1rem 0 0;
  font-size: clamp(2.6rem, 4vw, 4.8rem);
  line-height: 1.02;
  letter-spacing: -0.04em;
}
.gradient {
  color: transparent;
  background: linear-gradient(90deg, var(--accent), var(--accent-2));
  -webkit-background-clip: text;
  background-clip: text;
}
.hero p.lead,
.page-hero p.lead {
  margin: 1.25rem 0 0;
  font-size: 1.06rem;
  color: var(--muted);
  max-width: 60ch;
}
.profile-card {
  overflow: hidden;
}
.profile-card img {
  aspect-ratio: 4 / 5;
  object-fit: cover;
  width: 100%;
}
.profile-meta {
  padding: 1.2rem 1.3rem 1.4rem;
}
.profile-meta h2,
.profile-meta p { margin: 0; }
.profile-meta p { color: var(--muted); margin-top: 0.4rem; }
.stat-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}
.stat {
  padding: 1.1rem;
  border-radius: var(--radius-sm);
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.09);
}
.stat strong {
  display: block;
  font-size: 1.2rem;
  margin-bottom: 0.18rem;
}
.section-title {
  margin: 0 0 1rem;
  font-size: clamp(1.7rem, 2.4vw, 2.3rem);
}
.section-copy {
  margin: 0 0 1.4rem;
  color: var(--muted);
  max-width: 70ch;
}
.list-clean {
  list-style: none;
  margin: 0;
  padding: 0;
  display: grid;
  gap: 0.8rem;
}
.list-clean li {
  padding-left: 1.2rem;
  position: relative;
  color: var(--muted);
}
.list-clean li::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.72rem;
  width: 0.42rem;
  height: 0.42rem;
  border-radius: 999px;
  background: linear-gradient(135deg, var(--accent), var(--accent-2));
}
.timeline {
  display: grid;
  gap: 1rem;
}
.timeline-item {
  padding: 1.3rem;
  border-radius: 20px;
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.08);
}
.timeline-top {
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap;
  align-items: center;
}
.timeline-top h3 {
  margin: 0;
  font-size: 1.08rem;
}
.timeline-top .when {
  color: var(--muted);
  font-size: 0.95rem;
}
.timeline-item p { color: var(--muted); }
.skill-group {
  display: grid;
  gap: 0.8rem;
}
.skill-group h3, .info-card h3, .contact-card h3, .project-card h3 {
  margin: 0 0 0.4rem;
  font-size: 1.08rem;
}
.info-card,
.contact-card,
.project-card {
  padding: 1.35rem;
}
.resume-frame {
  width: 100%;
  min-height: 78vh;
  border: 1px solid rgba(255,255,255,0.08);
  border-radius: 18px;
  background: white;
}
.page-hero {
  padding: 3.3rem 0 1rem;
}
footer.site-footer {
  padding: 2rem 0 3rem;
  border-top: 1px solid var(--line);
  color: var(--muted);
}
.footer-row {
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap;
}
.callout {
  padding: 1.15rem 1.2rem;
  border-radius: 18px;
  background: rgba(83, 211, 191, 0.08);
  border: 1px solid rgba(83, 211, 191, 0.16);
}
.contact-links {
  display: grid;
  gap: 0.9rem;
}
.contact-line {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  align-items: center;
  color: var(--muted);
}
.contact-line strong { color: var(--text); }
.hero-note {
  margin-top: 1rem;
  padding: 1rem 1.1rem;
  border-radius: 18px;
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.08);
}
.hero-note p { margin: 0; color: var(--muted); }
@media (max-width: 980px) {
  .hero-grid,
  .grid-2,
  .grid-3 {
    grid-template-columns: 1fr;
  }
}
@media (max-width: 760px) {
  .nav-toggle { display: inline-flex; }
  .nav-links {
    display: none;
    position: absolute;
    top: calc(100% + 0.5rem);
    right: 1rem;
    flex-direction: column;
    align-items: stretch;
    min-width: 240px;
    padding: 0.8rem;
    background: rgba(9, 14, 27, 0.96);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: 16px;
    box-shadow: var(--shadow);
  }
  .nav-links.open { display: flex; }
  .hero { padding-top: 3.5rem; }
  .hero h1, .page-hero h1 { font-size: clamp(2.2rem, 11vw, 3.2rem); }
}
