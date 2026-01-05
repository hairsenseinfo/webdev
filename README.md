<!DOCTYPE html>
<html lang="en">
<head>
    <base target="_self">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HAIR SENSE | Premium Hair Care Products</title>
    <meta name="description" content="HAIR SENSE is a hair care brand dedicated to restoring, nourishing, and enhancing natural hair health through high-quality hair oils and complementary hair care products.">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'hair-gold': '#D4AF37',
                        'hair-brown': '#8B4513',
                        'hair-cream': '#F5F5DC',
                        'hair-dark': '#2C1810',
                        'hair-light': '#FAF3E0'
                    },
                    fontFamily: {
                        'serif': ['Playfair Display', 'serif'],
                        'sans': ['Inter', 'sans-serif']
                    },
                    spacing: {
                        '128': '32rem',
                        '144': '36rem'
                    }
                }
            }
        }
    </script>
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #FAF3E0 0%, #F5F5DC 50%, #E8DFCA 100%);
        }
        .product-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #D4AF37;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="min-h-screen bg-hair-light font-sans text-hair-dark">
    <!-- Navigation -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-sm shadow-sm">
        <nav class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-2">
                    <div class="w-10 h-10 bg-hair-gold rounded-full flex items-center justify-center">
                        <i class="fas fa-crown text-white"></i>
                    </div>
                    <h1 class="text-2xl font-serif font-bold text-hair-dark">HAIR SENSE</h1>
                </div>
                
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link relative text-hair-dark hover:text-hair-gold transition-colors duration-300 font-medium">Home</a>
                    <a href="#about" class="nav-link relative text-hair-dark hover:text-hair-gold transition-colors duration-300 font-medium">About</a>
                    <a href="#products" class="nav-link relative text-hair-dark hover:text-hair-gold transition-colors duration-300 font-medium">Products</a>
                    <a href="#values" class="nav-link relative text-hair-dark hover:text-hair-gold transition-colors duration-300 font-medium">Values</a>
                    <a href="#contact" class="nav-link relative text-hair-dark hover:text-hair-gold transition-colors duration-300 font-medium">Contact</a>
                </div>
                
                <button class="md:hidden text-hair-dark">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient py-16 md:py-24">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-12 lg:mb-0">
                    <h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-bold text-hair-dark mb-6">
                        Restore. Nourish. <span class="text-hair-gold">Enhance.</span>
                    </h2>
                    <p class="text-lg text-gray-700 mb-8 leading-relaxed">
                        Premium hair care dedicated to restoring, nourishing, and enhancing natural hair health through high-quality hair oils and complementary products.
                    </p>
                    <div class="flex space-x-4">
                        <button class="bg-hair-gold text-white px-8 py-3 rounded-full font-semibold hover:bg-hair-brown transition-all duration-300 transform hover:scale-105">
                            Shop Now
                        </button>
                        <button class="border-2 border-hair-gold text-hair-gold px-8 py-3 rounded-full font-semibold hover:bg-hair-gold hover:text-white transition-all duration-300">
                            Learn More
                        </button>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <div class="relative">
                        <div class="absolute -top-6 -right-6 w-64 h-64 bg-hair-gold/10 rounded-full"></div>
                        <img 
                            src="https://picsum.photos/600/500?random=1" 
                            alt="HAIR SENSE premium hair oil products displayed beautifully" 
                            class="relative rounded-2xl shadow-2xl z-10"
                            loading="lazy"
                        />
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-serif font-bold text-hair-dark mb-4">Our Philosophy</h2>
                <div class="w-24 h-1 bg-hair-gold mx-auto mb-8"></div>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <div class="bg-hair-light/50 p-8 md:p-12 rounded-2xl shadow-lg mb-12">
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        HAIR SENSE is a hair care brand dedicated to restoring, nourishing, and enhancing natural hair health through high-quality hair oils and complementary hair care products. Rooted in the belief that healthy hair begins with the right care, HAIR SENSE blends traditional wisdom with modern formulation techniques to deliver effective, reliable solutions for everyday hair concerns.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        Our product range focuses on promoting hair growth, reducing hair fall, strengthening roots, and improving overall scalp health. Each oil is thoughtfully crafted using carefully selected natural ingredients known for their nourishing and revitalizing properties, making our products suitable for diverse hair types and lifestyles.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        At HAIR SENSE, we prioritize quality, consistency, and customer trust. Our brand stands for simplicity, authenticity, and results—offering hair care that is easy to use yet impactful. We aim to empower individuals to feel confident in their hair by providing products that support long-term hair wellness rather than temporary fixes.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        With a growing commitment to innovation and customer satisfaction, HAIR SENSE continues to evolve as a brand that values natural beauty, self-care, and confidence.
                    </p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="text-center p-6">
                        <div class="w-16 h-16 bg-hair-gold/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-seedling text-hair-gold text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-hair-dark mb-2">Natural Ingredients</h3>
                        <p class="text-gray-600">Carefully selected natural components for optimal hair health</p>
                    </div>
                    <div class="text-center p-6">
                        <div class="w-16 h-16 bg-hair-gold/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-flask text-hair-gold text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-hair-dark mb-2">Modern Formulation</h3>
                        <p class="text-gray-600">Blending traditional wisdom with scientific innovation</p>
                    </div>
                    <div class="text-center p-6">
                        <div class="w-16 h-16 bg-hair-gold/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-heart text-hair-gold text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-hair-dark mb-2">Holistic Care</h3>
                        <p class="text-gray-600">Comprehensive solutions for long-term hair wellness</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-16 md:py-24 bg-hair-light">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-serif font-bold text-hair-dark mb-4">Our Products</h2>
                <div class="w-24 h-1 bg-hair-gold mx-auto mb-8"></div>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Discover our range of premium hair care solutions designed for every hair type and concern</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="product-card bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300">
                    <div class="h-64 overflow-hidden">
                        <img 
                            src="https://picsum.photos/400/300?random=2" 
                            alt="HAIR SENSE Growth Oil for promoting hair growth" 
                            class="w-full h-full object-cover transition-transform duration-500 hover:scale-110"
                            loading="lazy"
                        />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-hair-dark mb-2">Growth Oil</h3>
                        <p class="text-gray-600 mb-4">Specially formulated to promote hair growth and reduce hair fall with natural ingredients</p>
                        <div class="flex items-center justify-between">
                            <span class="text-hair-gold font-bold text-lg">$24.99</span>
                            <button class="bg-hair-gold text-white px-6 py-2 rounded-full hover:bg-hair-brown transition-colors duration-300">
                                Add to Cart
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="product-card bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300">
                    <div class="h-64 overflow-hidden">
                        <img 
                            src="https://picsum.photos/400/300?random=3" 
                            alt="HAIR SENSE Nourishing Oil for deep conditioning" 
                            class="w-full h-full object-cover transition-transform duration-500 hover:scale-110"
                            loading="lazy"
                        />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-hair-dark mb-2">Nourishing Oil</h3>
                        <p class="text-gray-600 mb-4">Deep conditioning treatment to restore moisture and vitality to dry, damaged hair</p>
                        <div class="flex items-center justify-between">
                            <span class="text-hair-gold font-bold text-lg">$22.99</span>
                            <button class="bg-hair-gold text-white px-6 py-2 rounded-full hover:bg-hair-brown transition-colors duration-300">
                                Add to Cart
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="product-card bg-white rounded-2xl shadow-lg overflow-hidden transition-all duration-300">
                    <div class="h-64 overflow-hidden">
                        <img 
                            src="https://picsum.photos/400/300?random=4" 
                            alt="HAIR SENSE Scalp Health Oil for improved scalp condition" 
                            class="w-full h-full object-cover transition-transform duration-500 hover:scale-110"
                            loading="lazy"
                        />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-hair-dark mb-2">Scalp Health Oil</h3>
                        <p class="text-gray-600 mb-4">Targeted treatment for scalp health, reducing irritation and promoting healthy roots</p>
                        <div class="flex items-center justify-between">
                            <span class="text-hair-gold font-bold text-lg">$26.99</span>
                            <button class="bg-hair-gold text-white px-6 py-2 rounded-full hover:bg-hair-brown transition-colors duration-300">
                                Add to Cart
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Values Section -->
    <section id="values" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-serif font-bold text-hair-dark mb-4">Our Core Values</h2>
                <div class="w-24 h-1 bg-hair-gold mx-auto mb-8"></div>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <div class="mb-8">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-hair-gold/10 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-award text-hair-gold"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-hair-dark">Quality & Consistency</h3>
                        </div>
                        <p class="text-gray-600">Every product undergoes rigorous testing to ensure consistent results and premium quality that our customers can trust.</p>
                    </div>
                    
                    <div class="mb-8">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-hair-gold/10 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-leaf text-hair-gold"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-hair-dark">Natural & Authentic</h3>
                        </div>
                        <p class="text-gray-600">We believe in the power of nature. Our formulations prioritize natural ingredients that deliver real results without harsh chemicals.</p>
                    </div>
                    
                    <div class="mb-8">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-hair-gold/10 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-users text-hair-gold"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-hair-dark">Customer Trust</h3>
                        </div>
                        <p class="text-gray-600">Building lasting relationships through transparency, education, and products that genuinely improve hair health.</p>
                    </div>
                </div>
                
                <div>
                    <img 
                        src="https://picsum.photos/600/500?random=5" 
                        alt="Natural ingredients used in HAIR SENSE products" 
                        class="rounded-2xl shadow-xl"
                        loading="lazy"
                    />
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-hair-light">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-serif font-bold text-hair-dark mb-4">Get In Touch</h2>
                <div class="w-24 h-1 bg-hair-gold mx-auto mb-8"></div>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Have questions about our products or need personalized hair care advice? We're here to help.</p>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                    <div>
                        <div class="bg-white rounded-2xl shadow-lg p-8">
                            <h3 class="text-2xl font-serif font-semibold text-hair-dark mb-6">Contact Form</h3>
                            <form id="contactForm" class="space-y-6">
                                <div>
                                    <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Full Name</label>
                                    <input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-hair-gold focus:border-transparent outline-none transition-all duration-300" placeholder="Your name">
                                </div>
                                <div>
                                    <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email Address</label>
                                    <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-hair-gold focus:border-transparent outline-none transition-all duration-300" placeholder="your@email.com">
                                </div>
                                <div>
                                    <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Your Message</label>
                                    <textarea id="message" rows="4" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-hair-gold focus:border-transparent outline-none transition-all duration-300" placeholder="Tell us about your hair care needs..."></textarea>
                                </div>
                                <button type="submit" class="w-full bg-hair-gold text-white py-3 rounded-lg font-semibold hover:bg-hair-brown transition-all duration-300 transform hover:scale-[1.02]">
                                    Send Message
                                </button>
                            </form>
                        </div>
                    </div>
                    
                    <div>
                        <div class="space-y-8">
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-hair-gold/10 rounded-full flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-envelope text-hair-gold"></i>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-hair-dark mb-2">Email Us</h4>
                                    <p class="text-gray-600">contact@hairsense.com</p>
                                    <p class="text-sm text-gray-500">We typically respond within 24 hours</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-hair-gold/10 rounded-full flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-phone text-hair-gold"></i>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-hair-dark mb-2">Call Us</h4>
                                    <p class="text-gray-600">+1 (555) 123-4567</p>
                                    <p class="text-sm text-gray-500">Mon-Fri, 9AM-6PM EST</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="w-12 h-12 bg-hair-gold/10 rounded-full flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-map-marker-alt text-hair-gold"></i>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-hair-dark mb-2">Visit Us</h4>
                                    <p class="text-gray-600">123 Beauty Street</p>
                                    <p class="text-gray-600">New York, NY 10001</p>
                                </div>
                            </div>
                            
                            <div class="pt-8">
                                <h4 class="text-lg font-semibold text-hair-dark mb-4">Follow Us</h4>
                                <div class="flex space-x-4">
                                    <a href="#" class="w-10 h-10 bg-hair-gold/10 rounded-full flex items-center justify-center text-hair-gold hover:bg-hair-gold hover:text-white transition-all duration-300">
                                        <i class="fab fa-instagram"></i>
                                    </a>
                                    <a href="#" class="w-10 h-10 bg-hair-gold/10 rounded-full flex items-center justify-center text-hair-gold hover:bg-hair-gold hover:text-white transition-all duration-300">
                                        <i class="fab fa-facebook-f"></i>
                                    </a>
                                    <a href="#" class="w-10 h-10 bg-hair-gold/10 rounded-full flex items-center justify-center text-hair-gold hover:bg-hair-gold hover:text-white transition-all duration-300">
                                        <i class="fab fa-pinterest-p"></i>
                                    </a>
                                    <a href="#" class="w-10 h-10 bg-hair-gold/10 rounded-full flex items-center justify-center text-hair-gold hover:bg-hair-gold hover:text-white transition-all duration-300">
                                        <i class="fab fa-youtube"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-hair-dark text-white py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-8 md:mb-0">
                    <div class="flex items-center space-x-2 mb-4">
                        <div class="w-8 h-8 bg-hair-gold rounded-full flex items-center justify-center">
                            <i class="fas fa-crown text-white text-sm"></i>
                        </div>
                        <h2 class="text-2xl font-serif font-bold">HAIR SENSE</h2>
                    </div>
                    <p class="text-gray-400 max-w-md">Restoring, nourishing, and enhancing natural hair health through premium hair care products.</p>
                </div>
                
                <div class="text-center md:text-right">
                    <p class="text-gray-400 mb-2">&copy; 2024 HAIR SENSE. All rights reserved.</p>
                    <div class="flex space-x-4 justify-center md:justify-end">
                        <a href="#" class="text-gray-400 hover:text-hair-gold transition-colors duration-300">Privacy Policy</a>
                        <a href="#" class="text-gray-400 hover:text-hair-gold transition-colors duration-300">Terms of Service</a>
                        <a href="#" class="text-gray-400 hover:text-hair-gold transition-colors duration-300">Shipping Policy</a>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 pt-8 border-t border-gray-800 text-center">
                <p class="text-gray-500 text-sm">These statements have not been evaluated by the Food and Drug Administration. This product is not intended to diagnose, treat, cure, or prevent any disease.</p>
            </div>
        </div>
    </footer>

    <script>
        // Define navigation data
        const navigationLinks = [
            { "id": "home", "label": "Home" },
            { "id": "about", "label": "About" },
            { "id": "products", "label": "Products" },
            { "id": "values", "label": "Values" },
            { "id": "contact", "label": "Contact" }
        ];

        // Define product data
        const products = [
            {
                "id": 1,
                "name": "Growth Oil",
                "description": "Specially formulated to promote hair growth and reduce hair fall with natural ingredients",
                "price": "$24.99",
                "image": "https://picsum.photos/400/300?random=2"
            },
            {
                "id": 2,
                "name": "Nourishing Oil",
                "description": "Deep conditioning treatment to restore moisture and vitality to dry, damaged hair",
                "price": "$22.99",
                "image": "https://picsum.photos/400/300?random=3"
            },
            {
                "id": 3,
                "name": "Scalp Health Oil",
                "description": "Targeted treatment for scalp health, reducing irritation and promoting healthy roots",
                "price": "$26.99",
                "image": "https://picsum.photos/400/300?random=4"
            }
        ];

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                if(targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if(targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Contact form submission
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            
            if(name && email && message) {
                alert('Thank you for your message! We will get back to you soon.');
                this.reset();
            } else {
                alert('Please fill in all fields.');
            }
        });

        // Mobile menu toggle
        const mobileMenuButton = document.querySelector('button.md\\:hidden');
        const mobileMenu = document.createElement('div');
        mobileMenu.className = 'md:hidden fixed inset-0 bg-white z-50 transform translate-x-full transition-transform duration-300';
        mobileMenu.innerHTML = `
            <div class="p-6">
                <div class="flex justify-between items-center mb-8">
                    <div class="flex items-center space-x-2">
                        <div class="w-8 h-8 bg-hair-gold rounded-full flex items-center justify-center">
                            <i class="fas fa-crown text-white text-sm"></i>
                        </div>
                        <h2 class="text-xl font-serif font-bold text-hair-dark">HAIR SENSE</h2>
                    </div>
                    <button class="close-menu text-2xl text-hair-dark">
                        <i class="fas fa-times"></i>
                    </button>
                </div>
                <div class="space-y-6">
                    ${navigationLinks.map(link => `
                        <a href="#${link.id}" class="block text-lg font-medium text-hair-dark hover:text-hair-gold transition-colors duration-300 py-2 border-b border-gray-100">
                            ${link.label}
                        </a>
                    `).join('')}
                </div>
            </div>
        `;
        
        document.body.appendChild(mobileMenu);
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.style.transform = 'translateX(0)';
        });
        
        mobileMenu.querySelector('.close-menu').addEventListener('click', () => {
            mobileMenu.style.transform = 'translateX(100%)';
        });

        // Add to cart functionality
        document.querySelectorAll('.product-card button').forEach((button, index) => {
            button.addEventListener('click', () => {
                const product = products[index];
                alert(`Added ${product.name} to cart!`);
            });
        });

        // Form validation
        const contactForm = document.getElementById('contactForm');
        const nameInput = document.getElementById('name');
        const emailInput = document.getElementById('email');
        const messageInput = document.getElementById('message');

        function validateEmail(email) {
            const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            return re.test(email);
        }

        nameInput.addEventListener('blur', () => {
            if(nameInput.value.trim().length < 2) {
                nameInput.classList.add('border-red-500');
                nameInput.classList.remove('border-gray-300');
            } else {
                nameInput.classList.remove('border-red-500');
                nameInput.classList.add('border-gray-300');
            }
        });

        emailInput.addEventListener('blur', () => {
            if(!validateEmail(emailInput.value)) {
                emailInput.classList.add('border-red-500');
                emailInput.classList.remove('border-gray-300');
            } else {
                emailInput.classList.remove('border-red-500');
                emailInput.classList.add('border-gray-300');
            }
        });

        messageInput.addEventListener('blur', () => {
            if(messageInput.value.trim().length < 10) {
                messageInput.classList.add('border-red-500');
                messageInput.classList.remove('border-gray-300');
            } else {
                messageInput.classList.remove('border-red-500');
                messageInput.classList.add('border-gray-300');
            }
        });
    </script>
</body>
</html>
