<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- ═══════════════════════════════════════════
       PRIMARY SEO — SWAP: update URL once live
  ════════════════════════════════════════════════ -->

  <title>Studio C Collective | Luxury Interior Design Orlando, FL</title>
  <meta name="description" content="Studio C Collective is Orlando's premier luxury interior design firm specializing in high-end home renovations, new construction, and full furnishings. Serving Orlando, Winter Park, Lake Nona, and surrounding Florida communities." />
  <meta name="keywords" content="luxury interior designer Orlando, interior design Orlando FL, high-end home renovation Orlando, new construction interior design Orlando, luxury furnishings Orlando, interior decorator Orlando Florida, Winter Park interior designer, Lake Nona interior design, full service interior design Florida, custom home design Orlando" />
  <meta name="author" content="Studio C Collective" />
  <meta name="robots" content="index, follow" />
  <link rel="canonical" href="https://www.studioccollective.com/" />

  <!-- ═══════════════════════════════════════════
       OPEN GRAPH — how site looks on social/links
  ════════════════════════════════════════════════ -->

  <meta property="og:type"        content="website" />
  <meta property="og:url"         content="https://www.studioccollective.com/" />
  <meta property="og:title"       content="Studio C Collective | Luxury Interior Design Orlando, FL" />
  <meta property="og:description" content="A boutique, full-service interior design studio crafting luxurious, livable homes for discerning clients across Orlando and Florida." />
  <meta property="og:image"       content="https://www.studioccollective.com/og-image.jpg" />
  <!-- SWAP: replace og:image with a real photo URL once live -->

  <!-- ═══════════════════════════════════════════
       TWITTER CARD
  ════════════════════════════════════════════════ -->

  <meta name="twitter:card"        content="summary_large_image" />
  <meta name="twitter:title"       content="Studio C Collective | Luxury Interior Design Orlando, FL" />
  <meta name="twitter:description" content="Boutique luxury interior design in Orlando, FL. New construction, renovations & full furnishings." />
  <meta name="twitter:image"       content="https://www.studioccollective.com/og-image.jpg" />

  <!-- ═══════════════════════════════════════════
       LOCAL BUSINESS SCHEMA — critical for Google
  ════════════════════════════════════════════════ -->

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "InteriorDesigner",
    "name": "Studio C Collective",
    "description": "Boutique, full-service luxury interior design firm in Orlando, Florida specializing in new construction, high-end home renovations, and complete furnishings projects.",
    "url": "https://www.studioccollective.com",
    "telephone": "+1-407-000-0000",
    "email": "hello@studioccollective.com",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Orlando",
      "addressRegion": "FL",
      "addressCountry": "US"
    },
    "geo": {
      "@type": "GeoCoordinates",
      "latitude": "28.5383",
      "longitude": "-81.3792"
    },
    "areaServed": [
      "Orlando, FL",
      "Winter Park, FL",
      "Lake Nona, FL",
      "Dr. Phillips, FL",
      "Windermere, FL",
      "Celebration, FL",
      "Florida"
    ],
    "serviceType": [
      "Luxury Interior Design",
      "Home Renovation",
      "New Construction Interior Design",
      "Furnishings and Styling",
      "Full Service Interior Design"
    ],
    "priceRange": "$$$",
    "sameAs": [
      "https://www.instagram.com/studioccollective",
      "https://www.pinterest.com/studioccollective"
    ]
  }
  </script>

  <!-- ═══════════════════════════════════════════
       WEBSITE SCHEMA
  ════════════════════════════════════════════════ -->

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "Studio C Collective",
    "url": "https://www.studioccollective.com",
    "potentialAction": {
      "@type": "SearchAction",
      "target": "https://www.studioccollective.com/?s={search_term_string}",
      "query-input": "required name=search_term_string"
    }
  }
  </script>

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet" />

  <style>
    /* ============================================================
       DESIGN TOKENS — edit these to retheme the entire site
    ============================================================ */
    :root {
      --cream:       #F8F5F0;
      --warm-white:  #FDFBF8;
      --charcoal:    #1C1C1A;
      --mid:         #6B6460;
      --light-rule:  #E2DDD8;
      --accent:      #A8967E;
      --serif:       'Cormorant Garamond', Georgia, serif;
      --sans:        'Jost', 'Helvetica Neue', sans-serif;
      --nav-speed:   0.55s;
      --ease:        cubic-bezier(0.76, 0, 0.24, 1);
    }

    /* ============================================================
       RESET & BASE
    ============================================================ */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; font-size: 16px; }

    body {
      background: var(--warm-white);
      color: var(--charcoal);
      font-family: var(--sans);
      font-weight: 300;
      line-height: 1.7;
      overflow-x: hidden;
    }

    img { display: block; width: 100%; height: 100%; object-fit: cover; }
    a   { text-decoration: none; color: inherit; }
    ul  { list-style: none; }

    /* ============================================================
       UTILITY
    ============================================================ */
    .container {
      max-width: 1340px;
      margin: 0 auto;
      padding: 0 48px;
    }
    @media (max-width: 768px) { .container { padding: 0 24px; } }

    .label {
      font-family: var(--sans);
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: var(--mid);
    }

    .serif-xl {
      font-family: var(--serif);
      font-weight: 300;
      line-height: 1.1;
    }

    .rule {
      width: 40px;
      height: 1px;
      background: var(--accent);
      display: block;
    }

    /* ============================================================
       PAGE TRANSITIONS
    ============================================================ */
    .page {
      display: none;
      animation: pageIn 0.6s var(--ease) forwards;
    }
    .page.active { display: block; }

    @keyframes pageIn {
      from { opacity: 0; transform: translateY(18px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    /* ============================================================
       NAV HEADER
    ============================================================ */
    .site-header {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 900;
      padding: 28px 48px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      transition: background 0.4s ease, padding 0.4s ease;
    }
    .site-header.scrolled {
      background: rgba(253, 251, 248, 0.96);
      backdrop-filter: blur(8px);
      padding: 18px 48px;
      border-bottom: 1px solid var(--light-rule);
    }
    @media (max-width: 768px) {
      .site-header, .site-header.scrolled { padding: 20px 24px; }
    }

    /* Logo */
    .logo {
      display: flex;
      flex-direction: column;
      cursor: pointer;
    }
    .logo-wordmark {
      font-family: var(--serif);
      font-size: 16px;
      font-weight: 400;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--charcoal);
      line-height: 1;
    }
    .logo-tagline {
      font-size: 8px;
      font-weight: 400;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--mid);
      margin-top: 4px;
    }

    /* Header right */
    .header-right {
      display: flex;
      align-items: center;
      gap: 40px;
    }

    .header-contact {
      font-size: 9px;
      font-weight: 500;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--charcoal);
      border-bottom: 1px solid var(--charcoal);
      padding-bottom: 1px;
      transition: color 0.3s, border-color 0.3s;
    }
    .header-contact:hover { color: var(--accent); border-color: var(--accent); }

    /* Hamburger */
    .burger {
      display: flex;
      flex-direction: column;
      gap: 6px;
      cursor: pointer;
      padding: 4px;
      background: none;
      border: none;
    }
    .burger span {
      display: block;
      width: 26px;
      height: 1px;
      background: var(--charcoal);
      transition: transform 0.35s var(--ease), opacity 0.35s ease, width 0.35s ease;
      transform-origin: left center;
    }
    .burger.open span:nth-child(1) { transform: rotate(38deg) translateY(-1px); }
    .burger.open span:nth-child(2) { opacity: 0; width: 0; }
    .burger.open span:nth-child(3) { transform: rotate(-38deg) translateY(1px); }

    /* ============================================================
       FULL-SCREEN OVERLAY NAV
    ============================================================ */
    .nav-overlay {
      position: fixed;
      inset: 0;
      background: var(--charcoal);
      z-index: 800;
      display: flex;
      align-items: center;
      justify-content: center;
      clip-path: inset(0 0 100% 0);
      transition: clip-path 0.65s var(--ease);
      pointer-events: none;
    }
    .nav-overlay.open {
      clip-path: inset(0 0 0% 0);
      pointer-events: all;
    }

    .nav-inner {
      text-align: center;
    }

    .nav-links {
      display: flex;
      flex-direction: column;
      gap: 8px;
      margin-bottom: 56px;
    }

    .nav-links a {
      font-family: var(--serif);
      font-size: clamp(36px, 6vw, 64px);
      font-weight: 300;
      color: rgba(255,255,255,0.15);
      letter-spacing: 0.04em;
      transition: color 0.3s ease;
      display: inline-block;
      transform: translateY(30px);
      opacity: 0;
      transition: color 0.3s ease, transform 0.5s var(--ease), opacity 0.5s ease;
    }
    .nav-overlay.open .nav-links a {
      transform: translateY(0);
      opacity: 1;
      color: rgba(255,255,255,0.85);
    }
    .nav-overlay.open .nav-links a:nth-child(1) { transition-delay: 0.1s; }
    .nav-overlay.open .nav-links a:nth-child(2) { transition-delay: 0.16s; }
    .nav-overlay.open .nav-links a:nth-child(3) { transition-delay: 0.22s; }
    .nav-overlay.open .nav-links a:nth-child(4) { transition-delay: 0.28s; }
    .nav-overlay.open .nav-links a:nth-child(5) { transition-delay: 0.34s; }
    .nav-links a:hover { color: #fff; }

    .nav-socials {
      display: flex;
      gap: 32px;
      justify-content: center;
      transform: translateY(20px);
      opacity: 0;
      transition: transform 0.5s var(--ease) 0.4s, opacity 0.5s ease 0.4s;
    }
    .nav-overlay.open .nav-socials { transform: translateY(0); opacity: 1; }

    .nav-socials a {
      font-size: 9px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.45);
      transition: color 0.3s;
    }
    .nav-socials a:hover { color: rgba(255,255,255,0.9); }

    /* ============================================================
       ██ HOME PAGE
    ============================================================ */

    /* Hero */
    .hero {
      height: 100vh;
      min-height: 640px;
      position: relative;
      overflow: hidden;
    }
    .hero-image {
      position: absolute;
      inset: 0;
      /* SWAP IMAGE — replace this URL */
      background: url('https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?w=1800&q=80') center/cover no-repeat;
    }
    .hero-image::after {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(
        to bottom,
        rgba(28,28,26,0.25) 0%,
        rgba(28,28,26,0.1) 40%,
        rgba(28,28,26,0.5) 100%
      );
    }
    .hero-content {
      position: absolute;
      bottom: 80px;
      left: 48px;
      right: 48px;
      color: #fff;
    }
    .hero-content .label { color: rgba(255,255,255,0.6); margin-bottom: 20px; }
    .hero-headline {
      font-family: var(--serif);
      font-size: clamp(42px, 6vw, 88px);
      font-weight: 300;
      font-style: italic;
      line-height: 1.05;
      color: #fff;
      max-width: 700px;
    }
    .hero-cta {
      margin-top: 40px;
      display: inline-flex;
      align-items: center;
      gap: 16px;
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.85);
      transition: gap 0.3s ease;
    }
    .hero-cta::after {
      content: '';
      display: block;
      width: 40px;
      height: 1px;
      background: rgba(255,255,255,0.6);
      transition: width 0.3s ease;
    }
    .hero-cta:hover { gap: 22px; }
    .hero-cta:hover::after { width: 52px; }

    @media (max-width: 768px) {
      .hero-content { bottom: 48px; left: 24px; right: 24px; }
    }

    /* Intro strip */
    .intro-strip {
      background: var(--charcoal);
      padding: 72px 48px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 48px;
    }
    @media (max-width: 768px) {
      .intro-strip { flex-direction: column; padding: 56px 24px; }
    }
    .intro-strip-text {
      font-family: var(--serif);
      font-size: clamp(22px, 3vw, 34px);
      font-weight: 300;
      font-style: italic;
      color: rgba(255,255,255,0.88);
      max-width: 640px;
      line-height: 1.4;
    }
    .intro-strip-link {
      flex-shrink: 0;
      font-size: 9px;
      font-weight: 500;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.5);
      border-bottom: 1px solid rgba(255,255,255,0.25);
      padding-bottom: 2px;
      transition: color 0.3s, border-color 0.3s;
      white-space: nowrap;
    }
    .intro-strip-link:hover { color: rgba(255,255,255,0.9); border-color: rgba(255,255,255,0.6); }

    /* About snapshot */
    .about-snapshot {
      display: grid;
      grid-template-columns: 1fr 1fr;
      min-height: 680px;
    }
    @media (max-width: 900px) { .about-snapshot { grid-template-columns: 1fr; } }

    .about-snap-image {
      /* SWAP IMAGE */
      background: url('https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?w=1200&q=80') center/cover no-repeat;
      min-height: 500px;
    }

    .about-snap-text {
      background: var(--cream);
      padding: 96px 72px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    @media (max-width: 768px) {
      .about-snap-text { padding: 64px 24px; }
    }
    .about-snap-text .label { margin-bottom: 24px; }
    .about-snap-text h2 {
      font-family: var(--serif);
      font-size: clamp(32px, 4vw, 52px);
      font-weight: 300;
      line-height: 1.15;
      margin-bottom: 28px;
    }
    .about-snap-text p {
      font-size: 15px;
      font-weight: 300;
      color: var(--mid);
      max-width: 400px;
      line-height: 1.8;
      margin-bottom: 40px;
    }
    .btn-text {
      display: inline-flex;
      align-items: center;
      gap: 14px;
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: var(--charcoal);
      transition: gap 0.3s ease;
    }
    .btn-text::after {
      content: '';
      display: block;
      width: 32px;
      height: 1px;
      background: var(--charcoal);
      transition: width 0.3s ease;
    }
    .btn-text:hover { gap: 20px; }
    .btn-text:hover::after { width: 48px; }

    /* Portfolio preview */
    .portfolio-preview {
      padding: 120px 48px;
      background: var(--warm-white);
    }
    @media (max-width: 768px) { .portfolio-preview { padding: 80px 24px; } }

    .section-header {
      display: flex;
      align-items: flex-end;
      justify-content: space-between;
      margin-bottom: 56px;
      gap: 24px;
    }
    .section-header h2 {
      font-family: var(--serif);
      font-size: clamp(28px, 4vw, 48px);
      font-weight: 300;
    }

    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(12, 1fr);
      grid-template-rows: auto auto;
      gap: 16px;
    }
    .pg-item {
      overflow: hidden;
      position: relative;
      cursor: pointer;
    }
    .pg-item:nth-child(1) {
      grid-column: 1 / 8;
      aspect-ratio: 4/3;
    }
    .pg-item:nth-child(2) {
      grid-column: 8 / 13;
      aspect-ratio: 3/4;
    }
    .pg-item:nth-child(3) {
      grid-column: 1 / 5;
      aspect-ratio: 3/4;
    }
    .pg-item:nth-child(4) {
      grid-column: 5 / 10;
      aspect-ratio: 4/3;
    }
    .pg-item:nth-child(5) {
      grid-column: 10 / 13;
      aspect-ratio: 4/3;
    }
    @media (max-width: 900px) {
      .pg-item { grid-column: 1 / -1 !important; aspect-ratio: 16/10 !important; }
    }

    .pg-item img {
      transition: transform 0.7s var(--ease);
    }
    .pg-item:hover img { transform: scale(1.04); }

    .pg-caption {
      position: absolute;
      bottom: 0; left: 0; right: 0;
      padding: 24px 20px 18px;
      background: linear-gradient(to top, rgba(28,28,26,0.72) 0%, transparent 100%);
      color: #fff;
      transform: translateY(8px);
      opacity: 0;
      transition: transform 0.4s var(--ease), opacity 0.4s ease;
    }
    .pg-item:hover .pg-caption { transform: translateY(0); opacity: 1; }
    .pg-caption .label { color: rgba(255,255,255,0.55); margin-bottom: 4px; }
    .pg-caption h3 {
      font-family: var(--serif);
      font-size: 20px;
      font-weight: 300;
      font-style: italic;
    }

    /* Process teaser */
    .process-teaser {
      background: var(--cream);
      padding: 120px 48px;
    }
    @media (max-width: 768px) { .process-teaser { padding: 80px 24px; } }

    .process-teaser-inner {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 96px;
      align-items: start;
    }
    @media (max-width: 900px) {
      .process-teaser-inner { grid-template-columns: 1fr; gap: 56px; }
    }

    .process-teaser h2 {
      font-family: var(--serif);
      font-size: clamp(32px, 4vw, 52px);
      font-weight: 300;
      line-height: 1.15;
      margin-bottom: 24px;
    }
    .process-teaser p {
      font-size: 15px;
      color: var(--mid);
      line-height: 1.85;
      margin-bottom: 40px;
      max-width: 420px;
    }

    .steps-list { display: flex; flex-direction: column; gap: 0; }

    .step-item {
      border-top: 1px solid var(--light-rule);
      padding: 22px 0;
      display: flex;
      align-items: center;
      gap: 24px;
      cursor: pointer;
      transition: background 0.2s;
    }
    .step-item:last-child { border-bottom: 1px solid var(--light-rule); }
    .step-num {
      font-family: var(--serif);
      font-size: 13px;
      font-weight: 400;
      color: var(--accent);
      min-width: 28px;
    }
    .step-name {
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      flex: 1;
    }
    .step-arrow {
      width: 20px;
      height: 1px;
      background: var(--light-rule);
      transition: width 0.3s ease, background 0.3s;
    }
    .step-item:hover .step-arrow { width: 32px; background: var(--accent); }

    /* Testimonial strip */
    .testimonial-strip {
      background: var(--charcoal);
      padding: 112px 48px;
      text-align: center;
    }
    @media (max-width: 768px) { .testimonial-strip { padding: 80px 24px; } }

    .testimonial-quote {
      font-family: var(--serif);
      font-size: clamp(20px, 3vw, 32px);
      font-weight: 300;
      font-style: italic;
      color: rgba(255,255,255,0.82);
      max-width: 860px;
      margin: 0 auto 32px;
      line-height: 1.5;
    }
    .testimonial-attr {
      font-size: 9px;
      font-weight: 500;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      color: var(--accent);
    }
    .testimonial-dots {
      display: flex;
      gap: 8px;
      justify-content: center;
      margin-top: 40px;
    }
    .t-dot {
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: rgba(255,255,255,0.2);
      cursor: pointer;
      transition: background 0.3s;
    }
    .t-dot.active { background: var(--accent); }

    /* ============================================================
       ██ ABOUT PAGE
    ============================================================ */
    .page-hero {
      height: 70vh;
      min-height: 500px;
      position: relative;
      overflow: hidden;
    }
    .page-hero-image {
      position: absolute;
      inset: 0;
    }
    .page-hero-image::after {
      content: '';
      position: absolute;
      inset: 0;
      background: rgba(28,28,26,0.38);
    }
    .page-hero-content {
      position: absolute;
      bottom: 72px;
      left: 48px;
      right: 48px;
      color: #fff;
    }
    .page-hero-content .label { color: rgba(255,255,255,0.55); margin-bottom: 16px; }
    .page-hero-content h1 {
      font-family: var(--serif);
      font-size: clamp(40px, 6vw, 80px);
      font-weight: 300;
      font-style: italic;
      line-height: 1.05;
    }
    @media (max-width: 768px) {
      .page-hero-content { bottom: 40px; left: 24px; right: 24px; }
    }

    .about-bio {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0;
    }
    @media (max-width: 900px) { .about-bio { grid-template-columns: 1fr; } }

    .about-bio-image {
      /* SWAP IMAGE */
      background: url('https://images.unsplash.com/photo-1567538096630-e0c55bd6374c?w=1000&q=80') center/cover no-repeat;
      min-height: 600px;
    }
    .about-bio-text {
      padding: 96px 80px;
      background: var(--warm-white);
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    @media (max-width: 768px) {
      .about-bio-text { padding: 64px 24px; }
    }
    .about-bio-text .label { margin-bottom: 20px; }
    .about-bio-text h2 {
      font-family: var(--serif);
      font-size: clamp(28px, 3.5vw, 44px);
      font-weight: 300;
      margin-bottom: 28px;
      line-height: 1.2;
    }
    .about-bio-text p {
      font-size: 15px;
      font-weight: 300;
      color: var(--mid);
      line-height: 1.85;
      margin-bottom: 20px;
    }
    .about-bio-text p:last-of-type { margin-bottom: 40px; }

    .values-section {
      background: var(--cream);
      padding: 120px 48px;
    }
    @media (max-width: 768px) { .values-section { padding: 80px 24px; } }

    .values-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 64px;
      margin-top: 72px;
    }
    @media (max-width: 900px) {
      .values-grid { grid-template-columns: 1fr; gap: 40px; }
    }
    .value-card .rule { margin-bottom: 24px; }
    .value-card h3 {
      font-family: var(--serif);
      font-size: 24px;
      font-weight: 400;
      margin-bottom: 14px;
    }
    .value-card p {
      font-size: 14px;
      color: var(--mid);
      line-height: 1.85;
    }

    /* ============================================================
       ██ SERVICES PAGE
    ============================================================ */
    .services-intro {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0;
      min-height: 620px;
    }
    @media (max-width: 900px) { .services-intro { grid-template-columns: 1fr; } }

    .services-intro-text {
      padding: 96px 80px;
      background: var(--warm-white);
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    @media (max-width: 768px) {
      .services-intro-text { padding: 64px 24px; }
    }
    .services-intro-text .label { margin-bottom: 24px; }
    .services-intro-text h2 {
      font-family: var(--serif);
      font-size: clamp(30px, 4vw, 52px);
      font-weight: 300;
      line-height: 1.15;
      margin-bottom: 28px;
    }
    .services-intro-text p {
      font-size: 15px;
      color: var(--mid);
      line-height: 1.85;
      margin-bottom: 20px;
      max-width: 440px;
    }
    .services-intro-text p:last-of-type { margin-bottom: 40px; }
    .services-intro-image {
      /* SWAP IMAGE */
      background: url('https://images.unsplash.com/photo-1631679706909-1844bbd07221?w=1200&q=80') center/cover no-repeat;
      min-height: 500px;
    }

    /* Process accordion */
    .process-section {
      background: var(--cream);
      padding: 120px 48px;
    }
    @media (max-width: 768px) { .process-section { padding: 80px 24px; } }

    .process-section h2 {
      font-family: var(--serif);
      font-size: clamp(28px, 4vw, 48px);
      font-weight: 300;
      margin-bottom: 64px;
    }

    .accordion { max-width: 860px; }
    .accordion-item { border-top: 1px solid var(--light-rule); }
    .accordion-item:last-child { border-bottom: 1px solid var(--light-rule); }

    .accordion-btn {
      width: 100%;
      background: none;
      border: none;
      padding: 28px 0;
      display: flex;
      align-items: center;
      gap: 24px;
      cursor: pointer;
      text-align: left;
    }
    .accordion-num {
      font-family: var(--serif);
      font-size: 14px;
      color: var(--accent);
      min-width: 32px;
    }
    .accordion-title {
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      flex: 1;
      color: var(--charcoal);
    }
    .accordion-icon {
      width: 20px;
      height: 20px;
      position: relative;
    }
    .accordion-icon::before,
    .accordion-icon::after {
      content: '';
      position: absolute;
      top: 50%; left: 50%;
      background: var(--charcoal);
      transition: transform 0.35s var(--ease), opacity 0.35s ease;
    }
    .accordion-icon::before { width: 1px; height: 14px; transform: translate(-50%, -50%); }
    .accordion-icon::after  { width: 14px; height: 1px; transform: translate(-50%, -50%); }
    .accordion-item.open .accordion-icon::before { transform: translate(-50%, -50%) rotate(90deg); opacity: 0; }

    .accordion-body {
      display: grid;
      grid-template-rows: 0fr;
      transition: grid-template-rows 0.4s var(--ease);
    }
    .accordion-item.open .accordion-body { grid-template-rows: 1fr; }
    .accordion-body-inner {
      overflow: hidden;
      padding: 0 0 0 56px;
    }
    .accordion-body-inner p {
      font-size: 15px;
      color: var(--mid);
      line-height: 1.85;
      padding-bottom: 28px;
      max-width: 560px;
    }

    /* Included services */
    .included-section {
      padding: 120px 48px;
      background: var(--warm-white);
    }
    @media (max-width: 768px) { .included-section { padding: 80px 24px; } }

    .included-section h2 {
      font-family: var(--serif);
      font-size: clamp(28px, 4vw, 48px);
      font-weight: 300;
      margin-bottom: 16px;
    }
    .included-section > p {
      font-size: 15px;
      color: var(--mid);
      max-width: 560px;
      line-height: 1.85;
      margin-bottom: 56px;
    }
    .included-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 0;
      max-width: 640px;
    }
    @media (max-width: 600px) { .included-grid { grid-template-columns: 1fr; } }
    .included-item {
      padding: 18px 0;
      border-bottom: 1px solid var(--light-rule);
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: var(--charcoal);
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .included-item::before {
      content: '';
      display: block;
      width: 4px;
      height: 4px;
      border-radius: 50%;
      background: var(--accent);
      flex-shrink: 0;
    }

    /* ============================================================
       ██ PORTFOLIO PAGE
    ============================================================ */
    .portfolio-page {
      padding: 140px 48px 120px;
      background: var(--warm-white);
    }
    @media (max-width: 768px) { .portfolio-page { padding: 120px 24px 80px; } }

    .portfolio-page h1 {
      font-family: var(--serif);
      font-size: clamp(36px, 5vw, 64px);
      font-weight: 300;
      font-style: italic;
      margin-bottom: 16px;
    }
    .portfolio-page > p {
      font-size: 15px;
      color: var(--mid);
      max-width: 480px;
      margin-bottom: 72px;
      line-height: 1.85;
    }
    .portfolio-full-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 24px;
    }
    @media (max-width: 768px) { .portfolio-full-grid { grid-template-columns: 1fr; } }

    .pf-card {
      overflow: hidden;
      cursor: pointer;
      position: relative;
    }
    .pf-card:nth-child(odd) { margin-top: 0; }
    .pf-card:nth-child(even) { margin-top: 48px; }
    @media (max-width: 768px) { .pf-card:nth-child(even) { margin-top: 0; } }

    .pf-card-img {
      aspect-ratio: 4/5;
      overflow: hidden;
    }
    .pf-card-img img {
      transition: transform 0.8s var(--ease);
    }
    .pf-card:hover .pf-card-img img { transform: scale(1.05); }

    .pf-card-info {
      padding: 20px 0 32px;
    }
    .pf-card-info .label { margin-bottom: 8px; }
    .pf-card-info h3 {
      font-family: var(--serif);
      font-size: 26px;
      font-weight: 300;
      font-style: italic;
    }

    /* ============================================================
       ██ CONTACT PAGE
    ============================================================ */
    .contact-page {
      display: grid;
      grid-template-columns: 1fr 1fr;
      min-height: calc(100vh - 200px);
    }
    @media (max-width: 900px) { .contact-page { grid-template-columns: 1fr; } }

    .contact-info {
      background: var(--cream);
      padding: 140px 80px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    @media (max-width: 768px) { .contact-info { padding: 120px 24px 64px; } }

    .contact-info .label { margin-bottom: 24px; }
    .contact-info h1 {
      font-family: var(--serif);
      font-size: clamp(32px, 4vw, 56px);
      font-weight: 300;
      font-style: italic;
      line-height: 1.1;
      margin-bottom: 28px;
    }
    .contact-info p {
      font-size: 15px;
      color: var(--mid);
      line-height: 1.85;
      max-width: 380px;
      margin-bottom: 48px;
    }
    .contact-details { display: flex; flex-direction: column; gap: 20px; }
    .contact-detail-item { display: flex; flex-direction: column; gap: 4px; }
    .contact-detail-item .label { color: var(--charcoal); }
    .contact-detail-item span {
      font-family: var(--serif);
      font-size: 17px;
      font-weight: 400;
      color: var(--mid);
    }

    .contact-form-wrap {
      background: var(--charcoal);
      padding: 140px 80px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    @media (max-width: 768px) { .contact-form-wrap { padding: 64px 24px; } }

    .contact-form-wrap h2 {
      font-family: var(--serif);
      font-size: 32px;
      font-weight: 300;
      color: rgba(255,255,255,0.85);
      margin-bottom: 40px;
    }

    .form-group { margin-bottom: 28px; }
    .form-group label {
      display: block;
      font-size: 9px;
      font-weight: 500;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.4);
      margin-bottom: 10px;
    }
    .form-group input,
    .form-group select,
    .form-group textarea {
      width: 100%;
      background: rgba(255,255,255,0.06);
      border: none;
      border-bottom: 1px solid rgba(255,255,255,0.18);
      padding: 12px 0;
      font-family: var(--sans);
      font-size: 14px;
      font-weight: 300;
      color: rgba(255,255,255,0.85);
      outline: none;
      transition: border-color 0.3s;
      appearance: none;
    }
    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus { border-bottom-color: var(--accent); }
    .form-group textarea { resize: none; min-height: 100px; }
    .form-group select option { background: var(--charcoal); }

    .form-submit {
      margin-top: 40px;
      background: none;
      border: 1px solid rgba(255,255,255,0.25);
      padding: 16px 40px;
      font-family: var(--sans);
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.8);
      cursor: pointer;
      transition: background 0.3s, color 0.3s, border-color 0.3s;
    }
    .form-submit:hover {
      background: rgba(255,255,255,0.08);
      border-color: rgba(255,255,255,0.5);
      color: #fff;
    }

    /* ============================================================
       TESTIMONIALS (shared)
    ============================================================ */
    .testimonials-full {
      background: var(--cream);
      padding: 120px 48px;
    }
    @media (max-width: 768px) { .testimonials-full { padding: 80px 24px; } }

    .testimonials-full h2 {
      font-family: var(--serif);
      font-size: clamp(28px, 4vw, 48px);
      font-weight: 300;
      margin-bottom: 64px;
    }
    .testimonials-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 40px;
    }
    @media (max-width: 900px) { .testimonials-grid { grid-template-columns: 1fr; } }

    .t-card { border-top: 1px solid var(--light-rule); padding-top: 32px; }
    .t-card-quote {
      font-family: var(--serif);
      font-size: 18px;
      font-weight: 300;
      font-style: italic;
      color: var(--charcoal);
      line-height: 1.6;
      margin-bottom: 24px;
    }
    .t-card-attr {
      font-size: 9px;
      font-weight: 500;
      letter-spacing: 0.24em;
      text-transform: uppercase;
      color: var(--accent);
    }

    /* ============================================================
       FOOTER
    ============================================================ */
    .site-footer {
      background: var(--charcoal);
      padding: 80px 48px 40px;
    }
    @media (max-width: 768px) { .site-footer { padding: 64px 24px 32px; } }

    .footer-top {
      display: grid;
      grid-template-columns: 1fr auto 1fr;
      gap: 48px;
      align-items: start;
      padding-bottom: 64px;
      border-bottom: 1px solid rgba(255,255,255,0.08);
      margin-bottom: 40px;
    }
    @media (max-width: 900px) {
      .footer-top { grid-template-columns: 1fr; gap: 40px; }
    }

    .footer-brand { }
    .footer-logo {
      font-family: var(--serif);
      font-size: 22px;
      font-weight: 400;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.85);
      margin-bottom: 14px;
    }
    .footer-tagline {
      font-size: 11px;
      color: rgba(255,255,255,0.35);
      letter-spacing: 0.1em;
      line-height: 1.7;
      max-width: 280px;
    }

    .footer-nav {
      display: flex;
      flex-direction: column;
      gap: 14px;
      align-items: center;
    }
    .footer-nav a {
      font-size: 9px;
      font-weight: 500;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.4);
      transition: color 0.3s;
    }
    .footer-nav a:hover { color: rgba(255,255,255,0.9); }

    .footer-contact { text-align: right; }
    @media (max-width: 900px) { .footer-contact { text-align: left; } }
    .footer-contact p {
      font-size: 11px;
      color: rgba(255,255,255,0.35);
      letter-spacing: 0.08em;
      line-height: 1.7;
    }
    .footer-contact a {
      color: rgba(255,255,255,0.55);
      transition: color 0.3s;
    }
    .footer-contact a:hover { color: rgba(255,255,255,0.9); }

    .footer-bottom {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px;
      flex-wrap: wrap;
    }
    .footer-copy {
      font-size: 9px;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.2);
    }
    .footer-legal {
      display: flex;
      gap: 24px;
    }
    .footer-legal a {
      font-size: 9px;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.2);
      transition: color 0.3s;
    }
    .footer-legal a:hover { color: rgba(255,255,255,0.5); }

    /* ============================================================
       CTA BAND
    ============================================================ */
    .cta-band {
      background: var(--accent);
      padding: 80px 48px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 40px;
      flex-wrap: wrap;
    }
    @media (max-width: 768px) { .cta-band { padding: 64px 24px; } }

    .cta-band h2 {
      font-family: var(--serif);
      font-size: clamp(26px, 4vw, 44px);
      font-weight: 300;
      font-style: italic;
      color: #fff;
      max-width: 540px;
    }
    .btn-light {
      flex-shrink: 0;
      display: inline-flex;
      align-items: center;
      gap: 14px;
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: #fff;
      border: 1px solid rgba(255,255,255,0.6);
      padding: 16px 36px;
      transition: background 0.3s, border-color 0.3s;
    }
    .btn-light:hover { background: rgba(255,255,255,0.12); border-color: #fff; }

    /* ============================================================
       SCROLL FADE-IN ANIMATION
    ============================================================ */
    .reveal {
      opacity: 0;
      transform: translateY(28px);
      transition: opacity 0.7s ease, transform 0.7s var(--ease);
    }
    .reveal.visible { opacity: 1; transform: translateY(0); }
    .reveal-delay-1 { transition-delay: 0.1s; }
    .reveal-delay-2 { transition-delay: 0.2s; }
    .reveal-delay-3 { transition-delay: 0.3s; }
    .reveal-delay-4 { transition-delay: 0.4s; }

    /* ============================================================
       PAGE-SPECIFIC HERO BG SWAPS
    ============================================================ */
    #about-page    .page-hero-image { background: url('https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?w=1800&q=80') center/cover no-repeat; }
    #services-page .page-hero-image { background: url('https://images.unsplash.com/photo-1631679706909-1844bbd07221?w=1800&q=80') center/cover no-repeat; }
    #portfolio-page-hero             { background: url('https://images.unsplash.com/photo-1600210492493-0946911123ea?w=1800&q=80') center/cover no-repeat; }
  </style>

</head>

<body>

  <!-- ═══════════════ OVERLAY NAV ═══════════════ -->

  <nav class="nav-overlay" id="navOverlay">
    <div class="nav-inner">
      <ul class="nav-links">
        <li><a href="#" onclick="showPage('home')">Home</a></li>
        <li><a href="#" onclick="showPage('about')">About</a></li>
        <li><a href="#" onclick="showPage('services')">Services</a></li>
        <li><a href="#" onclick="showPage('portfolio')">Portfolio</a></li>
        <li><a href="#" onclick="showPage('contact')">Contact</a></li>
      </ul>
      <div class="nav-socials">
        <a href="#">Instagram</a>
        <a href="#">Pinterest</a>
        <a href="#">Email</a>
      </div>
    </div>
  </nav>

  <!-- ═══════════════ HEADER ═══════════════ -->

  <header class="site-header" id="siteHeader">
    <div class="logo" onclick="showPage('home')">
      <!-- SWAP LOGO — replace text or add <img> tag -->
      <span class="logo-wordmark">Studio C Collective</span>
      <span class="logo-tagline">Interior Design</span>
    </div>
    <div class="header-right">
      <a href="#" class="header-contact" onclick="showPage('contact')">Contact</a>
      <button class="burger" id="burgerBtn" aria-label="Menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <!-- ═══════════════════════════════════════════
       HOME PAGE
  ════════════════════════════════════════════════ -->

  <div id="home-page" class="page active">

```
<!-- HERO -->
<section class="hero">
  <div class="hero-image"></div>
  <div class="hero-content">
    <p class="label">Luxury Interior Design · Orlando, FL</p>
    <h1 class="hero-headline">Interiors that feel<br>as beautiful as<br>they look.</h1>
    <a href="#" class="hero-cta" onclick="showPage('portfolio')">View Our Work</a>
  </div>
</section>

<!-- INTRO STRIP -->
<div class="intro-strip reveal">
  <p class="intro-strip-text">A boutique studio crafting luxurious, livable spaces for discerning clients across the country.</p>
  <a href="#" class="intro-strip-link" onclick="showPage('about')">About the Studio</a>
</div>

<!-- ABOUT SNAPSHOT -->
<section class="about-snapshot">
  <div class="about-snap-image"></div>
  <div class="about-snap-text">
    <p class="label reveal">The Studio</p>
    <h2 class="reveal reveal-delay-1">Where restraint<br>meets richness.</h2>
    <p class="reveal reveal-delay-2">Studio C Collective is a boutique, full-service interior design firm based in Orlando, Florida, specializing in luxury new construction homes, large-scale renovations, and complete furnishings projects for discerning clients across Central Florida and beyond.</p>
    <a href="#" class="btn-text reveal reveal-delay-3" onclick="showPage('about')">Our Story</a>
  </div>
</section>

<!-- PORTFOLIO PREVIEW -->
<section class="portfolio-preview">
  <div class="section-header reveal">
    <h2>Select Work</h2>
    <a href="#" class="btn-text" onclick="showPage('portfolio')">View All Projects</a>
  </div>
  <div class="portfolio-grid">
    <div class="pg-item reveal">
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=1200&q=80" alt="Luxury living room interior design Orlando FL by Studio C Collective" loading="lazy" />
      <div class="pg-caption">
        <p class="label">Residential · 2024</p>
        <h3>The Haverford Residence</h3>
      </div>
    </div>
    <div class="pg-item reveal reveal-delay-1">
      <img src="https://images.unsplash.com/photo-1615529182904-14819c35db37?w=800&q=80" alt="High-end bedroom renovation Orlando Florida" loading="lazy" />
      <div class="pg-caption">
        <p class="label">Renovation · 2024</p>
        <h3>Casa Del Sol</h3>
      </div>
    </div>
    <div class="pg-item reveal">
      <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?w=800&q=80" alt="Custom luxury kitchen new construction Orlando FL" loading="lazy" />
      <div class="pg-caption">
        <p class="label">New Build · 2023</p>
        <h3>The Meridian</h3>
      </div>
    </div>
    <div class="pg-item reveal reveal-delay-1">
      <img src="https://images.unsplash.com/photo-1617806118233-18e1de247200?w=1000&q=80" alt="Luxury dining room furnishings and styling Orlando" loading="lazy" />
      <div class="pg-caption">
        <p class="label">Furnishings · 2023</p>
        <h3>Alderton Park Estate</h3>
      </div>
    </div>
    <div class="pg-item reveal reveal-delay-2">
      <img src="https://images.unsplash.com/photo-1586023492125-27b2c045efd7?w=800&q=80" alt="Custom home study interior design Central Florida" loading="lazy" />
      <div class="pg-caption">
        <p class="label">Residential · 2023</p>
        <h3>The Willow Study</h3>
      </div>
    </div>
  </div>
</section>

<!-- PROCESS TEASER -->
<section class="process-teaser">
  <div class="process-teaser-inner">
    <div>
      <p class="label reveal">Our Approach</p>
      <h2 class="reveal reveal-delay-1">A considered process from first call to final styling.</h2>
      <p class="reveal reveal-delay-2">We guide every client through a clear, collaborative process — removing uncertainty and ensuring that each decision reflects your lifestyle and vision.</p>
      <a href="#" class="btn-text reveal reveal-delay-3" onclick="showPage('services')">Explore Services</a>
    </div>
    <ul class="steps-list reveal reveal-delay-1">
      <li class="step-item"><span class="step-num">01</span><span class="step-name">Onboarding &amp; Consultation</span><span class="step-arrow"></span></li>
      <li class="step-item"><span class="step-num">02</span><span class="step-name">Design Development</span><span class="step-arrow"></span></li>
      <li class="step-item"><span class="step-num">03</span><span class="step-name">Ordering &amp; Procurement</span><span class="step-arrow"></span></li>
      <li class="step-item"><span class="step-num">04</span><span class="step-name">Project Management</span><span class="step-arrow"></span></li>
      <li class="step-item"><span class="step-num">05</span><span class="step-name">Install &amp; Final Styling</span><span class="step-arrow"></span></li>
    </ul>
  </div>
</section>

<!-- TESTIMONIAL STRIP -->
<section class="testimonial-strip">
  <div id="testimonialQuote" class="testimonial-quote">
    "Working with Studio C Collective was a complete transformation — not just of our home, but of how we live in it. Every detail felt intentional."
  </div>
  <p id="testimonialAttr" class="testimonial-attr">Sarah &amp; Marcus V. — The Haverford Residence</p>
  <div class="testimonial-dots">
    <div class="t-dot active" onclick="setTestimonial(0)"></div>
    <div class="t-dot" onclick="setTestimonial(1)"></div>
    <div class="t-dot" onclick="setTestimonial(2)"></div>
  </div>
</section>

<!-- CTA BAND -->
<div class="cta-band">
  <h2>Ready to begin your project?</h2>
  <a href="#" class="btn-light" onclick="showPage('contact')">Start a Conversation</a>
</div>

<!-- FOOTER -->
<footer class="site-footer">
  <div class="footer-top">
    <div class="footer-brand">
      <div class="footer-logo">Studio C Collective</div>
      <p class="footer-tagline">A boutique luxury interior design studio in Orlando, FL creating timeless, livable homes for discerning clients across Central Florida.</p>
    </div>
    <nav class="footer-nav">
      <a href="#" onclick="showPage('home')">Home</a>
      <a href="#" onclick="showPage('about')">About</a>
      <a href="#" onclick="showPage('services')">Services</a>
      <a href="#" onclick="showPage('portfolio')">Portfolio</a>
      <a href="#" onclick="showPage('contact')">Contact</a>
    </nav>
    <div class="footer-contact">
      <p><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="dbb3beb7b7b49ba8afaebfb2b4adbeb7baf5b8b4b6">[email&#160;protected]</a></p>
      <p style="margin-top:8px;">Based in Orlando, FL<br>Working Nationwide</p>
      <p style="margin-top:16px;">
        <a href="#">Instagram</a>&nbsp;&nbsp;·&nbsp;&nbsp;
        <a href="#">Pinterest</a>
      </p>
    </div>
  </div>
  <div class="footer-bottom">
    <p class="footer-copy">© 2025 Studio C Collective. All rights reserved.</p>
    <div class="footer-legal">
      <a href="#">Privacy Policy</a>
      <a href="#">Terms &amp; Conditions</a>
    </div>
  </div>
</footer>
```

  </div>

  <!-- ═══════════════════════════════════════════
       ABOUT PAGE
  ════════════════════════════════════════════════ -->

  <div id="about-page" class="page">
    <section class="page-hero">
      <div class="page-hero-image"></div>
      <div class="page-hero-content">
        <p class="label">The Studio</p>
        <h1>About Studio C Collective</h1>
      </div>
    </section>

```
<section class="about-bio">
  <div class="about-bio-image"></div>
  <div class="about-bio-text">
    <p class="label reveal">Our Founder</p>
    <h2 class="reveal reveal-delay-1">Design rooted in how you actually live.</h2>
    <p class="reveal reveal-delay-2">Studio C Collective was founded on a single belief: that exceptional design should be both beautiful and deeply livable. Based in Orlando, Florida, we serve luxury homeowners across Central Florida — from Winter Park and Lake Nona to Dr. Phillips and Windermere — and beyond.</p>
    <p class="reveal reveal-delay-2">With a background in architecture and a passion for materiality, our principal designer brings a rigorous eye to every project — whether a full new-build, a top-to-bottom renovation, or a complete furnishings package.</p>
    <a href="#" class="btn-text reveal reveal-delay-3" onclick="showPage('contact')">Work With Us</a>
  </div>
</section>

<section class="values-section">
  <p class="label reveal">What We Believe</p>
  <div class="values-grid">
    <div class="value-card reveal">
      <span class="rule"></span>
      <h3>Intention Over Impulse</h3>
      <p>Every selection we make — from stone to sofa — is grounded in a clear design rationale. We don't trend-chase. We build spaces that age gracefully.</p>
    </div>
    <div class="value-card reveal reveal-delay-1">
      <span class="rule"></span>
      <h3>Clarity Through Process</h3>
      <p>Our structured, five-phase process removes uncertainty from what can be an overwhelming experience. You'll always know where we are and what comes next.</p>
    </div>
    <div class="value-card reveal reveal-delay-2">
      <span class="rule"></span>
      <h3>Your Life, Elevated</h3>
      <p>We listen deeply to how you live, who you entertain, and what brings you joy — then design around that truth. The result feels entirely, unmistakably yours.</p>
    </div>
  </div>
</section>

<!-- Testimonials -->
<section class="testimonials-full">
  <h2 class="reveal">Kind Words</h2>
  <div class="testimonials-grid">
    <div class="t-card reveal">
      <p class="t-card-quote">"Studio C Collective transformed our home into something we never thought possible. Their vision, their process, their commitment — all extraordinary."</p>
      <p class="t-card-attr">Jamie &amp; Cole R. — Casa Del Sol</p>
    </div>
    <div class="t-card reveal reveal-delay-1">
      <p class="t-card-quote">"From the first call to the final install, we felt completely cared for. The 3D visualizations alone were worth every penny — nothing was a surprise."</p>
      <p class="t-card-attr">Priya M. — The Meridian</p>
    </div>
    <div class="t-card reveal reveal-delay-2">
      <p class="t-card-quote">"Timely, creative, and genuinely passionate. They understood exactly what we needed before we could even articulate it ourselves."</p>
      <p class="t-card-attr">Thomas &amp; Lydia W. — Alderton Park Estate</p>
    </div>
  </div>
</section>

<div class="cta-band">
  <h2>Let's build something beautiful together.</h2>
  <a href="#" class="btn-light" onclick="showPage('contact')">Get In Touch</a>
</div>

<footer class="site-footer">
  <div class="footer-top">
    <div class="footer-brand">
      <div class="footer-logo">Studio C Collective</div>
      <p class="footer-tagline">A boutique luxury interior design studio in Orlando, FL creating timeless, livable homes for discerning clients across Central Florida.</p>
    </div>
    <nav class="footer-nav">
      <a href="#" onclick="showPage('home')">Home</a>
      <a href="#" onclick="showPage('about')">About</a>
      <a href="#" onclick="showPage('services')">Services</a>
      <a href="#" onclick="showPage('portfolio')">Portfolio</a>
      <a href="#" onclick="showPage('contact')">Contact</a>
    </nav>
    <div class="footer-contact">
      <p><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="90f8f5fcfcffd0e3e4e5f4f9ffe6f5fcf1bef3fffd">[email&#160;protected]</a></p>
    </div>
  </div>
  <div class="footer-bottom">
    <p class="footer-copy">© 2025 Studio C Collective. All rights reserved.</p>
    <div class="footer-legal">
      <a href="#">Privacy Policy</a>
      <a href="#">Terms &amp; Conditions</a>
    </div>
  </div>
</footer>
```

  </div>

  <!-- ═══════════════════════════════════════════
       SERVICES PAGE
  ════════════════════════════════════════════════ -->

  <div id="services-page" class="page">
    <section class="page-hero">
      <div class="page-hero-image"></div>
      <div class="page-hero-content">
        <p class="label">What We Offer</p>
        <h1>Full-Service Design</h1>
      </div>
    </section>

```
<section class="services-intro">
  <div class="services-intro-text">
    <p class="label reveal">Our Philosophy</p>
    <h2 class="reveal reveal-delay-1">Luxurious, timeless,<br>and livable homes.</h2>
    <p class="reveal reveal-delay-2">Studio C Collective focuses on large-scale, full-service projects that bring together construction, architecture, and furnishings for a completely seamless experience.</p>
    <p class="reveal reveal-delay-2">By working closely with our clients and providing expert 3D visualizations at every milestone, we ensure that every choice is intentional and aligned with your life as you actually live it.</p>
    <a href="#" class="btn-text reveal reveal-delay-3" onclick="showPage('contact')">Start a Project</a>
  </div>
  <div class="services-intro-image"></div>
</section>

<!-- PROCESS ACCORDION -->
<section class="process-section">
  <h2 class="reveal">Our Process</h2>
  <div class="accordion">
    <div class="accordion-item open">
      <button class="accordion-btn" onclick="toggleAccordion(this)">
        <span class="accordion-num">01</span>
        <span class="accordion-title">Onboarding &amp; Consultation</span>
        <span class="accordion-icon"></span>
      </button>
      <div class="accordion-body">
        <div class="accordion-body-inner">
          <p>We begin by getting to know you — your vision, lifestyle, and the specific needs of your project. Through an in-depth consultation, we align on goals, budget, and timeline before a single line is drawn.</p>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <button class="accordion-btn" onclick="toggleAccordion(this)">
        <span class="accordion-num">02</span>
        <span class="accordion-title">Design Development</span>
        <span class="accordion-icon"></span>
      </button>
      <div class="accordion-body">
        <div class="accordion-body-inner">
          <p>We create comprehensive moodboards, select all finishes, and produce detailed 3D visualizations so you can see your space before anything is built or ordered. Every element is curated for cohesion and function.</p>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <button class="accordion-btn" onclick="toggleAccordion(this)">
        <span class="accordion-num">03</span>
        <span class="accordion-title">Ordering &amp; Procurement</span>
        <span class="accordion-icon"></span>
      </button>
      <div class="accordion-body">
        <div class="accordion-body-inner">
          <p>Once designs are approved, we manage the ordering of all materials, furnishings, and finishes through our trusted trade network — ensuring quality, fair pricing, and on-time delivery.</p>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <button class="accordion-btn" onclick="toggleAccordion(this)">
        <span class="accordion-num">04</span>
        <span class="accordion-title">Project Management</span>
        <span class="accordion-icon"></span>
      </button>
      <div class="accordion-body">
        <div class="accordion-body-inner">
          <p>We oversee the entire project from our side — coordinating with contractors, trades, and vendors to ensure everything is executed according to plan, on time, and within budget.</p>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <button class="accordion-btn" onclick="toggleAccordion(this)">
        <span class="accordion-num">05</span>
        <span class="accordion-title">Install &amp; Final Styling</span>
        <span class="accordion-icon"></span>
      </button>
      <div class="accordion-body">
        <div class="accordion-body-inner">
          <p>The most exciting phase. We handle every aspect of the final install — placing furniture, hanging art, and styling accessories until the space is exactly as envisioned. The reveal is always something to behold.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- INCLUDED SERVICES -->
<section class="included-section">
  <h2 class="reveal">What's Included</h2>
  <p class="reveal reveal-delay-1">Our full-service package encompasses every detail of your home's transformation. Below is a sampling of what's covered:</p>
  <div class="included-grid">
    <div class="included-item">Moodboards &amp; Concept</div>
    <div class="included-item">Finish Selections</div>
    <div class="included-item">3D Visualizations</div>
    <div class="included-item">Scaled Elevations</div>
    <div class="included-item">Furnishings Planning</div>
    <div class="included-item">Furniture &amp; Fabric</div>
    <div class="included-item">Paint &amp; Wall Treatments</div>
    <div class="included-item">Flooring Selection</div>
    <div class="included-item">Artwork &amp; Accessories</div>
    <div class="included-item">Trade Coordination</div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials-full" style="background:var(--cream);">
  <h2 class="reveal">Kind Words</h2>
  <div class="testimonials-grid">
    <div class="t-card reveal">
      <p class="t-card-quote">"Their process is second to none. We knew exactly what to expect at every stage — and the result exceeded every expectation."</p>
      <p class="t-card-attr">Sarah &amp; Marcus V.</p>
    </div>
    <div class="t-card reveal reveal-delay-1">
      <p class="t-card-quote">"The 3D visualizations were a game-changer. Seeing our home before it was built gave us so much confidence in every decision."</p>
      <p class="t-card-attr">Priya M.</p>
    </div>
    <div class="t-card reveal reveal-delay-2">
      <p class="t-card-quote">"Studio C Collective didn't just design our home — they understood our family and made a space that actually works for how we live."</p>
      <p class="t-card-attr">Thomas &amp; Lydia W.</p>
    </div>
  </div>
</section>

<div class="cta-band">
  <h2>Interested in working together?</h2>
  <a href="#" class="btn-light" onclick="showPage('contact')">Let's Talk</a>
</div>

<footer class="site-footer">
  <div class="footer-top">
    <div class="footer-brand">
      <div class="footer-logo">Studio C Collective</div>
      <p class="footer-tagline">A boutique, full-service interior design studio.</p>
    </div>
    <nav class="footer-nav">
      <a href="#" onclick="showPage('home')">Home</a>
      <a href="#" onclick="showPage('about')">About</a>
      <a href="#" onclick="showPage('services')">Services</a>
      <a href="#" onclick="showPage('portfolio')">Portfolio</a>
      <a href="#" onclick="showPage('contact')">Contact</a>
    </nav>
    <div class="footer-contact"><p><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="c2aaa7aeaead82b1b6b7a6abadb4a7aea3eca1adaf">[email&#160;protected]</a></p></div>
  </div>
  <div class="footer-bottom">
    <p class="footer-copy">© 2025 Studio C Collective. All rights reserved.</p>
    <div class="footer-legal"><a href="#">Privacy Policy</a><a href="#">Terms &amp; Conditions</a></div>
  </div>
</footer>
```

  </div>

  <!-- ═══════════════════════════════════════════
       PORTFOLIO PAGE
  ════════════════════════════════════════════════ -->

  <div id="portfolio-page" class="page">
    <section class="portfolio-page">
      <p class="label reveal" style="margin-bottom:16px;">Our Work</p>
      <h1 class="reveal reveal-delay-1">Select Work</h1>
      <p class="reveal reveal-delay-2">A collection of projects spanning new construction, large-scale renovation, and full furnishings — each designed with intention, restraint, and a deep understanding of how our clients live.</p>

```
  <div class="portfolio-full-grid">
    <div class="pf-card reveal">
      <div class="pf-card-img">
        <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=900&q=80" alt="Luxury new construction home interior design Orlando FL" loading="lazy" />
      </div>
      <div class="pf-card-info">
        <p class="label">New Build · 2024</p>
        <h3>The Haverford Residence</h3>
      </div>
    </div>
    <div class="pf-card reveal reveal-delay-1">
      <div class="pf-card-img">
        <img src="https://images.unsplash.com/photo-1615529182904-14819c35db37?w=900&q=80" alt="High-end home renovation Winter Park Florida" loading="lazy" />
      </div>
      <div class="pf-card-info">
        <p class="label">Renovation · 2024</p>
        <h3>Casa Del Sol</h3>
      </div>
    </div>
    <div class="pf-card reveal">
      <div class="pf-card-img">
        <img src="https://images.unsplash.com/photo-1617806118233-18e1de247200?w=900&q=80" alt="Full furnishings and styling luxury home Orlando" loading="lazy" />
      </div>
      <div class="pf-card-info">
        <p class="label">Furnishings · 2023</p>
        <h3>Alderton Park Estate</h3>
      </div>
    </div>
    <div class="pf-card reveal reveal-delay-1">
      <div class="pf-card-img">
        <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?w=900&q=80" alt="New construction interior design Lake Nona Florida" loading="lazy" />
      </div>
      <div class="pf-card-info">
        <p class="label">New Build · 2023</p>
        <h3>The Meridian</h3>
      </div>
    </div>
    <div class="pf-card reveal">
      <div class="pf-card-img">
        <img src="https://images.unsplash.com/photo-1586023492125-27b2c045efd7?w=900&q=80" alt="Custom interior design Dr Phillips Orlando Florida" loading="lazy" />
      </div>
      <div class="pf-card-info">
        <p class="label">Residential · 2023</p>
        <h3>The Willow Study</h3>
      </div>
    </div>
    <div class="pf-card reveal reveal-delay-1">
      <div class="pf-card-img">
        <img src="https://images.unsplash.com/photo-1631679706909-1844bbd07221?w=900&q=80" alt="Luxury kitchen renovation Windermere Florida" loading="lazy" />
      </div>
      <div class="pf-card-info">
        <p class="label">Renovation · 2022</p>
        <h3>Elsinore Kitchen</h3>
      </div>
    </div>
  </div>
</section>

<div class="cta-band">
  <h2>Interested in collaborating?</h2>
  <a href="#" class="btn-light" onclick="showPage('contact')">Begin Your Project</a>
</div>

<footer class="site-footer">
  <div class="footer-top">
    <div class="footer-brand">
      <div class="footer-logo">Studio C Collective</div>
      <p class="footer-tagline">A boutique, full-service interior design studio.</p>
    </div>
    <nav class="footer-nav">
      <a href="#" onclick="showPage('home')">Home</a>
      <a href="#" onclick="showPage('about')">About</a>
      <a href="#" onclick="showPage('services')">Services</a>
      <a href="#" onclick="showPage('portfolio')">Portfolio</a>
      <a href="#" onclick="showPage('contact')">Contact</a>
    </nav>
    <div class="footer-contact"><p><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="620a070e0e0d22111617060b0d14070e034c010d0f">[email&#160;protected]</a></p></div>
  </div>
  <div class="footer-bottom">
    <p class="footer-copy">© 2025 Studio C Collective. All rights reserved.</p>
    <div class="footer-legal"><a href="#">Privacy Policy</a><a href="#">Terms &amp; Conditions</a></div>
  </div>
</footer>
```

  </div>

  <!-- ═══════════════════════════════════════════
       CONTACT PAGE
  ════════════════════════════════════════════════ -->

  <div id="contact-page" class="page">
    <div class="contact-page">
      <div class="contact-info">
        <p class="label reveal">Get In Touch</p>
        <h1 class="reveal reveal-delay-1">Let's begin<br>your project.</h1>
        <p class="reveal reveal-delay-2">We'd love to hear about what you're envisioning. Whether you have a fully-formed brief or a feeling you can't yet put into words — we're here for all of it.</p>
        <div class="contact-details reveal reveal-delay-3">
          <div class="contact-detail-item">
            <p class="label">Email</p>
            <span><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="d4bcb1b8b8bb94a7a0a1b0bdbba2b1b8b5fab7bbb9">[email&#160;protected]</a></span>
          </div>
          <div class="contact-detail-item">
            <p class="label">Location</p>
            <span>Orlando, FL — Serving Florida Statewide</span>
          </div>
          <div class="contact-detail-item">
            <p class="label">Follow Along</p>
            <span>@studioccollective</span>
          </div>
        </div>
      </div>
      <div class="contact-form-wrap">
        <h2>Send a Message</h2>
        <div>
          <div class="form-group">
            <label for="fname">Your Name</label>
            <input type="text" id="fname" placeholder="First &amp; Last Name" />
          </div>
          <div class="form-group">
            <label for="femail">Email Address</label>
            <input type="email" id="femail" placeholder="you@email.com" />
          </div>
          <div class="form-group">
            <label for="fproject">Project Type</label>
            <select id="fproject">
              <option value="">Select one…</option>
              <option>New Construction</option>
              <option>Full Renovation</option>
              <option>Furnishings Only</option>
              <option>Other</option>
            </select>
          </div>
          <div class="form-group">
            <label for="fmessage">Tell Us About Your Project</label>
            <textarea id="fmessage" placeholder="Share as much or as little as you'd like…"></textarea>
          </div>
          <button class="form-submit" onclick="handleFormSubmit()">Send Inquiry</button>
        </div>
      </div>
    </div>

```
<footer class="site-footer">
  <div class="footer-top">
    <div class="footer-brand">
      <div class="footer-logo">Studio C Collective</div>
      <p class="footer-tagline">A boutique, full-service interior design studio.</p>
    </div>
    <nav class="footer-nav">
      <a href="#" onclick="showPage('home')">Home</a>
      <a href="#" onclick="showPage('about')">About</a>
      <a href="#" onclick="showPage('services')">Services</a>
      <a href="#" onclick="showPage('portfolio')">Portfolio</a>
      <a href="#" onclick="showPage('contact')">Contact</a>
    </nav>
    <div class="footer-contact"><p><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="19717c757576596a6d6c7d70766f7c7578377a7674">[email&#160;protected]</a></p></div>
  </div>
  <div class="footer-bottom">
    <p class="footer-copy">© 2025 Studio C Collective. All rights reserved.</p>
    <div class="footer-legal"><a href="#">Privacy Policy</a><a href="#">Terms &amp; Conditions</a></div>
  </div>
</footer>
```

  </div>

  <!-- ═══════════════ SCRIPTS ═══════════════ -->

  <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>

```
/* ── Page routing ─────────────────────────── */
function showPage(name) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  const target = document.getElementById(name + '-page');
  if (target) {
    target.classList.add('active');
    window.scrollTo({ top: 0, behavior: 'instant' });
    // Close nav if open
    closeNav();
    // Re-trigger reveals
    setTimeout(initReveals, 50);
  }
}

/* ── Hamburger + overlay nav ──────────────── */
const burger      = document.getElementById('burgerBtn');
const navOverlay  = document.getElementById('navOverlay');
let navOpen = false;

burger.addEventListener('click', () => navOpen ? closeNav() : openNav());

function openNav() {
  navOpen = true;
  navOverlay.classList.add('open');
  burger.classList.add('open');
  document.body.style.overflow = 'hidden';
}
function closeNav() {
  navOpen = false;
  navOverlay.classList.remove('open');
  burger.classList.remove('open');
  document.body.style.overflow = '';
}

/* ── Sticky header ────────────────────────── */
const header = document.getElementById('siteHeader');
window.addEventListener('scroll', () => {
  header.classList.toggle('scrolled', window.scrollY > 60);
});

/* ── Scroll reveal ────────────────────────── */
function initReveals() {
  const reveals = document.querySelectorAll('.page.active .reveal');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) { e.target.classList.add('visible'); io.unobserve(e.target); }
    });
  }, { threshold: 0.12 });
  reveals.forEach(r => io.observe(r));
}
initReveals();

/* ── Accordion ────────────────────────────── */
function toggleAccordion(btn) {
  const item = btn.closest('.accordion-item');
  const isOpen = item.classList.contains('open');
  // Close all
  document.querySelectorAll('.accordion-item.open').forEach(i => i.classList.remove('open'));
  // Open this one if it wasn't open
  if (!isOpen) item.classList.add('open');
}

/* ── Testimonials ─────────────────────────── */
const testimonials = [
  {
    quote: '"Working with Studio C Collective was a complete transformation — not just of our home, but of how we live in it. Every detail felt intentional."',
    attr:  'Sarah & Marcus V. — The Haverford Residence'
  },
  {
    quote: '"From the first call to the final install, we felt completely cared for. The 3D visualizations alone were worth every penny — nothing was a surprise."',
    attr:  'Priya M. — The Meridian'
  },
  {
    quote: '"Timely, creative, and genuinely passionate. They understood exactly what we needed before we could even articulate it ourselves."',
    attr:  'Thomas & Lydia W. — Alderton Park Estate'
  }
];
let currentT = 0;

function setTestimonial(idx) {
  currentT = idx;
  const q = document.getElementById('testimonialQuote');
  const a = document.getElementById('testimonialAttr');
  q.style.opacity = '0'; a.style.opacity = '0';
  setTimeout(() => {
    q.textContent = testimonials[idx].quote;
    a.textContent = testimonials[idx].attr;
    q.style.transition = a.style.transition = 'opacity 0.5s 
```
