<script>
    // No script logic needed for this static recreation yet
</script>

<section class="py-20 bg-white font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Die Förderflink Plattform</span>
        <h2 class="mt-8 text-5xl md:text-7xl font-serif-display text-gray-900 leading-tight">Wo deutsche KMUs <br/> ihre Förderung <br/> finden</h2>
    </div>
    
    <!-- Tabbed interface image area -->
    <div class="max-w-7xl mx-auto mt-16 px-4">
        <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm bg-white grid md:grid-cols-12 min-h-[600px]">
             <div class="md:col-span-4 p-8 md:p-12 border-r border-gray-200 flex flex-col justify-center">
                 <h3 class="text-3xl font-serif-display mb-4">Ihr Unternehmensprofil – der Schlüssel zur passenden Förderung</h3>
                 <p class="text-gray-600 text-base leading-relaxed mb-8">Förderflink analysiert Ihre Branche, Unternehmensgröße, Standort und Vorhaben. Unsere KI gleicht diese Daten automatisch mit den Förderkriterien von über 1.400 Programmen ab und liefert Ihnen eine priorisierte Liste mit Relevanz-Scores. So wissen Sie sofort, welche Förderungen sich lohnen.</p>
                 <div>
                    <button class="text-sm font-bold border-b border-gray-300 pb-0.5 hover:border-gray-900 transition-colors">Mehr erfahren -></button>
                 </div>
             </div>
             <div class="md:col-span-8 bg-gray-50 p-8 md:p-12 flex items-center justify-center relative overflow-hidden">
                 <!-- Simplified UI Mockup -->
                 <div class="bg-white shadow-xl rounded-lg w-full h-full border border-gray-200 p-6 relative flex flex-col">
                    <div class="flex gap-2 mb-6 border-b border-gray-100 pb-4">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                        <div class="ml-auto flex gap-2">
                            <div class="h-4 w-32 bg-gray-100 rounded-full"></div>
                        </div>
                    </div>
                    
                    <div class="space-y-6">
                        <!-- Header Stats -->
                        <div class="grid grid-cols-4 gap-4">
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Programme</div>
                                 <div class="text-xl font-bold text-gray-900">1,400+</div>
                                 <div class="text-[10px] text-brand-green font-bold">Gescannt</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Matches</div>
                                 <div class="text-xl font-bold text-gray-900">12</div>
                                 <div class="text-[10px] text-brand-green font-bold">Gefunden</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Volumen</div>
                                 <div class="text-xl font-bold text-gray-900">€450k</div>
                                 <div class="text-[10px] text-brand-green font-bold">Möglich</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Zeit</div>
                                 <div class="text-xl font-bold text-gray-900">4:32</div>
                                 <div class="text-[10px] text-gray-400 font-bold">Min</div>
                             </div>
                        </div>

                        <!-- Data Table -->
                        <div class="border border-gray-100 rounded-lg overflow-hidden">
                            <div class="bg-gray-50 px-4 py-2 border-b border-gray-100 flex text-[10px] font-bold text-gray-500 uppercase tracking-wider">
                                <div class="w-2/5">Förderprogramm</div>
                                <div class="w-1/6 text-right">Volumen</div>
                                <div class="w-1/6 text-right">Match</div>
                                <div class="w-1/6 text-right">Ebene</div>
                            </div>
                            <div class="divide-y divide-gray-50 text-xs">
                                 {#each [
                                     {name: 'Digital Jetzt', vol: '€50k', match: '98', level: 'Bund'},
                                     {name: 'Bayerisches Innovationsprogramm', vol: '€200k', match: '95', level: 'Land'},
                                     {name: 'go-digital', vol: '€16.5k', match: '92', level: 'Bund'},
                                     {name: 'Horizon Europe SME', vol: '€2.5M', match: '87', level: 'EU'},
                                     {name: 'KfW Energieeffizienz', vol: '€100k', match: '85', level: 'Bund'}
                                 ] as item}
                                 <div class="px-4 py-3 flex items-center hover:bg-gray-50 transition-colors">
                                     <div class="w-2/5 font-medium text-gray-900">{item.name}</div>
                                     <div class="w-1/6 text-right text-gray-600">{item.vol}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="px-1.5 py-0.5 rounded text-[10px] font-bold {parseInt(item.match) > 90 ? 'bg-green-100 text-green-700' : parseInt(item.match) > 80 ? 'bg-yellow-100 text-yellow-700' : 'bg-gray-100 text-gray-700'}">{item.match}%</span>
                                     </div>
                                     <div class="w-1/6 text-right">
                                         <span class="text-[10px] font-bold text-brand-green">{item.level}</span>
                                     </div>
                                 </div>
                                 {/each}
                            </div>
                        </div>
                    </div>
                 </div>
             </div>
        </div>
        
        <!-- Bottom Grid of 3 items -->
        <div class="grid md:grid-cols-3 gap-0 mt-0 border-x border-b border-gray-200 divide-x divide-gray-200 bg-white">
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">1</div>
                <p class="text-xs text-gray-600 leading-relaxed">Automatischer Scan aller Bundes-, Landes- und EU-Programme mit kontinuierlichen Updates zu neuen Fördermöglichkeiten.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">2</div>
                <p class="text-xs text-gray-600 leading-relaxed">Intelligentes Matching basierend auf Branche, Größe, Standort und Vorhaben – mit präzisen Relevanz-Scores.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">3</div>
                <p class="text-xs text-gray-600 leading-relaxed">Direkte Links zu Antragsunterlagen und Kontaktstellen – alles an einem Ort, priorisiert nach Erfolgswahrscheinlichkeit.</p>
            </div>
        </div>
    </div>
</section>