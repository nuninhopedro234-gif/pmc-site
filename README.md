[pmc_energy_advisory_website_oficial.html](https://github.com/user-attachments/files/33346725/pmc_energy_advisory_website_oficial.html)# pmc-site
site da pmcea
[Uploading pmc_energy_advisory_<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PMC — Energy Advisory | Engenharia & Consultoria Eletrotécnica em Lisboa</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,300;0,6..72,400;0,6..72,500;1,6..72,400&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        stone: {
                            50: '#FBFBF9',
                            100: '#F4F3EF',
                            200: '#E9E7DF',
                            300: '#D5D1C3',
                            700: '#4A4843',
                            800: '#2C2B28',
                            900: '#1A1918',
                        },
                        navy: {
                            900: '#141E28',
                            950: '#0B1219',
                        },
                        bronze: {
                            500: '#AC7248',
                            600: '#945E37',
                            700: '#7B4C2A',
                        }
                    },
                    fontFamily: {
                        serif: ['Newsreader', 'Georgia', 'serif'],
                        sans: ['Plus Jakarta Sans', 'system-ui', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #FBFBF9;
            color: #1A1918;
            font-family: 'Plus Jakarta Sans', sans-serif;
            -webkit-font-smoothing: antialiased;
        }
        .font-serif-title {
            font-family: 'Newsreader', Georgia, serif;
        }
        .grid-pattern {
            background-image: radial-gradient(#d5d1c3 0.75px, transparent 0.75px);
            background-size: 24px 24px;
        }
        .architectural-line {
            border-color: rgba(26, 25, 24, 0.12);
        }
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #F4F3EF;
        }
        ::-webkit-scrollbar-thumb {
            background: #D5D1C3;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #AC7248;
        }
        .technical-border {
            position: relative;
        }
        .technical-border::after {
            content: '';
            position: absolute;
            bottom: -1px;
            left: 0;
            width: 12px;
            height: 1px;
            background-color: #AC7248;
        }
    </style>
</head>
<body class="selection:bg-bronze-500 selection:text-white">

    <!-- Top Bar Info -->
    <div class="bg-stone-900 text-stone-300 text-xs py-2 px-6 border-b border-stone-800">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-6 font-mono text-[11px] tracking-tight">
                <span>GABINETE TÉCNICO SEDIADO EM LISBOA</span>
                <span class="hidden sm:inline text-stone-600">|</span>
                <span class="hidden sm:inline">NIPC: 515031518</span>
                <span class="hidden md:inline text-stone-600">|</span>
                <span class="hidden md:inline">PEDRO MIGUEL CAROÇO, LDA.</span>
            </div>
            <div class="flex items-center gap-6 text-[11px] font-medium">
                <a href="tel:+351210162325" class="hover:text-bronze-500 transition-colors flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    +351 210 162 325
                </a>
                <span class="text-stone-700">|</span>
                <span class="text-stone-400">SEGUNDA A SEXTA: 09:00 - 18:00</span>
            </div>
        </div>
    </div>

    <!-- Main Header -->
    <header class="sticky top-0 z-40 bg-stone-50/95 backdrop-blur-md border-b architectural-line">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-10 h-10 bg-stone-900 flex items-center justify-center text-stone-100 font-serif text-xl font-bold tracking-tighter group-hover:bg-bronze-500 transition-colors">
                    PMC
                </div>
                <div>
                    <div class="font-serif-title text-lg font-medium leading-none tracking-tight text-stone-900">PMC — Energy Advisory</div>
                    <div class="text-[10px] uppercase tracking-widest text-stone-500 font-semibold mt-1">Engenharia & Consultoria Eletrotécnica</div>
                </div>
            </a>

            <!-- Desktop Navigation -->
            <nav class="hidden lg:flex items-center gap-8 text-xs font-semibold uppercase tracking-wider text-stone-700">
                <a href="#servicos" class="hover:text-bronze-500 transition-colors py-2">Serviços Especializados</a>
                <a href="#simulador" class="hover:text-bronze-500 transition-colors py-2 flex items-center gap-1.5">
                    <span class="w-1.5 h-1.5 bg-bronze-500 rounded-full"></span>
                    Simulador Energético
                </a>
                <a href="#peritagens" class="hover:text-bronze-500 transition-colors py-2">Peritagens Técnicas</a>
                <a href="#sobre" class="hover:text-bronze-500 transition-colors py-2">O Gabinete</a>
                <a href="#contactos" class="hover:text-bronze-500 transition-colors py-2">Contactos</a>
            </nav>

            <!-- Actions -->
            <div class="flex items-center gap-4">
                <button onclick="toggleModal('modal-orcamento')" class="hidden sm:inline-flex items-center justify-center px-4 py-2.5 text-xs font-semibold uppercase tracking-wider text-white bg-stone-900 hover:bg-bronze-600 transition-all border border-stone-900 hover:border-bronze-600">
                    Solicitar Consulta
                </button>
                <button onclick="toggleMobileMenu()" class="lg:hidden p-2 text-stone-800 hover:text-bronze-500">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M4 6h16M4 12h16M4 18h16"/></svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden lg:hidden border-t architectural-line bg-stone-100 px-6 py-6 space-y-4 text-sm uppercase tracking-wider font-semibold">
            <a href="#servicos" onclick="toggleMobileMenu()" class="block text-stone-800 hover:text-bronze-500">Serviços Especializados</a>
            <a href="#simulador" onclick="toggleMobileMenu()" class="block text-stone-800 hover:text-bronze-500">Simulador Energético</a>
            <a href="#peritagens" onclick="toggleMobileMenu()" class="block text-stone-800 hover:text-bronze-500">Peritagens Técnicas</a>
            <a href="#sobre" onclick="toggleMobileMenu()" class="block text-stone-800 hover:text-bronze-500">O Gabinete</a>
            <a href="#contactos" onclick="toggleMobileMenu()" class="block text-stone-800 hover:text-bronze-500">Contactos</a>
            <button onclick="toggleMobileMenu(); toggleModal('modal-orcamento');" class="w-full text-center px-4 py-3 text-xs uppercase tracking-wider font-semibold text-white bg-stone-900">
                Solicitar Consulta Técnica
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative border-b architectural-line grid-pattern overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 py-20 lg:py-28">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                
                <!-- Main Copy -->
                <div class="lg:col-span-7 space-y-8">
                    <div class="inline-flex items-center gap-2 px-3 py-1 bg-stone-200/70 border border-stone-300 text-stone-800 text-xs font-mono tracking-tight">
                        <span class="w-2 h-2 bg-emerald-600 rounded-full animate-pulse"></span>
                        PROJETOS & CONSULTORIA TÉCNICA INDEPENDENTE
                    </div>

                    <h1 class="font-serif-title text-4xl sm:text-5xl lg:text-6xl font-normal leading-[1.15] text-stone-900 tracking-tight">
                        Engenharia Eletrotécnica <br>
                        <span class="italic font-light text-stone-700">& Consultoria Energética</span> <br>
                        de Precisão.
                    </h1>

                    <p class="text-stone-700 text-base sm:text-lg leading-relaxed max-w-2xl font-normal">
                        Atuamos há mais de duas décadas no desenvolvimento de projetos de instalações elétricas, telecomunicações (ITED/ITUR) e mobilidade elétrica. Oferecemos um acompanhamento rigoroso e independente para edifícios residenciais, comerciais e industriais.
                    </p>

                    <div class="flex flex-wrap items-center gap-4 pt-2">
                        <button onclick="toggleModal('modal-orcamento')" class="px-6 py-3.5 bg-stone-900 text-white text-xs font-semibold uppercase tracking-wider hover:bg-bronze-600 transition-colors flex items-center gap-3">
                            <span>Solicitar Consulta Técnica</span>
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M14 5l7 7m0 0l-7 7m7-7H3"/></svg>
                        </button>
                        <a href="#simulador" class="px-6 py-3.5 bg-transparent border border-stone-400 text-stone-900 text-xs font-semibold uppercase tracking-wider hover:bg-stone-200/50 transition-colors">
                            Simular Viabilidade
                        </a>
                    </div>

                    <!-- Technical Tags -->
                    <div class="pt-8 border-t architectural-line grid grid-cols-3 gap-4 font-mono text-xs text-stone-600">
                        <div>
                            <span class="block text-stone-400 text-[10px]">ORGANISMO</span>
                            <span class="font-semibold text-stone-800">Ordem dos Engenheiros</span>
                        </div>
                        <div>
                            <span class="block text-stone-400 text-[10px]">CONFORMIDADE</span>
                            <span class="font-semibold text-stone-800">RTIEBT & ITED4</span>
                        </div>
                        <div>
                            <span class="block text-stone-400 text-[10px]">LOCALIZAÇÃO</span>
                            <span class="font-semibold text-stone-800">Lisboa & Vale do Tejo</span>
                        </div>
                    </div>
                </div>

                <!-- Hero Graphic / Technical Diagram SVG -->
                <div class="lg:col-span-5 bg-stone-100 border architectural-line p-6 sm:p-8 space-y-6">
                    <div class="flex justify-between items-center font-mono text-xs text-stone-500 border-b architectural-line pb-3">
                        <span>ESQUEMA TÉCNICO #01-A</span>
                        <span>SISTEMA INTEGRADO</span>
                    </div>

                    <!-- SVG Schematic -->
                    <div class="w-full bg-white border border-stone-200 p-4">
                        <svg viewBox="0 0 400 240" class="w-full h-auto text-stone-800" fill="none" stroke="currentColor">
                            <!-- Background Grid Lines in SVG -->
                            <path d="M0 40 H400 M0 80 H400 M0 120 H400 M0 160 H400 M0 200 H400" stroke="#f0efe9" stroke-width="1"/>
                            <path d="M80 0 V240 M160 0 V240 M240 0 V240 M320 0 V240" stroke="#f0efe9" stroke-width="1"/>

                            <!-- Main Grid Connection -->
                            <rect x="30" y="30" width="80" height="50" stroke="#1A1918" stroke-width="1.5" fill="#fcfbf9"/>
                            <text x="70" y="52" font-family="sans-serif" font-size="9" text-anchor="middle" fill="#1A1918" font-weight="bold">REDE ELÉTRICA</text>
                            <text x="70" y="66" font-family="sans-serif" font-size="8" text-anchor="middle" fill="#777">RESP. E-REDES</text>

                            <!-- Transformer / Board -->
                            <path d="M110 55 H180 V120 H250" stroke="#AC7248" stroke-width="1.5" stroke-dasharray="4 2"/>
                            <circle cx="180" cy="55" r="3" fill="#AC7248"/>
                            
                            <!-- Main Switchboard -->
                            <rect x="140" y="120" width="100" height="70" stroke="#1A1918" stroke-width="1.5" fill="#ffffff"/>
                            <text x="190" y="142" font-family="sans-serif" font-size="9" text-anchor="middle" fill="#1A1918" font-weight="bold">QUADRO GERAL</text>
                            <text x="190" y="156" font-family="sans-serif" font-size="8" text-anchor="middle" fill="#1A1918">PROTEÇÃO & MEDIÇÃO</text>
                            <line x1="150" y1="170" x2="230" y2="170" stroke="#AC7248" stroke-width="2"/>

                            <!-- Solar PV Branch -->
                            <rect x="280" y="30" width="90" height="50" stroke="#1A1918" stroke-width="1.5" fill="#fcfbf9"/>
                            <text x="325" y="52" font-family="sans-serif" font-size="9" text-anchor="middle" fill="#1A1918" font-weight="bold">FOTOVOLTAICO</text>
                            <text x="325" y="66" font-family="sans-serif" font-size="8" text-anchor="middle" fill="#777">AUTOCONSUMO</text>
                            <path d="M325 80 V120 H240" stroke="#1A1918" stroke-width="1.5"/>

                            <!-- EV Charger Branch -->
                            <rect x="280" y="150" width="90" height="50" stroke="#1A1918" stroke-width="1.5" fill="#fcfbf9"/>
                            <text x="325" y="172" font-family="sans-serif" font-size="9" text-anchor="middle" fill="#1A1918" font-weight="bold">POSTO CARGA VE</text>
                            <text x="325" y="186" font-family="sans-serif" font-size="8" text-anchor="middle" fill="#777">DEDICADO</text>
                            <path d="M240 170 H280" stroke="#1A1918" stroke-width="1.5"/>
                        </svg>
                    </div>

                    <div class="space-y-3 font-mono text-xs">
                        <div class="flex justify-between border-b architectural-line pb-1.5 text-stone-600">
                            <span>Conformidade Legal:</span>
                            <span class="text-stone-900 font-semibold">Garantia DGEG / Imprensa Nacional</span>
                        </div>
                        <div class="flex justify-between border-b architectural-line pb-1.5 text-stone-600">
                            <span>Peritagens de Segurança:</span>
                            <span class="text-stone-900 font-semibold">Análise Termográfica e Isolamento</span>
                        </div>
                        <div class="flex justify-between text-stone-600">
                            <span>Prazo médio de elaboração:</span>
                            <span class="text-stone-900 font-semibold">5 a 10 dias úteis</span>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Metrics Strip -->
    <section class="bg-stone-900 text-stone-100 py-12 border-b border-stone-800">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div class="space-y-1">
                    <div class="font-serif-title text-3xl sm:text-4xl text-bronze-500 font-light">+20 Anos</div>
                    <div class="text-xs uppercase tracking-wider text-stone-400">Experiência Consolidada</div>
                </div>
                <div class="space-y-1">
                    <div class="font-serif-title text-3xl sm:text-4xl text-stone-100 font-light">100%</div>
                    <div class="text-xs uppercase tracking-wider text-stone-400">Rigor Regulamentar</div>
                </div>
                <div class="space-y-1">
                    <div class="font-serif-title text-3xl sm:text-4xl text-bronze-500 font-light">+850</div>
                    <div class="text-xs uppercase tracking-wider text-stone-400">Projetos & Peritagens</div>
                </div>
                <div class="space-y-1">
                    <div class="font-serif-title text-3xl sm:text-4xl text-stone-100 font-light">Lisboa</div>
                    <div class="text-xs uppercase tracking-wider text-stone-400">Sede e Operação Principal</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servicos" class="py-24 border-b architectural-line bg-stone-50">
        <div class="max-w-7xl mx-auto px-6">
            
            <!-- Section Header -->
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 pb-6 border-b architectural-line gap-6">
                <div>
                    <span class="font-mono text-xs text-bronze-600 uppercase tracking-widest block mb-2">01 / ÁREAS DE ATUAÇÃO</span>
                    <h2 class="font-serif-title text-3xl sm:text-4xl text-stone-900">Serviços de Engenharia Eletrotécnica</h2>
                </div>
                <p class="text-stone-600 text-sm max-w-md">
                    Elaboração de projetos regulamentares, acompanhamento técnico e certificação para o setor residencial, empresarial e industrial.
                </p>
            </div>

            <!-- Filter Tabs -->
            <div class="flex flex-wrap gap-2 mb-12 font-mono text-xs uppercase">
                <button onclick="filterServices('all')" id="btn-all" class="px-4 py-2 border border-stone-900 bg-stone-900 text-white transition-all">Todos os Projetos</button>
                <button onclick="filterServices('residential')" id="btn-residential" class="px-4 py-2 border border-stone-300 bg-white text-stone-700 hover:border-stone-900 transition-all">Habitação & Moradias</button>
                <button onclick="filterServices('commercial')" id="btn-commercial" class="px-4 py-2 border border-stone-300 bg-white text-stone-700 hover:border-stone-900 transition-all">Comércio & Escritórios</button>
                <button onclick="filterServices('industrial')" id="btn-industrial" class="px-4 py-2 border border-stone-300 bg-white text-stone-700 hover:border-stone-900 transition-all">Industrial & Infraestruturas</button>
            </div>

            <!-- Services Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- Service 1 -->
                <div class="service-card residential commercial bg-white border architectural-line p-8 flex flex-col justify-between hover:border-stone-900 transition-colors">
                    <div>
                        <div class="flex justify-between items-start mb-6 font-mono text-xs text-stone-400">
                            <span>PROJECTO #01</span>
                            <span>RTIEBT</span>
                        </div>
                        <h3 class="font-serif-title text-2xl text-stone-900 mb-3">Instalações Elétricas</h3>
                        <p class="text-stone-600 text-sm leading-relaxed mb-6">
                            Dimensionamento de redes elétricas em baixa tensão para edifícios habitacionais, restauração, serviços e armazéns. Garantia de licenciamento e declarações de conformidade.
                        </p>
                    </div>
                    <ul class="text-xs text-stone-700 font-mono space-y-2 border-t architectural-line pt-4">
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Projetos de Execução & Telas Finais
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Aumento de Potência e Redes de Terra
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Quadros Elétricos e Iluminação Técnica
                        </li>
                    </ul>
                </div>

                <!-- Service 2 -->
                <div class="service-card residential commercial industrial bg-white border architectural-line p-8 flex flex-col justify-between hover:border-stone-900 transition-colors">
                    <div>
                        <div class="flex justify-between items-start mb-6 font-mono text-xs text-stone-400">
                            <span>PROJECTO #02</span>
                            <span>ITED4 / ITUR</span>
                        </div>
                        <h3 class="font-serif-title text-2xl text-stone-900 mb-3">Telecomunicações ITED / ITUR</h3>
                        <p class="text-stone-600 text-sm leading-relaxed mb-6">
                            Projetos de infraestruturas de telecomunicações em edifícios e loteamentos. Soluções de rede estruturada, fibra ótica (FTTH) e coaxial com rigor às diretivas ANACOM.
                        </p>
                    </div>
                    <ul class="text-xs text-stone-700 font-mono space-y-2 border-t architectural-line pt-4">
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Certificação e Ensaios de Rede
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Redemensionamento ITED para Reabilitação
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Termos de Responsabilidade
                        </li>
                    </ul>
                </div>

                <!-- Service 3 -->
                <div class="service-card residential commercial industrial bg-white border architectural-line p-8 flex flex-col justify-between hover:border-stone-900 transition-colors">
                    <div>
                        <div class="flex justify-between items-start mb-6 font-mono text-xs text-stone-400">
                            <span>PROJECTO #03</span>
                            <span>SOLAR PV</span>
                        </div>
                        <h3 class="font-serif-title text-2xl text-stone-900 mb-3">Energia Fotovoltaica</h3>
                        <p class="text-stone-600 text-sm leading-relaxed mb-6">
                            Estudos independentes de viabilidade, dimensionamento de UPAC (Unidades de Produção para Autoconsumo) e armazenamento por baterias sem vinculação a marcas.
                        </p>
                    </div>
                    <ul class="text-xs text-stone-700 font-mono space-y-2 border-t architectural-line pt-4">
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Análise de Perfil de Consumo Rápida
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Cálculo do Retorno de Investimento (ROI)
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Acompanhamento na Registo DGEG
                        </li>
                    </ul>
                </div>

                <!-- Service 4 -->
                <div class="service-card residential commercial bg-white border architectural-line p-8 flex flex-col justify-between hover:border-stone-900 transition-colors">
                    <div>
                        <div class="flex justify-between items-start mb-6 font-mono text-xs text-stone-400">
                            <span>PROJECTO #04</span>
                            <span>VE / VEÍCULOS</span>
                        </div>
                        <h3 class="font-serif-title text-2xl text-stone-900 mb-3">Mobilidade Elétrica</h3>
                        <p class="text-stone-600 text-sm leading-relaxed mb-6">
                            Infraestruturas dedicadas de carregamento de veículos elétricos para garagens de condomínio, empresas e parques de estacionamento privados.
                        </p>
                    </div>
                    <ul class="text-xs text-stone-700 font-mono space-y-2 border-t architectural-line pt-4">
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Gestão Dinâmica de Carga
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Projetos para Condomínios Habitações
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Aumentos de Potência Dedicados
                        </li>
                    </ul>
                </div>

                <!-- Service 5 -->
                <div class="service-card residential commercial industrial bg-white border architectural-line p-8 flex flex-col justify-between hover:border-stone-900 transition-colors">
                    <div>
                        <div class="flex justify-between items-start mb-6 font-mono text-xs text-stone-400">
                            <span>PROJECTO #05</span>
                            <span>AUDITORIA</span>
                        </div>
                        <h3 class="font-serif-title text-2xl text-stone-900 mb-3">Diagnósticos & Peritagens</h3>
                        <p class="text-stone-600 text-sm leading-relaxed mb-6">
                            Avaliação técnica imparcial do estado das instalações existentes. Inspeções para compra/arrendamento de edifícios, seguros e auditoria de segurança.
                        </p>
                    </div>
                    <ul class="text-xs text-stone-700 font-mono space-y-2 border-t architectural-line pt-4">
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Relatório Técnico Detalhado com Fotos
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Deteção de Riscos de Incêndio/Sobrecarga
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Plano de Ação e Prioridades
                        </li>
                    </ul>
                </div>

                <!-- Service 6 -->
                <div class="service-card commercial industrial bg-white border architectural-line p-8 flex flex-col justify-between hover:border-stone-900 transition-colors">
                    <div>
                        <div class="flex justify-between items-start mb-6 font-mono text-xs text-stone-400">
                            <span>PROJECTO #06</span>
                            <span>CONSULTORIA</span>
                        </div>
                        <h3 class="font-serif-title text-2xl text-stone-900 mb-3">Otimização Tarifária</h3>
                        <p class="text-stone-600 text-sm leading-relaxed mb-6">
                            Consultoria técnica especializada na análise de faturação elétrica, potência contratada, correção do fator de potência (energia reativa) e redução de custos operacionais.
                        </p>
                    </div>
                    <ul class="text-xs text-stone-700 font-mono space-y-2 border-t architectural-line pt-4">
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Análise de Curvas de Carga
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Dimensionamento de Baterias de Condensadores
                        </li>
                        <li class="flex items-center gap-2">
                            <span class="w-1.5 h-1.5 bg-bronze-500"></span>
                            Redução de Penalizações na Fatura
                        </li>
                    </ul>
                </div>

            </div>
        </div>
    </section>

    <!-- Interactive Calculator / Simulator Section -->
    <section id="simulador" class="py-24 border-b architectural-line bg-stone-100">
        <div class="max-w-7xl mx-auto px-6">
            
            <div class="max-w-3xl mb-12">
                <span class="font-mono text-xs text-bronze-600 uppercase tracking-widest block mb-2">02 / FERRAMENTA INTERATIVA</span>
                <h2 class="font-serif-title text-3xl sm:text-4xl text-stone-900 mb-4">Simulador de Viabilidade Técnico-Energética</h2>
                <p class="text-stone-600 text-sm leading-relaxed">
                    Selecione os parâmetros da sua instalação para gerar uma estimativa de requisitos técnicos e obter uma recomendação inicial do nosso gabinete.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                
                <!-- Inputs Form -->
                <div class="lg:col-span-7 bg-white border architectural-line p-8 space-y-6">
                    
                    <!-- Step 1: Type of Property -->
                    <div>
                        <label class="block font-mono text-xs text-stone-500 uppercase mb-3">1. Tipo de Instalação</label>
                        <div class="grid grid-cols-3 gap-3">
                            <button type="button" onclick="setSimulatorParam('tipo', 'Residencial', this)" class="sim-type-btn p-3 text-xs border border-stone-900 bg-stone-900 text-white font-medium text-center">
                                Habitação
                            </button>
                            <button type="button" onclick="setSimulatorParam('tipo', 'Comercial', this)" class="sim-type-btn p-3 text-xs border border-stone-300 bg-white text-stone-800 font-medium text-center hover:border-stone-500">
                                Comércio / Escritório
                            </button>
                            <button type="button" onclick="setSimulatorParam('tipo', 'Industrial', this)" class="sim-type-btn p-3 text-xs border border-stone-300 bg-white text-stone-800 font-medium text-center hover:border-stone-500">
                                Armazém / Indústria
                            </button>
                        </div>
                    </div>

                    <!-- Step 2: Contracted Power (kVA) -->
                    <div>
                        <div class="flex justify-between items-center mb-2">
                            <label class="font-mono text-xs text-stone-500 uppercase">2. Potência Contratada Aprox. (kVA)</label>
                            <span id="kva-display" class="font-mono text-xs font-bold text-stone-900">6.9 kVA</span>
                        </div>
                        <input type="range" id="kva-range" min="3.45" max="41.4" step="3.45" value="6.9" oninput="updateSimulator()" class="w-full accent-stone-900 cursor-pointer">
                        <div class="flex justify-between text-[10px] font-mono text-stone-400 mt-1">
                            <span>3.45 kVA (Monofásico)</span>
                            <span>13.8 kVA (Trifásico)</span>
                            <span>41.4 kVA (Elevado)</span>
                        </div>
                    </div>

                    <!-- Step 3: Main Intention -->
                    <div>
                        <label class="block font-mono text-xs text-stone-500 uppercase mb-3">3. Objetivo Principal</label>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <label class="flex items-center p-3 border border-stone-200 cursor-pointer hover:bg-stone-50">
                                <input type="checkbox" id="obj-solar" onchange="updateSimulator()" checked class="accent-stone-900 mr-3">
                                <span class="text-xs font-medium text-stone-800">Painéis Fotovoltaicos</span>
                            </label>
                            <label class="flex items-center p-3 border border-stone-200 cursor-pointer hover:bg-stone-50">
                                <input type="checkbox" id="obj-ve" onchange="updateSimulator()" class="accent-stone-900 mr-3">
                                <span class="text-xs font-medium text-stone-800">Carregador Carro Elétrico</span>
                            </label>
                            <label class="flex items-center p-3 border border-stone-200 cursor-pointer hover:bg-stone-50">
                                <input type="checkbox" id="obj-certificacao" onchange="updateSimulator()" class="accent-stone-900 mr-3">
                                <span class="text-xs font-medium text-stone-800">Peritagem / Certificação</span>
                            </label>
                            <label class="flex items-center p-3 border border-stone-200 cursor-pointer hover:bg-stone-50">
                                <input type="checkbox" id="obj-ited" onchange="updateSimulator()" class="accent-stone-900 mr-3">
                                <span class="text-xs font-medium text-stone-800">Telecomunicações ITED</span>
                            </label>
                        </div>
                    </div>

                </div>

                <!-- Live Results Box -->
                <div class="lg:col-span-5 bg-stone-900 text-stone-100 p-8 space-y-6">
                    <div class="border-b border-stone-800 pb-4">
                        <span class="font-mono text-xs text-bronze-500 uppercase">DIAGNÓSTICO TÉCNICO ESTIMADO</span>
                        <h3 class="font-serif-title text-2xl font-light mt-1 text-white">Resumo da Recomendação</h3>
                    </div>

                    <div class="space-y-4 font-mono text-xs">
                        <div class="flex justify-between border-b border-stone-800 pb-2">
                            <span class="text-stone-400">Fase da Instalação:</span>
                            <span id="res-fase" class="text-stone-100 font-semibold">Monofásica Standard</span>
                        </div>
                        <div class="flex justify-between border-b border-stone-800 pb-2">
                            <span class="text-stone-400">Potência Recomendada Solar:</span>
                            <span id="res-solar" class="text-bronze-500 font-semibold">2.5 kWp a 3.5 kWp</span>
                        </div>
                        <div class="flex justify-between border-b border-stone-800 pb-2">
                            <span class="text-stone-400">Necessidade Aumento Potência:</span>
                            <span id="res-aumento" class="text-stone-100 font-semibold">Não Requerida</span>
                        </div>
                        <div class="flex justify-between border-b border-stone-800 pb-2">
                            <span class="text-stone-400">Enquadramento DGEG:</span>
                            <span id="res-dgeg" class="text-stone-100 font-semibold">Comunicação Prévia</span>
                        </div>
                    </div>

                    <p class="text-xs text-stone-400 leading-relaxed pt-2">
                        * Os dados acima servem como estimativa preliminar com base nas normas RTIEBT. Uma verificação presencial por engenheiro inscrito na OE é recomendada.
                    </p>

                    <button onclick="enviarDadosSimulador()" class="w-full py-3.5 bg-bronze-500 hover:bg-bronze-600 text-white font-semibold uppercase text-xs tracking-wider transition-colors">
                        Solicitar Proposta Formal com Estes Dados
                    </button>
                </div>

            </div>

        </div>
    </section>

    <!-- 5-Point Technical Methodology -->
    <section id="peritagens" class="py-24 border-b architectural-line bg-stone-50">
        <div class="max-w-7xl mx-auto px-6">
            
            <div class="max-w-3xl mb-16">
                <span class="font-mono text-xs text-bronze-600 uppercase tracking-widest block mb-2">03 / METODOLOGIA DE INSPEÇÃO</span>
                <h2 class="font-serif-title text-3xl sm:text-4xl text-stone-900 mb-4">Relatórios de Peritagem em 5 Pontos Críticos</h2>
                <p class="text-stone-600 text-sm leading-relaxed">
                    Quando contratado para uma auditoria técnica ou peritagem legal, o nosso gabinete segue uma matriz estrita de verificação e ensaios físicos.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-5 gap-4">
                
                <!-- Point 1 -->
                <div class="bg-white border architectural-line p-6 space-y-4">
                    <div class="font-serif-title text-3xl text-bronze-500">01.</div>
                    <h3 class="font-semibold text-stone-900 text-sm">Segurança de Pessoas</h3>
                    <p class="text-stone-600 text-xs leading-relaxed">
                        Teste de interruptores diferenciais, continuidade de condutores de proteção e medição do valor da resistência de terra.
                    </p>
                </div>

                <!-- Point 2 -->
                <div class="bg-white border architectural-line p-6 space-y-4">
                    <div class="font-serif-title text-3xl text-stone-400">02.</div>
                    <h3 class="font-semibold text-stone-900 text-sm">Continuidade de Serviço</h3>
                    <p class="text-stone-600 text-xs leading-relaxed">
                        Verificação do equilíbrio de fases, estado de conservação de disjuntores e ausência de sobreaquecimentos.
                    </p>
                </div>

                <!-- Point 3 -->
                <div class="bg-white border architectural-line p-6 space-y-4">
                    <div class="font-serif-title text-3xl text-bronze-500">03.</div>
                    <h3 class="font-semibold text-stone-900 text-sm">Eficiência Energética</h3>
                    <p class="text-stone-600 text-xs leading-relaxed">
                        Análise de perdas na distribuição interior, consumo residual e adequação de transformadores e iluminação.
                    </p>
                </div>

                <!-- Point 4 -->
                <div class="bg-white border architectural-line p-6 space-y-4">
                    <div class="font-serif-title text-3xl text-stone-400">04.</div>
                    <h3 class="font-semibold text-stone-900 text-sm">Estado de Conservação</h3>
                    <p class="text-stone-600 text-xs leading-relaxed">
                        Inspeção visual detalhada de tubagens, caixas de visita, isolamentos e envelhecimento de condutores.
                    </p>
                </div>

                <!-- Point 5 -->
                <div class="bg-white border architectural-line p-6 space-y-4">
                    <div class="font-serif-title text-3xl text-bronze-500">05.</div>
                    <h3 class="font-semibold text-stone-900 text-sm">Conformidade Legal</h3>
                    <p class="text-stone-600 text-xs leading-relaxed">
                        Confrontação do instalado com as disposições legais vigentes, normas europeias e exigências das seguradoras.
                    </p>
                </div>

            </div>

            <!-- Example Report Preview Banner -->
            <div class="mt-12 bg-stone-900 text-stone-200 p-8 flex flex-col md:flex-row items-center justify-between gap-6">
                <div class="space-y-2">
                    <span class="font-mono text-[11px] text-bronze-500 tracking-wider">DOCUMENTAÇÃO TÉCNICA</span>
                    <h4 class="font-serif-title text-xl text-white">Necessita de uma Peritagem Eletrotécnica para Compra de Imóvel ou Seguradora?</h4>
                    <p class="text-stone-400 text-xs max-w-2xl">
                        Apresentamos relatórios completos com registo fotográfico termográfico e assinatura digital de Engenheiro Eletrotécnico Certificado.
                    </p>
                </div>
                <button onclick="toggleModal('modal-orcamento')" class="whitespace-nowrap px-6 py-3 bg-white text-stone-900 text-xs font-semibold uppercase tracking-wider hover:bg-stone-200 transition-colors">
                    Agendar Inspeção
                </button>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="sobre" class="py-24 border-b architectural-line bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-16 items-center">
                
                <div class="lg:col-span-6 space-y-6">
                    <span class="font-mono text-xs text-bronze-600 uppercase tracking-widest block">04 / SOBRE O GABINETE</span>
                    <h2 class="font-serif-title text-3xl sm:text-4xl text-stone-900 leading-tight">
                        A PMC – Energy Advisory combina a experiência rigorosa com o pragmatismo técnico.
                    </h2>
                    <p class="text-stone-700 text-sm leading-relaxed">
                        Liderada por **Pedro Miguel Caroço**, a empresa opera a partir do seu gabinete em Lisboa com uma premissa clara: a engenharia eletrotécnica deve ser transparente, altamente técnica e livre de interesses comerciais na venda de equipamentos.
                    </p>
                    <p class="text-stone-700 text-sm leading-relaxed">
                        Esta independência garante ao cliente uma opinião isenta sobre as melhores soluções de racionalização energética, projetos de licenciamento e escolha de fornecedores.
                    </p>

                    <div class="pt-4 grid grid-cols-2 gap-6 font-mono text-xs">
                        <div class="border-l-2 border-bronze-500 pl-4 space-y-1">
                            <span class="block text-stone-900 font-bold">Pedro Miguel Caroço, Lda.</span>
                            <span class="text-stone-500">NIPC 515031518</span>
                        </div>
                        <div class="border-l-2 border-stone-300 pl-4 space-y-1">
                            <span class="block text-stone-900 font-bold">Ordem dos Engenheiros</span>
                            <span class="text-stone-500">Inscrição Ativa & Acreditada</span>
                        </div>
                    </div>
                </div>

                <!-- Office / Map Location Card -->
                <div class="lg:col-span-6 bg-stone-100 border architectural-line p-8 space-y-6">
                    <div class="flex justify-between items-center border-b architectural-line pb-4">
                        <div>
                            <span class="font-mono text-xs text-stone-400 block">SEDE SOCIAL & CONSULTÓRIO</span>
                            <span class="font-serif-title text-lg text-stone-900">Lisboa, Portugal</span>
                        </div>
                        <span class="w-3 h-3 bg-emerald-500 rounded-full"></span>
                    </div>

                    <div class="space-y-3 text-xs text-stone-700 font-mono">
                        <p class="flex items-start gap-3">
                            <svg class="w-4 h-4 text-bronze-600 shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            <span>Rua Odette de Saint-Maurice, n.º 380, Lote 3C(K) – Loja 4<br>1700-921 Lisboa, Portugal</span>
                        </p>
                        <p class="flex items-center gap-3">
                            <svg class="w-4 h-4 text-bronze-600 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                            <span>+351 210 162 325</span>
                        </p>
                        <p class="flex items-center gap-3">
                            <svg class="w-4 h-4 text-bronze-600 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                            <span>geral@pmcea.pt</span>
                        </p>
                    </div>

                    <!-- Stylized Architectural Map Graphic -->
                    <div class="w-full h-36 bg-stone-200 border border-stone-300 relative overflow-hidden flex items-center justify-center">
                        <div class="absolute inset-0 opacity-30 grid-pattern"></div>
                        <div class="relative z-10 text-center font-mono">
                            <span class="text-[10px] text-stone-500 block uppercase">COORDENADAS GEOGRÁFICAS</span>
                            <span class="text-xs font-bold text-stone-800">38.7612° N, 9.1284° W</span>
                            <span class="block text-[10px] text-bronze-600 font-semibold mt-1">ALVALADE / LISBOA</span>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contactos" class="py-24 border-b architectural-line bg-stone-100">
        <div class="max-w-7xl mx-auto px-6">
            
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                
                <!-- Info Column -->
                <div class="lg:col-span-5 space-y-6">
                    <span class="font-mono text-xs text-bronze-600 uppercase tracking-widest block">05 / CONTACTO DIRETO</span>
                    <h2 class="font-serif-title text-3xl sm:text-4xl text-stone-900">Solicite uma Consulta ou Análise de Projeto</h2>
                    <p class="text-stone-600 text-sm leading-relaxed">
                        Preencha o formulário para agendamento de inspeções presenciais, pedidos de orçamento para projetos ITED/Eletrotécnicos ou esclarecimento de dúvidas regulamentares.
                    </p>

                    <div class="space-y-4 pt-4 border-t architectural-line text-xs font-mono">
                        <div>
                            <span class="text-stone-400 block">ATENDIMENTO TELEFÓNICO</span>
                            <span class="text-stone-900 font-bold">+351 210 162 325</span>
                        </div>
                        <div>
                            <span class="text-stone-400 block">CORREIO ELETRÓNICO</span>
                            <span class="text-stone-900 font-bold">geral@pmcea.pt</span>
                        </div>
                        <div>
                            <span class="text-stone-400 block">TEMPO MÉDIO DE RESPOSTA</span>
                            <span class="text-bronze-600 font-bold">Até 24 Horas Úteis</span>
                        </div>
                    </div>
                </div>

                <!-- Form Column -->
                <div class="lg:col-span-7 bg-white border architectural-line p-8">
                    <form id="contact-form" onsubmit="submitContactForm(event)" class="space-y-6">
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label class="block font-mono text-xs text-stone-600 uppercase mb-2">Nome Completo *</label>
                                <input type="text" required class="w-full px-4 py-3 bg-stone-50 border border-stone-300 text-sm focus:outline-none focus:border-stone-900 text-stone-900">
                            </div>
                            <div>
                                <label class="block font-mono text-xs text-stone-600 uppercase mb-2">Telefone *</label>
                                <input type="tel" required class="w-full px-4 py-3 bg-stone-50 border border-stone-300 text-sm focus:outline-none focus:border-stone-900 text-stone-900">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label class="block font-mono text-xs text-stone-600 uppercase mb-2">E-mail de Contacto *</label>
                                <input type="email" required class="w-full px-4 py-3 bg-stone-50 border border-stone-300 text-sm focus:outline-none focus:border-stone-900 text-stone-900">
                            </div>
                            <div>
                                <label class="block font-mono text-xs text-stone-600 uppercase mb-2">Tipo de Serviço</label>
                                <select class="w-full px-4 py-3 bg-stone-50 border border-stone-300 text-sm focus:outline-none focus:border-stone-900 text-stone-900">
                                    <option>Projeto de Instalação Elétrica</option>
                                    <option>Projeto ITED / ITUR</option>
                                    <option>Estudo Fotovoltaico</option>
                                    <option>Carregamento Veículos Elétricos</option>
                                    <option>Peritagem / Diagnóstico Técnico</option>
                                    <option>Outro Assunto</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block font-mono text-xs text-stone-600 uppercase mb-2">Localização da Instalação / Descrição</label>
                            <textarea rows="4" placeholder="Indique a localidade e detalhes breves sobre o projeto..." class="w-full px-4 py-3 bg-stone-50 border border-stone-300 text-sm focus:outline-none focus:border-stone-900 text-stone-900"></textarea>
                        </div>

                        <div class="flex items-start gap-3">
                            <input type="checkbox" id="rgpd" required class="mt-1 accent-stone-900">
                            <label for="rgpd" class="text-xs text-stone-500">
                                Aceito o tratamento dos meus dados exclusivamente para efeitos de resposta a este pedido de contacto, nos termos do RGPD e da Política de Privacidade.
                            </label>
                        </div>

                        <button type="submit" class="w-full py-4 bg-stone-900 hover:bg-bronze-600 text-white font-semibold text-xs uppercase tracking-wider transition-colors">
                            Enviar Pedido de Consulta
                        </button>

                    </form>

                    <!-- Alert Box -->
                    <div id="form-feedback" class="hidden mt-4 p-4 bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-mono">
                        ✓ Mensagem enviada com sucesso. O nosso gabinete entrará em contacto num prazo máximo de 24h.
                    </div>
                </div>

            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-stone-900 text-stone-400 text-xs py-16">
        <div class="max-w-7xl mx-auto px-6 space-y-12">
            
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 pb-12 border-b border-stone-800">
                <div class="space-y-4">
                    <div class="text-white font-serif-title text-xl font-bold">PMC — Energy Advisory</div>
                    <p class="text-stone-400 leading-relaxed text-[11px]">
                        Engenharia e Consultoria Eletrotécnica independente. Projetos, licenciamentos e peritagens com rigor normativo.
                    </p>
                </div>

                <div>
                    <span class="font-mono text-stone-200 block mb-3 uppercase tracking-wider text-[11px]">Navegação</span>
                    <ul class="space-y-2 text-[11px]">
                        <li><a href="#servicos" class="hover:text-bronze-500 transition-colors">Projetos & Serviços</a></li>
                        <li><a href="#simulador" class="hover:text-bronze-500 transition-colors">Simulador Técnico</a></li>
                        <li><a href="#peritagens" class="hover:text-bronze-500 transition-colors">Peritagens de Segurança</a></li>
                        <li><a href="#sobre" class="hover:text-bronze-500 transition-colors">O Gabinete em Lisboa</a></li>
                    </ul>
                </div>

                <div>
                    <span class="font-mono text-stone-200 block mb-3 uppercase tracking-wider text-[11px]">Acreditações</span>
                    <ul class="space-y-2 text-[11px]">
                        <li>Ordem dos Engenheiros (OE)</li>
                        <li>Conformidade DGEG / RTIEBT</li>
                        <li>Técnico Certificado ITED4</li>
                        <li>Inspeção e Termos de Responsabilidade</li>
                    </ul>
                </div>

                <div>
                    <span class="font-mono text-stone-200 block mb-3 uppercase tracking-wider text-[11px]">Entidade Legal</span>
                    <p class="text-[11px] leading-relaxed">
                        Pedro Miguel Caroço, Lda.<br>
                        NIPC: 515031518<br>
                        Sede: Lisboa, Portugal
                    </p>
                </div>
            </div>

            <div class="flex flex-col sm:flex-row justify-between items-center gap-4 text-[11px] font-mono">
                <div>
                    &copy; 2026 PMC — Energy Advisory. Todos os direitos reservados.
                </div>
                <div class="flex gap-6">
                    <a href="#" class="hover:text-stone-200 transition-colors">Política de Privacidade</a>
                    <a href="#" class="hover:text-stone-200 transition-colors">Termos & Condições</a>
                    <a href="#" class="hover:text-stone-200 transition-colors">Livro de Reclamações</a>
                </div>
            </div>

        </div>
    </footer>

    <!-- Modal for Quick Quote Request -->
    <div id="modal-orcamento" class="fixed inset-0 z-50 hidden bg-stone-900/80 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white border architectural-line w-full max-w-lg p-8 relative">
            <button onclick="toggleModal('modal-orcamento')" class="absolute top-4 right-4 text-stone-400 hover:text-stone-900">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>

            <span class="font-mono text-xs text-bronze-600 uppercase tracking-widest block mb-1">PEDIDO RÁPIDO DE CONSULTA</span>
            <h3 class="font-serif-title text-2xl text-stone-900 mb-6">Proposta para o seu Projeto</h3>

            <form onsubmit="submitModalForm(event)" class="space-y-4">
                <div>
                    <label class="block font-mono text-xs text-stone-600 uppercase mb-1">Nome</label>
                    <input type="text" required class="w-full px-3 py-2 bg-stone-50 border border-stone-300 text-xs focus:outline-none focus:border-stone-900">
                </div>
                <div>
                    <label class="block font-mono text-xs text-stone-600 uppercase mb-1">E-mail ou Telefone</label>
                    <input type="text" required class="w-full px-3 py-2 bg-stone-50 border border-stone-300 text-xs focus:outline-none focus:border-stone-900">
                </div>
                <div>
                    <label class="block font-mono text-xs text-stone-600 uppercase mb-1">Notas / Requisitos Técnicos</label>
                    <textarea id="modal-notes" rows="3" placeholder="Descreva brevemente o projeto..." class="w-full px-3 py-2 bg-stone-50 border border-stone-300 text-xs focus:outline-none focus:border-stone-900"></textarea>
                </div>
                <button type="submit" class="w-full py-3 bg-stone-900 hover:bg-bronze-600 text-white font-semibold text-xs uppercase tracking-wider transition-colors">
                    Solicitar Diagnóstico
                </button>
            </form>

            <div id="modal-feedback" class="hidden mt-3 p-3 bg-emerald-50 text-emerald-800 text-xs font-mono">
                ✓ Pedido registado. Entraremos em contacto brevemente.
            </div>
        </div>
    </div>

    <!-- JavaScript Interactions -->
    <script>
        // State for Simulator
        let simState = {
            tipo: 'Residencial',
            kva: 6.9,
            solar: true,
            ve: false,
            certificacao: false,
            ited: false
        };

        function filterServices(category) {
            const cards = document.querySelectorAll('.service-card');
            cards.forEach(card => {
                if (category === 'all' || card.classList.contains(category)) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });

            // Update Active Buttons
            const buttons = ['all', 'residential', 'commercial', 'industrial'];
            buttons.forEach(b => {
                const btn = document.getElementById('btn-' + b);
                if (b === category) {
                    btn.className = 'px-4 py-2 border border-stone-900 bg-stone-900 text-white transition-all';
                } else {
                    btn.className = 'px-4 py-2 border border-stone-300 bg-white text-stone-700 hover:border-stone-900 transition-all';
                }
            });
        }

        function setSimulatorParam(param, value, btnElement) {
            if (param === 'tipo') {
                simState.tipo = value;
                const buttons = document.querySelectorAll('.sim-type-btn');
                buttons.forEach(b => {
                    b.className = 'sim-type-btn p-3 text-xs border border-stone-300 bg-white text-stone-800 font-medium text-center hover:border-stone-500';
                });
                btnElement.className = 'sim-type-btn p-3 text-xs border border-stone-900 bg-stone-900 text-white font-medium text-center';
            }
            updateSimulator();
        }

        function updateSimulator() {
            const kvaRange = document.getElementById('kva-range');
            simState.kva = parseFloat(kvaRange.value);
            document.getElementById('kva-display').innerText = simState.kva.toFixed(2) + ' kVA';

            simState.solar = document.getElementById('obj-solar').checked;
            simState.ve = document.getElementById('obj-ve').checked;
            simState.certificacao = document.getElementById('obj-certificacao').checked;
            simState.ited = document.getElementById('obj-ited').checked;

            // Diagnostic Logic
            const resFase = document.getElementById('res-fase');
            const resSolar = document.getElementById('res-solar');
            const resAumento = document.getElementById('res-aumento');
            const resDgeg = document.getElementById('res-dgeg');

            // Phase
            if (simState.kva > 10.35) {
                resFase.innerText = 'Trifásica (3x230V/400V)';
            } else {
                resFase.innerText = 'Monofásica Standard (230V)';
            }

            // Solar Recommendation
            if (simState.solar) {
                if (simState.tipo === 'Residencial') {
                    resSolar.innerText = '2.0 kWp a 4.5 kWp (4-8 Painéis)';
                } else if (simState.tipo === 'Comercial') {
                    resSolar.innerText = '6.0 kWp a 15.0 kWp';
                } else {
                    resSolar.innerText = '> 20.0 kWp (UPAC Industrial)';
                }
            } else {
                resSolar.innerText = 'Não Solicitado';
            }

            // Power Increase
            if (simState.ve && simState.kva < 6.9) {
                resAumento.innerText = 'Recomendado (mínimo 6.9 kVA)';
                resAumento.className = 'text-amber-400 font-semibold';
            } else {
                resAumento.innerText = 'Suficiente para Carga Normal';
                resAumento.className = 'text-stone-100 font-semibold';
            }

            // DGEG Rules
            if (simState.solar && simState.tipo !== 'Residencial') {
                resDgeg.innerText = 'Registo DGEG + Termo OE';
            } else {
                resDgeg.innerText = 'Comunicação Prévia Isenta';
            }
        }

        function enviarDadosSimulador() {
            const notas = `Simulação efetuada: Tipo: ${simState.tipo}, Potência: ${simState.kva} kVA, Solar: ${simState.solar ? 'Sim' : 'Não'}, VE: ${simState.ve ? 'Sim' : 'Não'}`;
            document.getElementById('modal-notes').value = notas;
            toggleModal('modal-orcamento');
        }

        function toggleModal(id) {
            const modal = document.getElementById(id);
            modal.classList.toggle('hidden');
        }

        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        function submitContactForm(event) {
            event.preventDefault();
            const feedback = document.getElementById('form-feedback');
            feedback.classList.remove('hidden');
            event.target.reset();
        }

        function submitModalForm(event) {
            event.preventDefault();
            const feedback = document.getElementById('modal-feedback');
            feedback.classList.remove('hidden');
            setTimeout(() => {
                toggleModal('modal-orcamento');
                feedback.classList.add('hidden');
            }, 2000);
        }

        // Initialize Simulator Defaults on Load
        window.onload = function() {
            updateSimulator();
        }
    </script>
</body>
</html>website_oficial.html…]()
