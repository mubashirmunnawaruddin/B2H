# B2H
B2H Global — A humanitarian-driven blockchain project designed to help the poor through every burn and every transaction. Built with a long-term vision to grow stronger than any coin in existence,  InshaAllah, B2H creates a sustainable, transparent, and community-powered economic system for global impact."
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>B2H — Better2Humanity</title>
  <style>
    body{font-family:Inter,system-ui,Arial,Helvetica,sans-serif;background:#f7fafc;color:#0f172a;margin:0}
    header{background:linear-gradient(90deg,#0ea5a0,#2563eb);color:white;padding:28px 20px;display:flex;align-items:center;gap:18px}
    .logo{display:flex;align-items:center;gap:12px}
    .logo svg{width:64px;height:64px}
    h1{margin:0;font-size:28px}
    .tag{opacity:.95}
    main{max-width:980px;margin:28px auto;padding:16px}
    .card{background:white;border-radius:12px;padding:18px;margin:12px 0;box-shadow:0 6px 20px rgba(12,14,20,0.06)}
    h2{margin:6px 0 12px}
    pre{background:#0f172a;color:#f8fafc;padding:12px;border-radius:8px;overflow:auto}
    footer{font-size:13px;text-align:center;color:#64748b;padding:28px}
    .btn{display:inline-block;background:#0ea5a0;color:white;padding:10px 14px;border-radius:10px;text-decoration:none}
    .two-col{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    @media(max-width:700px){.two-col{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <!-- Inline SVG logo: simple heart + flame representing charity + burn -->
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="B2H logo">
        <defs>
          <linearGradient id="g" x1="0" x2="1">
            <stop offset="0%" stop-color="#ffb84d"/>
            <stop offset="100%" stop-color="#ff4d6d"/>
          </linearGradient>
        </defs>
        <g transform="translate(10,10) scale(0.8)">
          <path d="M40 70c-20-18-32-28-32-40a18 18 0 0 1 36 0 18 18 0 0 1 36 0c0 12-12 22-32 40z" fill="#fff" opacity="0.12"/>
          <path d="M50 16c-6 8-10 9-10 18 0 10 8 15 20 28 12-13 20-18 20-28 0-9-4-10-10-18-6-8-10-6-20 0z" fill="url(#g)"/>
          <circle cx="50" cy="75" r="7" fill="#06b6d4" opacity="0.9"/>
        </g>
      </svg>
      <div>
        <h1>B2H — Better2Humanity</h1>
        <div class="tag">Every burn saves a life • Deflationary charity token • 100-year vision</div>
      </div>
    </div>
  </header>

  <main>
    <section class="card">
      <h2>Quick Facts</h2>
      <div class="two-col">
        <div>
          <strong>Total supply:</strong><br>500,000,000,000 B2H
        </div>
        <div>
          <strong>Chain (first):</strong><br>BNB Smart Chain (BEP-20)
        </div>
      </div>
      <p style="margin-top:12px">Transaction fees (default): <strong>2% burn • 1% charity • 1% treasury</strong>. Buys have minimal/no fee to encourage adoption. Project is designed to be self-sustaining: treasury funds operations, NFTs and marketplace fees feed rewards and the staking pool.</p>
      <p><a class="btn" href="#whitepaper">Download Whitepaper (PDF)</a></p>
    </section>

    <section id="tokenomics" class="card">
      <h2>Tokenomics (Final)</h2>
      <ul>
        <li><strong>Supply:</strong> 500,000,000,000 B2H (fixed)</li>
        <li><strong>Public Supply:</strong> 65% — 325,000,000,000 B2H</li>
        <li><strong>Treasury Reserve:</strong> 35% — 175,000,000,000 B2H (locked)</li>
        <li><strong>Sell Tax:</strong> 4% (2% charity, 2% operations) — selected strategy</li>
        <li><strong>Anti-whale:</strong> max tx 1% default; configurable</li>
      </ul>
      <p>Charity burns are recorded on-chain and cross-linked to off-chain receipts (IPFS). NFTs are minted as donor certificates. The treasury funds long-term operations and future audits/partnerships.</p>
    </section>

    <section id="whitepaper" class="card">
      <h2>Whitepaper — Executive Summary</h2>
      <p><strong>Mission:</strong> Convert blockchain activity into measurable help for the poor and needy by linking token burns to real-world charity events and building a self-sustaining treasury that funds operations forever.</p>

      <h3>Problem</h3>
      <p>Charity and humanitarian aid suffer from lack of transparency, misuse of funds, and limited perpetual funding. Traditional charity models often struggle with administrative overhead and trust.</p>

      <h3>Solution</h3>
      <p>B2H is a deflationary token built to: (1) burn tokens as an expression of impact, (2) route part of economy to verified charity, and (3) sustain operations through a treasury and secondary revenue channels like NFTs and marketplace fees.</p>

      <h3>Architecture</h3>
      <ol>
        <li>Fixed supply BEP-20 token.</li>
        <li>Smart contract enforces fees and routing (burn, charity PDA, treasury PDA).</li>
        <li>Off-chain backend validates charity receipts, pins evidence to IPFS, and triggers verified burns via multisig.</li>
        <li>NFT certificate engine mints public donor receipts (metadata includes evidence URI & burn tx).</li>
        <li>Staking & ecosystem modules funded from treasury and operations wallet.</li>
      </ol>

      <h3>Governance & Trust</h3>
      <p>Multi-sig council (initial 3 signers), a Charity Board to verify events, and a roadmap to transfer governance to a DAO over time. All charity burns and treasury movements will be posted publicly and archived on IPFS.</p>

      <h3>Roadmap (short)</h3>
      <ul>
        <li>Phase 1 — Launch, first burns, basic NGO partners</li>
        <li>Phase 2 — Listing, marketplace, NFT engine</li>
        <li>Phase 3 — Institutional partnerships, government collaboration</li>
        <li>Phase 4 — Perpetual treasury & DAO governance</li>
      </ul>

      <h3>Impact & Metrics</h3>
      <p>Key performance indicators: total tokens burned, number of verified charity events, funds disbursed, people helped, and treasury growth. All KPIs will be visible on the public dashboard.</p>

      <h3>Legal & Compliance</h3>
      <p>We will work with local counsel for charity handling and KYC/AML where required. B2H is designed as an impact-first public good project; it does not promise financial returns.</p>

      <p style="font-size:13px;color:#475569">The full, printable whitepaper PDF is included for download. The website includes a live burn dashboard and donor NFT gallery.</p>
    </section>

    <section class="card">
      <h2>Get Involved</h2>
      <p>Join our community on Telegram and Twitter. If you represent an NGO or government body interested in partnership, please contact us via the site's Contact page.</p>
      <div style="display:flex;gap:10px;flex-wrap:wrap;margin-top:8px">
        <a class="btn" href="#">Telegram</a>
        <a class="btn" href="#">Twitter</a>
        <a class="btn" href="#">Contact</a>
      </div>
    </section>

    <footer class="card">
      <strong>Better2Humanity (B2H)</strong><br>
      Built for impact • Designed for 100 years • InshaAllah
    </footer>
  </main>
</body>
</html>
