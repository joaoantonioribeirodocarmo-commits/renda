<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NexaOS — Apresentação Interativa do Novo Sistema Operacional</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Plus Jakarta Sans & Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">
  
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            display: ['Plus Jakarta Sans', 'sans-serif'],
          },
          animation: {
            'float': 'float 6s ease-in-out infinite',
            'pulse-slow': 'pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite',
          },
          keyframes: {
            float: {
              '0%, 100%': { transform: 'translateY(0px)' },
              '50%': { transform: 'translateY(-10px)' },
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Modos de Acessibilidade em Tempo Real (Slide 7) */
    body.high-contrast {
      background-color: #000000 !important;
      color: #ffff00 !important;
    }
    body.high-contrast .slide-container,
    body.high-contrast .glass-panel,
    body.high-contrast header,
    body.high-contrast footer {
      background: #000000 !important;
      border: 2px solid #ffff00 !important;
      color: #ffff00 !important;
      box-shadow: none !important;
    }
    body.high-contrast p, 
    body.high-contrast span, 
    body.high-contrast h1, 
    body.high-contrast h2, 
    body.high-contrast h3,
    body.high-contrast li {
      color: #ffff00 !important;
    }

    body.large-font {
      font-size: 115%;
    }
    body.large-font .text-xs { font-size: 0.92rem !important; }
    body.large-font .text-sm { font-size: 1.05rem !important; }
    body.large-font .text-base { font-size: 1.2rem !important; }

    /* Modo Leitura Guiada / Foco */
    body.reading-guide .slide-container {
      line-height: 1.85 !important;
      letter-spacing: 0.02em !important;
      background: rgba(15, 23, 42, 0.96) !important;
    }

    /* Transição suave entre slides */
    .slide-container {
      transition: opacity 0.35s ease, transform 0.35s cubic-bezier(0.22, 1, 0.36, 1);
    }
    .slide-hidden {
      display: none;
      opacity: 0;
      transform: translateY(10px) scale(0.99);
    }
    .slide-active {
      display: flex;
      opacity: 1;
      transform: translateY(0) scale(1);
    }

    /* Scrollbar customizada */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: rgba(15, 23, 42, 0.4);
    }
    ::-webkit-scrollbar-thumb {
      background: rgba(6, 182, 212, 0.5);
      border-radius: 9999px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: rgba(6, 182, 212, 0.85);
    }
  </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen flex flex-col selection:bg-cyan-500 selection:text-slate-950 overflow-x-hidden">

  <!-- Fundo Decorativo Futurista -->
  <div class="fixed inset-0 pointer-events-none overflow-hidden -z-10">
    <div class="absolute -top-32 -left-32 w-96 h-96 bg-cyan-500/20 rounded-full blur-3xl"></div>
    <div class="absolute top-1/2 -right-32 w-96 h-96 bg-indigo-600/20 rounded-full blur-3xl"></div>
    <div class="absolute -bottom-32 left-1/3 w-96 h-96 bg-emerald-500/15 rounded-full blur-3xl"></div>
  </div>

  <!-- BARRA SUPERIOR DE CONTROLE -->
  <header class="sticky top-0 z-40 bg-slate-900/85 backdrop-blur-md border-b border-slate-800 px-4 py-2.5 flex flex-wrap items-center justify-between gap-2">
    <div class="flex items-center gap-3">
      <!-- Mini Logo Hexagonal NexaOS -->
      <div class="w-9 h-9 rounded-xl bg-gradient-to-tr from-cyan-500 via-indigo-600 to-emerald-400 flex items-center justify-center shadow-lg shadow-cyan-500/25">
        <svg class="w-5 h-5 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2">
          <polygon points="12 2 21 7 21 17 12 22 3 17 3 7 12 2"/>
          <path d="M8 15V9l8 6V9" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <div>
        <div class="flex items-center gap-2">
          <span class="font-display font-bold text-sm sm:text-base tracking-tight text-white">NexaOS</span>
          <span id="top-slide-badge" class="px-2 py-0.5 rounded-full text-[11px] font-semibold bg-cyan-500/15 text-cyan-300 border border-cyan-500/30">Slide 1 de 10</span>
        </div>
        <span class="hidden md:inline-block text-[11px] text-slate-400">Atividade: Criando um Novo Sistema Operacional</span>
      </div>
    </div>

    <!-- Controles Rápidos do Topo -->
    <div class="flex items-center gap-1.5 sm:gap-2">
      <!-- Botão Todos os Slides -->
      <button id="btn-grid-view" onclick="toggleGridView()" class="px-3 py-1.5 rounded-xl text-xs sm:text-sm font-medium bg-slate-800 hover:bg-slate-700 text-slate-200 border border-slate-700 transition flex items-center gap-1.5 cursor-pointer" title="Ver grade com todos os 10 slides">
        <svg class="w-4 h-4 text-cyan-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"/></svg>
        <span id="grid-btn-text">Todos os Slides</span>
      </button>

      <!-- Botão Copiar Código -->
      <button onclick="copyFullSourceCode()" class="px-3 py-1.5 rounded-xl text-xs sm:text-sm font-medium bg-emerald-600/20 hover:bg-emerald-600/35 text-emerald-300 border border-emerald-500/40 transition flex items-center gap-1.5 cursor-pointer" title="Copiar código-fonte HTML/JS completo">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>
        <span class="hidden sm:inline">Copiar Código</span>
      </button>

      <!-- Botão Tela Cheia -->
      <button onclick="toggleFullscreen()" class="p-2 rounded-xl bg-cyan-600 hover:bg-cyan-500 text-slate-950 font-bold shadow-md shadow-cyan-600/25 transition cursor-pointer" title="Modo Tela Cheia">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 8V4m0 0h4M4 4l5 5m11-1V4m0 0h-4m4 0l-5 5M4 16v4m0 0h4m-4 0l5-5m11 5l-5-5m5 5v-4m0 4h-4"/></svg>
      </button>
    </div>
  </header>

  <!-- Barra de Progresso -->
  <div class="w-full h-1 bg-slate-800">
    <div id="progress-bar" class="h-full bg-gradient-to-r from-cyan-400 via-indigo-500 to-emerald-400 transition-all duration-300" style="width: 10%;"></div>
  </div>

  <!-- PALCO PRINCIPAL DA APRESENTAÇÃO -->
  <main id="presentation-stage" class="flex-1 flex items-center justify-center p-3 sm:p-6 md:p-8 max-w-6xl w-full mx-auto">

    <!-- ==================== SLIDE 1: NOME DO SISTEMA OPERACIONAL ==================== -->
    <section data-slide="1" data-title="Nome do Sistema Operacional" class="slide-container slide-active w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 md:p-12 flex-col justify-between relative overflow-hidden">
      <div class="flex items-center justify-between">
        <span class="px-3 py-1 rounded-full text-xs font-semibold tracking-wider uppercase bg-cyan-500/20 text-cyan-300 border border-cyan-500/30">Slide 01 • Identidade do SO</span>
        <span class="text-xs text-slate-400 font-mono">NexaCore v2.0 • Microkernel</span>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center my-auto py-4">
        <div class="lg:col-span-6 space-y-4 text-center lg:text-left">
          <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-300 text-xs font-medium">
            <span class="w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
            Nova Arquitetura Operacional Híbrida
          </div>
          <h1 class="font-display text-5xl sm:text-6xl md:text-7xl font-extrabold tracking-tight bg-gradient-to-r from-white via-cyan-200 to-indigo-400 bg-clip-text text-transparent">
            NexaOS
          </h1>
          <p class="text-xl sm:text-2xl font-semibold text-cyan-300">
            “Inteligência fluida em cada tela.”
          </p>
          <p class="text-slate-300 text-sm sm:text-base max-w-xl mx-auto lg:mx-0 leading-relaxed">
            Criado para conectar dispositivos, pessoas e ideias com velocidade instantânea, segurança blindada e inteligência artificial integrada diretamente ao núcleo.
          </p>

          <!-- Botão Interativo: Origem do Nome & Arquitetura -->
          <div class="pt-2 flex flex-wrap items-center justify-center lg:justify-start gap-3">
            <button onclick="openDetailModal('s1_origem')" class="px-4 py-2.5 rounded-2xl bg-gradient-to-r from-cyan-500 to-indigo-600 hover:from-cyan-400 hover:to-indigo-500 text-slate-950 font-bold text-xs sm:text-sm shadow-lg shadow-cyan-500/25 transition flex items-center gap-2 cursor-pointer">
              <span>🔍 Origem do Nome & Arquitetura</span>
            </button>
            <button onclick="openDetailModal('s1_kernel')" class="px-4 py-2.5 rounded-2xl bg-slate-800 hover:bg-slate-700 text-cyan-300 border border-cyan-500/30 font-semibold text-xs sm:text-sm transition cursor-pointer">
              ⚙️ Entenda o Núcleo NexaCore
            </button>
          </div>
        </div>

        <!-- Logotipo Hexagonal Geométrico NexaOS + Imagem Futurista -->
        <div class="lg:col-span-6 flex justify-center">
          <div class="relative w-full max-w-md h-64 sm:h-72 rounded-3xl overflow-hidden border border-cyan-500/40 shadow-2xl group">
            <img
              src="https://images.unsplash.com/photo-1639322537228-f710d846310a?auto=format&fit=crop&w=900&q=80"
              alt="Rede neural hexagonal futurista representando o NexaOS"
              data-fallback-theme="logo"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover opacity-55 group-hover:scale-105 transition duration-700"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-900/45 to-transparent"></div>
            
            <!-- Logotipo Hexagonal/Nexus Central -->
            <div class="absolute inset-0 flex flex-col items-center justify-center p-4 animate-float">
              <div class="w-36 h-36 sm:w-40 sm:h-40 rounded-3xl bg-slate-900/90 backdrop-blur-md border border-cyan-400/50 shadow-2xl flex flex-col items-center justify-center p-3">
                <svg class="w-24 h-24" viewBox="0 0 120 120" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <defs>
                    <linearGradient id="nexaGrad" x1="15" y1="15" x2="105" y2="105" gradientUnits="userSpaceOnUse">
                      <stop offset="0%" stop-color="#22D3EE"/>
                      <stop offset="50%" stop-color="#6366F1"/>
                      <stop offset="100%" stop-color="#10B981"/>
                    </linearGradient>
                  </defs>
                  <!-- Hexágono Externo -->
                  <polygon points="60,10 104,35 104,85 60,110 16,85 16,35" stroke="url(#nexaGrad)" stroke-width="5" fill="rgba(34,211,238,0.08)"/>
                  <!-- Hexágono Interno Conectado -->
                  <polygon points="60,26 90,43 90,77 60,94 30,77 30,43" stroke="#22D3EE" stroke-width="2" stroke-opacity="0.5"/>
                  <!-- Letra N Geométrica -->
                  <path d="M44 76V44L76 76V44" stroke="url(#nexaGrad)" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/>
                  <!-- Nós de Conexão -->
                  <circle cx="44" cy="44" r="4" fill="#FFFFFF"/>
                  <circle cx="76" cy="76" r="4" fill="#10B981"/>
                </svg>
                <span class="mt-1 font-display font-extrabold text-xs tracking-[0.25em] text-cyan-300">NEXA OS</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400 border-t border-slate-800/80 pt-3">
        <span>Clique nos botões em cada slide para explorar os detalhes técnicos</span>
        <span class="text-cyan-400 font-semibold">Slide 1 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 2: TIPO DE DISPOSITIVO ==================== -->
    <section data-slide="2" data-title="Tipo de Dispositivo" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <div class="lg:col-span-7 space-y-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-indigo-500/20 text-indigo-300 border border-indigo-500/30">Slide 02 • Tipo de Dispositivo</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Um Núcleo. <span class="text-cyan-400">Todos os Dispositivos.</span></h2>
          <p class="text-slate-300 text-xs sm:text-sm">
            Selecione um dispositivo abaixo para testar como o <strong>NexaFlex UI</strong> adapta automaticamente tela, RAM e controles:
          </p>
          <!-- Botões Interativos para Trocar Dispositivo -->
          <div class="flex flex-wrap gap-2 pt-1">
            <button onclick="selectDeviceMode('pc')" id="dev-btn-pc" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-cyan-500 text-slate-950 transition cursor-pointer">💻 PC / Notebook</button>
            <button onclick="selectDeviceMode('phone')" id="dev-btn-phone" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">📱 Smartphone</button>
            <button onclick="selectDeviceMode('console')" id="dev-btn-console" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">🎮 Videogame</button>
            <button onclick="selectDeviceMode('tablet')" id="dev-btn-tablet" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">📟 Tablet</button>
          </div>
        </div>

        <!-- Imagem dos Dispositivos -->
        <div class="lg:col-span-5">
          <div class="relative h-40 sm:h-44 rounded-2xl overflow-hidden border border-cyan-500/35 shadow-lg">
            <img
              src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=800&q=80"
              alt="Computadores, smartphones e tablets rodando NexaOS"
              data-fallback-theme="devices"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-transparent to-transparent flex items-end justify-between p-3">
              <span class="text-xs font-semibold text-cyan-300">Ecossistema NexaFlex</span>
              <button onclick="openDetailModal('s2_adaptacao')" class="px-2.5 py-1 rounded-lg bg-cyan-500/90 hover:bg-cyan-400 text-slate-950 font-bold text-[11px] cursor-pointer">
                Ver Adaptação de Tela
              </button>
            </div>
          </div>
        </div>
      </div>

      <!-- Painel Dinâmico do Dispositivo Selecionado -->
      <div id="device-inspector-panel" class="glass-panel rounded-2xl bg-slate-800/70 border border-cyan-500/40 p-5 my-4 grid grid-cols-1 md:grid-cols-12 gap-4 items-center">
        <div class="md:col-span-8 space-y-1.5">
          <div class="flex items-center gap-2">
            <span id="dev-icon" class="text-2xl">💻</span>
            <h3 id="dev-title" class="font-display font-bold text-xl text-white">Modo Desktop & Notebook</h3>
            <span id="dev-badge" class="px-2.5 py-0.5 rounded-full text-[11px] font-semibold bg-cyan-500/20 text-cyan-300">Multitarefa Completa</span>
          </div>
          <p id="dev-desc" class="text-xs sm:text-sm text-slate-300 leading-relaxed">
            Interface com múltiplas janelas flutuantes, barra de tarefas inteligente, suporte a até 4 monitores 8K e atalhos profissionais de teclado.
          </p>
        </div>
        <div class="md:col-span-4 bg-slate-950/70 rounded-xl p-3.5 border border-slate-700/80 space-y-2 text-xs">
          <div class="flex justify-between"><span class="text-slate-400">Consumo Base RAM:</span><span id="dev-ram" class="font-bold text-emerald-400">1.1 GB</span></div>
          <div class="flex justify-between"><span class="text-slate-400">Entrada Principal:</span><span id="dev-input" class="font-bold text-cyan-300">Mouse, Teclado & Touch</span></div>
          <div class="flex justify-between"><span class="text-slate-400">Sincronia Nuvem:</span><span class="font-bold text-indigo-300">Instantânea (NexaLink)</span></div>
        </div>
      </div>

      <div class="flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400 border-t border-slate-800 pt-3">
        <span>✨ Um único sistema operacional para todos os seus aparelhos</span>
        <span class="text-cyan-400 font-semibold">Slide 2 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 3: DIFERENCIAIS DO SISTEMA ==================== -->
    <section data-slide="3" data-title="Diferenciais do Sistema" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div>
        <div class="flex items-center justify-between mb-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-indigo-500/20 text-indigo-300 border border-indigo-500/30">Slide 03 • Diferenciais Tecnológicos</span>
          <span class="text-xs text-slate-400">O que torna o NexaOS único</span>
        </div>
        <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Por que o NexaOS é <span class="text-cyan-400">mais moderno e útil?</span></h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 my-4 items-stretch">
        <!-- Imagem de Inovação -->
        <div class="lg:col-span-4 relative rounded-2xl overflow-hidden border border-indigo-500/35 min-h-[200px] shadow-xl">
          <img
            src="https://images.unsplash.com/photo-1677442136019-21780ecad995?auto=format&fit=crop&w=800&q=80"
            alt="Inovação e Inteligência Artificial no NexaOS"
            data-fallback-theme="innovation"
            onerror="handleImageFallback(this)"
            class="w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/35 to-transparent flex flex-col justify-end p-4">
            <span class="text-xs font-bold uppercase tracking-wider text-cyan-300">NexaMind Engine</span>
            <p class="text-xs text-slate-200 mt-1">Inovação real que antecipa suas tarefas sem comprometer sua privacidade.</p>
          </div>
        </div>

        <!-- 3 Cards de Diferenciais com Botões "Saiba Mais" -->
        <div class="lg:col-span-8 grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex flex-col justify-between">
            <div>
              <div class="w-11 h-11 rounded-xl bg-cyan-500/20 text-cyan-300 flex items-center justify-center text-xl mb-3">🧠</div>
              <h3 class="font-display font-bold text-base text-white">IA Nativa Offline</h3>
              <p class="text-xs text-slate-300 mt-1.5 leading-relaxed">
                A assistente <strong>NexaMind</strong> resume documentos, organiza pastas e traduz áudios mesmo sem internet.
              </p>
            </div>
            <button onclick="openDetailModal('s3_ia')" class="mt-4 w-full py-2 rounded-xl bg-cyan-500/15 hover:bg-cyan-500/30 text-cyan-300 border border-cyan-500/30 text-xs font-bold transition cursor-pointer">
              Saiba Mais →
            </button>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex flex-col justify-between">
            <div>
              <div class="w-11 h-11 rounded-xl bg-indigo-500/20 text-indigo-300 flex items-center justify-center text-xl mb-3">☁️</div>
              <h3 class="font-display font-bold text-base text-white">Nuvem Híbrida Instantânea</h3>
              <p class="text-xs text-slate-300 mt-1.5 leading-relaxed">
                Seus arquivos aparecem em todos os aparelhos em tempo real, ocupando quase zero espaço no disco local.
              </p>
            </div>
            <button onclick="openDetailModal('s3_nuvem')" class="mt-4 w-full py-2 rounded-xl bg-indigo-500/15 hover:bg-indigo-500/30 text-indigo-300 border border-indigo-500/30 text-xs font-bold transition cursor-pointer">
              Saiba Mais →
            </button>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex flex-col justify-between">
            <div>
              <div class="w-11 h-11 rounded-xl bg-emerald-500/20 text-emerald-300 flex items-center justify-center text-xl mb-3">⚡</div>
              <h3 class="font-display font-bold text-base text-white">Zero Lentidão</h3>
              <p class="text-xs text-slate-300 mt-1.5 leading-relaxed">
                Sem registro fragmentado e sem processos inúteis. O sistema mantém a mesma rapidez após anos de uso.
              </p>
            </div>
            <button onclick="openDetailModal('s3_velocidade')" class="mt-4 w-full py-2 rounded-xl bg-emerald-500/15 hover:bg-emerald-500/30 text-emerald-300 border border-emerald-500/30 text-xs font-bold transition cursor-pointer">
              Saiba Mais →
            </button>
          </div>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Clique em "Saiba Mais" em qualquer diferencial para ver detalhes técnicos</span>
        <span class="text-cyan-400 font-semibold">Slide 3 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 4: INTERFACE GRÁFICA ==================== -->
    <section data-slide="4" data-title="Interface Gráfica" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-5 sm:p-8 flex-col justify-between">
      <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
        <div>
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-cyan-500/20 text-cyan-300 border border-cyan-500/30">Slide 04 • Interface Gráfica</span>
          <h2 class="font-display text-2xl sm:text-3xl font-bold text-white mt-1">Tela Inicial & Ícones Interativos do NexaOS</h2>
        </div>
        <button onclick="openDetailModal('s4_interface')" class="px-3.5 py-1.5 rounded-xl bg-indigo-600 hover:bg-indigo-500 text-white text-xs font-bold transition cursor-pointer">
          ✨ Explorar Recursos da Interface
        </button>
      </div>

      <!-- MOCKUP INTERATIVO DA ÁREA DE TRABALHO DO NEXAOS -->
      <div class="w-full h-80 sm:h-96 rounded-2xl border-2 border-slate-700/90 shadow-inner relative overflow-hidden flex flex-col justify-between p-4 select-none">
        <!-- Wallpaper Gráfico Temático -->
        <img
          src="https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=1200&q=80"
          alt="Wallpaper fluido da interface gráfica do NexaOS"
          data-fallback-theme="interface"
          onerror="handleImageFallback(this)"
          class="absolute inset-0 w-full h-full object-cover opacity-55 -z-10"
        />
        <div class="absolute inset-0 bg-slate-950/45 -z-10"></div>

        <!-- Barra Superior do NexaOS -->
        <div class="flex items-center justify-between bg-slate-950/75 backdrop-blur-md px-3.5 py-1.5 rounded-xl border border-white/15 text-xs text-slate-200">
          <div class="flex items-center gap-2 font-bold">
            <span class="w-2.5 h-2.5 rounded-full bg-cyan-400"></span>
            <span class="text-cyan-300">NexaOS</span>
            <span id="os-active-app-label" class="text-slate-300 font-normal ml-2">Área de Trabalho</span>
          </div>
          <div class="flex items-center gap-3">
            <span class="hidden sm:inline text-emerald-300">🛡️ Protegido</span>
            <span>📶 Wi-Fi 7</span>
            <span id="os-live-clock" class="font-mono font-bold text-cyan-300">16:24</span>
          </div>
        </div>

        <!-- Área Central: Widgets + Janela Simulada -->
        <div class="flex-1 grid grid-cols-1 sm:grid-cols-12 gap-3 my-3 items-center">
          <div class="sm:col-span-4 space-y-2.5">
            <div class="bg-slate-950/65 backdrop-blur-md border border-white/15 rounded-2xl p-3">
              <div class="text-[11px] uppercase tracking-wider text-cyan-300 font-bold">Widget IA Nexa</div>
              <p class="text-xs text-slate-200 mt-1">“Tudo pronto! Clique nos ícones abaixo para abrir aplicativos do sistema.”</p>
            </div>
            <div class="bg-slate-950/65 backdrop-blur-md border border-white/15 rounded-2xl p-3 flex items-center justify-between">
              <div>
                <div class="text-[11px] text-slate-300">Desempenho</div>
                <div class="text-sm font-bold text-emerald-400">CPU 8% • RAM 1.1GB</div>
              </div>
              <span class="text-xl">🚀</span>
            </div>
          </div>

          <!-- Janela Flutuante Interativa -->
          <div class="sm:col-span-8 h-full flex items-center justify-center">
            <div id="os-window" class="w-full h-44 sm:h-52 bg-slate-900/90 backdrop-blur-xl border border-cyan-400/50 rounded-2xl shadow-2xl flex flex-col overflow-hidden">
              <div class="bg-slate-800/95 px-3 py-2 flex items-center justify-between border-b border-slate-700">
                <div class="flex items-center gap-1.5">
                  <button onclick="closeOsWindow()" class="w-3 h-3 rounded-full bg-rose-500 hover:bg-rose-400 cursor-pointer" title="Fechar janela"></button>
                  <span class="w-3 h-3 rounded-full bg-amber-400"></span>
                  <span class="w-3 h-3 rounded-full bg-emerald-500"></span>
                  <span id="os-window-title" class="text-xs font-bold text-white ml-2">Central de Boas-Vindas NexaOS</span>
                </div>
                <span class="text-[10px] text-cyan-300 font-mono">NexaGlass UI</span>
              </div>
              <div id="os-window-body" class="p-4 text-xs sm:text-sm text-slate-200 flex-1 overflow-y-auto flex flex-col justify-center">
                <p class="font-bold text-cyan-300 mb-1">👆 Experimente a Barra de Tarefas Abaixo!</p>
                <p class="text-slate-300">Clique em <strong>Arquivos</strong>, <strong>Navegador</strong>, <strong>IA Nexa</strong> ou <strong>Ajustes</strong> para abrir janelas reais simuladas dentro do NexaOS.</p>
              </div>
            </div>
          </div>
        </div>

        <!-- Dock Inferior Clicável -->
        <div class="mx-auto bg-slate-950/85 backdrop-blur-xl border border-white/20 px-4 py-2 rounded-2xl flex items-center gap-4 sm:gap-6 shadow-xl">
          <button onclick="openOsApp('files')" class="flex flex-col items-center group cursor-pointer">
            <span class="w-9 h-9 rounded-xl bg-amber-500/25 border border-amber-400/50 flex items-center justify-center text-lg group-hover:-translate-y-1 transition">📁</span>
            <span class="text-[10px] text-slate-200 mt-0.5 font-medium">Arquivos</span>
          </button>
          <button onclick="openOsApp('browser')" class="flex flex-col items-center group cursor-pointer">
            <span class="w-9 h-9 rounded-xl bg-cyan-500/25 border border-cyan-400/50 flex items-center justify-center text-lg group-hover:-translate-y-1 transition">🌐</span>
            <span class="text-[10px] text-slate-200 mt-0.5 font-medium">Navegador</span>
          </button>
          <button onclick="openOsApp('ai')" class="flex flex-col items-center group cursor-pointer">
            <span class="w-9 h-9 rounded-xl bg-indigo-500/25 border border-indigo-400/50 flex items-center justify-center text-lg group-hover:-translate-y-1 transition">🤖</span>
            <span class="text-[10px] text-slate-200 mt-0.5 font-medium">IA Nexa</span>
          </button>
          <button onclick="openOsApp('settings')" class="flex flex-col items-center group cursor-pointer">
            <span class="w-9 h-9 rounded-xl bg-emerald-500/25 border border-emerald-400/50 flex items-center justify-center text-lg group-hover:-translate-y-1 transition">⚙️</span>
            <span class="text-[10px] text-slate-200 mt-0.5 font-medium">Ajustes</span>
          </button>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center pt-2">
        <span>Rascunho visual interativo • Design translúcido adaptativo</span>
        <span class="text-cyan-400 font-semibold">Slide 4 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 5: APLICATIVOS INCLUSOS ==================== -->
    <section data-slide="5" data-title="Aplicativos Inclusos" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div>
        <div class="flex items-center justify-between mb-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-emerald-500/20 text-emerald-300 border border-emerald-500/30">Slide 05 • Aplicativos Inclusos</span>
          <span class="text-xs text-slate-400">Programas nativos + Loja oficial</span>
        </div>
        <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Apps Inclusos & <span class="text-emerald-400">NexaStore</span></h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 my-4 items-stretch">
        <!-- Apps Pré-Instalados com Botão "Detalhes do App" -->
        <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-3">
          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-3.5 flex flex-col justify-between">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-xl bg-cyan-500/20 text-cyan-300 flex items-center justify-center text-xl shrink-0">📝</div>
              <div>
                <h3 class="font-bold text-white text-sm">NexaOffice</h3>
                <p class="text-[11px] text-slate-400">Textos, planilhas e slides compatíveis com Word/PDF.</p>
              </div>
            </div>
            <button onclick="openDetailModal('app_office')" class="mt-2.5 self-end text-[11px] font-bold text-cyan-300 hover:underline cursor-pointer">Detalhes do App →</button>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-3.5 flex flex-col justify-between">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-xl bg-indigo-500/20 text-indigo-300 flex items-center justify-center text-xl shrink-0">🧭</div>
              <div>
                <h3 class="font-bold text-white text-sm">NexaBrowser</h3>
                <p class="text-[11px] text-slate-400">Navegador ultrarrápido com bloqueio de rastreadores.</p>
              </div>
            </div>
            <button onclick="openDetailModal('app_browser')" class="mt-2.5 self-end text-[11px] font-bold text-indigo-300 hover:underline cursor-pointer">Detalhes do App →</button>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-3.5 flex flex-col justify-between">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-xl bg-purple-500/20 text-purple-300 flex items-center justify-center text-xl shrink-0">🎨</div>
              <div>
                <h3 class="font-bold text-white text-sm">NexaStudio</h3>
                <p class="text-[11px] text-slate-400">Editor de imagens, vídeos 4K e design vetorial leve.</p>
              </div>
            </div>
            <button onclick="openDetailModal('app_studio')" class="mt-2.5 self-end text-[11px] font-bold text-purple-300 hover:underline cursor-pointer">Detalhes do App →</button>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-3.5 flex flex-col justify-between">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-xl bg-emerald-500/20 text-emerald-300 flex items-center justify-center text-xl shrink-0">💻</div>
              <div>
                <h3 class="font-bold text-white text-sm">NexaCode</h3>
                <p class="text-[11px] text-slate-400">IDE educativa para programar em Python, JS e C++.</p>
              </div>
            </div>
            <button onclick="openDetailModal('app_code')" class="mt-2.5 self-end text-[11px] font-bold text-emerald-300 hover:underline cursor-pointer">Detalhes do App →</button>
          </div>
        </div>

        <!-- Simulação da Loja NexaStore + Imagem -->
        <div class="lg:col-span-5 rounded-2xl bg-gradient-to-b from-slate-800 to-slate-900 border border-cyan-500/35 overflow-hidden flex flex-col justify-between">
          <div class="relative h-28 w-full overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1551650975-87deedd944c3?auto=format&fit=crop&w=800&q=80"
              alt="Simulação da loja de aplicativos NexaStore"
              data-fallback-theme="apps"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-900 via-slate-900/45 to-transparent flex items-end justify-between p-3">
              <span class="font-display font-bold text-sm text-white">🛍️ NexaStore</span>
              <span class="text-[10px] px-2 py-0.5 rounded-full bg-emerald-500/30 text-emerald-200 border border-emerald-400/30">100% Verificada</span>
            </div>
          </div>

          <div class="p-3.5 space-y-2 flex-1 flex flex-col justify-center">
            <div class="flex items-center justify-between bg-slate-950/70 p-2 rounded-xl border border-slate-800">
              <div class="flex items-center gap-2">
                <span class="text-base">🎮</span>
                <div>
                  <div class="text-xs font-bold text-white">Steam & Cloud Play</div>
                  <div class="text-[10px] text-slate-400">Jogos sem instalar</div>
                </div>
              </div>
              <div class="flex gap-1.5">
                <button onclick="openDetailModal('store_steam')" class="px-2 py-1 rounded-lg text-[11px] bg-slate-800 text-slate-200 hover:bg-slate-700 cursor-pointer">Info</button>
                <button onclick="installAppDemo(this)" class="px-2.5 py-1 rounded-lg text-[11px] font-bold bg-cyan-500 hover:bg-cyan-400 text-slate-950 transition cursor-pointer">Instalar</button>
              </div>
            </div>

            <div class="flex items-center justify-between bg-slate-950/70 p-2 rounded-xl border border-slate-800">
              <div class="flex items-center gap-2">
                <span class="text-base">🎵</span>
                <div>
                  <div class="text-xs font-bold text-white">Spotify & NexaMusic</div>
                  <div class="text-[10px] text-slate-400">Áudio espacial Hi-Fi</div>
                </div>
              </div>
              <div class="flex gap-1.5">
                <button onclick="openDetailModal('store_music')" class="px-2 py-1 rounded-lg text-[11px] bg-slate-800 text-slate-200 hover:bg-slate-700 cursor-pointer">Info</button>
                <button onclick="installAppDemo(this)" class="px-2.5 py-1 rounded-lg text-[11px] font-bold bg-cyan-500 hover:bg-cyan-400 text-slate-950 transition cursor-pointer">Instalar</button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Sem propagandas no sistema (Zero Bloatware)</span>
        <span class="text-cyan-400 font-semibold">Slide 5 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 6: SEGURANÇA DIGITAL ==================== -->
    <section data-slide="6" data-title="Segurança Digital" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <div class="lg:col-span-7 space-y-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-emerald-500/20 text-emerald-300 border border-emerald-500/30">Slide 06 • Segurança Digital</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Proteção Blindada <span class="text-emerald-400">NexaGuard</span></h2>
          <p class="text-slate-300 text-xs sm:text-sm">
            Clique nos escudos abaixo para entender cada camada ou execute uma varredura simulada em tempo real:
          </p>
          <button onclick="runSecurityScan()" id="btn-security-scan" class="px-4 py-2 rounded-xl bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-bold text-xs sm:text-sm shadow-lg shadow-emerald-500/25 transition cursor-pointer">
            🛡️ Simular Escaneamento & Firewall
          </button>
        </div>

        <!-- Imagem de Cibersegurança -->
        <div class="lg:col-span-5">
          <div class="relative h-36 sm:h-40 rounded-2xl overflow-hidden border border-emerald-500/40 shadow-lg">
            <img
              src="https://images.unsplash.com/photo-1563986768609-322da13575f3?auto=format&fit=crop&w=800&q=80"
              alt="Cadeado digital, escudo e firewall do NexaOS"
              data-fallback-theme="security"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-slate-950/25 to-transparent flex items-end p-3">
              <span id="security-status-badge" class="text-xs font-bold text-emerald-300">✅ Firewall IA Ativo • 0 Ameaças Detectadas</span>
            </div>
          </div>
        </div>
      </div>

      <!-- 3 Camadas Clicáveis de Segurança -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 my-4">
        <button onclick="openDetailModal('sec_quantum')" class="text-left glass-panel rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-emerald-500/35 p-4 transition cursor-pointer group">
          <div class="flex items-center justify-between mb-2">
            <span class="text-2xl">🔐</span>
            <span class="text-[11px] font-bold text-emerald-300 group-hover:translate-x-1 transition">Ver detalhes →</span>
          </div>
          <h3 class="font-display font-bold text-base text-white">Criptografia Quântica</h3>
          <p class="text-xs text-slate-300 mt-1">Protege arquivos, senhas e mensagens contra interceptação externa.</p>
        </button>

        <button onclick="openDetailModal('sec_ransomware')" class="text-left glass-panel rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-cyan-500/35 p-4 transition cursor-pointer group">
          <div class="flex items-center justify-between mb-2">
            <span class="text-2xl">🛡️</span>
            <span class="text-[11px] font-bold text-cyan-300 group-hover:translate-x-1 transition">Ver detalhes →</span>
          </div>
          <h3 class="font-display font-bold text-base text-white">Escudo Anti-Ransomware</h3>
          <p class="text-xs text-slate-300 mt-1">Isola downloads suspeitos em bolha virtual (Sandbox) e mantém backups imutáveis.</p>
        </button>

        <button onclick="openDetailModal('sec_biometric')" class="text-left glass-panel rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-indigo-500/35 p-4 transition cursor-pointer group">
          <div class="flex items-center justify-between mb-2">
            <span class="text-2xl">🧬</span>
            <span class="text-[11px] font-bold text-indigo-300 group-hover:translate-x-1 transition">Ver detalhes →</span>
          </div>
          <h3 class="font-display font-bold text-base text-white">Cofre Biométrico</h3>
          <p class="text-xs text-slate-300 mt-1">Desbloqueio facial 3D, digital e controle total de câmera e microfone.</p>
        </button>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Núcleo protegido contra alterações não autorizadas</span>
        <span class="text-cyan-400 font-semibold">Slide 6 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 7: ACESSIBILIDADE ==================== -->
    <section data-slide="7" data-title="Acessibilidade" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div class="flex flex-wrap items-center justify-between gap-3">
        <div>
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-amber-500/20 text-amber-300 border border-amber-500/30">Slide 07 • Acessibilidade Universal</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-white mt-1">Inclusão Digital <span class="text-amber-400">Sem Barreiras</span></h2>
        </div>

        <!-- Botões Reais de Acessibilidade -->
        <div class="flex flex-wrap items-center gap-2 bg-slate-800/90 p-2 rounded-2xl border border-slate-700">
          <button onclick="toggleHighContrast()" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-amber-400 text-slate-950 hover:bg-amber-300 transition cursor-pointer">
            🌓 Alto Contraste
          </button>
          <button onclick="toggleLargeFont()" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-cyan-500 text-slate-950 hover:bg-cyan-400 transition cursor-pointer">
            🔍 Aumentar Fonte
          </button>
          <button onclick="toggleReadingGuide()" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-indigo-500 text-white hover:bg-indigo-400 transition cursor-pointer">
            📖 Leitura Guiada
          </button>
        </div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 my-4 items-stretch">
        <!-- Imagem de Símbolos de Acessibilidade -->
        <div class="lg:col-span-4 relative rounded-2xl overflow-hidden border border-amber-500/35 min-h-[190px] shadow-xl flex flex-col justify-between">
          <img
            src="https://images.unsplash.com/photo-1573164713988-8665fc963095?auto=format&fit=crop&w=800&q=80"
            alt="Recursos de acessibilidade e inclusão digital"
            data-fallback-theme="accessibility"
            onerror="handleImageFallback(this)"
            class="w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/35 to-transparent flex flex-col justify-end p-4">
            <div class="text-amber-300 font-bold text-xs mb-1">♿ • 👁️ • 🗣️ • 🤟 Libras IA</div>
            <button onclick="openDetailModal('s7_como_funciona')" class="w-full py-1.5 rounded-xl bg-amber-400 hover:bg-amber-300 text-slate-950 font-bold text-xs transition cursor-pointer">
              Como Funciona na Prática →
            </button>
          </div>
        </div>

        <!-- Cards de Recursos Inclusivos -->
        <div class="lg:col-span-8 grid grid-cols-1 sm:grid-cols-2 gap-3.5">
          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex items-start gap-3">
            <span class="text-2xl">🗣️</span>
            <div>
              <h3 class="font-display font-bold text-sm sm:text-base text-white">Leitor de Tela Neural</h3>
              <p class="text-xs text-slate-300 mt-1">Voz natural que lê textos e descreve imagens automaticamente para pessoas com deficiência visual.</p>
            </div>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex items-start gap-3">
            <span class="text-2xl">👁️</span>
            <div>
              <h3 class="font-display font-bold text-sm sm:text-base text-white">Controle Ocular e por Voz</h3>
              <p class="text-xs text-slate-300 mt-1">Navegação completa usando apenas movimentos dos olhos pela webcam ou comandos de voz.</p>
            </div>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex items-start gap-3">
            <span class="text-2xl">🤟</span>
            <div>
              <h3 class="font-display font-bold text-sm sm:text-base text-white">Legendas & Tradutor Libras</h3>
              <p class="text-xs text-slate-300 mt-1">Gera legendas ao vivo em qualquer vídeo e oferece avatar 3D tradutor de Libras integrado.</p>
            </div>
          </div>

          <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 flex items-start gap-3">
            <span class="text-2xl">🎨</span>
            <div>
              <h3 class="font-display font-bold text-sm sm:text-base text-white">Filtros para Daltonismo</h3>
              <p class="text-xs text-slate-300 mt-1">Ajuste cromático inteligente e modo de foco reduzindo distrações visuais.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Testou os botões acima? Eles alteram esta apresentação em tempo real!</span>
        <span class="text-cyan-400 font-semibold">Slide 7 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 8: DESEMPENHO E CONSUMO DE ENERGIA ==================== -->
    <section data-slide="8" data-title="Desempenho e Energia" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <div class="lg:col-span-7 space-y-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-cyan-500/20 text-cyan-300 border border-cyan-500/30">Slide 08 • Desempenho & Energia</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Velocidade Máxima. <span class="text-emerald-400">Pouca Bateria.</span></h2>
          <p class="text-slate-300 text-xs sm:text-sm">Alterne entre os perfis inteligentes de energia do NexaOS para ver os medidores mudarem:</p>
          <!-- Botões Seletores de Perfil de Energia -->
          <div class="flex flex-wrap gap-2 pt-1">
            <button onclick="setPowerProfile('turbo')" id="pwr-btn-turbo" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">🚀 Modo Turbo Gamer</button>
            <button onclick="setPowerProfile('balanced')" id="pwr-btn-balanced" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-cyan-500 text-slate-950 transition cursor-pointer">⚡ Equilibrado</button>
            <button onclick="setPowerProfile('eco')" id="pwr-btn-eco" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">🔋 Ultra Economia</button>
          </div>
        </div>

        <!-- Imagem de Velocidade & Hardware -->
        <div class="lg:col-span-5">
          <div class="relative h-36 sm:h-40 rounded-2xl overflow-hidden border border-cyan-500/35 shadow-lg">
            <img
              src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=800&q=80"
              alt="Processador rápido, engrenagens e eficiência energética"
              data-fallback-theme="performance"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-transparent to-transparent flex items-end p-3">
              <span id="pwr-tagline" class="text-xs font-semibold text-cyan-300">⚡ Perfil Equilibrado • Fluidez diária com baixo consumo</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Medidores Dinâmicos (CPU, RAM, FPS e Autonomia de Bateria) -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-4 my-4">
        <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 text-center">
          <span class="text-2xl">⚙️</span>
          <div id="metric-cpu" class="font-display text-2xl sm:text-3xl font-extrabold text-cyan-300 mt-1">18%</div>
          <div class="text-xs font-semibold text-white">Uso de CPU</div>
          <div class="w-full h-1.5 bg-slate-700 rounded-full mt-2 overflow-hidden">
            <div id="bar-cpu" class="h-full bg-cyan-400 transition-all duration-500" style="width: 18%;"></div>
          </div>
        </div>

        <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 text-center">
          <span class="text-2xl">🧠</span>
          <div id="metric-ram" class="font-display text-2xl sm:text-3xl font-extrabold text-indigo-300 mt-1">1.2 GB</div>
          <div class="text-xs font-semibold text-white">Memória RAM</div>
          <div class="w-full h-1.5 bg-slate-700 rounded-full mt-2 overflow-hidden">
            <div id="bar-ram" class="h-full bg-indigo-400 transition-all duration-500" style="width: 24%;"></div>
          </div>
        </div>

        <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 text-center">
          <span class="text-2xl">⚡</span>
          <div id="metric-fps" class="font-display text-2xl sm:text-3xl font-extrabold text-amber-300 mt-1">120 FPS</div>
          <div class="text-xs font-semibold text-white">Taxa de Quadros</div>
          <div class="w-full h-1.5 bg-slate-700 rounded-full mt-2 overflow-hidden">
            <div id="bar-fps" class="h-full bg-amber-400 transition-all duration-500" style="width: 70%;"></div>
          </div>
        </div>

        <div class="glass-panel rounded-2xl bg-slate-800/60 border border-slate-700 p-4 text-center">
          <span class="text-2xl">🔋</span>
          <div id="metric-bat" class="font-display text-2xl sm:text-3xl font-extrabold text-emerald-400 mt-1">16 horas</div>
          <div class="text-xs font-semibold text-white">Autonomia Bateria</div>
          <div class="w-full h-1.5 bg-slate-700 rounded-full mt-2 overflow-hidden">
            <div id="bar-bat" class="h-full bg-emerald-400 transition-all duration-500" style="width: 78%;"></div>
          </div>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Inicialização completa em apenas 1.9 segundo</span>
        <span class="text-cyan-400 font-semibold">Slide 8 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 9: COMPATIBILIDADE ==================== -->
    <section data-slide="9" data-title="Compatibilidade" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <div class="lg:col-span-7 space-y-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-indigo-500/20 text-indigo-300 border border-indigo-500/30">Slide 09 • Compatibilidade</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Funciona com Tudo, <span class="text-indigo-400">Sem Erro</span></h2>
          <p class="text-slate-300 text-xs sm:text-sm">Clique nas categorias abaixo para verificar a compatibilidade instantânea do NexaOS:</p>
          <!-- Botões Verificadores de Compatibilidade -->
          <div class="flex flex-wrap gap-2 pt-1">
            <button onclick="selectCompatTab('peripherals')" id="compat-btn-peripherals" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-indigo-500 text-white transition cursor-pointer">🖱️ Periféricos Plug & Play</button>
            <button onclick="selectCompatTab('apps')" id="compat-btn-apps" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">📦 Apps Windows/Linux/Android</button>
            <button onclick="selectCompatTab('games')" id="compat-btn-games" class="px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">🎮 Jogos & Drivers</button>
          </div>
        </div>

        <!-- Imagem de Periféricos -->
        <div class="lg:col-span-5">
          <div class="relative h-36 sm:h-40 rounded-2xl overflow-hidden border border-indigo-500/35 shadow-lg">
            <img
              src="https://images.unsplash.com/photo-1587829741301-dc798b83add3?auto=format&fit=crop&w=800&q=80"
              alt="Mouse, teclado e periféricos compatíveis com NexaOS"
              data-fallback-theme="peripherals"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-transparent to-transparent flex items-end p-3">
              <span class="text-xs font-semibold text-indigo-300">🖱️ Mouse • ⌨️ Teclado • 🖨️ Impressora • 📱 Apps</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Painel Dinâmico do Verificador de Compatibilidade -->
      <div id="compat-details-box" class="glass-panel rounded-2xl bg-slate-800/65 border border-indigo-500/35 p-5 my-4 grid grid-cols-1 sm:grid-cols-3 gap-4">
        <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
          <div class="text-sm font-bold text-white">🖱️ Mouse & Teclado</div>
          <p class="text-xs text-slate-300 mt-1">Reconhecimento imediato via USB-C ou Bluetooth sem instalar nenhum programa extra.</p>
          <span class="inline-block mt-2 text-[11px] font-bold text-emerald-400">✓ 100% Plug & Play</span>
        </div>
        <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
          <div class="text-sm font-bold text-white">🖨️ Impressoras & Scanners</div>
          <p class="text-xs text-slate-300 mt-1">Detecta automaticamente qualquer impressora Wi-Fi ou USB na rede local.</p>
          <span class="inline-block mt-2 text-[11px] font-bold text-emerald-400">✓ Sem Driver Manual</span>
        </div>
        <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
          <div class="text-sm font-bold text-white">🎧 Webcams & Áudio</div>
          <p class="text-xs text-slate-300 mt-1">Microfones, fones Bluetooth e monitores externos configurados em 1 segundo.</p>
          <span class="inline-block mt-2 text-[11px] font-bold text-emerald-400">✓ Baixa Latência</span>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Camada universal NexaBridge integrada ao sistema</span>
        <span class="text-cyan-400 font-semibold">Slide 9 de 10</span>
      </div>
    </section>

    <!-- ==================== SLIDE 10: PREÇO E PÚBLICO-ALVO ==================== -->
    <section data-slide="10" data-title="Preço e Público-Alvo" class="slide-container slide-hidden w-full min-h-[540px] rounded-3xl bg-slate-900/75 backdrop-blur-xl border border-slate-800 shadow-2xl p-6 sm:p-10 flex-col justify-between">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <div class="lg:col-span-7 space-y-2">
          <span class="px-3 py-1 rounded-full text-xs font-semibold uppercase bg-emerald-500/20 text-emerald-300 border border-emerald-500/30">Slide 10 • Preço & Público-Alvo</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-white">Escolha seu Perfil e <span class="text-emerald-400">Veja o Plano Ideal</span></h2>
          <!-- Botões Seletores de Público-Alvo -->
          <div class="flex flex-wrap gap-2 pt-1">
            <button onclick="selectAudience('students')" id="aud-btn-students" class="px-3.5 py-1.5 rounded-xl text-xs font-bold bg-emerald-500 text-slate-950 transition cursor-pointer">🎓 Estudantes</button>
            <button onclick="selectAudience('gamers')" id="aud-btn-gamers" class="px-3.5 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">🎮 Gamers</button>
            <button onclick="selectAudience('enterprise')" id="aud-btn-enterprise" class="px-3.5 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer">🏢 Empresas</button>
          </div>
        </div>

        <!-- Imagem Dinâmica do Público-Alvo -->
        <div class="lg:col-span-5">
          <div class="relative h-36 sm:h-40 rounded-2xl overflow-hidden border border-emerald-500/35 shadow-lg">
            <img
              id="audience-img"
              src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=800&q=80"
              alt="Público-alvo do NexaOS"
              data-fallback-theme="audience"
              onerror="handleImageFallback(this)"
              class="w-full h-full object-cover transition duration-500"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-transparent to-transparent flex items-end p-3">
              <span id="audience-img-caption" class="text-xs font-bold text-emerald-300">🎓 Estudantes, Escolas & Universidades</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Card Dinâmico do Plano Recomendado -->
      <div id="audience-plan-card" class="glass-panel rounded-2xl bg-gradient-to-br from-emerald-950/50 to-slate-800/80 border-2 border-emerald-500/40 p-5 my-4 grid grid-cols-1 md:grid-cols-12 gap-4 items-center">
        <div class="md:col-span-5 border-b md:border-b-0 md:border-r border-slate-700 pb-3 md:pb-0 md:pr-4">
          <span id="plan-tag" class="px-2.5 py-0.5 rounded-full text-[11px] font-extrabold bg-emerald-500 text-slate-950">LICENÇA EDUCACIONAL</span>
          <h3 id="plan-name" class="font-display text-2xl font-bold text-white mt-2">NexaOS Edu & Personal</h3>
          <div id="plan-price" class="font-display text-3xl sm:text-4xl font-extrabold text-emerald-400 mt-1">GRATUITO <span class="text-xs font-normal text-slate-300">/ para sempre</span></div>
        </div>
        <div class="md:col-span-7 space-y-2 text-xs sm:text-sm text-slate-200">
          <p id="plan-desc" class="text-slate-300">Perfeito para estudantes, professores e uso doméstico diário, sem anúncios e sem custo de licença.</p>
          <ul id="plan-benefits" class="space-y-1 text-xs text-emerald-200 font-medium">
            <li>✅ Pacote completo NexaOffice + NexaCode + NexaStudio inclusos</li>
            <li>✅ 100 GB de armazenamento gratuito na nuvem NexaCloud</li>
            <li>✅ Atualizações de segurança vitalícias sem cobrar nada</li>
          </ul>
        </div>
      </div>

      <div class="text-xs text-slate-400 flex justify-between items-center border-t border-slate-800 pt-3">
        <span>Obrigado pela atenção! • Apresentação Oficial NexaOS</span>
        <span class="text-cyan-400 font-bold">Slide 10 de 10</span>
      </div>
    </section>

  </main>

  <!-- VISÃO GERAL EM GRADE (TODOS OS 10 SLIDES) -->
  <section id="grid-overview" class="hidden max-w-6xl w-full mx-auto p-4 sm:p-8 flex-1">
    <div class="flex items-center justify-between mb-6">
      <div>
        <h2 class="font-display text-2xl font-bold text-white">Todos os Slides — NexaOS (10 Slides)</h2>
        <p class="text-sm text-slate-400">Clique em qualquer cartão para ir diretamente ao slide.</p>
      </div>
      <button onclick="toggleGridView()" class="px-4 py-2 rounded-xl bg-cyan-500 hover:bg-cyan-400 text-slate-950 text-sm font-bold transition cursor-pointer">
        Voltar à Apresentação
      </button>
    </div>
    <div id="grid-cards-container" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
      <!-- Gerado via JS -->
    </div>
  </section>

  <!-- BARRA INFERIOR DE NAVEGAÇÃO -->
  <footer id="bottom-nav" class="sticky bottom-0 z-30 bg-slate-900/90 backdrop-blur-md border-t border-slate-800 px-4 py-3">
    <div class="max-w-4xl mx-auto flex items-center justify-between gap-3">
      <button id="btn-prev" onclick="prevSlide()" class="px-4 py-2 rounded-xl bg-slate-800 hover:bg-slate-700 disabled:opacity-40 disabled:pointer-events-none text-white text-sm font-semibold border border-slate-700 transition flex items-center gap-2 cursor-pointer">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"/></svg>
        <span>Anterior</span>
      </button>

      <!-- Bolinhas Indicadoras -->
      <div id="slide-dots" class="flex items-center gap-1.5 sm:gap-2 overflow-x-auto py-1"></div>

      <button id="btn-next" onclick="nextSlide()" class="px-4 py-2 rounded-xl bg-gradient-to-r from-cyan-500 to-indigo-600 hover:from-cyan-400 hover:to-indigo-500 disabled:opacity-40 disabled:pointer-events-none text-slate-950 text-sm font-bold shadow-lg shadow-cyan-500/20 transition flex items-center gap-2 cursor-pointer">
        <span>Próximo</span>
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/></svg>
      </button>
    </div>
  </footer>

  <!-- MODAL INTERATIVO "ENTENDA MAIS" (DETALHES TÉCNICOS DE CADA SLIDE) -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden bg-slate-950/80 backdrop-blur-sm items-center justify-center p-4" onclick="if(event.target===this) closeDetailModal()">
    <div class="bg-slate-900 border border-cyan-500/40 rounded-3xl max-w-xl w-full shadow-2xl overflow-hidden animate-[fadeIn_0.2s_ease]">
      <div class="px-6 py-4 bg-slate-800/80 border-b border-slate-700 flex items-center justify-between">
        <div class="flex items-center gap-2.5">
          <span id="modal-detail-icon" class="text-2xl">💡</span>
          <h3 id="modal-detail-title" class="font-display font-bold text-lg text-white">Detalhes Técnicos NexaOS</h3>
        </div>
        <button onclick="closeDetailModal()" class="w-8 h-8 rounded-xl bg-slate-700 hover:bg-slate-600 text-slate-200 flex items-center justify-center font-bold cursor-pointer">✕</button>
      </div>
      <div class="p-6 space-y-4">
        <p id="modal-detail-desc" class="text-sm text-slate-200 leading-relaxed"></p>
        <div id="modal-detail-highlights" class="bg-slate-950/70 border border-slate-800 rounded-2xl p-4 space-y-2 text-xs text-cyan-200"></div>
        <div class="flex justify-end">
          <button onclick="closeDetailModal()" class="px-5 py-2 rounded-xl bg-cyan-500 hover:bg-cyan-400 text-slate-950 font-bold text-xs sm:text-sm transition cursor-pointer">
            Entendi! Voltar ao Slide
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- NOTIFICAÇÃO FLUTUANTE (TOAST) -->
  <div id="toast-box" class="fixed bottom-20 left-1/2 -translate-x-1/2 z-50 hidden px-4 py-2.5 rounded-2xl bg-slate-800 border border-cyan-500/50 text-white text-xs sm:text-sm font-medium shadow-2xl"></div>

  <!-- JAVASCRIPT COMPLETO DA APRESENTAÇÃO INTERATIVA -->
  <script>
    // Fallback automático em SVG caso alguma imagem externa falhe
    function handleImageFallback(imgElement) {
      imgElement.onerror = null;
      const theme = imgElement.getAttribute('data-fallback-theme') || 'default';
      const themes = {
        logo: { c1: '#0e7490', c2: '#312e81', label: 'NEXA OS • NEXACORE' },
        devices: { c1: '#0f172a', c2: '#0284c7', label: 'PC • SMARTPHONE • CONSOLE • TABLET' },
        innovation: { c1: '#1e1b4b', c2: '#0891b2', label: 'NEXAMIND IA OFFLINE' },
        interface: { c1: '#0f172a', c2: '#4338ca', label: 'NEXAGLASS UI' },
        apps: { c1: '#064e3b', c2: '#0284c7', label: 'NEXASTORE & APPS' },
        security: { c1: '#022c22', c2: '#059669', label: 'NEXAGUARD SEGURANÇA' },
        accessibility: { c1: '#451a03', c2: '#d97706', label: 'ACESSIBILIDADE UNIVERSAL' },
        performance: { c1: '#083344', c2: '#10b981', label: 'DESEMPENHO & BATERIA' },
        peripherals: { c1: '#1e1b4b', c2: '#4f46e5', label: 'PLUG & PLAY UNIVERSAL' },
        audience: { c1: '#064e3b', c2: '#1d4ed8', label: 'ESTUDANTES • GAMERS • EMPRESAS' },
        default: { c1: '#0f172a', c2: '#0891b2', label: 'NEXA OS' }
      };
      const t = themes[theme] || themes.default;
      const svg = `<svg xmlns="http://www.w3.org/2000/svg" width="800" height="450" viewBox="0 0 800 450">
        <defs>
          <linearGradient id="g" x1="0" y1="0" x2="1" y2="1">
            <stop offset="0%" stop-color="${t.c1}"/>
            <stop offset="100%" stop-color="${t.c2}"/>
          </linearGradient>
        </defs>
        <rect width="800" height="450" fill="url(#g)"/>
        <polygon points="400,60 540,140 540,310 400,390 260,310 260,140" fill="none" stroke="#ffffff" stroke-opacity="0.12" stroke-width="4"/>
        <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" fill="#ffffff" font-family="sans-serif" font-weight="bold" font-size="24" letter-spacing="2">${t.label}</text>
      </svg>`;
      imgElement.src = 'data:image/svg+xml;charset=UTF-8,' + encodeURIComponent(svg);
    }

    // ==================== NAVEGAÇÃO ENTRE OS 10 SLIDES ====================
    let currentSlide = 1;
    const totalSlides = 10;
    let isGridView = false;

    document.addEventListener('DOMContentLoaded', () => {
      buildSlideDots();
      buildGridOverview();
      updateSlideUI();
      startLiveClock();
    });

    function buildSlideDots() {
      const container = document.getElementById('slide-dots');
      container.innerHTML = '';
      for (let i = 1; i <= totalSlides; i++) {
        const dot = document.createElement('button');
        dot.setAttribute('aria-label', `Ir para slide ${i}`);
        dot.className = `h-2.5 rounded-full transition-all duration-300 cursor-pointer ${i === currentSlide ? 'w-7 bg-cyan-400' : 'w-2.5 bg-slate-600 hover:bg-slate-400'}`;
        dot.onclick = () => goToSlide(i);
        container.appendChild(dot);
      }
    }

    function updateSlideUI() {
      document.querySelectorAll('[data-slide]').forEach(slide => {
        const num = parseInt(slide.getAttribute('data-slide'), 10);
        if (num === currentSlide) {
          slide.classList.remove('slide-hidden');
          slide.classList.add('slide-active');
        } else {
          slide.classList.remove('slide-active');
          slide.classList.add('slide-hidden');
        }
      });

      document.getElementById('top-slide-badge').textContent = `Slide ${currentSlide} de ${totalSlides}`;
      document.getElementById('progress-bar').style.width = `${(currentSlide / totalSlides) * 100}%`;
      document.getElementById('btn-prev').disabled = currentSlide === 1;
      document.getElementById('btn-next').disabled = currentSlide === totalSlides;
      buildSlideDots();
    }

    function nextSlide() {
      if (currentSlide < totalSlides) {
        currentSlide++;
        updateSlideUI();
      }
    }

    function prevSlide() {
      if (currentSlide > 1) {
        currentSlide--;
        updateSlideUI();
      }
    }

    function goToSlide(num) {
      currentSlide = num;
      if (isGridView) toggleGridView();
      updateSlideUI();
    }

    // Teclado (Setas e Esc)
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape') {
        closeDetailModal();
        return;
      }
      if (document.getElementById('detail-modal').classList.contains('flex')) return;
      if (e.key === 'ArrowRight' || e.key === 'PageDown') nextSlide();
      else if (e.key === 'ArrowLeft' || e.key === 'PageUp') prevSlide();
    });

    // Suporte a deslize (Touch Swipe)
    let touchStartX = 0;
    document.addEventListener('touchstart', (e) => {
      touchStartX = e.changedTouches[0].screenX;
    }, { passive: true });

    document.addEventListener('touchend', (e) => {
      if (isGridView || document.getElementById('detail-modal').classList.contains('flex')) return;
      const diff = touchStartX - e.changedTouches[0].screenX;
      if (Math.abs(diff) > 55) {
        if (diff > 0) nextSlide();
        else prevSlide();
      }
    }, { passive: true });

    // Grade Geral ("Todos os Slides")
    function buildGridOverview() {
      const container = document.getElementById('grid-cards-container');
      container.innerHTML = '';
      document.querySelectorAll('[data-slide]').forEach(slide => {
        const num = parseInt(slide.getAttribute('data-slide'), 10);
        const title = slide.getAttribute('data-title');
        const card = document.createElement('button');
        card.className = 'text-left rounded-2xl bg-slate-900/90 hover:bg-slate-800 border border-slate-700 hover:border-cyan-400 p-5 transition flex flex-col justify-between gap-3 group cursor-pointer';
        card.onclick = () => goToSlide(num);
        card.innerHTML = `
          <div class="flex items-center justify-between w-full">
            <span class="px-2.5 py-1 rounded-lg text-xs font-bold bg-cyan-500/20 text-cyan-300">Slide ${String(num).padStart(2, '0')}</span>
            <span class="text-xs text-slate-400 group-hover:text-cyan-400 transition">Abrir →</span>
          </div>
          <div class="font-display font-bold text-lg text-white">${title}</div>
        `;
        container.appendChild(card);
      });
    }

    function toggleGridView() {
      isGridView = !isGridView;
      document.getElementById('presentation-stage').classList.toggle('hidden', isGridView);
      document.getElementById('bottom-nav').classList.toggle('hidden', isGridView);
      document.getElementById('grid-overview').classList.toggle('hidden', !isGridView);
      document.getElementById('grid-btn-text').textContent = isGridView ? 'Modo Slide' : 'Todos os Slides';
    }

    function toggleFullscreen() {
      if (!document.fullscreenElement) {
        document.documentElement.requestFullscreen().catch(() => showToast('Tela cheia solicitada.'));
      } else {
        document.exitFullscreen();
      }
    }

    // ==================== BANCO DE CONTEÚDO DOS MODAIS "ENTENDA MAIS" ====================
    const detailTopics = {
      s1_origem: {
        icon: '🔷',
        title: 'Origem do Nome "NexaOS" & Identidade',
        desc: 'O nome NexaOS vem de "Nexus" (conexão central). Ele simboliza um sistema que une hardware, inteligência artificial e nuvem em um único ponto fluido, representado pelo logotipo hexagonal de 6 vértices.',
        points: [
          '• Slogan: "Inteligência fluida em cada tela"',
          '• Paleta Ciano + Índigo + Esmeralda: transmite tecnologia limpa e baixo cansaço visual',
          '• Design modular preparado para telas pequenas ou monitores ultrawide'
        ]
      },
      s1_kernel: {
        icon: '⚙️',
        title: 'Arquitetura Microkernel NexaCore v2.0',
        desc: 'Diferente de sistemas antigos monolíticos, o NexaCore mantém apenas o gerenciamento essencial de memória e CPU no núcleo. Drivers e aplicativos rodam isolados, impedindo telas azuis ou travamentos.',
        points: [
          '• Escrito em Rust e C++ moderno para máxima segurança de memória',
          '• Recuperação automática de drivers em menos de 50 milissegundos',
          '• Suporte nativo a processadores x86-64 e ARM'
        ]
      },
      s2_adaptacao: {
        icon: '📱',
        title: 'Como Funciona o NexaFlex UI?',
        desc: 'O NexaFlex detecta o tamanho da tela e os sensores do aparelho em tempo real. Se você conectar um smartphone NexaOS a um monitor, ele alterna instantaneamente para o modo Desktop com janelas.',
        points: [
          '• PC/Notebook: Múltiplas janelas flutuantes e barra inferior completa',
          '• Smartphone/Tablet: Gestos fluidos com uma mão e divisão de tela por toque',
          '• Videogame: Interface 100% navegável por controle/joystick em 4K 120Hz'
        ]
      },
      s3_ia: {
        icon: '🧠',
        title: 'NexaMind: Inteligência Artificial Offline',
        desc: 'A IA do NexaOS roda localmente no chip neural (NPU) do dispositivo. Isso significa respostas instantâneas, funcionamento sem internet e privacidade total, pois seus dados nunca saem do aparelho.',
        points: [
          '• Busca semântica: encontre arquivos descrevendo o conteúdo ("trabalho de história sobre o Brasil")',
          '• Resumo automático de PDFs, páginas web e gravações de aula',
          '• Automação inteligente de brilho, som e organização de janelas'
        ]
      },
      s3_nuvem: {
        icon: '☁️',
        title: 'Nuvem Híbrida Instantânea (NexaLink)',
        desc: 'Com o NexaLink, seus documentos ficam disponíveis em todos os dispositivos sem precisar enviar e-mails para si mesmo ou usar cabos USB.',
        points: [
          '• Área de transferência universal: copie no celular e cole no PC',
          '• Arquivos sob demanda: economiza até 80% do armazenamento interno',
          '• Sincronização criptografada ponto a ponto'
        ]
      },
      s3_velocidade: {
        icon: '⚡',
        title: 'Zero Lentidão ao Longo dos Anos',
        desc: 'Sistemas tradicionais acumulam lixo digital e processos ocultos que deixam o computador lento com o tempo. No NexaOS, cada app é instalado em um contêiner limpo que não deixa rastros ao ser removido.',
        points: [
          '• Sem registro centralizado que corrompe ou fica pesado',
          '• Atualizações em partição dupla: instala em segundo plano sem reiniciar',
          '• Desempenho constante mesmo em notebooks básicos'
        ]
      },
      s4_interface: {
        icon: '✨',
        title: 'Recursos da Interface NexaGlass UI',
        desc: 'A interface foi projetada para reduzir distrações e acelerar o acesso às tarefas diárias com transparências suaves, cantos arredondados e agrupamento inteligente de janelas.',
        points: [
          '• Snap Inteligente: organize até 4 janelas na tela com um clique',
          '• Widgets dinâmicos na lateral com resumo do dia e status do sistema',
          '• Tema escuro nativo calibrado para economia de energia em telas OLED'
        ]
      },
      app_office: {
        icon: '📝',
        title: 'NexaOffice — Suíte de Produtividade',
        desc: 'Inclui editor de documentos, planilhas inteligentes e criador de slides com suporte total aos formatos .docx, .xlsx, .pptx e .pdf, já vindo instalado gratuitamente.',
        points: ['• Correção gramatical e geração de gráficos assistida pela IA Nexa', '• Colaboração em tempo real via link']
      },
      app_browser: {
        icon: '🧭',
        title: 'NexaBrowser — Navegação Privada e Leve',
        desc: 'Construído para consumir 40% menos memória RAM que navegadores comuns, bloqueando rastreadores de anúncios e scripts maliciosos por padrão.',
        points: ['• Modo Leitura limpa artigos com um clique', '• Suspensão automática de abas inativas']
      },
      app_studio: {
        icon: '🎨',
        title: 'NexaStudio — Criação Visual e Vídeo',
        desc: 'Ferramenta nativa para editar fotos, recortar fundos com IA e montar vídeos escolares ou profissionais em 4K usando aceleração de hardware.',
        points: ['• Exportação rápida para redes sociais e apresentações', '• Biblioteca gratuita de ícones e fontes']
      },
      app_code: {
        icon: '💻',
        title: 'NexaCode — Ambiente de Programação',
        desc: 'Ideal para estudantes de tecnologia e desenvolvedores: já vem com terminal integrado, destaque de sintaxe e suporte pronto para Python, JavaScript, HTML/CSS e C++.',
        points: ['• Execução de código com 1 clique sem configurações complexas', '• Assistente de explicação de erros integrado']
      },
      store_steam: {
        icon: '🎮',
        title: 'Steam & Cloud Play na NexaStore',
        desc: 'Permite rodar jogos instalados localmente com modo Game Boost ou jogar títulos pesados via streaming na nuvem mesmo em notebooks simples.',
        points: ['• Suporte nativo a controles Xbox, PlayStation e genéricos']
      },
      store_music: {
        icon: '🎵',
        title: 'Spotify & NexaMusic Hi-Fi',
        desc: 'Integração direta com a barra superior do sistema para controlar músicas, podcasts e equalizador espacial 3D sem abrir janelas.',
        points: ['• Modo foco com sons ambientes integrado']
      },
      sec_quantum: {
        icon: '🔐',
        title: 'Criptografia Quântica Pós-Modernidade',
        desc: 'Todos os arquivos salvos no disco e trafegados na rede utilizam algoritmos resistentes a ataques avançados, garantindo que apenas você tenha a chave de leitura.',
        points: ['• Proteção automática de Wi-Fi público com VPN nativa', '• Cofre de senhas integrado ao navegador']
      },
      sec_ransomware: {
        icon: '🛡️',
        title: 'Escudo Anti-Ransomware & Sandbox',
        desc: 'Qualquer arquivo baixado da internet é executado dentro de uma caixa isolada (Sandbox). Se tentar sequestrar ou criptografar suas pastas, o NexaGuard bloqueia e restaura tudo na hora.',
        points: ['• Partição do sistema somente-leitura (imutável)', '• Pontos de restauração instantâneos a cada hora']
      },
      sec_biometric: {
        icon: '🧬',
        title: 'Cofre Biométrico & Privacidade de Hardware',
        desc: 'Desbloqueie o computador com reconhecimento facial 3D, impressão digital ou aproximação do seu smartphone NexaOS. Um indicador luminoso avisa sempre que câmera ou microfone são ativados.',
        points: ['• Bloqueio de câmera e microfone por software com 1 clique', '• Zero coleta de dados pessoais para publicidade']
      },
      s7_como_funciona: {
        icon: '♿',
        title: 'Como a Acessibilidade Funciona no NexaOS?',
        desc: 'Todos os recursos inclusivos fazem parte do núcleo do sistema, funcionando em qualquer aplicativo ou site sem exigir instalações extras ou custos adicionais.',
        points: [
          '• Pressione 3x a tecla Espaço na tela inicial para ativar o assistente de voz',
          '• Avatar de Libras traduz textos selecionados em tempo real',
          '• Calibração de cores para protanopia, deuteranopia e tritanopia'
        ]
      }
    };

    function openDetailModal(key) {
      const item = detailTopics[key];
      if (!item) return;
      document.getElementById('modal-detail-icon').textContent = item.icon;
      document.getElementById('modal-detail-title').textContent = item.title;
      document.getElementById('modal-detail-desc').textContent = item.desc;
      document.getElementById('modal-detail-highlights').innerHTML = item.points.map(p => `<p>${p}</p>`).join('');
      const modal = document.getElementById('detail-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // ==================== SLIDE 2: SELETOR DE DISPOSITIVOS ====================
    function selectDeviceMode(mode) {
      const modes = {
        pc: {
          icon: '💻',
          title: 'Modo Desktop & Notebook',
          badge: 'Multitarefa Completa',
          desc: 'Interface com múltiplas janelas flutuantes, barra de tarefas inteligente, suporte a até 4 monitores 8K e atalhos profissionais de teclado.',
          ram: '1.1 GB',
          input: 'Mouse, Teclado & Touch'
        },
        phone: {
          icon: '📱',
          title: 'Modo Smartphone',
          badge: 'Gestos com 1 Mão',
          desc: 'Layout vertical dinâmico com botões alcançáveis pelo polegar, widgets interativos na tela de bloqueio e economia extrema de bateria em 5G.',
          ram: '750 MB',
          input: 'Toque & Comandos de Voz'
        },
        console: {
          icon: '🎮',
          title: 'Modo Videogame / Console',
          badge: 'Máximo FPS & GPU',
          desc: 'Pausa todos os processos em segundo plano, dedica 98% da placa de vídeo aos jogos e oferece menu panorâmico navegável pelo controle.',
          ram: '680 MB',
          input: 'Joystick Xbox / PS / PC'
        },
        tablet: {
          icon: '📟',
          title: 'Modo Tablet & Estúdio',
          badge: 'Caneta Stylus Zero-Delay',
          desc: 'Tela dividida inteligente para assistir aulas enquanto faz anotações à mão, com reconhecimento instantâneo de escrita e desenhos.',
          ram: '890 MB',
          input: 'Caneta Digital & Multi-Toque'
        }
      };

      const data = modes[mode];
      if (!data) return;

      document.getElementById('dev-icon').textContent = data.icon;
      document.getElementById('dev-title').textContent = data.title;
      document.getElementById('dev-badge').textContent = data.badge;
      document.getElementById('dev-desc').textContent = data.desc;
      document.getElementById('dev-ram').textContent = data.ram;
      document.getElementById('dev-input').textContent = data.input;

      ['pc', 'phone', 'console', 'tablet'].forEach(k => {
        const btn = document.getElementById(`dev-btn-${k}`);
        if (k === mode) {
          btn.className = 'px-3 py-1.5 rounded-xl text-xs font-bold bg-cyan-500 text-slate-950 transition cursor-pointer';
        } else {
          btn.className = 'px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer';
        }
      });
    }

    // ==================== SLIDE 4: MOCKUP INTERATIVO DO NEXAOS ====================
    function startLiveClock() {
      const clockEl = document.getElementById('os-live-clock');
      const update = () => {
        const now = new Date();
        clockEl.textContent = `${String(now.getHours()).padStart(2, '0')}:${String(now.getMinutes()).padStart(2, '0')}`;
      };
      update();
      setInterval(update, 15000);
    }

    function openOsApp(appKey) {
      const win = document.getElementById('os-window');
      const title = document.getElementById('os-window-title');
      const body = document.getElementById('os-window-body');
      const topLabel = document.getElementById('os-active-app-label');

      win.classList.remove('hidden');

      const apps = {
        files: {
          name: 'NexaFiles — Meus Projetos',
          html: `<div class="space-y-2">
                  <div class="flex items-center justify-between text-xs font-bold text-amber-300">
                    <span>📁 Nuvem Híbrida NexaLink</span>
                    <span class="text-emerald-400">Sincronizado</span>
                  </div>
                  <div class="grid grid-cols-2 gap-2 text-xs">
                    <div class="bg-slate-950/70 p-2 rounded-lg border border-slate-800">📄 Trabalho_SO.ndoc</div>
                    <div class="bg-slate-950/70 p-2 rounded-lg border border-slate-800">📊 Apresentacao.nslide</div>
                  </div>
                </div>`
        },
        browser: {
          name: 'NexaBrowser — Navegação Rápida',
          html: `<div class="space-y-2">
                  <div class="bg-slate-950 px-3 py-1 rounded-lg text-[11px] text-cyan-300 border border-slate-800">🔒 https://nexaos.tech/arquitetura</div>
                  <p class="text-xs text-slate-300">Bloqueador nativo ativo: <strong>18 rastreadores bloqueados</strong> nesta página. Economia de 40% de memória RAM.</p>
                </div>`
        },
        ai: {
          name: 'Assistente IA NexaMind (Offline)',
          html: `<div class="space-y-2 bg-indigo-950/40 p-3 rounded-xl border border-indigo-500/30">
                  <div class="text-xs font-bold text-cyan-300">🤖 NexaMind pronta para ajudar:</div>
                  <p class="text-xs text-slate-200">“Posso resumir seus PDFs de estudo, organizar suas janelas ou ativar o modo economia de bateria agora mesmo.”</p>
                </div>`
        },
        settings: {
          name: 'Ajustes do Sistema NexaOS',
          html: `<div class="space-y-1.5 text-xs">
                  <div class="flex justify-between"><span>Versão do Núcleo:</span><span class="text-cyan-300 font-bold">NexaCore v2.0 (Rust)</span></div>
                  <div class="flex justify-between"><span>Segurança NexaGuard:</span><span class="text-emerald-400 font-bold">Criptografia Quântica Ativa</span></div>
                  <div class="flex justify-between"><span>Tempo de Boot:</span><span class="text-amber-300 font-bold">1.9 segundo</span></div>
                </div>`
        }
      };

      const selected = apps[appKey];
      if (selected) {
        title.textContent = selected.name;
        topLabel.textContent = selected.name;
        body.innerHTML = selected.html;
      }
    }

    function closeOsWindow() {
      document.getElementById('os-window').classList.add('hidden');
      document.getElementById('os-active-app-label').textContent = 'Área de Trabalho';
    }

    // ==================== SLIDE 5: INSTALAÇÃO NA NEXASTORE ====================
    function installAppDemo(btn) {
      if (btn.dataset.installed === 'true') return;
      btn.textContent = 'Baixando...';
      btn.classList.replace('bg-cyan-500', 'bg-amber-400');
      setTimeout(() => {
        btn.textContent = '✓ Instalado';
        btn.dataset.installed = 'true';
        btn.classList.replace('bg-amber-400', 'bg-emerald-500');
        showToast('Aplicativo instalado em contêiner isolado na NexaStore!');
      }, 600);
    }

    // ==================== SLIDE 6: SIMULAÇÃO DE ESCANEAMENTO DE SEGURANÇA ====================
    function runSecurityScan() {
      const btn = document.getElementById('btn-security-scan');
      const badge = document.getElementById('security-status-badge');
      btn.disabled = true;
      btn.textContent = '⏳ Verificando núcleo e firewall...';
      badge.textContent = '🔍 Escaneando memória, rede e arquivos...';
      badge.className = 'text-xs font-bold text-amber-300';

      setTimeout(() => {
        btn.disabled = false;
        btn.textContent = '🛡️ Simular Escaneamento & Firewall';
        badge.textContent = '✅ 100% Seguro • Firewall IA & Criptografia Ativos';
        badge.className = 'text-xs font-bold text-emerald-300';
        showToast('Varredura concluída: 0 vírus e 0 invasões detectadas!');
      }, 1100);
    }

    // ==================== SLIDE 7: ACESSIBILIDADE AO VIVO ====================
    function toggleHighContrast() {
      document.body.classList.toggle('high-contrast');
      showToast(document.body.classList.contains('high-contrast') ? 'Modo Alto Contraste ativado!' : 'Modo Alto Contraste desativado.');
    }

    function toggleLargeFont() {
      document.body.classList.toggle('large-font');
      showToast(document.body.classList.contains('large-font') ? 'Fonte ampliada ativada!' : 'Tamanho de fonte padrão.');
    }

    function toggleReadingGuide() {
      document.body.classList.toggle('reading-guide');
      showToast(document.body.classList.contains('reading-guide') ? 'Modo Leitura Guiada ativado!' : 'Modo Leitura Guiada desativado.');
    }

    // ==================== SLIDE 8: PERFIS DE DESEMPENHO E BATERIA ====================
    function setPowerProfile(profile) {
      const profiles = {
        turbo: {
          cpu: '42%', barCpu: '42%',
          ram: '2.1 GB', barRam: '45%',
          fps: '240 FPS', barFps: '100%',
          bat: '8 horas', barBat: '40%',
          tag: '🚀 Modo Turbo Gamer • Máxima potência gráfica e latência zero'
        },
        balanced: {
          cpu: '18%', barCpu: '18%',
          ram: '1.2 GB', barRam: '24%',
          fps: '120 FPS', barFps: '70%',
          bat: '16 horas', barBat: '78%',
          tag: '⚡ Perfil Equilibrado • Fluidez diária com baixo consumo'
        },
        eco: {
          cpu: '6%', barCpu: '8%',
          ram: '0.8 GB', barRam: '16%',
          fps: '60 FPS', barFps: '45%',
          bat: '24 horas', barBat: '100%',
          tag: '🔋 Ultra Economia • Hiberna apps inativos para durar o dia inteiro'
        }
      };

      const p = profiles[profile];
      if (!p) return;

      document.getElementById('metric-cpu').textContent = p.cpu;
      document.getElementById('bar-cpu').style.width = p.barCpu;
      document.getElementById('metric-ram').textContent = p.ram;
      document.getElementById('bar-ram').style.width = p.barRam;
      document.getElementById('metric-fps').textContent = p.fps;
      document.getElementById('bar-fps').style.width = p.barFps;
      document.getElementById('metric-bat').textContent = p.bat;
      document.getElementById('bar-bat').style.width = p.barBat;
      document.getElementById('pwr-tagline').textContent = p.tag;

      ['turbo', 'balanced', 'eco'].forEach(k => {
        const btn = document.getElementById(`pwr-btn-${k}`);
        if (k === profile) {
          btn.className = 'px-3 py-1.5 rounded-xl text-xs font-bold bg-cyan-500 text-slate-950 transition cursor-pointer';
        } else {
          btn.className = 'px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer';
        }
      });
    }

    // ==================== SLIDE 9: VERIFICADOR DE COMPATIBILIDADE ====================
    function selectCompatTab(tab) {
      const box = document.getElementById('compat-details-box');
      const content = {
        peripherals: `
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🖱️ Mouse & Teclado</div>
            <p class="text-xs text-slate-300 mt-1">Reconhecimento imediato via USB-C ou Bluetooth sem instalar nenhum programa extra.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-emerald-400">✓ 100% Plug & Play</span>
          </div>
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🖨️ Impressoras & Scanners</div>
            <p class="text-xs text-slate-300 mt-1">Detecta automaticamente qualquer impressora Wi-Fi ou USB na rede local.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-emerald-400">✓ Sem Driver Manual</span>
          </div>
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🎧 Webcams & Áudio</div>
            <p class="text-xs text-slate-300 mt-1">Microfones, fones Bluetooth e monitores externos configurados em 1 segundo.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-emerald-400">✓ Baixa Latência</span>
          </div>
        `,
        apps: `
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🪟 Programas Windows (.exe)</div>
            <p class="text-xs text-slate-300 mt-1">Camada de tradução nativa NexaBridge roda softwares clássicos sem emuladores lentos.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-cyan-300">✓ Execução Direta</span>
          </div>
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🤖 Apps Android (.apk)</div>
            <p class="text-xs text-slate-300 mt-1">Abra aplicativos móveis em janelas redimensionáveis diretamente na área de trabalho.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-cyan-300">✓ Suporte Nativo</span>
          </div>
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🐧 Pacotes Linux & Web</div>
            <p class="text-xs text-slate-300 mt-1">Compatível com Flatpak, AppImage e aplicativos web progressivos (PWA).</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-cyan-300">✓ Ecossistema Aberto</span>
          </div>
        `,
        games: `
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🎮 Controles & Volantes</div>
            <p class="text-xs text-slate-300 mt-1">Mapeamento automático para controles Xbox, DualSense, Nintendo e volantes USB.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-amber-300">✓ Vibração & Gatilhos</span>
          </div>
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🖥️ Drivers Gráficos Vulkan</div>
            <p class="text-xs text-slate-300 mt-1">Drivers NVIDIA, AMD e Intel já vêm pré-otimizados no núcleo do NexaOS.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-amber-300">✓ Ray Tracing Pronto</span>
          </div>
          <div class="bg-slate-900/80 p-3.5 rounded-xl border border-slate-700">
            <div class="text-sm font-bold text-white">🕹️ Lojas & Anti-Cheat</div>
            <p class="text-xs text-slate-300 mt-1">Compatível com Steam, Epic Games e jogos competitivos online sem bloqueios.</p>
            <span class="inline-block mt-2 text-[11px] font-bold text-amber-300">✓ Alta Performance</span>
          </div>
        `
      };

      box.innerHTML = content[tab];
      ['peripherals', 'apps', 'games'].forEach(k => {
        const btn = document.getElementById(`compat-btn-${k}`);
        if (k === tab) {
          btn.className = 'px-3 py-1.5 rounded-xl text-xs font-bold bg-indigo-500 text-white transition cursor-pointer';
        } else {
          btn.className = 'px-3 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer';
        }
      });
    }

    // ==================== SLIDE 10: SELETOR DE PÚBLICO-ALVO E PREÇO ====================
    function selectAudience(aud) {
      const audiences = {
        students: {
          img: 'https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=800&q=80',
          caption: '🎓 Estudantes, Escolas & Universidades',
          tag: 'LICENÇA EDUCACIONAL',
          name: 'NexaOS Edu & Personal',
          price: 'GRATUITO <span class="text-xs font-normal text-slate-300">/ para sempre</span>',
          desc: 'Perfeito para estudantes, professores e uso doméstico diário, sem anúncios e sem custo de licença.',
          benefits: [
            '✅ Pacote completo NexaOffice + NexaCode + NexaStudio inclusos',
            '✅ 100 GB de armazenamento gratuito na nuvem NexaCloud',
            '✅ Atualizações de segurança vitalícias sem cobrar nada'
          ]
        },
        gamers: {
          img: 'https://images.unsplash.com/photo-1542751371-adc38448a05e?auto=format&fit=crop&w=800&q=80',
          caption: '🎮 Gamers & Criadores de Conteúdo',
          tag: 'ASSINATURA OPCIONAL PRO',
          name: 'NexaOS Gamer & Creator Pro',
          price: 'R$ 19,90 <span class="text-xs font-normal text-slate-300">/ mês (Sistema grátis)</span>',
          desc: 'O sistema operacional continua gratuito, com assinatura opcional para recursos de nuvem gamer e edição profissional.',
          benefits: [
            '✅ Modo Turbo Gamer + gravação de gameplay em 4K 120FPS sem perda de desempenho',
            '✅ 2 TB na nuvem NexaCloud + acesso ao NexaCloud Gaming',
            '✅ Ferramentas avançadas de renderização no NexaStudio'
          ]
        },
        enterprise: {
          img: 'https://images.unsplash.com/photo-1553877522-43269d4ea984?auto=format&fit=crop&w=800&q=80',
          caption: '🏢 Empresas, Escritórios & Governos',
          tag: 'PLANO CORPORATIVO',
          name: 'NexaOS Enterprise Security',
          price: 'R$ 39,90 <span class="text-xs font-normal text-slate-300">/ dispositivo / mês</span>',
          desc: 'Desenvolvido para equipes que exigem segurança máxima, gerenciamento remoto e suporte técnico especializado.',
          benefits: [
            '✅ Painel centralizado de TI para gerenciar centenas de computadores',
            '✅ Criptografia quântica corporativa e backup automático por hora',
            '✅ Suporte técnico dedicado 24 horas por dia, 7 dias por semana'
          ]
        }
      };

      const data = audiences[aud];
      if (!data) return;

      document.getElementById('audience-img').src = data.img;
      document.getElementById('audience-img-caption').textContent = data.caption;
      document.getElementById('plan-tag').textContent = data.tag;
      document.getElementById('plan-name').textContent = data.name;
      document.getElementById('plan-price').innerHTML = data.price;
      document.getElementById('plan-desc').textContent = data.desc;
      document.getElementById('plan-benefits').innerHTML = data.benefits.map(b => `<li>${b}</li>`).join('');

      ['students', 'gamers', 'enterprise'].forEach(k => {
        const btn = document.getElementById(`aud-btn-${k}`);
        if (k === aud) {
          btn.className = 'px-3.5 py-1.5 rounded-xl text-xs font-bold bg-emerald-500 text-slate-950 transition cursor-pointer';
        } else {
          btn.className = 'px-3.5 py-1.5 rounded-xl text-xs font-bold bg-slate-800 text-slate-200 hover:bg-slate-700 border border-slate-700 transition cursor-pointer';
        }
      });
    }

    // ==================== COPIAR CÓDIGO-FONTE E NOTIFICAÇÕES ====================
    function copyFullSourceCode() {
      const codeText = '<!DOCTYPE html>\n' + document.documentElement.outerHTML;
      const tempArea = document.createElement('textarea');
      tempArea.value = codeText;
      document.body.appendChild(tempArea);
      tempArea.select();
      try {
        document.execCommand('copy');
        showToast('✅ Código-fonte completo do NexaOS copiado!');
      } catch (err) {
        showToast('Não foi possível copiar automaticamente.');
      }
      document.body.removeChild(tempArea);
    }

    let toastTimer;
    function showToast(msg) {
      const toast = document.getElementById('toast-box');
      toast.textContent = msg;
      toast.classList.remove('hidden');
      clearTimeout(toastTimer);
      toastTimer = setTimeout(() => {
        toast.classList.add('hidden');
      }, 3000);
    }
  </script>
</body>
</html>
