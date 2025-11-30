# flowfixer.github.io
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>FlowFixer — Fast, Secure Crypto Liquidity</title>
  <meta name="description" content="FlowFixer: Fast, Secure Crypto Liquidity — safe, transparent way to access and convert frozen assets into crypto. Quick results, trusted process, no stress." />
  <style>
    /* Simple, modern hero layout — no external fonts so it runs offline */
    :root{
      --bg:#0f1724; --card:#0b1220; --accent:#7c3aed; --muted:#9aa4b2; --glass: rgba(255,255,255,0.03);
      --radius:14px; --max:1100px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,var(--bg), #071021 120%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:40px 20px;
    }
    .wrap{
      width:100%;
      max-width:var(--max);
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:20px;
      padding:28px;
      display:grid;
      grid-template-columns: 1fr 420px;
      gap:28px;
      box-shadow: 0 8px 30px rgba(2,6,23,0.7);
      align-items:center;
    }
    @media (max-width:920px){
      .wrap{grid-template-columns:1fr; padding:20px}
    }
    .hero{
      padding:14px 8px;
    }
    .kicker{
      display:inline-flex;
      gap:10px;
      align-items:center;
      background:var(--glass);
      padding:6px 10px;
      border-radius:999px;
      color:var(--muted);
      font-size:13px;
      margin-bottom:14px;
      width:max-content;
    }
    .title{
      font-size:28px;
      line-height:1.02;
      margin:0 0 10px 0;
      letter-spacing:-0.3px;
      font-weight:700;
    }
    .subtitle{
      margin:0 0 18px 0;
      color:var(--muted);
      font-size:15px;
      max-width:62ch;
    }
    .features{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
      margin-top:16px;
    }
    .feature{
      display:flex;
      gap:10px;
      align-items:center;
      background: rgba(255,255,255,0.02);
      padding:10px 12px;
      border-radius:12px;
      font-size:14px;
      color:#dbe9ff;
    }
    .feature svg{width:18px;height:18px;flex:0 0 18px}
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:18px;
      box-shadow: inset 0 1px 0 rgba(255,255,255,0.02);
      border: 1px solid rgba(255,255,255,0.03);
    }
    .right{
      display:flex;
      flex-direction:column;
      gap:12px;
    }
    .summary{
      font-size:14px;
      color:var(--muted);
      line-height:1.45;
    }
    .cta{
      display:flex;
      gap:10px;
      margin-top:6px;
    }
    .btn{
      border:0;
      padding:12px 14px;
      border-radius:12px;
      font-weight:600;
      cursor:pointer;
      font-size:15px;
    }
    .btn-primary{
      background: linear-gradient(90deg,var(--accent), #4f46e5);
      color:white;
      box-shadow: 0 10px 30px rgba(124,58,237,0.18);
    }
    .btn-ghost{
      background:transparent;
      color:var(--muted);
      border:1px solid rgba(255,255,255,0.04);
    }
    label{font-size:13px;color:var(--muted);display:block;margin-bottom:6px}
    input[type="email"]{
      width:100%;
      padding:10px 12px;
      border-radius:10px;
      border:1px solid rgba(255,255,255,0.04);
      background:transparent;
      color:inherit;
    }
    .small{
      font-size:13px;color:var(--muted)
    }
    .legal{font-size:12px;color:#93a3b9;margin-top:8px}
    footer{font-size:12px;color:var(--muted);text-align:center;margin-top:18px}
    /* subtle gradient accent line */
    .accent-line{height:6px;border-radius:10px;background:linear-gradient(90deg,#7c3aed 0%, #4f46e5 60%);margin-top:8px}
    /* modal */
    .modal-backdrop{
      position:fixed;inset:0;background:rgba(2,6,23,0.6);display:none;align-items:center;justify-content:center;
    }
    .modal-backdrop.show{display:flex}
    .modal{
      width:clamp(300px, 90vw, 520px);
      background: #071126;
      border-radius:12px;
      padding:18px;
      border:1px solid rgba(255,255,255,0.04);
    }
  </style>
</head>
<body>
  <main class="wrap" role="main" aria-labelledby="site-title">
    <section class="hero">
      <div class="kicker" aria-hidden="true">
        <!-- lock icon -->
        <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M6 10v-2a6 6 0 1112 0v2" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" opacity="0.9"/></svg>
        Trusted solution
      </div>

      <h1 id="site-title" class="title">FlowFixer — Fast, Secure Crypto Liquidity</h1>

      <p class="subtitle" id="hero-copy">
        FlowFixer gives you a safe, transparent way to access and convert frozen assets into cryptocurrency. Quick results, trusted process, no stress—fast, verified liquidity so your funds can flow again.
      </p>

      <div class="features" aria-hidden="false">
        <div class="feature"><svg viewBox="0 0 24 24" fill="none"><path d="M12 2v6" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/><path d="M6 12h12" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/><path d="M4 20h16" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>Lightning fast</div>
        <div class="feature"><svg viewBox="0 0 24 24" fill="none"><path d="M12 11v6" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/><path d="M7 8a5 5 0 0110 0v3" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg>Secure & transparent</div>
        <div class="feature"><svg viewBox="0 0 24 24" fill="none"><path d="M12 5v14" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/><path d="M5 12h14" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg>Instant conversion</div>
      </div>

      <div class="accent-line" aria-hidden="true"></div>

      <div style="margin-top:18px;">
        <button class="btn btn-primary" id="openModal">Get Access</button>
        <button class="btn btn-ghost" id="copyBtn" title="Copy description">Copy blurb</button>
      </div>

      <p class="legal">No upfront guarantees shown here — real service requires KYC and proof of ownership. This demo is UI-only.</p>
    </section>

    <aside class="right card" aria-labelledby="quick-form-title">
      <h3 id="quick-form-title" style="margin:0 0 8px 0">Request a Quote</h3>

      <p class="summary">Submit your email and a short note. We'll email a secure intake link where you can provide wallet details and ownership proof. (Demo: form is client-only.)</p>

      <form id="leadForm" onsubmit="return handleSubmit(event)" aria-label="Request a quote">
        <label for="email">Email</label>
        <input id="email" type="email" placeholder="you@example.com" required />

        <label for="note" style="margin-top:10px">Short note (wallet type / issue)</label>
        <input id="note" type="text" placeholder="e.g. Trust Wallet — frozen transfer" />

        <div style="display:flex;gap:8px;margin-top:12px;align-items:center;">
          <button type="submit" class="btn btn-primary">Request Link</button>
          <button type="button" class="btn btn-ghost" id="learnBtn">Learn more</button>
        </div>
      </form>

      <div style="margin-top:12px;">
        <div class="small"><strong>Secure process:</strong> verification & proof of ownership required.</div>
      </div>
      <footer>© FlowFixer · Designed for demo</footer>
    </aside>
  </main>

  <!-- modal (simple) -->
  <div class="modal-backdrop" id="modal" role="dialog" aria-modal="true" aria-hidden="true">
    <div class="modal card" role="document">
      <h4 style="margin-top:0">Get Access — Demo Form</h4>
      <p class="small">This demo does not send data. In a real deployment the form would POST to a secure backend and trigger a verified intake flow.</p>
      <label for="modal-email">Email</label>
      <input id="modal-email" type="email" placeholder="you@example.com" />
      <div style="display:flex;gap:8px;margin-top:12px;justify-content:flex-end;">
        <button class="btn btn-ghost" id="modalClose">Close</button>
        <button class="btn btn-primary" id="modalSend">Request Link</button>
      </div>
    </div>
  </div>

  <script>
    // Copy the 350-character blurb to clipboard
    const blurb = "FlowFixer gives you a safe, transparent way to access and convert frozen assets into cryptocurrency. Quick results, trusted process, no stress—fast, verified liquidity so your funds can flow again.";
    document.getElementById('copyBtn').addEventListener('click', async () => {
      try {
        await navigator.clipboard.writeText(blurb);
        const b = document.getElementById('copyBtn');
        const old = b.innerText;
        b.innerText = "Copied!";
        setTimeout(()=> b.innerText = old, 1500);
      } catch(e){
        alert("Copy failed. Select the text and copy manually.");
      }
    });

    // Modal open/close
    const modal = document.getElementById('modal');
    document.getElementById('openModal').addEventListener('click', ()=> {
      modal.classList.add('show');
      modal.setAttribute('aria-hidden','false');
      document.getElementById('modal-email').focus();
    });
    document.getElementById('modalClose').addEventListener('click', ()=> {
      modal.classList.remove('show');
      modal.setAttribute('aria-hidden','true');
    });
    document.getElementById('modalSend').addEventListener('click', ()=> {
      // Demo only: show a success state
      document.getElementById('modalClose').click();
      const btn = document.getElementById('openModal');
      const prev = btn.innerText;
      btn.innerText = "Request Sent ✓";
      setTimeout(()=> btn.innerText = prev, 1800);
    });

    // Quick form submit (client-only demo)
    function handleSubmit(e){
      e.preventDefault();
      const email = document.getElementById('email').value.trim();
      const note = document.getElementById('note').value.trim();
      // Basic validation
      if(!email) return alert("Please enter your email.");
      // Show quick UI confirmation (no backend)
      const form = document.getElementById('leadForm');
      form.reset();
      const old = document.querySelector('#leadForm .btn-primary').innerText;
      document.querySelector('#leadForm .btn-primary').innerText = "Link Sent ✓";
      setTimeout(()=> document.querySelector('#leadForm .btn-primary').innerText = old, 1800);
      console.log("DEMO only — would submit:", {email, note});
      return false;
    }

    // Learn more button (demo)
    document.getElementById('learnBtn').addEventListener('click', ()=> {
      alert("In production, this would link to documentation explaining verification, timelines, and security.");
    });

    // Small accessibility: close modal on ESC
    document.addEventListener('keydown', (ev)=> {
      if(ev.key === 'Escape' && modal.classList.contains('show')){
        document.getElementById('modalClose').click();
      }
    });
  </script>
</body>
</html>
