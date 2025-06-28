# index.html

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI PlayMakers - AI News, Innovations, and Profit</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Custom Styles & Tailwind Config -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'brand-primary': '#0D0E13', // A very dark blue/black
                        'brand-secondary': '#1A1B23', // Dark gray
                        'brand-accent': '#00F5A0', // Vibrant Green
                        'brand-accent-hover': '#00D890',
                        'brand-text': '#E0E0E0', // Light gray text
                        'brand-subtle': '#A0A0A0', // Softer text
                    }
                }
            }
        }
    </script>
    <style>
        /* Small style tweaks for better aesthetics */
        .glow-effect {
            box-shadow: 0 0 15px rgba(0, 245, 160, 0.2), 0 0 5px rgba(0, 245, 160, 0.1);
        }
    </style>
</head>
<body class="bg-brand-primary text-brand-text font-sans antialiased">

    <!-- Header & Navigation -->
    <header id="home" class="bg-brand-primary/80 backdrop-blur-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#home" class="text-2xl font-bold text-white flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-2 text-brand-accent" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.486 2 2 6.486 2 12s4.486 10 10 10 10-4.486 10-10S17.514 2 12 2zm-1.707 14.707L6 12.414l1.414-1.414L10.293 14l5.293-5.293L17 10.121l-6.707 6.586z"/></svg>
                AI PlayMakers
            </a>
            <div class="hidden md:flex space-x-8 items-center">
                <a href="#blog" class="text-brand-subtle hover:text-white transition-colors duration-300">Blog</a>
                <a href="#tools" class="text-brand-subtle hover:text-white transition-colors duration-300">Recommended Tools</a>
                <a href="#about" class="text-brand-subtle hover:text-white transition-colors duration-300">About</a>
                <a href="#contact" class="text-brand-subtle hover:text-white transition-colors duration-300">Contact</a>
                <a href="#newsletter" class="bg-brand-accent text-brand-primary font-bold py-2 px-4 rounded-lg hover:bg-brand-accent-hover transition-all duration-300 glow-effect">Subscribe</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-white">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#blog" class="block py-2 text-brand-subtle hover:text-white">Blog</a>
            <a href="#tools" class="block py-2 text-brand-subtle hover:text-white">Recommended Tools</a>
            <a href="#about" class="block py-2 text-brand-subtle hover:text-white">About</a>
            <a href="#contact" class="block py-2 text-brand-subtle hover:text-white">Contact</a>
            <a href="#newsletter" class="block mt-2 bg-brand-accent text-brand-primary text-center font-bold py-2 px-4 rounded-lg hover:bg-brand-accent-hover">Subscribe</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="container mx-auto px-6 py-20 md:py-32 text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold text-white leading-tight">Your Guide to AI News, Innovations, and Profit.</h1>
            <p class="mt-6 text-lg md:text-xl text-brand-subtle max-w-3xl mx-auto">Stay ahead of the curve. We break down the latest in AI and tech, showing you how to turn knowledge into opportunity—whether you're a beginner or an expert.</p>
            <div class="mt-10">
                <a href="#newsletter" class="bg-brand-accent text-brand-primary font-bold py-4 px-8 rounded-lg text-lg hover:bg-brand-accent-hover transition-all duration-300 transform hover:scale-105 glow-effect">Subscribe to the Newsletter</a>
            </div>
        </section>

        <!-- Latest Blog Posts Section -->
        <section id="blog" class="py-20 bg-brand-secondary">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-white text-center mb-12">Latest Articles</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Blog Post 1 -->
                    <div class="bg-brand-primary rounded-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300">
                        <img src="https://placehold.co/600x400/1A1B23/00F5A0?text=AI+Automation" alt="AI Automation Trends" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="text-sm text-brand-accent font-semibold">Making Money with AI</p>
                            <h3 class="text-xl font-bold text-white mt-2">Top 5 AI Tools to Automate Your Side Hustle in 2025</h3>
                            <p class="text-brand-subtle mt-2">Discover how you can leverage simple AI tools to generate passive income with minimal effort.</p>
                            <a href="#" class="inline-block mt-4 text-brand-accent font-semibold hover:text-white">Read More &rarr;</a>
                        </div>
                    </div>
                    <!-- Blog Post 2 -->
                    <div class="bg-brand-primary rounded-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300">
                        <img src="https://placehold.co/600x400/1A1B23/FFFFFF?text=Tech+News" alt="Latest Tech News" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="text-sm text-brand-accent font-semibold">AI News</p>
                            <h3 class="text-xl font-bold text-white mt-2">The Generative Video Revolution: What's Next?</h3>
                            <p class="text-brand-subtle mt-2">Video generation models are getting scarily good. We explore the implications for creators and businesses.</p>
                            <a href="#" class="inline-block mt-4 text-brand-accent font-semibold hover:text-white">Read More &rarr;</a>
                        </div>
                    </div>
                    <!-- Blog Post 3 -->
                    <div class="bg-brand-primary rounded-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300">
                        <img src="https://placehold.co/600x400/1A1B23/E0E0E0?text=Tutorial" alt="Beginner's Guide" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="text-sm text-brand-accent font-semibold">Tech Tutorials</p>
                            <h3 class="text-xl font-bold text-white mt-2">Beginner's Guide to Prompt Engineering</h3>
                            <p class="text-brand-subtle mt-2">Learn the art of talking to AIs to get exactly what you want. It's easier than you think!</p>
                            <a href="#" class="inline-block mt-4 text-brand-accent font-semibold hover:text-white">Read More &rarr;</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Recommended Tools (Affiliate) Section -->
        <section id="tools" class="py-20">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-white text-center mb-4">Our Top Recommended Tools</h2>
                <p class="text-brand-subtle text-center max-w-2xl mx-auto mb-12">We've tested countless AI tools. These are the ones we use and recommend to build and grow your business.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Tool 1 -->
                    <div class="border border-brand-secondary rounded-lg p-6 text-center flex flex-col items-center">
                        <img src="https://placehold.co/100x100/1A1B23/FFFFFF?text=Tool+A" alt="Tool A Logo" class="h-16 w-16 rounded-full mb-4">
                        <h4 class="text-xl font-bold text-white">AI Writer Pro</h4>
                        <p class="text-brand-subtle mt-2 flex-grow">The best AI for generating high-quality blog posts and marketing copy.</p>
                        <a href="#" class="mt-4 w-full bg-brand-secondary text-white font-semibold py-2 px-4 rounded-lg hover:bg-gray-700 transition-colors">Get Started</a>
                    </div>
                    <!-- Tool 2 -->
                    <div class="border border-brand-secondary rounded-lg p-6 text-center flex flex-col items-center">
                        <img src="https://placehold.co/100x100/1A1B23/00F5A0?text=Tool+B" alt="Tool B Logo" class="h-16 w-16 rounded-full mb-4">
                        <h4 class="text-xl font-bold text-white">ImageGen AI</h4>
                        <p class="text-brand-subtle mt-2 flex-grow">Create stunning, royalty-free images for your content with a single prompt.</p>
                        <a href="#" class="mt-4 w-full bg-brand-secondary text-white font-semibold py-2 px-4 rounded-lg hover:bg-gray-700 transition-colors">Try It Now</a>
                    </div>
                    <!-- Tool 3 -->
                    <div class="border border-brand-secondary rounded-lg p-6 text-center flex flex-col items-center">
                        <img src="https://placehold.co/100x100/1A1B23/E0E0E0?text=Tool+C" alt="Tool C Logo" class="h-16 w-16 rounded-full mb-4">
                        <h4 class="text-xl font-bold text-white">VideoBoost</h4>
                        <p class="text-brand-subtle mt-2 flex-grow">Generate professional voiceovers and short videos for social media.</p>
                        <a href="#" class="mt-4 w-full bg-brand-secondary text-white font-semibold py-2 px-4 rounded-lg hover:bg-gray-700 transition-colors">Check Price</a>
                    </div>
                    <!-- Tool 4 -->
                    <div class="border border-brand-secondary rounded-lg p-6 text-center flex flex-col items-center">
                        <img src="https://placehold.co/100x100/00F5A0/0D0E13?text=Tool+D" alt="Tool D Logo" class="h-16 w-16 rounded-full mb-4">
                        <h4 class="text-xl font-bold text-white">CodeHelper</h4>
                        <p class="text-brand-subtle mt-2 flex-grow">An AI-powered assistant that helps you code faster and with fewer bugs.</p>
                        <a href="#" class="mt-4 w-full bg-brand-secondary text-white font-semibold py-2 px-4 rounded-lg hover:bg-gray-700 transition-colors">Learn More</a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Newsletter Section -->
        <section id="newsletter" class="py-20 bg-brand-secondary">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold text-white">Don't Miss Out</h2>
                <p class="mt-4 text-lg text-brand-subtle max-w-2xl mx-auto">Join the AI PlayMakers newsletter for exclusive content, early access to articles, and special affiliate deals delivered right to your inbox.</p>
                <form class="mt-8 max-w-md mx-auto">
                    <div class="flex flex-col sm:flex-row gap-4">
                        <input type="email" placeholder="Enter your email" required class="flex-grow w-full px-4 py-3 rounded-lg bg-brand-primary border border-brand-secondary focus:ring-2 focus:ring-brand-accent focus:outline-none text-white">
                        <button type="submit" class="bg-brand-accent text-brand-primary font-bold py-3 px-6 rounded-lg hover:bg-brand-accent-hover transition-all duration-300 glow-effect">Subscribe</button>
                    </div>
                </form>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-20">
            <div class="container mx-auto px-6 text-center max-w-3xl">
                <h2 class="text-3xl font-bold text-white">Our Mission</h2>
                <p class="mt-6 text-lg text-brand-subtle">AI is reshaping our world at an incredible pace. The problem? Most conversations are either too technical for beginners or too basic for experts. At AI PlayMakers, our mission is to bridge that gap. We exist to demystify artificial intelligence and empower everyone—from curious newcomers to seasoned pros—to understand, use, and profit from this revolutionary technology. We believe AI is a tool for creation and opportunity, and we're here to show you how to play.</p>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 bg-brand-secondary">
            <div class="container mx-auto px-6 max-w-xl">
                <h2 class="text-3xl font-bold text-white text-center mb-8">Get In Touch</h2>
                <form action="#" method="POST" class="space-y-6">
                    <div>
                        <label for="name" class="sr-only">Name</label>
                        <input type="text" name="name" id="name" placeholder="Your Name" class="w-full px-4 py-3 rounded-lg bg-brand-primary border border-transparent focus:ring-2 focus:ring-brand-accent focus:outline-none text-white">
                    </div>
                    <div>
                        <label for="email-contact" class="sr-only">Email</label>
                        <input type="email" name="email" id="email-contact" placeholder="Your Email" class="w-full px-4 py-3 rounded-lg bg-brand-primary border border-transparent focus:ring-2 focus:ring-brand-accent focus:outline-none text-white">
                    </div>
                    <div>
                        <label for="message" class="sr-only">Message</label>
                        <textarea name="message" id="message" rows="4" placeholder="Your Message" class="w-full px-4 py-3 rounded-lg bg-brand-primary border border-transparent focus:ring-2 focus:ring-brand-accent focus:outline-none text-white"></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-brand-accent text-brand-primary font-bold py-3 px-8 rounded-lg hover:bg-brand-accent-hover transition-all duration-300 transform hover:scale-105 glow-effect">Send Message</button>
                    </div>
                </form>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-brand-primary border-t border-brand-secondary">
        <div class="container mx-auto px-6 py-8 text-center text-brand-subtle">
            <p>&copy; 2025 AI PlayMakers. All Rights Reserved.</p>
            <p class="mt-2 text-sm">
                <a href="#" id="disclosure-link" class="hover:text-white underline">Affiliate Disclosure</a>
            </p>
        </div>
    </footer>
    
    <!-- Affiliate Disclosure Modal -->
    <div id="disclosure-modal" class="fixed inset-0 bg-black bg-opacity-70 z-50 flex justify-center items-center p-4 hidden">
        <div class="bg-brand-secondary rounded-lg p-8 max-w-2xl w-full relative">
            <button id="close-modal-button" class="absolute top-4 right-4 text-brand-subtle hover:text-white text-2xl">&times;</button>
            <h3 class="text-2xl font-bold text-white mb-4">Affiliate Disclosure</h3>
            <div class="text-brand-subtle space-y-4">
                <p>Transparency is important to us. Please be aware that some of the links on this website are affiliate links. This means that if you click on the link and make a purchase, we may receive a commission at no extra cost to you.</p>
                <p>We only recommend products and services that we have personally used, tested, and believe will provide value to our readers. Our goal is to help you discover amazing tools, and any commission we earn helps us continue to create high-quality, free content for you.</p>
                <p>AI PlayMakers is a participant in various affiliate programs, designed to provide a means for sites to earn advertising fees by advertising and linking to partner sites.</p>
                <p>Thank you for your support!</p>
            </div>
        </div>
    </div>


    <!-- JavaScript for interactivity -->
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Mobile menu toggle
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenuButton.addEventListener('click', function() {
                mobileMenu.classList.toggle('hidden');
            });

            // Close mobile menu when a link is clicked
            const mobileLinks = mobileMenu.querySelectorAll('a');
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                     mobileMenu.classList.add('hidden');
                });
            });

            // Affiliate Disclosure Modal
            const disclosureLink = document.getElementById('disclosure-link');
            const disclosureModal = document.getElementById('disclosure-modal');
            const closeModalButton = document.getElementById('close-modal-button');

            disclosureLink.addEventListener('click', function(e) {
                e.preventDefault();
                disclosureModal.classList.remove('hidden');
            });

            closeModalButton.addEventListener('click', function() {
                disclosureModal.classList.add('hidden');
            });

            // Close modal on outside click
            disclosureModal.addEventListener('click', function(e) {
                if (e.target === disclosureModal) {
                    disclosureModal.classList.add('hidden');
                }
            });
        });
    </script>

</body>
</html>
