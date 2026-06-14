<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vasco Mart Auctioneers | Fine Art, Jewellery & Antique Auctions</title>
<meta name="description" content="Vasco Mart is a luxury auction house specialising in fine art, rare jewellery, antiques and estate collections. Bid online or in person at our London saleroom.">
<meta name="keywords" content="auction house, fine art auction, jewellery auction, antiques auction, online bidding, estate sale, Vasco Mart, luxury auctions">
<meta name="author" content="Vasco Mart Auctioneers">
<meta name="robots" content="index, follow">
<meta name="theme-color" content="#0d0b07">
<link rel="canonical" href="https://yourusername.github.io/vasco-mart/index.html">

<!-- Open Graph (Facebook, WhatsApp, LinkedIn previews) -->
<meta property="og:title" content="Vasco Mart Auctioneers | Fine Art, Jewellery & Antique Auctions">
<meta property="og:description" content="Bid on exceptional fine art, rare jewellery, antiques and estate collections. Register free and join our next auction.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://yourusername.github.io/vasco-mart/">
<meta property="og:image" content="https://images.unsplash.com/photo-1563861826100-9cb868fdbe1c?w=1200&auto=format&fit=crop">
<meta property="og:site_name" content="Vasco Mart Auctioneers">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Vasco Mart Auctioneers | Fine Art & Antique Auctions">
<meta name="twitter:description" content="Bid on exceptional fine art, rare jewellery and antiques. Register free today.">
<meta name="twitter:image" content="https://images.unsplash.com/photo-1563861826100-9cb868fdbe1c?w=1200&auto=format&fit=crop">

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  :root {
    --ink: #0d0b07;
    --parchment: #f5f0e8;
    --gold: #b8973a;
    --gold-light: #d4b45a;
    --ash: #2a2520;
    --mist: #7a7060;
    --cream: #ede8de;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Inter', sans-serif;
    background: var(--ink);
    color: var(--parchment);
    overflow-x: hidden;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; width: 100%; z-index: 100;
    padding: 1.4rem 4rem;
    display: flex; justify-content: space-between; align-items: center;
    background: linear-gradient(to bottom, rgba(13,11,7,0.9), transparent);
    backdrop-filter: blur(2px);
    transition: background 0.4s;
  }
  nav.scrolled { background: rgba(13,11,7,0.97); }
  .nav-logo {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.5rem; font-weight: 300; letter-spacing: 0.15em;
    color: var(--gold); text-decoration: none;
  }
  .nav-links { display: flex; gap: 2.5rem; list-style: none; }
  .nav-links a {
    font-size: 0.78rem; letter-spacing: 0.12em; text-transform: uppercase;
    color: var(--parchment); text-decoration: none; opacity: 0.7;
    transition: opacity 0.2s;
  }
  .nav-links a:hover { opacity: 1; }
  .nav-cta {
    font-size: 0.78rem; letter-spacing: 0.1em; text-transform: uppercase;
    border: 1px solid var(--gold); color: var(--gold);
    padding: 0.5rem 1.4rem; text-decoration: none;
    transition: background 0.2s, color 0.2s;
  }
  .nav-cta:hover { background: var(--gold); color: var(--ink); }

  /* HERO */
  .hero {
    height: 100vh; position: relative; overflow: hidden;
    display: flex; align-items: center; justify-content: center;
  }
  .hero-bg {
    position: absolute; inset: 0;
    background: url('https://images.unsplash.com/photo-1563861826100-9cb868fdbe1c?w=1800&auto=format&fit=crop') center/cover no-repeat;
    transform: translateZ(0);
    will-change: transform;
  }
  .hero-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(160deg, rgba(13,11
