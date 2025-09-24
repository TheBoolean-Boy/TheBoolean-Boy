<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>GitHub Profile • Saswat</title>
  <meta name="description" content="Clean minimal GitHub profile readme — RAG pipelines, AI agents & full‑stack web apps." />
  <style>
    :root{
      --bg:#0b0b0c; /* almost black */
      --panel:#0f1720; /* dark gray */
      --muted:#9ca3af; /* gray for icons */
      --text:#ffffff; /* white labels */
      --sub:#cbd5e1; /* light gray text */
      --radius:14px;
      --glass: rgba(255,255,255,0.03);
      --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", "Helvetica Neue", monospace;
      --ui: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      background:linear-gradient(180deg,var(--bg),#050506 120%);
      color:var(--sub);
      font-family:var(--ui);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;align-items:center;justify-content:center;padding:40px;
    }
    .card{
      width:min(880px,96%);
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.04);
      border-radius:var(--radius);
      padding:28px;
      box-shadow:0 6px 30px rgba(2,6,23,0.6);
      display:grid;grid-template-columns: 1fr 360px;gap:24px;align-items:start;
      backdrop-filter: blur(6px) saturate(1.06);
    }
    .left{
      padding-right:8px;
    }
    header h1{
      margin:0;font-size:20px;color:var(--text);font-weight:700;letter-spacing:-0.2px;
    }
    header p.role{margin:8px 0 18px;color:var(--sub);font-size:13px}
    p.bio{line-height:1.6;color:var(--sub);margin:0 0 18px}
    .badges{display:flex;gap:8px;flex-wrap:wrap}
    .pill{background:var(--glass);border-radius:999px;padding:6px 10px;font-size:12px;color:var(--sub);border:1px solid rgba(255,255,255,0.02)}
    .tech-grid{
      margin-top:18px;display:grid;grid-template-columns:repeat(3, minmax(0,1fr));gap:12px
    }
    .tech{display:flex;gap:12px;align-items:center;padding:12px;border-radius:10px;background:transparent;border:1px solid rgba(255,255,255,0.02)}
    .tech img{width:28px;height:28px;filter:grayscale(100%);opacity:0.95}
    .tech span{font-weight:700;color:var(--text);font-size:13px}
    /* right column */
    .meta{
      padding:10px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03);
      height:100%;display:flex;flex-direction:column;gap:12px;align-items:stretch;justify-content:flex-start
    }
    .avatar{display:flex;gap:12px;align-items:center}
    .avatar .pic{width:72px;height:72px;border-radius:12px;background:linear-gradient(135deg,#111114,#0b0b0c);display:flex;align-items:center;justify-content:center;font-family:var(--mono);color:var(--muted);font-weight:700}
    .avatar .who{display:flex;flex-direction:column}
    .avatar .who b{color:var(--text)}
    .links{display:flex;gap:8px;flex-wrap:wrap}
    .btn{display:inline-flex;gap:8px;align-items:center;padding:8px 10px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:var(--sub);font-size:13px;text-decoration:none}
    .btn svg{width:16px;height:16px;opacity:0.9;filter:grayscale(100%)}
    small.hint{color:var(--muted);display:block;margin-top:6px}
    footer{margin-top:18px;color:var(--muted);font-size:13px}
    /* responsive */
    @media (max-width:880px){
      .card{grid-template-columns:1fr;}
      .meta{order:2}
    }
  </style>
</head>
<body>
  <main class="card" role="main">
    <section class="left">
      <header>
        <h1>Saswat — builder of RAG pipelines, AI agents & full‑stack apps</h1>
        <p class="role">Full‑stack engineer • AI / Retrieval‑Augmented systems • Open to collaborations</p>
      </header>
      <p class="bio">I build Retrieval‑Augmented Generation pipelines, autonomous AI agents, and modern full‑stack web applications. I focus on clean UX, reliable infra, and pragmatic ML integrations.</p>
      <div class="badges">
        <div class="pill">RAG</div>
        <div class="pill">AI agents</div>
        <div class="pill">Full‑stack</div>
        <div class="pill">Open to collab</div>
      </div>
      <h3 style="margin-top:20px;color:var(--text);font-size:14px">Tech stack</h3>
      <div class="tech-grid" aria-hidden="false">
        <!-- Icons pulled from simpleicons.org in neutral grey -->
        <div class="tech"><img src="https://cdn.simpleicons.org/typescript/9ca3af" alt="TypeScript"><span>TypeScript</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/javascript/9ca3af" alt="JavaScript"><span>JavaScript</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/postgresql/9ca3af" alt="Postgres"><span>Postgres</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/langchain/9ca3af" alt="LangChain"><span>LangChain</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/mongodb/9ca3af" alt="MongoDB"><span>MongoDB</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/node-dot-js/9ca3af" alt="Node.js"><span>Node.js</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/react/9ca3af" alt="React"><span>React</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/express/9ca3af" alt="Express"><span>Express</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/zustand/9ca3af" alt="Zustand"><span>Zustand</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/next-dot-js/9ca3af" alt="Next.js"><span>Next.js</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/vercel/9ca3af" alt="Vercel"><span>Vercel</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/tailwindcss/9ca3af" alt="Tailwind"><span>Tailwind</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/tanstack/9ca3af" alt="TanStack"><span>TanStack</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/cplusplus/9ca3af" alt="C++"><span>C++</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/socket-io/9ca3af" alt="Socket.IO"><span>Socket.IO</span></div>
        <div class="tech"><img src="https://cdn.simpleicons.org/java/9ca3af" alt="Java"><span>Java</span></div>
      </div>
      <footer>
        <small class="hint">Tip: place this HTML as <code>profile.html</code> in a repo or copy into your README as an HTML block. Want a Markdown README version? I can convert it.</small>
      </footer>
    </section>
    <aside class="meta" aria-label="contact and quick links">
      <div class="avatar">
        <div class="pic">SR</div>
        <div class="who">
          <div style="font-size:13px;color:var(--muted)">Hi, I'm</div>
          <div style="font-weight:700;color:var(--text);font-size:15px">Saswat Rath</div>
          <div style="font-size:12px;color:var(--muted);margin-top:6px">Building RAG, agents & web apps</div>
        </div>
      </div>
      <div>
        <div style="font-size:12px;color:var(--muted);margin-bottom:8px">Quick links</div>
        <div class="links">
          <a class="btn" href="https://github.com/" target="_blank" rel="noopener"> <!-- replace with your profile -->
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 .5C5.73.5.75 5.48.75 11.75c0 4.93 3.19 9.11 7.61 10.58.56.1.77-.24.77-.54 0-.26-.01-1.12-.02-2.03-3.09.67-3.74-1.49-3.74-1.49-.5-1.29-1.22-1.63-1.22-1.63-.99-.68.08-.67.08-.67 1.09.08 1.66 1.12 1.66 1.12.97 1.66 2.55 1.18 3.17.9.1-.7.38-1.18.69-1.45-2.47-.28-5.06-1.24-5.06-5.52 0-1.22.43-2.21 1.12-2.99-.11-.28-.49-1.41.11-2.95 0 0 .92-.29 3.02 1.13.88-.24 1.83-.36 2.77-.36.94 0 1.89.12 2.77.36 2.09-1.42 3.01-1.13 3.01-1.13.6 1.54.22 2.67.11 2.95.7.78 1.11 1.77 1.11 2.99 0 4.29-2.6 5.24-5.08 5.52.39.34.73 1.02.73 2.06 0 1.49-.01 2.69-.01 3.05 0 .3.21.65.78.54 4.42-1.47 7.6-5.65 7.6-10.58C23.25 5.48 18.27.5 12 .5z" fill="currentColor"/></svg>
            GitHub
          </a>
          <a class="btn" href="mailto:you@example.com"> <!-- replace -->
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M2 6.5v11A2.5 2.5 0 0 0 4.5 20h15a2.5 2.5 0 0 0 2.5-2.5v-11A2.5 2.5 0 0 0 19.5 4h-15A2.5 2.5 0 0 0 2 6.5z" stroke="currentColor" stroke-width="0" fill="currentColor"/></svg>
            Email
          </a>
          <a class="btn" href="https://vercel.com/" target="_blank" rel="noopener">
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 2 2 22h20L12 2z" fill="currentColor"/></svg>
            Deploy
          </a>
        </div>
      </div>
      <div style="margin-top:6px">
        <div style="font-size:12px;color:var(--muted);margin-bottom:6px">Contact</div>
        <div style="font-size:13px;color:var(--sub)">you@example.com · @your_handle</div>
      </div>
      <div style="margin-top:auto;font-size:12px;color:var(--muted)">Last updated — Sep 24, 2025</div>
    </aside>
  </main>
</body>
</html>
