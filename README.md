<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TIGERCAT • Hybrid Beast on Solana</title>
  <meta name="description" content="TIGERCAT – Fierce tiger-cat hybrid meme coin on Solana. Community-driven, limited supply, NFTs incoming. Join the pride.">
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    :root {
      --orange-glow: #ff4500;
      --teal-glow: #00f5d4;
    }
    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #000;
      color: #fff;
      scroll-behavior: smooth;
    }
    .glow-orange { text-shadow: 0 0 25px var(--orange-glow); }
    .glow-teal   { text-shadow: 0 0 25px var(--teal-glow); }
    .nft-card {
      transition: all 0.4s ease;
      background: rgba(20,20,30,0.7);
      backdrop-filter: blur(8px);
      border: 1px solid rgba(255,69,0,0.2);
    }
    .nft-card:hover {
      transform: translateY(-12px) scale(1.04);
      border-color: var(--teal-glow);
      box-shadow: 0 0 40px rgba(0,245,212,0.3);
    }
    .hero-bg {
      background: linear-gradient(rgba(0,0,0,0.88), rgba(0,0,0,0.88)),
                  url('https://images.unsplash.com/photo-1557683316-973673baf926?w=1600&q=80') center/cover no-repeat;
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav class="fixed top-0 w-full bg-black/80 backdrop-blur-lg z-50 border-b border-zinc-800">
    <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
      <a href="#" class="flex items-center gap-3">
        <img src="YOUR_TIGER_LOGO_URL_HERE" alt="TIGERCAT" class="w-10 h-10 rounded-full border-2 border-orange-600 shadow-lg shadow-orange-900/50">
        <span class="text-2xl font-black tracking-tight glow-orange">TIGERCAT</span>
      </a>
      <div class="hidden md:flex gap-10 text-lg font-medium">
        <a href="#about" class="hover:text-orange-400 transition">About</a>
        <a href="#buy" class="hover:text-orange-400 transition">Buy</a>
        <a href="#nfts" class="hover:text-teal-400 transition">NFTs</a>
        <a href="#community" class="hover:text-orange-400 transition">Community</a>
      </div>
      <a href="#buy" class="bg-gradient-to-r from-orange-600 to-red-600 hover:from-orange-500 hover:to-red-500 px-8 py-3 rounded-full font-bold shadow-lg shadow-orange-900/40 transition">
        BUY $TCAT
      </a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="hero-bg min-h-screen flex items-center justify-center text-center pt-20">
    <div class="max-w-5xl px-6">
      <h1 class="text-7xl md:text-9xl font-black glow-orange mb-6 tracking-tighter">TIGERCAT</h1>
      <p class="text-3xl md:text-5xl font-light mb-10">The Fiercest Hybrid on Solana • Community • Hype • Moonshots</p>
      <div class="flex flex-col sm:flex-row gap-6 justify-center">
        <a href="#buy" class="bg-gradient-to-r from-orange-600 to-red-600 px-12 py-6 rounded-full text-2xl font-bold hover:scale-105 transition shadow-2xl shadow-orange-900/60">BUY NOW</a>
        <a href="#nfts" class="border-2 border-teal-500 text-teal-400 px-12 py-6 rounded-full text-2xl font-bold hover:bg-teal-500/20 transition">VIEW NFT COLLECTION</a>
      </div>
      <p class="mt-12 text-lg opacity-80">CA: <span class="font-mono text-orange-400">[YOUR_CA_HERE]</span></p>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-32 bg-gradient-to-b from-black to-zinc-950">
    <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-6xl font-black glow-orange mb-8">The Hybrid King</h2>
        <p class="text-xl leading-relaxed mb-10">TIGERCAT fuses tiger ferocity with cat meme magic — a community-owned Solana token built for viral hype, limited supply, and real moon potential. No presale, no dev dumps — just pure pride energy.</p>
        <ul class="space-y-6 text-lg">
          <li class="flex items-center gap-4"><i class="fas fa-check-circle text-orange-500 text-2xl"></i> Fair launch on pump.fun</li>
          <li class="flex items-center gap-4"><i class="fas fa-check-circle text-orange-500 text-2xl"></i> Growing holder base & active pride</li>
          <li class="flex items-center gap-4"><i class="fas fa-check-circle text-teal-400 text-2xl"></i> NFT collection launching soon</li>
        </ul>
      </div>
      <img src="YOUR_ORIGINAL_TIGER_IMAGE_URL_HERE" alt="TIGERCAT Hybrid" class="rounded-3xl shadow-2xl shadow-orange-900/50 border border-orange-800/30">
    </div>
  </section>

  <!-- BUY -->
  <section id="buy" class="py-32 bg-black">
    <div class="max-w-5xl mx-auto px-6 text-center">
      <h2 class="text-6xl md:text-7xl font-black glow-orange mb-8">Join the Pride Now</h2>
      <p class="text-2xl mb-12 max-w-2xl mx-auto">Connect your Phantom wallet and grab $TCAT before the next leg up.</p>
      <div class="bg-zinc-900/70 backdrop-blur-lg rounded-3xl p-12 border border-orange-800/30">
        <p class="text-xl mb-6">Contract Address</p>
        <code class="bg-black/60 p-5 rounded-xl text-orange-300 font-mono text-lg block mb-10 break-all">[YOUR_CA_HERE]</code>
        <a href="YOUR_PUMP_FUN_URL_HERE" target="_blank" rel="noopener noreferrer" class="inline-block bg-gradient-to-r from-orange-600 to-red-600 hover:from-orange-500 hover:to-red-500 px-16 py-8 rounded-2xl text-3xl font-bold shadow-2xl shadow-orange-900/60 transition">
          BUY ON PUMP.FUN
        </a>
      </div>
    </div>
  </section>

  <!-- NFT SECTION -->
  <section id="nfts" class="py-32 bg-gradient-to-b from-zinc-950 to-black">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-6xl md:text-7xl font-black text-center glow-teal mb-6">TIGERCAT NFT COLLECTION</h2>
      <p class="text-2xl text-center text-teal-300 mb-16">Mystical cave editions • Glowing crystals • Holders get priority mints • Coming soon</p>
      
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-8">
        <!-- Repeat for each of your 10 NFTs – replace src with uploaded image URLs -->
        <div class="nft-card rounded-3xl overflow-hidden">
          <img src="YOUR_NFT_IMAGE_1_URL_HERE" alt="Fiery Stare Edition" class="w-full h-64 object-cover">
          <div class="p-6 text-center">
            <h3 class="font-bold text-xl">Fiery Stare Edition</h3>
            <p class="text-sm opacity-80">Legendary • Enchanted Glow</p>
          </div>
        </div>
        <!-- Add the other 9 here – copy-paste block and change image src + name -->
        <!-- Example for 2nd: -->
        <div class="nft-card rounded-3xl overflow-hidden">
          <img src="YOUR_NFT_IMAGE_2_URL_HERE" alt="Relaxed Ruler Variant" class="w-full h-64 object-cover">
          <div class="p-6 text-center">
            <h3 class="font-bold text-xl">Relaxed Ruler Variant</h3>
            <p class="text-sm opacity-80">Rare • Crystal Throne</p>
          </div>
        </div>
        <!-- ... continue for all 10 ... -->
      </div>

      <div class="text-center mt-20">
        <p class="text-2xl">Whitelist spots for early holders & active pride members. Stay tuned on X & Telegram!</p>
      </div>
    </div>
  </section>

  <!-- COMMUNITY -->
  <section id="community" class="py-32 bg-black">
    <div class="max-w-5xl mx-auto px-6 text-center">
      <h2 class="text-6xl font-black glow-orange mb-12">Join the Pride</h2>
      <div class="grid md:grid-cols-2 gap-10 max-w-3xl mx-auto">
        <a href="https://x.com/TigerCatHQ" target="_blank" class="bg-zinc-900/70 hover:bg-zinc-800/70 border border-orange-800/40 rounded-3xl p-12 flex flex-col items-center gap-6 transition">
          <i class="fab fa-x-twitter text-6xl text-orange-500"></i>
          <span class="text-3xl font-bold">Follow on X</span>
        </a>
        <a href="YOUR_TELEGRAM_LINK_HERE" target="_blank" class="bg-zinc-900/70 hover:bg-zinc-800/70 border border-teal-800/40 rounded-3xl p-12 flex flex-col items-center gap-6 transition">
          <i class="fab fa-telegram text-6xl text-teal-400"></i>
          <span class="text-3xl font-bold">Join Telegram</span>
        </a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black py-16 border-t border-zinc-800 text-center text-sm opacity-80">
    <p>© 2026 TIGERCAT • Not financial advice • DYOR • Crypto is high-risk</p>
    <p class="mt-4">Built with pride for the Solana community 🐯</p>
  </footer>

</body>
</html>