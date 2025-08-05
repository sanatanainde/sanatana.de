# sanatana.de
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Sanātana Dharma - Vedische Weisheit, Mantras und Meditation. Entdecke die zeitlose Spiritualität Indiens.">
    <meta name="keywords" content="OM, Dharma, indische Spiritualität, vedische Philosophie, Sanātana Dharma, Mantras, Meditation, Veden">
    <title>sanatana.de | Vedische Weisheit & Spiritualität</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Roboto:wght@300;400;500&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f8f8;
            color: #333;
        }
        
        .gold-text {
            color: #b8860b;
        }
        
        .gold-border {
            border-color: #b8860b;
        }
        
        .gold-bg {
            background-color: #b8860b;
        }
        
        .playfair {
            font-family: 'Playfair Display', serif;
        }
        
        .hero-image {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1547981609-4b6bfe67ca0b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
        }
        
        .instagram-feed {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 1rem;
        }
        
        .mantra-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        .transition-slow {
            transition: all 0.5s ease;
        }
    </style>
</head>
<body class="antialiased">
    <!-- Navigation -->
    <nav class="bg-black text-white py-4 px-6 shadow-lg sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold playfair gold-text">sanatana.de</a>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="hover:gold-text transition-slow">Über uns</a>
                <a href="#mantras" class="hover:gold-text transition-slow">Mantras</a>
                <a href="#blog" class="hover:gold-text transition-slow">Blog</a>
                <a href="#instagram" class="hover:gold-text transition-slow">Inspiration</a>
                <a href="#contact" class="hover:gold-text transition-slow">Kontakt</a>
            </div>
            <button class="md:hidden text-white focus:outline-none">
                <i class="fas fa-bars text-xl"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-image h-screen flex items-center justify-center text-center text-white">
        <div class="px-4 max-w-4xl">
            <h1 class="playfair text-4xl md:text-6xl font-bold mb-6">Sanātana Dharma</h1>
            <p class="text-xl md:text-2xl mb-8 playfair italic">„Für Seelen, die sich erinnern wollen“</p>
            <p class="text-lg mb-10">Die ewige Weisheit der Veden für das moderne Leben</p>
            <a href="#about" class="gold-bg text-black px-8 py-3 rounded-full font-medium hover:bg-yellow-700 transition-slow">Entdecken</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-4 bg-white">
        <div class="container mx-auto max-w-6xl">
            <h2 class="playfair text-3xl md:text-4xl font-bold text-center mb-16 gold-text">Über Sanātana Dharma</h2>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <p class="mb-6 text-lg">Sanātana Dharma, oft als Hinduismus bezeichnet, ist die zeitlose spirituelle Tradition Indiens, die auf den vedischen Schriften basiert. Das Wort "Sanātana" bedeutet ewig, während "Dharma" oft als Pflicht, Gesetz oder wesentliche Natur übersetzt wird.</p>
                    <p class="mb-6 text-lg">Diese uralte Weisheit bietet tiefe Einsichten in die Natur der Realität, des Selbst und des Universums. Sie lehrt uns, wie wir in Harmonie mit der kosmischen Ordnung leben können.</p>
                    <p class="text-lg">Auf sanatana.de erforschen wir diese ewigen Wahrheiten und wie sie unser modernes Leben bereichern können.</p>
                </div>
                <div class="relative">
                    <img src="https://images.unsplash.com/photo-1589998059171-988d887df646?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2076&q=80" alt="Vedische Weisheit" class="rounded-lg shadow-xl w-full h-auto">
                    <div class="absolute -bottom-6 -right-6 bg-black text-white p-4 playfair text-xl hidden md:block">
                        "Die Wahrheit ist eins, die Weisen beschreiben sie verschieden." - Rigveda
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Mantras Section -->
    <section id="mantras" class="py-20 px-4 bg-gray-50">
        <div class="container mx-auto max-w-6xl">
            <h2 class="playfair text-3xl md:text-4xl font-bold text-center mb-16 gold-text">Heilige Mantras</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Mantra Card 1 -->
                <div class="mantra-card bg-white p-6 rounded-lg shadow-md transition-slow">
                    <div class="text-4xl gold-text mb-4">
                        ॐ
                    </div>
                    <h3 class="playfair text-xl font-bold mb-3">Om Mantra</h3>
                    <p class="mb-4">Der Urklang des Universums. Das heiligste aller Mantras, das die Essenz der höchsten Realität verkörpert.</p>
                    
                </div>
                
                <!-- Mantra Card 2 -->
                <div class="mantra-card bg-white p-6 rounded-lg shadow-md transition-slow">
                    <div class="text-4xl gold-text mb-4">
                        ॐ नमः शिवाय
                    </div>
                    <h3 class="playfair text-xl font-bold mb-3">Om Namah Shivaya</h3>
                    <p class="mb-4">Das große fünfsilbige Mantra, das die Verehrung von Shiva ausdrückt und Transformation bewirkt.</p>
                    
                </div>
                
                <!-- Mantra Card 3 -->
                <div class="mantra-card bg-white p-6 rounded-lg shadow-md transition-slow">
                    <div class="text-4xl gold-text mb-4">
                        हरे कृष््ण
                    </div>
                    <h3 class="playfair text-xl font-bold mb-3">Hare Krishna Maha Mantra</h3>
                    <p class="mb-4">Das große Beschwörungsmantra, das die göttlichen Namen Krishnas und Ramas enthält.</p>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="#" class="gold-text underline hover:no-underline playfair text-lg">Alle Mantras entdecken →</a>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-20 px-4 bg-white">
        <div class="container mx-auto max-w-6xl">
            <h2 class="playfair text-3xl md:text-4xl font-bold text-center mb-16 gold-text">Vedische Weisheit</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Blog Post 1 -->
                <article class="border border-gray-200 rounded-lg overflow-hidden hover:shadow-lg transition-slow">
                    <img src="https://images.unsplash.com/photo-1547981609-4b6bfe67ca0b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Die vier Lebensziele" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="text-sm gold-text">VEDISCHE PHILOSOPHIE</span>
                        <h3 class="playfair text-xl font-bold my-2">Die vier Purusharthas: Dharma, Artha, Kama, Moksha</h3>
                        <p class="text-gray-600 mb-4">Die vedische Philosophie beschreibt vier legitime Lebensziele, die in Harmonie verfolgt werden sollten.</p>
                        <a href="#" class="gold-text font-medium hover:underline">Weiterlesen</a>
                    </div>
                </article>
                
                <!-- Blog Post 2 -->
                <article class="border border-gray-200 rounded-lg overflow-hidden hover:shadow-lg transition-slow">
                    <img src="https://images.unsplash.com/photo-1513097847644-f00cfe868607?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTV8fGElMjBsYWR5JTIwc2l0dGluZyUyMGluJTIwbWVkaXRhdGlvbnxlbnwwfHwwfHx8MA%3D%3D auto=format&fit=crop&w=2070&q=80" alt="Meditation" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="text-sm gold-text">MEDITATION</span>
                        <h3 class="playfair text-xl font-bold my-2">Dhyana: Die vedische Kunst der Meditation</h3>
                        <p class="text-gray-600 mb-4">Wie die alten Rishis Meditation praktizierten und wie wir diese Techniken heute anwenden können.</p>
                        <a href="#" class="gold-text font-medium hover:underline">Weiterlesen</a>
                    </div>
                </article>
                
                <!-- Blog Post 3 -->
                <article class="border border-gray-200 rounded-lg overflow-hidden hover:shadow-lg transition-slow">
                    <img src="https://images.unsplash.com/photo-1521146250551-a5578dcc2e64?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8YXl1cnZlZGljfGVufDB8fDB8fHww auto=format&fit=crop&w=2070&q=80" alt="Ayurveda" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="text-sm gold-text">AYURVEDA</span>
                        <h3 class="playfair text-xl font-bold my-2">Ayurveda: Das vedische Wissen von Gesundheit</h3>
                        <p class="text-gray-600 mb-4">Die ganzheitliche Wissenschaft des Lebens und wie sie uns zu Wohlbefinden verhilft.</p>
                        <a href="#" class="gold-text font-medium hover:underline">Weiterlesen</a>
                    </div>
                </article>
            </div>
            <div class="text-center mt-12">
                <a href="#" class="gold-bg text-black px-8 py-3 rounded-full font-medium hover:bg-yellow-700 transition-slow">Alle Artikel lesen</a>
            </div>
        </div>
    </section>

    <!-- Instagram Feed -->
    <section id="instagram" class="py-20 px-4 bg-gray-50">
        <div class="container mx-auto max-w-6xl">
            <h2 class="playfair text-3xl md:text-4xl font-bold text-center mb-16 gold-text">Inspiration auf Instagram</h2>
            <div class="instagram-feed">
                <!-- Instagram posts would be dynamically loaded here -->
                <div class="bg-black aspect-square flex items-center justify-center text-white text-2xl playfair">#OM</div>
                <div class="bg-black aspect-square flex items-center justify-center text-white text-2xl playfair">#Dharma</div>
                <div class="bg-black aspect-square flex items-center justify-center text-white text-2xl playfair">#Meditation</div>
                <div class="bg-black aspect-square flex items-center justify-center text-white text-2xl playfair">#Veden</div>
                <div class="bg-black aspect-square flex items-center justify-center text-white text-2xl playfair">#Spiritualität</div>
                <div class="bg-black aspect-square flex items-center justify-center text-white text-2xl playfair">#Mantra</div>
            </div>
            <div class="text-center mt-12">
                <a href="https://www.instagram.com/sanatana.de?igsh=MXc5d2l2NXA4OXR5Nw==" class="inline-flex items-center gold-text hover:underline">
                    <i class="fab fa-instagram mr-2 text-xl"></i>
                    Folge uns @sanatana.de
                </a>
            </div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="py-16 px-4 bg-black text-white">
        <div class="container mx-auto max-w-4xl text-center">
            <h2 class="playfair text-3xl font-bold mb-6 gold-text">Bleibe verbunden</h2>
            <p class="mb-8 max-w-2xl mx-auto">Erhalte regelmäßig vedische Weisheiten, Mantras und Meditationstipps direkt in dein Postfach.</p>
            <form class="flex flex-col sm:flex-row gap-4 max-w-lg mx-auto">
                <input type="email" placeholder="Deine E-Mail-Adresse" class="flex-grow px-4 py-3 rounded-full text-black focus:outline-none focus:ring-2 focus:ring-yellow-600">
                <button type="submit" class="gold-bg text-black px-6 py-3 rounded-full font-medium hover:bg-yellow-700 transition-slow">Anmelden</button>
            </form>
            <p class="text-sm mt-4 text-gray-400">Wir respektieren deine Privatsphäre. Kein Spam.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-900 text-white py-12 px-4">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <h3 class="playfair text-xl font-bold mb-4 gold-text">sanatana.de</h3>
                    <p class="mb-4">Für Seelen, die sich erinnern wollen.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-white hover:gold-text transition-slow"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div>
                    <h4 class="playfair font-bold mb-4">Navigation</h4>
                    <ul class="space-y-2">
                        <li><a href="#about" class="hover:gold-text transition-slow">Über uns</a></li>
                        <li><a href="#mantras" class="hover:gold-text transition-slow">Mantras</a></li>
                        <li><a href="#blog" class="hover:gold-text transition-slow">Blog</a></li>
                        <li><a href="#instagram" class="hover:gold-text transition-slow">Inspiration</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="playfair font-bold mb-4">Ressourcen</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:gold-text transition-slow">Vedische Texte</a></li>
                        <li><a href="#" class="hover:gold-text transition-slow">Meditationsanleitung</a></li>
                        <li><a href="#" class="hover:gold-text transition-slow">Glossar</a></li>
                        <li><a href="#" class="hover:gold-text transition-slow">Empfohlene Bücher</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="playfair font-bold mb-4">Kontakt</h4>
                    <ul class="space-y-2">
                        <li><a href="mailto:info@sanatana.de" class="hover:gold-text transition-slow">info@sanatana.de</a></li>
                        <li><a href="#" class="hover:gold-text transition-slow">Impressum</a></li>
                        <li><a href="#" class="hover:gold-text transition-slow">Datenschutz</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-500">
                <p>© 2023 sanatana.de - Alle Rechte vorbehalten.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle functionality
        document.addEventListener('DOMContentLoaded', function() {
            const mobileMenuButton = document.querySelector('button.md\\:hidden');
            const navLinks = document.querySelector('.hidden.md\\:flex');
            
            mobileMenuButton.addEventListener('click', function() {
                navLinks.classList.toggle('hidden');
                navLinks.classList.toggle('flex');
                navLinks.classList.toggle('flex-col');
                navLinks.classList.toggle('absolute');
                navLinks.classList.toggle('top-16');
                navLinks.classList.toggle('left-0');
                navLinks.classList.toggle('right-0');
                navLinks.classList.toggle('bg-black');
                navLinks.classList.toggle('p-4');
                navLinks.classList.toggle('space-y-4');
                navLinks.classList.toggle('space-x-8');
            });
            
            // Smooth scrolling for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (!navLinks.classList.contains('hidden')) {
                        mobileMenuButton.click();
                    }
                });
            });
        });
    </script>
</body>
</html>
