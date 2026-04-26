                    <h3 class="text-2xl font-bold mb-4 text-center">Rose Passion</h3>
                    <p class="text-slate-400 mb-6 text-center leading-relaxed">
                        Rose damascena, jasmin et musc blanc pour une soirée romantique
                    </p>
                    <div class="flex items-center justify-center space-x-4 mb-6">
                        <span class="text-2xl font-bold text-amber-400">€28</span>
                        <span class="text-slate-500 line-through">€38</span>
                    </div>
                    <button class="w-full bg-gradient-to-r from-amber-500 to-orange-500 hover:from-amber-400 hover:to-orange-400 text-lg font-semibold py-4 rounded-2xl transition-all duration-300 transform hover:-translate-y-1">
                        Ajouter au panier
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Section À Propos -->
    <section id="a-propos" class="py-32 px-4 bg-white/5 backdrop-blur-sm">
        <div class="max-w-7xl mx-auto">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div class="order-2 lg:order-1">
                    <h2 class="text-4xl md:text-5xl font-bold bg-gradient-to-r from-amber-400 to-orange-500 bg-clip-text text-transparent mb-8">
                        L'Art de la Bougie Parfumée
                    </h2>
                    <p class="text-xl text-slate-300 mb-8 leading-relaxed">
                        Depuis 5 ans, nous créons des bougies artisanales avec des ingrédients 100% naturels. 
                        Chaque bougie est coulée à la main dans notre atelier en Provence.
                    </p>
                    <div class="grid md:grid-cols-2 gap-8 mb-12">
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-amber-400 rounded-2xl flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="fas fa-seedling text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-xl mb-2">Naturel</h4>
                                <p class="text-slate-400">Cire de soja et huiles essentielles</p>
                            </div>
                        </div>
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-amber-400 rounded-2xl flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="fas fa-hand-holding-heart text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-xl mb-2">Artisanal</h4>
                                <p class="text-slate-400">Fabriqué à la main en petite série</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="order-1 lg:order-2 relative">
                    <div class="relative z-10">
                        <img src="https://images.unsplash.com/photo-1558618047-3c8c76fdd9e4?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" 
                             alt="Atelier de fabrication" 
                             class="w-full h-96 object-cover rounded-3xl shadow-2xl">
                    </div>
                    <div class="absolute -top-8 -right-8 w-72 h-72 bg-gradient-to-br from-amber-400/20 to-orange-500/20 rounded-full blur-xl"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact" class="py-32 px-4 relative">
        <div class="max-w-4xl mx-auto text-center">
            <div class="glass-effect backdrop-blur-md rounded-3xl p-12 md:p-20 max-w-3xl mx-auto">
                <div class="w-24 h-24 bg-gradient-to-br from-amber-400 to-orange-500 rounded-3xl mx-auto mb-8 flex items-center justify-center">
                    <i class="fas fa-envelope text-3xl text-white"></i>
                </div>
                <h2 class="text-4xl md:text-5xl font-bold bg-gradient-to-r from-amber-400 to-orange-500 bg-clip-text text-transparent mb-6">
                    Prêt à illuminer votre intérieur ?
                </h2>
                <p class="text-xl text-slate-300 mb-12 max-w-2xl mx-auto leading-relaxed">
                    Contactez-nous pour toute question ou pour commander vos bougies préférées
                </p>
                
                <div class="grid md:grid-cols-3 gap-8 mb-12">
                    <div class="flex flex-col items-center space-y-3 p-6">
                        <div class="w-16 h-16 bg-amber-400/20 rounded-2xl flex items-center justify-center">
                            <i class="fas fa-phone text-2xl text-amber-400"></i>
                        </div>
                        <div>
                            <p class="font-semibold">Téléphone</p>
                            <p class="text-slate-400">+33 6 12 34 56 78</p>
                        </div>
                    </div>
                    <div class="flex flex-col items-center space-y-3 p-6">
                        <div class="w-16 h-16 bg-amber-400/20 rounded-2xl flex items-center justify-center">
                            <i class="fas fa-envelope text-2xl text-amber-400"></i>
                        </div>
                        <div>
                            <p class="font-semibold">Email</p>
                            <p class="text-slate-400">contact@lumiere-parfum.fr</p>
                        </div>
                    </div>
                    <div class="flex flex-col items-center space-y-3 p-6">
                        <div class="w-16 h-16 bg-amber-400/20 rounded-2xl flex items-center justify-center">
                            <i class="fas fa-map-marker-alt text-2xl text-amber-400"></i>
                        </div>
                        <div>
                            <p class="font-semibold">Adresse</p>
                            <p class="text-slate-400">Provence, France</p>
                        </div>
                    </div>
                </div>

                <form class="max-w-2xl mx-auto space-y-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <input type="text" placeholder="Votre prénom" 
                               class="w-full px-6 py-4 bg-white/10 backdrop-blur-sm border border-white/30 rounded-2xl focus:outline-none focus:border-amber-400 focus:ring-4 focus:ring-amber-400/20 transition-all duration-300 text-white placeholder-slate-400">
                        <input type="text" placeholder="Votre email" 
                               class="w-full px-6 py-4 bg-white/10 backdrop-blur-sm border border-white/30 rounded-2xl focus:outline-none focus:border-amber-400 focus:ring-4 focus:ring-amber-400/20 transition-all duration-300 text-white placeholder-slate-400">
                    </div>
                    <textarea rows="5" placeholder="Votre message" 
                              class="w-full px-6 py-4 bg-white/10 backdrop-blur-sm border border-white/30 rounded-2xl focus:outline-none focus:border-amber-400 focus:ring-4 focus:ring-amber-400/20 transition-all duration-300 text-white placeholder-slate-400 resize-none"></textarea>
                    <button type="submit" 
                            class="w-full bg-gradient-to-r from-amber-500 to-orange-500 hover:from-amber-400 hover:to-orange-400 text-xl font-semibold py-6 rounded-3xl shadow-2xl hover:shadow-amber-500/25 transform hover:-translate-y-2 transition-all duration-300">
                        <i class="fas fa-paper-plane mr-3"></i>
                        Envoyer le message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 px-4 border-t border-white/10">
        <div class="max-w-7xl mx-auto text-center">
            <div class="flex items-center justify-center space-x-4 mb-6">
                <i class="fas fa-candle-stick text-3xl text-amber-400"></i>
                <span class="text-2xl font-bold bg-gradient-to-r from-amber-400 to-orange-500 bg-clip-text text-transparent">
                    Lumière & Parfum
                </span>
            </div>
            <p class="text-slate-500 mb-8">
                © 2024 Lumière & Parfum. Toutes les bougies sont fabriquées avec ❤️ en France.
            </p>
            <div class="flex justify-center space-x-6">
                <a href="#" class="w-12 h-12 bg-white/10 backdrop-blur-sm rounded-2xl flex items-center justify-center hover:bg-amber-400/20 transition-all duration-300">
                    <i class="fab fa-instagram text-xl"></i>
                </a>
                <a href="#" class="w-12 h-12 bg-white/10 backdrop-blur-sm rounded-2xl flex items-center justify-center hover:bg-amber-400/20 transition-all duration-300">
                    <i class="fab fa-facebook text-xl"></i>
                </a>
                <a href="#" class="w-12 h-12 bg-white/10 backdrop-blur-sm rounded-2xl flex items-center justify-center hover:bg-amber-400/20 transition-all duration-300">
                    <i class="fab fa-pinterest text-xl"></i>
                </a>
            </div>
        </div>
    </footer>

    <!-- JavaScript pour le menu mobile et smooth scroll -->
    <script>
        // Menu mobile
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scroll pour les liens de navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
                // Fermer le menu mobile
                mobileMenu.classList.add('hidden');
            });
        });

        // Animation au scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Observer les sections
        document.querySelectorAll('section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(30px)';
            section.style.transition = 'all 0.6s ease-out';
            observer.observe(section);
        });
    </script>
</body>
</html>
