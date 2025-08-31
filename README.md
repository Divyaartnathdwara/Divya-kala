<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pushtimarg Art Gallery - Divya Kalakriti, Atma Ki Pustak</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            color: #C8B9A6;
            background-color: #121212;
        }
        .playfair {
            font-family: 'Playfair Display', serif;
        }
        .bg-pushtimarg-gold {
            background-color: #E8C17F;
        }
        .text-pushtimarg-brown {
            color: #6A4A3B;
        }
        .hover\:bg-pushtimarg-gold:hover {
            background-color: #E8C17F;
        }
        .hover\:text-pushtimarg-brown:hover {
            color: #6A4A3B;
        }
        .dark-card {
            background-color: #1E1E1E;
            color: #C8B9A6;
        }
        .text-pushtimarg-light-gold {
            color: #FFEFD5;
        }
        .feather-container {
            position: fixed;
            z-index: 0;
            opacity: 0.1;
            pointer-events: none;
        }
        .feather-top-left {
            top: 10px;
            left: 10px;
            transform: rotate(-30deg);
        }
        .feather-bottom-right {
            bottom: 10px;
            right: 10px;
            transform: rotate(150deg);
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">

    <!-- Peacock Feather Decorations -->
    <div class="feather-container feather-top-left">
        <svg width="100" height="100" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.58 20 4 16.42 4 12C4 7.58 7.58 4 12 4C16.42 4 20 7.58 20 12C20 16.42 16.42 20 12 20Z" fill="#88D8B0"/>
            <path d="M12 6.5C10.62 6.5 9.5 7.62 9.5 9C9.5 10.38 10.62 11.5 12 11.5C13.38 11.5 14.5 10.38 14.5 9C14.5 7.62 13.38 6.5 12 6.5Z" fill="#66BB6A"/>
            <path d="M12 13C10.9 13 10 13.9 10 15C10 16.1 10.9 17 12 17C13.1 17 14 16.1 14 15C14 13.9 13.1 13 12 13Z" fill="#42A5F5"/>
            <path d="M12 9.5C10.62 9.5 9.5 10.62 9.5 12C9.5 13.38 10.62 14.5 12 14.5C13.38 14.5 14.5 13.38 14.5 12C14.5 10.62 13.38 9.5 12 9.5Z" fill="#1565C0"/>
        </svg>
    </div>
    <div class="feather-container feather-bottom-right">
        <svg width="100" height="100" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.58 20 4 16.42 4 12C4 7.58 7.58 4 12 4C16.42 4 20 7.58 20 12C20 16.42 16.42 20 12 20Z" fill="#88D8B0"/>
            <path d="M12 6.5C10.62 6.5 9.5 7.62 9.5 9C9.5 10.38 10.62 11.5 12 11.5C13.38 11.5 14.5 10.38 14.5 9C14.5 7.62 13.38 6.5 12 6.5Z" fill="#66BB6A"/>
            <path d="M12 13C10.9 13 10 13.9 10 15C10 16.1 10.9 17 12 17C13.1 17 14 16.1 14 15C14 13.9 13.1 13 12 13Z" fill="#42A5F5"/>
            <path d="M12 9.5C10.62 9.5 9.5 10.62 9.5 12C9.5 13.38 10.62 14.5 12 14.5C13.38 14.5 14.5 13.38 14.5 12C14.5 10.62 13.38 9.5 12 9.5Z" fill="#1565C0"/>
        </svg>
    </div>

    <!-- Header & Navigation -->
    <header class="dark-card shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#home" class="playfair text-2xl font-bold text-pushtimarg-light-gold">Pushtimarg Art Gallery</a>
            <nav>
                <ul class="flex space-x-6 text-sm md:text-base">
                    <li><a href="#gallery" class="text-gray-400 hover:text-pushtimarg-light-gold font-medium transition-colors duration-300">Gallery</a></li>
                    <li><a href="#about" class="text-gray-400 hover:text-pushtimarg-light-gold font-medium transition-colors duration-300">About</a></li>
                    <li><a href="#contact" class="text-gray-400 hover:text-pushtimarg-light-gold font-medium transition-colors duration-300">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container mx-auto px-4">

        <!-- Hero Section -->
        <section id="home" class="py-16 md:py-24 text-center">
            <div class="dark-card rounded-3xl p-8 md:p-16">
                <h1 class="playfair text-3xl md:text-5xl font-bold text-pushtimarg-light-gold leading-tight mb-4 md:mb-6">Divya Kalakriti, Atma ki Pustak</h1>
                <p class="text-gray-300 text-base md:text-lg max-w-2xl mx-auto mb-8">Pushtimarg ki parampara se prerit, hum Shri Krishna, Radha Krishna, aur Shrinathji ke divya roopon ko rang aur bhav mein jeevant karte hain.</p>
                <a href="#gallery" class="bg-pushtimarg-gold text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-yellow-600 transition-colors duration-300 transform hover:scale-105">Art Gallery dekhen</a>
            </div>
        </section>

        <!-- Gallery Section -->
        <section id="gallery" class="py-16 md:py-24">
            <h2 class="playfair text-3xl md:text-4xl font-bold text-center mb-10 text-pushtimarg-light-gold">Hamari Kalakriti</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Painting 1 -->
                <div class="dark-card rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300 cursor-pointer">
                    <img src="http://googleusercontent.com/file_content/4" alt="Shrinathji Painting" class="w-full h-auto object-cover">
                    <div class="p-6 text-center">
                        <h3 class="font-bold text-xl text-pushtimarg-light-gold mb-2">Shri Shrinathji</h3>
                        <p class="text-sm text-gray-400">Pushtimarg ke mukhya svarup ki divya tasveer.</p>
                    </div>
                </div>

                <!-- Painting 2 -->
                <div class="dark-card rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300 cursor-pointer">
                    <img src="https://placehold.co/600x400/2A2A2A/FFEFD5?text=Radha+Krishna+Painting" alt="Radha Krishna Painting" class="w-full h-auto object-cover">
                    <div class="p-6 text-center">
                        <h3 class="font-bold text-xl text-pushtimarg-light-gold mb-2">Shri Radha Krishna</h3>
                        <p class="text-sm text-gray-400">Canvas par ek shant aur prem purn tasveer.</p>
                    </div>
                </div>

                <!-- Painting 3 -->
                <div class="dark-card rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300 cursor-pointer">
                    <img src="https://placehold.co/600x400/2A2A2A/FFEFD5?text=Pichwai+Art" alt="Pichwai Art" class="w-full h-auto object-cover">
                    <div class="p-6 text-center">
                        <h3 class="font-bold text-xl text-pushtimarg-light-gold mb-2">Paramparik Pichwai</h3>
                        <p class="text-sm text-gray-400">Mandir ke liye hath se bani Pichwai.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-16 md:py-24 dark-card rounded-xl shadow-lg p-8 md:p-12 mb-8">
            <h2 class="playfair text-3xl md:text-4xl font-bold text-center mb-6 text-pushtimarg-light-gold">Hamare Baare Mein</h2>
            <div class="flex flex-col md:flex-row items-center space-y-6 md:space-y-0 md:space-x-12">
                <div class="md:w-1/2">
                    <img src="https://placehold.co/600x400/2A2A2A/FFEFD5?text=Artist+Photo" alt="Artist Photo" class="rounded-xl shadow-lg w-full h-auto object-cover">
                </div>
                <div class="md:w-1/2">
                    <p class="text-gray-300 text-base md:text-lg mb-4 leading-relaxed">
                        Hum Pushtimargiya paramparaon aur shreshth shilp par adharit hath se bani kalakritiyan banate hain. Har ek piece mein Shri Krishna, Radha aur Shrinathji ke prati hamara gehra samarpan aur prem dikhta hai.
                    </p>
                    <p class="text-gray-300 text-base md:text-lg leading-relaxed">
                        Hamara lakshya na sirf sundar tasveeren banana hai, balki unme adhyatmik bhav aur divyata bhi lana hai. Hum gold aur American diamond jaise vibhinna samagri ka upyog karke har painting ko advitiya banate hain.
                    </p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16 md:py-24">
            <div class="bg-pushtimarg-gold rounded-xl p-8 md:p-12 text-center text-white">
                <h2 class="playfair text-3xl md:text-4xl font-bold mb-4">Humse Sampark Karen</h2>
                <p class="text-base md:text-lg mb-8 max-w-xl mx-auto">Apne pasand ki painting order karne ya kisi bhi jankari ke liye, humse sampark karen.</p>
                <a href="mailto:info@example.com" class="bg-white text-pushtimarg-brown font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-100 transition-colors duration-300 transform hover:scale-105">Email bhejें</a>
                <p class="text-sm mt-4">Ya hamara phone number: +91 9876543210</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="dark-card py-6 mt-8">
        <div class="container mx-auto px-4 text-center text-gray-500 text-sm">
            <p>&copy; 2025 Pushtimarg Art Gallery. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
