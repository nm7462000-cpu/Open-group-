<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>नीरज भाई खाईवाल - Official</title>
  
  <!-- Meta Pixel Code -->
  <script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '1643018623531725');
  fbq('track', 'PageView');
  </script>
  <noscript><img height="1" width="1" style="display:none"
  src="https://www.facebook.com/tr?id=1643018623531725&ev=PageView&noscript=1"
  /></noscript>
  <!-- End Meta Pixel Code -->

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Devanagari:wght@500;600;700;800;900&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100dvh;
      overflow: hidden;
      font-family: 'Noto Sans Devanagari', 'Plus Jakarta Sans', sans-serif;
      background-color: #f4f7f5;
      background-image: 
        radial-gradient(at 0% 0%, rgba(16, 185, 129, 0.14) 0px, transparent 50%),
        radial-gradient(at 100% 100%, rgba(245, 158, 11, 0.12) 0px, transparent 50%),
        radial-gradient(#cbd5e1 1px, transparent 1px);
      background-size: 100% 100%, 100% 100%, 20px 20px;
      user-select: none;
    }

    /* Animated Emerald Verified Badge */
    @keyframes badgeFloat {
      0%, 100% { transform: translateY(0) scale(1); }
      50% { transform: translateY(-2px) scale(1.08); }
    }

    @keyframes pulseRing {
      0% { transform: scale(0.9); opacity: 0.8; }
      100% { transform: scale(1.8); opacity: 0; }
    }

    .verify-badge {
      position: relative;
      display: inline-flex;
      align-items: center;
      justify-content: center;
    }

    .verify-pulse {
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.35);
      animation: pulseRing 2s ease-out infinite;
    }

    .verify-icon {
      position: relative;
      z-index: 2;
      animation: badgeFloat 2.4s ease-in-out infinite;
    }

    /* CTA Button Glow & Slide Shine */
    @keyframes slideShine {
      0% { transform: translateX(-150%) skewX(-25deg); }
      50%, 100% { transform: translateX(250%) skewX(-25deg); }
    }

    @keyframes btnBounceGlow {
      0%, 100% {
        box-shadow: 0 10px 25px -5px rgba(5, 150, 105, 0.45), 0 0 0 0 rgba(16, 185, 129, 0.4);
      }
      50% {
        box-shadow: 0 14px 30px -5px rgba(5, 150, 105, 0.6), 0 0 0 7px rgba(16, 185, 129, 0);
      }
    }

    .cta-emerald {
      background: linear-gradient(135deg, #065f46 0%, #059669 55%, #10b981 100%);
      animation: btnBounceGlow 2.2s infinite ease-in-out;
      position: relative;
      overflow: hidden;
      transition: transform 0.15s ease;
    }

    .cta-emerald:active {
      transform: scale(0.97);
    }

    .cta-emerald::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 45%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,0.38), transparent);
      animation: slideShine 2.6s infinite;
    }

    /* Smooth Card Entrance */
    @keyframes popIn {
      from { opacity: 0; transform: scale(0.96) translateY(8px); }
      to { opacity: 1; transform: scale(1) translateY(0); }
    }

    .main-shell {
      animation: popIn 0.4s cubic-bezier(0.16, 1, 0.3, 1) forwards;
    }

    /* Ultra-compact mobile viewport fit */
    @media (max-height: 650px) {
      .main-shell { padding: 0.75rem !important; }
      .header-box { padding: 0.65rem 0.75rem !important; }
      .brand-title { font-size: 1.45rem !important; }
      .grid-box { padding: 0.55rem 0.4rem !important; }
      .rate-strip { padding: 0.5rem 0.75rem !important; }
      .cta-emerald { padding-top: 0.7rem !important; padding-bottom: 0.7rem !important; }
    }
  </style>
</head>
<body class="flex items-center justify-center p-3 sm:p-5">

  <!-- Main Card Container -->
  <main class="main-shell w-full max-w-[410px] h-full max-h-[680px] bg-white rounded-[26px] border border-emerald-900/10 shadow-[0_24px_48px_-12px_rgba(6,78,59,0.14)] p-4 sm:p-5 flex flex-col justify-between relative overflow-hidden">

    <!-- Top Emerald Accent Line -->
    <div class="absolute top-0 left-0 right-0 h-1.5 bg-gradient-to-r from-emerald-600 via-teal-500 to-amber-400"></div>

    <!-- 1. TOP DARK EMERALD HEADER BANNER -->
    <header class="header-box bg-gradient-to-br from-[#064e3b] via-[#065f46] to-[#047857] rounded-2xl p-3.5 sm:p-4 text-center text-white shadow-md relative overflow-hidden">
      <!-- Subtle geometric pattern overlay -->
      <div class="absolute -right-6 -top-6 w-24 h-24 rounded-full bg-white/5 pointer-events-none"></div>
      <div class="absolute -left-6 -bottom-6 w-20 h-20 rounded-full bg-amber-400/10 pointer-events-none"></div>

      <div class="inline-flex items-center gap-1.5 px-2.5 py-0.5 rounded-full bg-white/15 backdrop-blur-sm border border-white/20 text-[10px] font-bold tracking-widest uppercase text-amber-200 mb-1.5">
        <span class="w-1.5 h-1.5 rounded-full bg-amber-300 animate-ping"></span>
        100% Trusted & Verified
      </div>

      <h1 class="brand-title text-[26px] sm:text-[29px] font-black tracking-tight leading-tight flex items-center justify-center gap-2">
        <span>नीरज भाई खाईवाल</span>
        <!-- Animated Emerald/Gold Verified Badge -->
        <span class="verify-badge w-7 h-7 shrink-0" title="Verified Official">
          <span class="verify-pulse"></span>
          <svg class="verify-icon w-7 h-7" viewBox="0 0 24 24" fill="none">
            <path d="M22.25 12c0-1.43-.88-2.67-2.19-3.34.46-1.39.2-2.9-.81-3.91s-2.52-1.27-3.91-.81c-.66-1.31-1.91-2.19-3.34-2.19s-2.67.88-3.33 2.19c-1.4-.46-2.91-.2-3.92.81s-1.26 2.52-.8 3.91c-1.31.67-2.2 1.91-2.2 3.34s.89 2.67 2.2 3.34c-.46 1.39-.21 2.9.8 3.91s2.52 1.26 3.91.81c.67 1.31 1.91 2.19 3.34 2.19s2.68-.88 3.34-2.19c1.39.45 2.9.2 3.91-.81s1.27-2.52.81-3.91c1.31-.67 2.19-1.91 2.19-3.34z" fill="#10B981"/>
            <path d="M8.5 12.3L10.9 14.7L15.8 9.6" stroke="#FFFFFF" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </span>
      </h1>
    </header>

    <!-- 2. 3-COLUMN TRUST GRID -->
    <section class="grid grid-cols-3 gap-2 my-1" aria-label="Trust Highlights">
      <!-- Card 1 -->
      <div class="grid-box bg-[#f8faf9] border border-emerald-900/10 rounded-2xl p-2.5 text-center flex flex-col items-center justify-center shadow-sm">
        <div class="w-8 h-8 rounded-full bg-emerald-100 text-emerald-700 flex items-center justify-center mb-1.5">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z"/>
          </svg>
        </div>
        <span class="text-[12.5px] sm:text-[13px] font-extrabold text-slate-800 leading-tight">
          तुरंत पेमेंट<br/>के हिसाब
        </span>
      </div>

      <!-- Card 2 -->
      <div class="grid-box bg-[#f8faf9] border border-emerald-900/10 rounded-2xl p-2.5 text-center flex flex-col items-center justify-center shadow-sm">
        <div class="w-8 h-8 rounded-full bg-amber-100 text-amber-700 flex items-center justify-center mb-1.5">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/>
          </svg>
        </div>
        <span class="text-[12.5px] sm:text-[13px] font-extrabold text-slate-800 leading-tight">
          15,000+<br/>लोगों का भरोसा
        </span>
      </div>

      <!-- Card 3 -->
      <div class="grid-box bg-[#f8faf9] border border-emerald-900/10 rounded-2xl p-2.5 text-center flex flex-col items-center justify-center shadow-sm">
        <div class="w-8 h-8 rounded-full bg-teal-100 text-teal-700 flex items-center justify-center mb-1.5">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"/>
          </svg>
        </div>
        <span class="text-[12.5px] sm:text-[13px] font-extrabold text-slate-800 leading-tight">
          सबसे शानदार<br/>रेट
        </span>
      </div>
    </section>

    <!-- 3. RATE TICKET SECTION (Warm Gold & Cream Contrast) -->
    <section class="bg-gradient-to-r from-amber-50 via-yellow-50/80 to-amber-50 border-2 border-dashed border-amber-300/90 rounded-2xl p-3 relative" aria-label="Rate Chart">
      <div class="flex items-center justify-between mb-2 px-1">
        <span class="text-[11px] font-black uppercase tracking-wider text-amber-900">
          ◆ आज का शानदार रेट
        </span>
        <span class="text-[10px] font-bold bg-amber-200/80 text-amber-950 px-2 py-0.5 rounded-md">
          FULL RATE
        </span>
      </div>

      <div class="flex flex-col gap-2">
        <!-- Jodi Row -->
        <div class="rate-strip bg-white rounded-xl px-3.5 py-2 flex items-center justify-between border border-amber-200/70 shadow-sm">
          <div class="flex items-center gap-2">
            <span class="w-2 h-2 rounded-full bg-emerald-600"></span>
            <span class="text-sm sm:text-[15px] font-bold text-slate-700">जोड़ी रेट</span>
          </div>
          <span class="text-base sm:text-lg font-black text-emerald-800 bg-emerald-50 px-2.5 py-0.5 rounded-lg border border-emerald-200/60">
            10 का 990
          </span>
        </div>

        <!-- Haruf Row -->
        <div class="rate-strip bg-white rounded-xl px-3.5 py-2 flex items-center justify-between border border-amber-200/70 shadow-sm">
          <div class="flex items-center gap-2">
            <span class="w-2 h-2 rounded-full bg-amber-500"></span>
            <span class="text-sm sm:text-[15px] font-bold text-slate-700">हरूफ रेट</span>
          </div>
          <span class="text-base sm:text-lg font-black text-emerald-800 bg-emerald-50 px-2.5 py-0.5 rounded-lg border border-emerald-200/60">
            100 का 990
          </span>
        </div>
      </div>
    </section>

    <!-- 4. PRIMARY TELEGRAM CTA BUTTON -->
    <div class="my-1">
      <a
        href="https://t.me/+uVd13OnfC6xmZjI1"
        target="_blank"
        rel="noopener noreferrer"
        class="cta-emerald w-full rounded-2xl py-3.5 px-5 flex items-center justify-center gap-3 text-white font-extrabold text-[16px] sm:text-[17px] tracking-wide cursor-pointer"
      >
        <span class="w-8 h-8 rounded-xl bg-white/20 flex items-center justify-center shrink-0">
          <svg class="w-5 h-5 text-white -ml-0.5" viewBox="0 0 24 24" fill="currentColor">
            <path d="M11.944 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0a12 12 0 0 0-.056 0zm4.962 7.224c.1-.002.321.023.465.14a.506.506 0 0 1 .171.325c.016.093.036.306.02.472-.18 1.898-.962 6.502-1.36 8.627-.168.9-.499 1.201-.82 1.23-.696.065-1.225-.46-1.9-.902-1.056-.693-1.653-1.124-2.678-1.8-1.185-.78-.417-1.21.258-1.91.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.14-5.061 3.345-.48.33-.913.49-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.245-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.83-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635z"/>
          </svg>
        </span>
        <span style="font-family: 'Plus Jakarta Sans', sans-serif;">JOIN OPEN GROUP</span>
        <svg class="w-4 h-4 text-emerald-200 ml-0.5" fill="none" stroke="currentColor" stroke-width="2.8" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/>
        </svg>
      </a>
    </div>

    <!-- 5. FOOTER AGENCY LINK -->
    <footer class="pt-0.5 text-center">
      <a
        href="https://t.me/CG_GROUP_OFFOCAL"
        target="_blank"
        rel="noopener noreferrer"
        class="inline-flex items-center justify-center gap-1.5 px-4 py-1.5 rounded-full bg-slate-100 hover:bg-emerald-50 border border-slate-200/90 hover:border-emerald-300 text-xs font-bold text-slate-600 hover:text-emerald-800 transition-colors"
      >
        <svg class="w-3.5 h-3.5 text-emerald-600 shrink-0" viewBox="0 0 24 24" fill="currentColor">
          <path d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm5.562 8.161c-.18 1.897-.962 6.502-1.359 8.627-.168.9-.5 1.201-.82 1.23-.697.064-1.226-.461-1.901-.903-1.056-.692-1.653-1.123-2.678-1.799-1.185-.781-.417-1.21.258-1.911.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.139-5.062 3.345-.479.329-.913.489-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.244-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.831-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635.099-.002.321.023.465.14.121.099.154.232.17.325.015.093.034.305.019.473z"/>
        </svg>
        <span style="font-family: 'Plus Jakarta Sans', sans-serif;">Ads by <strong class="text-slate-900 underline decoration-emerald-400 underline-offset-2">CG ad agency</strong></span>
      </a>
    </footer>

  </main>

</body>
</html>
