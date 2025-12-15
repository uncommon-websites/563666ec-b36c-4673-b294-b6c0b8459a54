<script>
    const logos = [
        { name: 'BMW', hasCaseStudy: false },
        { name: 'Siemens', hasCaseStudy: false },
        { name: 'Bosch', hasCaseStudy: false },
        { name: 'SAP', hasCaseStudy: false, icon: true },
        { name: 'Bayer', hasCaseStudy: false },
        { name: 'Adidas', hasCaseStudy: false },
        { name: 'Lufthansa', hasCaseStudy: false },
        { name: 'Deutsche Bank', hasCaseStudy: false, icon: true },
        { name: 'Volkswagen', hasCaseStudy: false },
        { name: 'Merck', hasCaseStudy: false },
        { name: 'BASF', hasCaseStudy: false },
        { name: 'Allianz', hasCaseStudy: false, icon: true },
        { name: 'Porsche', hasCaseStudy: false },
        { name: 'Henkel', hasCaseStudy: false },
        { name: 'Continental', hasCaseStudy: false }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-brand-green font-bold mb-8">
            Vertraut von führenden deutschen Unternehmen
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <!-- Logo Placeholder -->
                    <span class="text-xl md:text-2xl font-bold text-gray-400 group-hover:text-gray-900 transition-colors flex items-center gap-2">
                        {#if logo.icon}
                        <!-- Generic Icon for some -->
                        <div class="w-6 h-6 bg-gray-300 rounded-sm"></div>
                        {/if}
                        {logo.name}
                    </span>
                </div>
            {/each}
        </div>
    </div>
</section>
