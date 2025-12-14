<script>
    // Hero Component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 bg-gray-50 relative overflow-hidden font-sans">
    <!-- Grid Background Pattern -->
    <div class="absolute inset-0 z-0 opacity-[0.4]" 
         style="background-image: linear-gradient(#e5e7eb 1px, transparent 1px), linear-gradient(90deg, #e5e7eb 1px, transparent 1px); background-size: 40px 40px;">
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col items-center text-center">
        
        <!-- Headline -->
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif-display text-gray-900 leading-[1.1] tracking-tight mb-6 max-w-5xl mx-auto">
            Finden Sie die passende 
            <span class="inline-flex items-center align-middle mx-1 md:mx-2 relative -top-1 md:-top-2">
                <svg width="60" height="60" viewBox="0 0 100 100" class="w-10 h-10 md:w-16 md:h-16 text-brand-green animate-spin-slow" fill="currentColor">
                    <!-- Stylized Asterisk/Flower -->
                    <path d="M50 0 L60 35 L95 25 L70 50 L95 75 L60 65 L50 100 L40 65 L5 75 L30 50 L5 25 L40 35 Z" />
                </svg>
            </span>
            <br class="hidden md:block" />
            Förderung in Minuten
        </h1>

        <!-- Subheadline -->
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
            Förderflink durchsucht automatisch 1.400+ Förderprogramme und findet die passenden Zuschüsse für Ihr Unternehmen – in unter 5 Minuten statt 3 Stunden manueller Recherche.
        </p>

        <!-- CTA -->
        <div class="mb-16">
            <a href="#" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-base font-medium rounded-full text-white bg-brand-green hover:bg-brand-green-hover transition-all shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
                Kostenlose Förderanalyse starten
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </a>
        </div>

        <!-- Platform Preview -->
        <div class="w-full max-w-5xl mx-auto rounded-lg overflow-hidden shadow-2xl bg-white border border-gray-200 aspect-video relative">
            <!-- Mockup of funding analysis interface -->
            <div class="absolute inset-0 bg-gradient-to-br from-gray-50 to-white p-8 flex flex-col">
                <!-- Header -->
                <div class="flex items-center justify-between mb-6 pb-4 border-b border-gray-200">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-brand-green/10 flex items-center justify-center">
                            <svg class="w-6 h-6 text-brand-green" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        </div>
                        <div>
                            <div class="text-sm font-bold text-gray-900">Analyse abgeschlossen</div>
                            <div class="text-xs text-gray-500">12 passende Förderprogramme gefunden</div>
                        </div>
                    </div>
                    <div class="text-xs font-mono text-gray-400">4:32 Min.</div>
                </div>

                <!-- Results List -->
                <div class="space-y-3 flex-1 overflow-hidden">
                    <div class="bg-white rounded-lg border border-gray-200 p-4 flex items-center justify-between hover:shadow-md transition-shadow">
                        <div class="flex-1">
                            <div class="flex items-center gap-2 mb-1">
                                <span class="text-xs font-bold text-brand-green bg-brand-green/10 px-2 py-0.5 rounded">98% Match</span>
                                <span class="text-xs text-gray-500">Bund</span>
                            </div>
                            <div class="text-sm font-medium text-gray-900">Digital Jetzt – Digitalisierung des Mittelstands</div>
                            <div class="text-xs text-gray-600 mt-1">Bis zu €50.000 Zuschuss</div>
                        </div>
                        <svg class="w-5 h-5 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 p-4 flex items-center justify-between hover:shadow-md transition-shadow">
                        <div class="flex-1">
                            <div class="flex items-center gap-2 mb-1">
                                <span class="text-xs font-bold text-brand-green bg-brand-green/10 px-2 py-0.5 rounded">95% Match</span>
                                <span class="text-xs text-gray-500">Bayern</span>
                            </div>
                            <div class="text-sm font-medium text-gray-900">Bayerisches Innovationsprogramm</div>
                            <div class="text-xs text-gray-600 mt-1">Bis zu €200.000 Zuschuss</div>
                        </div>
                        <svg class="w-5 h-5 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 p-4 flex items-center justify-between hover:shadow-md transition-shadow opacity-75">
                        <div class="flex-1">
                            <div class="flex items-center gap-2 mb-1">
                                <span class="text-xs font-bold text-gray-600 bg-gray-100 px-2 py-0.5 rounded">87% Match</span>
                                <span class="text-xs text-gray-500">EU</span>
                            </div>
                            <div class="text-sm font-medium text-gray-900">Horizon Europe SME Instrument</div>
                            <div class="text-xs text-gray-600 mt-1">Bis zu €2.5M Zuschuss</div>
                        </div>
                        <svg class="w-5 h-5 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
