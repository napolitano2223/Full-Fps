[index.html](https://github.com/user-attachments/files/23696376/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FiveM Full FPS - Optimizaciones Profesionales</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
        }
        .gradient-text {
            color: #3b0764; /* Purple 950 - Ultra Dark Solid */
        }
        /* Custom Scrollbar for Terms */
        .custom-scrollbar::-webkit-scrollbar {
            width: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #0a0a0a; 
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #2d1b4e; 
            border-radius: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #4c1d95; 
        }
    </style>
</head>
<body class="bg-black text-gray-200">

    <!-- Navigation -->
    <nav class="bg-black/80 backdrop-blur-md fixed w-full z-50 border-b border-[#2d1b4e]">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-white">
                FiveM<span class="text-purple-900">FPS</span>
            </a>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="text-gray-300 hover:text-purple-800 transition">Inicio</a>
                <a href="#results" class="text-gray-300 hover:text-purple-800 transition">Clientes</a>
                <a href="#services" class="text-gray-300 hover:text-purple-800 transition">Servicios</a>
                <a href="#free-optimization" class="text-gray-300 hover:text-purple-800 transition">Guía Free</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="menu-btn" class="md:hidden text-white focus:outline-none">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-black border-t border-[#2d1b4e]">
            <a href="#home" class="block py-3 px-6 text-gray-300 hover:bg-[#1a0b2e]">Inicio</a>
            <a href="#results" class="block py-3 px-6 text-gray-300 hover:bg-[#1a0b2e]">Clientes</a>
            <a href="#services" class="block py-3 px-6 text-gray-300 hover:bg-[#1a0b2e]">Servicios</a>
            <a href="#free-optimization" class="block py-3 px-6 text-gray-300 hover:bg-[#1a0b2e]">Guía Free</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-40 pb-20 bg-black relative overflow-hidden min-h-screen flex items-center">
        <div class="absolute top-0 right-0 w-[800px] h-[800px] bg-[#1a0b2e] rounded-full blur-[120px] -z-10 opacity-60 pointer-events-none"></div>
        <div class="absolute bottom-0 left-0 w-[600px] h-[600px] bg-[#150520] rounded-full blur-[100px] -z-10 opacity-60 pointer-events-none"></div>
        <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] bg-[#2d1b4e] rounded-full blur-[150px] -z-10 opacity-30 pointer-events-none"></div>

        <div class="container mx-auto px-6">
            <div class="flex flex-col lg:flex-row items-center justify-between gap-12">
                <!-- Left Content -->
                <div class="lg:w-1/2 text-center lg:text-left">
                    <!-- Optimizar Gratis Banner -->
                    <div class="mb-8 inline-block">
                        <a href="#free-optimization" class="flex items-center bg-black border-2 border-[#2d1b4e] text-white px-8 py-4 rounded-xl font-bold text-xl shadow-2xl shadow-[#1a0b2e]/50 hover:shadow-[#2d1b4e]/70 hover:bg-[#1a0b2e]/20 hover:border-[#4c1d95] transition-all duration-300 transform hover:scale-105">
                            <i class="fas fa-gift mr-3 text-[#4c1d95]"></i>
                            Optimizar Gratis
                        </a>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold mb-6 leading-tight text-white">
                        Maximiza tu <br>
                        <span class="gradient-text">FiveM</span>
                    </h1>
                    <p class="text-xl text-gray-400 mb-10 max-w-xl mx-auto lg:mx-0 leading-relaxed">
                        Somos el servicio de optimización más confiable para FiveM. Garantizamos FPS estables, latencia mínima y el máximo rendimiento para tu servidor.
                    </p>
                    <div class="flex flex-col sm:flex-row justify-center lg:justify-start gap-4">
                        <a href="#services" class="px-8 py-4 bg-[#2d1b4e] text-white rounded-xl font-semibold hover:bg-[#1a0b2e] transition shadow-xl shadow-[#1a0b2e]/30 flex items-center justify-center gap-2 border border-transparent hover:border-[#4c1d95]">
                            Optimizar Ahora <i class="fas fa-arrow-right"></i>
                        </a>
                        <a href="#services" class="px-8 py-4 bg-transparent text-white border border-[#2d1b4e] rounded-xl font-semibold hover:bg-[#1a0b2e]/20 transition flex items-center justify-center gap-2">
                            Ver Servicios
                        </a>
                    </div>
                </div>

                <!-- Right Content -->
                <div class="lg:w-1/2 grid grid-cols-4 gap-4">
                    <div class="bg-[#0a0a0a] p-4 rounded-2xl border border-[#2d1b4e] flex flex-col items-center justify-center aspect-square hover:bg-[#1a0b2e]/30 transition duration-300 shadow-lg shadow-[#1a0b2e]/20">
                        <i class="fas fa-tachometer-alt text-3xl sm:text-4xl text-purple-900 mb-3"></i>
                        <span class="text-gray-300 font-semibold text-sm sm:text-base">+ FPS</span>
                    </div>
                    <div class="bg-[#0a0a0a] p-4 rounded-2xl border border-[#2d1b4e] flex flex-col items-center justify-center aspect-square hover:bg-[#1a0b2e]/30 transition duration-300 shadow-lg shadow-[#1a0b2e]/20">
                        <i class="fas fa-server text-3xl sm:text-4xl text-purple-900 mb-3"></i>
                        <span class="text-gray-300 font-semibold text-sm sm:text-base">Estabilidad</span>
                    </div>
                    <div class="bg-[#0a0a0a] p-4 rounded-2xl border border-[#2d1b4e] flex flex-col items-center justify-center aspect-square hover:bg-[#1a0b2e]/30 transition duration-300 shadow-lg shadow-[#1a0b2e]/20">
                        <i class="fas fa-rocket text-3xl sm:text-4xl text-purple-900 mb-3"></i>
                        <span class="text-gray-300 font-semibold text-sm sm:text-base">Velocidad</span>
                    </div>
                    <div class="bg-[#0a0a0a] p-4 rounded-2xl border border-[#2d1b4e] flex flex-col items-center justify-center aspect-square hover:bg-[#1a0b2e]/30 transition duration-300 shadow-lg shadow-[#1a0b2e]/20">
                        <i class="fas fa-gamepad text-3xl sm:text-4xl text-purple-900 mb-3"></i>
                        <span class="text-gray-300 font-semibold text-sm sm:text-base">Gaming</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Results Section -->
    <section id="results" class="py-20 bg-black border-y border-[#2d1b4e]/30">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div>
                    <h2 class="text-3xl font-bold text-white mb-2">Clientes Optimizados</h2>
                    <p class="text-gray-400">Resultados reales comprobados.</p>
                </div>
                <div class="flex text-purple-900 gap-1 mt-4 md:mt-0">
                    <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                </div>
            </div>
            <div class="grid md:grid-cols-3 gap-6">
                <!-- Result 1 -->
                <div class="bg-[#050505] rounded-2xl p-6 border border-[#2d1b4e] hover:border-purple-900 transition flex flex-col">
                    <div class="flex items-center justify-between mb-4">
                        <div class="w-10 h-10 bg-[#1a0b2e] rounded-lg flex items-center justify-center text-purple-900">
                            <i class="fas fa-desktop"></i>
                        </div>
                        <span class="text-green-500 font-bold text-sm bg-green-500/10 px-2 py-1 rounded">+60 FPS</span>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">PC Gama Baja</h3>
                    <p class="text-gray-400 text-sm mb-4 flex-grow">"Mi PC es viejo y FiveM me iba a 30 FPS. Ahora juego a 90 FPS estables en zona vip."</p>
                </div>
                <!-- Result 2 -->
                <div class="bg-[#050505] rounded-2xl p-6 border border-[#2d1b4e] hover:border-purple-900 transition flex flex-col">
                    <div class="flex items-center justify-between mb-4">
                        <div class="w-10 h-10 bg-[#1a0b2e] rounded-lg flex items-center justify-center text-purple-900">
                            <i class="fas fa-microchip"></i>
                        </div>
                        <span class="text-green-500 font-bold text-sm bg-green-500/10 px-2 py-1 rounded">0 Tirones</span>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">PC Gama Media</h3>
                    <p class="text-gray-400 text-sm mb-4 flex-grow">"Tenía tirones al conducir rápido. La optimización eliminó todo el stuttering."</p>
                </div>
                <!-- Result 3 -->
                <div class="bg-[#050505] rounded-2xl p-6 border border-[#2d1b4e] hover:border-purple-900 transition flex flex-col">
                    <div class="flex items-center justify-between mb-4">
                        <div class="w-10 h-10 bg-[#1a0b2e] rounded-lg flex items-center justify-center text-purple-900">
                            <i class="fas fa-laptop"></i>
                        </div>
                        <span class="text-green-500 font-bold text-sm bg-green-500/10 px-2 py-1 rounded">-Input Lag</span>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">Laptop / Portátil</h3>
                    <p class="text-gray-400 text-sm mb-4 flex-grow">"Mi portátil se calentaba y bajaba el rendimiento. Ahora va fresco y el PvP es instantáneo."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-black relative overflow-hidden">
        <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-[1000px] h-[600px] bg-[#1a0b2e] rounded-full blur-[120px] -z-10 opacity-40 pointer-events-none"></div>
        
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-white mb-4">Planes de Optimización</h2>
                <p class="text-gray-400 max-w-xl mx-auto">Elige el nivel de rendimiento que necesitas.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="p-8 rounded-2xl bg-[#050505] hover:bg-[#0f0518] hover:shadow-xl hover:shadow-[#1a0b2e]/20 transition duration-300 border border-[#2d1b4e] group relative overflow-hidden">
                    <div class="absolute top-0 right-0 w-20 h-20 bg-[#2d1b4e]/20 rounded-bl-full -mr-4 -mt-4"></div>
                    <div class="w-14 h-14 bg-[#1a0b2e] rounded-xl flex items-center justify-center mb-6 text-purple-900 group-hover:scale-110 transition border border-[#2d1b4e]">
                        <i class="fas fa-bolt text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-white">Optimización Básica</h3>
                    <p class="text-gray-400 text-sm mb-6">Mejora FPS y reduce lag en servidores con recursos limitados.</p>
                    <div class="mt-auto pt-6 border-t border-[#2d1b4e] flex justify-center">
                        <button class="buy-btn bg-green-700 text-white font-bold text-xl px-6 py-2 rounded-xl shadow-lg shadow-green-900/50 inline-block transform hover:scale-105 transition duration-300 cursor-pointer">
                            Comprar 20€
                        </button>
                    </div>
                </div>
                <!-- Service 2 -->
                <div class="p-8 rounded-2xl bg-[#0a0a0a] hover:bg-[#0f0518] hover:shadow-2xl hover:shadow-[#1a0b2e]/30 transition duration-300 border-2 border-[#2d1b4e] group relative overflow-hidden">
                    <div class="absolute top-0 right-0 bg-[#2d1b4e] text-white text-xs font-bold px-3 py-1 rounded-bl-lg">POPULAR</div>
                    <div class="w-14 h-14 bg-[#1a0b2e] rounded-xl flex items-center justify-center mb-6 text-purple-900 group-hover:scale-110 transition border border-[#2d1b4e]">
                        <i class="fas fa-tachometer-alt text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-white">Optimización Avanzada</h3>
                    <p class="text-gray-400 text-sm mb-6">Scripts personalizados y ajustes avanzados para máximo rendimiento.</p>
                    <div class="mt-auto pt-6 border-t border-[#2d1b4e] flex justify-center">
                        <button class="buy-btn bg-green-700 text-white font-bold text-xl px-6 py-2 rounded-xl shadow-lg shadow-green-900/50 inline-block transform hover:scale-105 transition duration-300 cursor-pointer">
                            Comprar 50€
                        </button>
                    </div>
                </div>
                <!-- Service 3 -->
                <div class="p-8 rounded-2xl bg-[#050505] hover:bg-[#0f0518] hover:shadow-xl hover:shadow-[#1a0b2e]/20 transition duration-300 border border-[#2d1b4e] group relative overflow-hidden">
                    <div class="absolute top-0 right-0 w-20 h-20 bg-[#2d1b4e]/20 rounded-bl-full -mr-4 -mt-4"></div>
                    <div class="w-14 h-14 bg-[#1a0b2e] rounded-xl flex items-center justify-center mb-6 text-purple-900 group-hover:scale-110 transition border border-[#2d1b4e]">
                        <i class="fas fa-crown text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-white">Optimización Premium</h3>
                    <p class="text-gray-400 text-sm mb-6">Overclocking avanzado, BIOS tweaks, optimización de registros y configuración de hardware para máximo rendimiento.</p>
                    <div class="mt-auto pt-6 border-t border-[#2d1b4e] flex justify-center">
                        <button class="buy-btn bg-green-700 text-white font-bold text-xl px-6 py-2 rounded-xl shadow-lg shadow-green-900/50 inline-block transform hover:scale-105 transition duration-300 cursor-pointer">
                            Comprar 100€
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Free Optimization Section -->
    <section id="free-optimization" class="py-20 bg-black relative">
        <div class="absolute inset-0 bg-[#1a0b2e]/10 skew-y-3 transform origin-bottom-right -z-10"></div>
        <div class="container mx-auto px-6">
            <div class="max-w-5xl mx-auto bg-[#050505] rounded-3xl p-10 border border-[#2d1b4e] shadow-2xl shadow-[#1a0b2e]/30 flex flex-col md:flex-row items-center gap-10">
                <div class="md:w-1/3 flex justify-center">
                    <div class="w-40 h-40 bg-[#1a0b2e] border-2 border-[#2d1b4e] rounded-3xl flex items-center justify-center shadow-2xl shadow-[#1a0b2e]/50 rotate-3 hover:rotate-0 transition duration-500">
                        <i class="fas fa-gift text-[#2d1b4e] text-6xl"></i>
                    </div>
                </div>
                <div class="md:w-2/3">
                    <h2 class="text-3xl font-bold text-white mb-4">Optimización Gratis</h2>
                    <p class="text-gray-400 mb-6">Prueba nuestros servicios sin compromiso. Análisis completo de tu servidor sin costo.</p>
                    
                    <div class="grid grid-cols-2 gap-4 mb-8">
                        <div class="flex items-center text-gray-300">
                            <i class="fas fa-check-circle text-purple-900 mr-2"></i> Análisis completo
                        </div>
                        <div class="flex items-center text-gray-300">
                            <i class="fas fa-check-circle text-purple-900 mr-2"></i> Reporte detallado
                        </div>
                        <div class="flex items-center text-gray-300">
                            <i class="fas fa-check-circle text-purple-900 mr-2"></i> Diagnóstico FPS
                        </div>
                        <div class="flex items-center text-gray-300">
                            <i class="fas fa-check-circle text-purple-900 mr-2"></i> Recomendaciones
                        </div>
                    </div>

                    <div id="new-guide-btn" class="w-full md:w-auto inline-flex justify-center items-center bg-black border-2 border-[#2d1b4e] text-white px-8 py-4 rounded-xl font-bold text-lg shadow-lg shadow-[#1a0b2e]/50 hover:bg-[#1a0b2e]/20 hover:border-[#4c1d95] transition-all duration-300 transform hover:scale-105 cursor-pointer">
                        CONSEGUIR AHORA
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black text-white py-12 border-t border-[#2d1b4e]">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center mb-8">
                <div class="text-2xl font-bold mb-4 md:mb-0">
                    FiveM<span class="text-[#240046]">FPS</span>
                </div>
                <div class="flex space-x-6">
                    <a href="https://discord.gg/XHehzGrH" target="_blank" class="hover:text-purple-800 transition"><i class="fab fa-discord text-2xl text-[#240046] hover:text-[#4c1d95]"></i></a>
                    <a href="https://www.tiktok.com/@1jrk00?_r=1&_t=ZM-91ddjQxhl3y" target="_blank" class="hover:text-purple-800 transition"><i class="fab fa-tiktok text-2xl text-[#240046] hover:text-[#4c1d95]"></i></a>
                </div>
            </div>
            <div class="border-t border-[#1a0b2e] pt-8 text-center text-gray-500 text-sm">
                &copy; 2023 FiveMFPS. Todos los derechos reservados.
            </div>
        </div>
    </footer>

    <!-- Modal Guía Free (Ultra Dark Purple) -->
    <div id="guide-modal" class="fixed inset-0 z-[60] hidden flex items-center justify-center bg-black/90 backdrop-blur-md px-4">
        <div class="bg-black border-2 border-[#1a0b2e] rounded-2xl p-6 max-w-md w-full relative shadow-2xl shadow-[#1a0b2e]/50 transform transition-all">
            <!-- Close Button -->
            <button id="close-guide-btn" class="absolute top-4 right-4 text-gray-400 hover:text-white transition">
                <i class="fas fa-times text-2xl"></i>
            </button>
            
            <div class="text-center mb-6">
                <div class="w-16 h-16 bg-[#1a0b2e] rounded-full flex items-center justify-center mx-auto mb-4 border border-[#2d1b4e]">
                    <i class="fas fa-gift text-purple-900 text-2xl"></i>
                </div>
                <h2 class="text-2xl font-bold text-white mb-2">¿Cómo conseguir?</h2>
                <p class="text-gray-400 text-sm">Sigue estos 4 pasos para tu optimización gratis</p>
            </div>

            <div class="space-y-4">
                <!-- Step 1 -->
                <a href="https://discord.gg/XHehzGrH" target="_blank" class="flex items-center p-3 rounded-xl hover:bg-[#1a0b2e]/30 transition cursor-pointer group">
                    <div class="flex-shrink-0 w-8 h-8 bg-[#1a0b2e] rounded-full flex items-center justify-center text-white font-bold border border-[#2d1b4e] shadow-lg shadow-[#1a0b2e]/50 group-hover:border-[#5865F2] transition text-sm">
                        1
                    </div>
                    <div class="ml-4">
                        <h4 class="text-base font-bold text-white group-hover:text-[#5865F2] transition">Entra al Discord</h4>
                        <p class="text-xs text-gray-500">(Click para unirse)</p>
                    </div>
                </a>

                <!-- Step 2 -->
                <div class="flex items-center p-3 rounded-xl hover:bg-[#1a0b2e]/30 transition">
                    <div class="flex-shrink-0 w-8 h-8 bg-[#1a0b2e] rounded-full flex items-center justify-center text-white font-bold border border-[#2d1b4e] shadow-lg shadow-[#1a0b2e]/50 text-sm">
                        2
                    </div>
                    <div class="ml-4">
                        <h4 class="text-base font-bold text-white">Crea invitación permanente</h4>
                    </div>
                </div>

                <!-- Step 3 -->
                <div class="flex items-center p-3 rounded-xl hover:bg-[#1a0b2e]/30 transition">
                    <div class="flex-shrink-0 w-8 h-8 bg-[#1a0b2e] rounded-full flex items-center justify-center text-white font-bold border border-[#2d1b4e] shadow-lg shadow-[#1a0b2e]/50 text-sm">
                        3
                    </div>
                    <div class="ml-4">
                        <h4 class="text-base font-bold text-white">Invita a 10 personas</h4>
                    </div>
                </div>

                <!-- Step 4 -->
                <div class="flex items-center p-3 rounded-xl hover:bg-[#1a0b2e]/30 transition">
                    <div class="flex-shrink-0 w-8 h-8 bg-[#1a0b2e] rounded-full flex items-center justify-center text-white font-bold border border-[#2d1b4e] shadow-lg shadow-[#1a0b2e]/50 text-sm">
                        4
                    </div>
                    <div class="ml-4">
                        <h4 class="text-base font-bold text-white">Interacción en TikTok</h4>
                        <p class="text-xs text-gray-500 ml-2">(Like y comentar en 3 videos)</p>
                    </div>
                </div>
            </div>

            <div class="mt-6 pt-4 border-t border-[#2d1b4e] flex flex-col gap-3">
                <a href="https://discord.gg/XHehzGrH" target="_blank" class="flex items-center justify-center w-full bg-[#5865F2] hover:bg-[#4752C4] text-white font-bold py-3 rounded-xl transition duration-300 shadow-lg hover:shadow-[#1a0b2e]/50 text-sm">
                    <i class="fab fa-discord mr-2"></i> Unirse al Discord
                </a>
                <a href="https://www.tiktok.com/@1jrk00?_r=1&_t=ZM-91ddjQxhl3y" target="_blank" class="flex items-center justify-center w-full bg-black border-2 border-[#2d1b4e] hover:bg-[#1a0b2e] text-white font-bold py-3 rounded-xl transition duration-300 shadow-lg hover:shadow-[#1a0b2e]/50 text-sm">
                    <i class="fab fa-tiktok mr-2"></i> Ir al TikTok
                </a>
            </div>
        </div>
    </div>

    <!-- Modal Términos y Condiciones (Ultra Dark Purple) -->
    <div id="tos-modal" class="fixed inset-0 z-[70] hidden flex items-center justify-center bg-black/90 backdrop-blur-md px-4">
        <div class="bg-black border-2 border-[#2d1b4e] rounded-2xl p-8 max-w-md w-full relative shadow-2xl shadow-[#2d1b4e]/50 transform transition-all">
            
            <div class="text-center mb-6">
                <h3 class="text-2xl font-bold text-white mb-2">Términos y Condiciones</h3>
                <p class="text-gray-400 text-sm">Por favor lee antes de continuar.</p>
            </div>

            <div class="space-y-4 mb-8 text-gray-300 text-sm bg-[#0a0a0a] p-5 rounded-xl border border-[#2d1b4e] max-h-[60vh] overflow-y-auto custom-scrollbar">
                
                <!-- Term 1: Reembolsos -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-white"><i class="fas fa-hand-holding-dollar"></i></div>
                    <p>Al comprar la optimización <span class="text-white font-bold">no hay reembolso bajo ninguna circunstancia</span>.</p>
                </div>

                <!-- Term 2: Cambios PC -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-purple-900"><i class="fas fa-desktop"></i></div>
                    <p>Aceptas <span class="text-white font-bold">cualquier tipo de cambio en tu PC</span> necesario para el rendimiento.</p>
                </div>

                <!-- Term 3: Acceso Remoto -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-purple-900"><i class="fas fa-wifi"></i></div>
                    <p>Debes permitir el acceso remoto mediante <span class="text-white font-bold">AnyDesk</span> para realizar el trabajo.</p>
                </div>

                <!-- Term 4: Responsabilidad -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-purple-900"><i class="fas fa-history"></i></div>
                    <p>No nos hacemos responsables de errores, por ello <span class="text-gray-400 font-bold">haremos un punto de restauración</span> previo por seguridad.</p>
                </div>

                <!-- Term 5: Hardware/Overclock -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-white"><i class="fas fa-microchip"></i></div>
                    <div>
                        <p class="mb-1">El overclocking conlleva riesgos y <span class="text-white font-bold">no nos hacemos responsables</span> de daños.</p>
                        <p class="text-green-500 text-xs font-bold bg-green-900/20 p-1 rounded inline-block"><i class="fas fa-shield-alt mr-1"></i> Nota: El 99% de los casos es seguro y es extremadamente difícil que ocurra un error.</p>
                    </div>
                </div>

                <!-- Term 6: Conducta -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-white"><i class="fas fa-comment-slash"></i></div>
                    <p>Cualquier tipo de <span class="text-white font-bold">insulto o mentira</span> será motivo para no entregar el servicio.</p>
                </div>

                <!-- Term 7: Grabación -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-white"><i class="fas fa-video-slash"></i></div>
                    <p>Está <span class="text-white font-bold">prohibido grabar la optimización</span>. Si se detecta, el producto se cancelará.</p>
                </div>

                <!-- Term 8: Paciencia -->
                <div class="flex items-start gap-3">
                    <div class="mt-0.5 min-w-[20px] text-purple-900"><i class="fas fa-clock"></i></div>
                    <p>Se requiere paciencia y respeto a los horarios de atención.</p>
                </div>

            </div>

            <div class="flex gap-4">
                <button id="cancel-tos-btn" class="w-1/2 bg-transparent border border-[#2d1b4e] text-gray-400 font-bold py-3 rounded-xl hover:bg-[#2d1b4e]/20 transition cursor-pointer">
                    Cancelar
                </button>
                <button id="accept-tos-btn" class="w-1/2 bg-[#5865F2] hover:bg-[#4752C4] text-white font-bold py-3 rounded-xl shadow-lg hover:shadow-blue-900/50 transition cursor-pointer">
                    Aceptar
                </button>
            </div>
        </div>
    </div>

    <!-- Modal Métodos de Pago (Ultra Dark Purple) -->
    <div id="payment-modal" class="fixed inset-0 z-[80] hidden flex items-center justify-center bg-black/90 backdrop-blur-md px-4">
        <div class="bg-black border-2 border-[#2d1b4e] rounded-2xl p-8 max-w-md w-full relative shadow-2xl shadow-[#2d1b4e]/50 transform transition-all">
            <!-- Close Button -->
            <button id="close-payment-btn" class="absolute top-4 right-4 text-gray-400 hover:text-white transition">
                <i class="fas fa-times text-2xl"></i>
            </button>
            
            <!-- STEP 1: Payment Instructions -->
            <div id="payment-step-1">
                <div class="text-center mb-6">
                    <h3 class="text-2xl font-bold text-white mb-2">Método de Pago</h3>
                    <p class="text-gray-400 text-sm">Finaliza tu compra de forma segura.</p>
                </div>

                <!-- PayPal Button Visual (Triggers Step 1.5) -->
                <button id="paypal-initial-btn" class="w-full bg-[#003087] rounded-xl p-4 mb-6 flex items-center justify-center gap-3 border border-[#2d1b4e] shadow-lg hover:bg-[#00256b] transition cursor-pointer group">
                    <i class="fab fa-paypal text-3xl text-white group-hover:scale-110 transition"></i>
                    <span class="text-white font-bold text-xl">Pagar con PayPal</span>
                </button>

                <!-- Important Warnings -->
                <div class="space-y-4 mb-4 bg-[#0a0a0a] p-5 rounded-xl border border-red-900/50">
                    <div class="text-center mb-4">
                        <i class="fas fa-exclamation-triangle text-red-600 text-3xl mb-2"></i>
                        <h4 class="text-red-500 font-bold uppercase tracking-wider">Advertencia Crítica</h4>
                    </div>
                    <ul class="space-y-3 text-sm text-gray-300">
                        <li class="flex items-start gap-2">
                            <i class="fas fa-check text-green-500 mt-1"></i>
                            <span>Opción: <b class="text-white bg-purple-900/50 px-2 rounded">Amigos y Familiares</b></span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fas fa-pen-slash text-red-500 mt-1"></i>
                            <span>Enviar <b class="text-red-500 uppercase underline">Sin Notas</b> (En blanco)</span>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- STEP 1.5: Copy Email Interface (Compact & Verify) -->
            <div id="payment-step-email" style="display: none;">
                <div class="text-center mb-6">
                    <h3 class="text-xl font-bold text-white mb-1">Realizar Pago</h3>
                    <p class="text-gray-500 text-xs">Copia el correo y paga en PayPal.</p>
                </div>
                
                <!-- Compact Email Box -->
                <div class="bg-[#0a0a0a] border border-[#2d1b4e] rounded-lg p-4 mb-6 relative group cursor-pointer text-center hover:bg-[#1a0b2e] transition" id="copy-email-area">
                    <p class="text-lg font-mono font-bold text-purple-300 select-all">yeratty8@gmail.com</p>
                    <p class="text-[10px] text-gray-500 mt-1 uppercase tracking-wider">Click para copiar</p>
                </div>

                <div class="grid gap-3">
                    <!-- 1. Go to PayPal -->
                    <button id="continue-to-paypal-btn" class="w-full bg-[#003087] hover:bg-[#00256b] text-white font-bold py-3 rounded-lg shadow-lg transition flex items-center justify-center gap-2 text-sm">
                        <span>1. Ir a PayPal</span> <i class="fas fa-external-link-alt"></i>
                    </button>

                    <!-- 2. Verify Payment (Green) -->
                    <button id="verify-payment-btn" class="w-full bg-green-700 hover:bg-green-800 text-white font-bold py-3 rounded-lg shadow-lg shadow-green-900/30 transition flex items-center justify-center gap-2 text-sm relative overflow-hidden">
                        <span id="verify-text">2. Pago Realizado</span>
                        <div id="verify-spinner" class="hidden w-4 h-4 border-2 border-white border-t-transparent rounded-full animate-spin ml-2"></div>
                    </button>
                </div>

                <div id="verify-msg" class="mt-3 text-center text-xs hidden"></div>

                <button id="back-to-step1-btn" class="mt-4 w-full text-gray-500 hover:text-white text-xs">
                    Volver atrás
                </button>
            </div>

            <!-- STEP 2: Verification (Hidden by default) -->
            <div id="payment-step-2" style="display: none;">
                <div class="text-center mb-6">
                    <h3 class="text-2xl font-bold text-white mb-2">Verificación</h3>
                    <p class="text-gray-400 text-sm">Envía estos datos por Discord.</p>
                </div>

                <!-- Payment Sent Reminder -->
                <div class="text-center mb-4">
                    <p class="text-xs text-gray-500">Pago enviado a:</p>
                    <p class="text-purple-300 font-mono text-sm font-bold">yeratty8@gmail.com</p>
                </div>

                <!-- Generated Key Display -->
                <div class="bg-[#1a0b2e] border-2 border-[#2d1b4e] rounded-xl p-4 text-center mb-6 relative overflow-hidden">
                    <p class="text-gray-400 text-xs uppercase tracking-widest mb-1">Tu Código de Seguridad</p>
                    <div id="generated-key" class="text-4xl font-mono font-bold text-purple-400 tracking-widest">----</div>
                    <div class="absolute top-0 right-0 bg-purple-900/20 p-1 rounded-bl-lg text-xs text-purple-300">KEY</div>
                </div>

                <!-- Form Simulation -->
                <div class="space-y-4 mb-6">
                    <div>
                        <label class="block text-gray-400 text-xs mb-1 ml-1">1. Tu Email de PayPal</label>
                        <input type="email" placeholder="ejemplo@gmail.com" class="w-full bg-[#0a0a0a] border border-[#2d1b4e] rounded-lg px-4 py-3 text-white focus:outline-none focus:border-purple-600 transition">
                    </div>
                    
                    <div>
                        <label class="block text-gray-400 text-xs mb-1 ml-1">2. Comprobante de Pago</label>
                        <div class="w-full bg-[#0a0a0a] border border-[#2d1b4e] border-dashed rounded-lg px-4 py-3 text-gray-500 flex items-center justify-center cursor-not-allowed opacity-70">
                            <i class="fas fa-camera mr-2"></i> Subir Captura (Requerido en Discord)
                        </div>
                    </div>
                </div>

                <div class="bg-blue-900/20 border border-blue-900/50 p-3 rounded-lg mb-6 text-xs text-blue-200 flex items-start gap-2">
                    <i class="fas fa-info-circle mt-0.5"></i>
                    <p>Abre ticket en Discord y envía: <br><b>1. Tu Email</b> <br><b>2. La Key Generada</b> <br><b>3. Captura del pago</b></p>
                </div>

                <button id="finish-discord-btn" class="w-full bg-[#5865F2] hover:bg-[#4752C4] text-white font-bold py-4 rounded-xl shadow-lg hover:shadow-blue-900/50 transition cursor-pointer flex items-center justify-center gap-2">
                    <i class="fab fa-discord"></i> Abrir Discord y Enviar
                </button>
            </div>

        </div>
    </div>

    <script>
        // --- Mobile Menu & Smooth Scroll ---
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                // Special handlers
                if (targetId === '#guia-free' || targetId === '#como-conseguir') {
                    e.preventDefault();
                    document.getElementById('guide-modal').classList.remove('hidden');
                    return;
                }

                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    e.preventDefault();
                    mobileMenu.classList.add('hidden');
                    targetElement.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });

        // FORCE REMOVE ICON FROM BUTTON (CLEANUP)
        const cleanBtn = document.getElementById('new-guide-btn');
        if(cleanBtn) {
            const icon = cleanBtn.querySelector('i');
            if(icon) icon.remove();
        }

        // --- Modals Logic ---
        const guideModal = document.getElementById('guide-modal');
        const closeGuideBtn = document.getElementById('close-guide-btn');
        
        const tosModal = document.getElementById('tos-modal');
        const paymentModal = document.getElementById('payment-modal');
        
        const buyBtns = document.querySelectorAll('.buy-btn');
        const cancelTosBtn = document.getElementById('cancel-tos-btn');
        const acceptTosBtn = document.getElementById('accept-tos-btn');
        const closePaymentBtn = document.getElementById('close-payment-btn');

        // Guide Modal (New Button)
        const newGuideBtn = document.getElementById('new-guide-btn');
        if(newGuideBtn) {
            newGuideBtn.onclick = (e) => { 
                e.preventDefault(); 
                document.getElementById('guide-modal').classList.remove('hidden'); 
            };
        }
        if(closeGuideBtn) closeGuideBtn.onclick = () => guideModal.classList.add('hidden');

        // TOS Modal
        buyBtns.forEach(btn => {
            btn.onclick = (e) => {
                e.preventDefault();
                tosModal.classList.remove('hidden');
            };
        });
        if(cancelTosBtn) cancelTosBtn.onclick = () => tosModal.classList.add('hidden');

        // --- LOGICA DE PAGO ROBUSTA (V4 FINAL) ---
        
        // Función para resetear todo el flujo
        function resetPayment() {
            document.getElementById('payment-step-1').style.display = 'block';
            document.getElementById('payment-step-email').style.display = 'none';
            document.getElementById('payment-step-2').style.display = 'none';
        }

        // Inicializar
        resetPayment();

        // ABRIR MODAL DE PAGO (Desde TOS)
        if(acceptTosBtn) {
            acceptTosBtn.onclick = function() {
                tosModal.classList.add('hidden');
                paymentModal.classList.remove('hidden');
                resetPayment(); 
            };
        }

        // CERRAR MODAL DE PAGO
        if(closePaymentBtn) {
            closePaymentBtn.onclick = function() {
                paymentModal.classList.add('hidden');
                document.body.style.overflow = 'auto';
            };
        }

        // PASO 1 -> PASO EMAIL (Botón Pagar con PayPal)
        document.getElementById('paypal-initial-btn').onclick = function() {
            document.getElementById('payment-step-1').style.display = 'none';
            document.getElementById('payment-step-email').style.display = 'block';
        };

        // COPIAR EMAIL (Click en el área)
        document.getElementById('copy-email-area').onclick = function() {
            const email = "yeratty8@gmail.com";
            navigator.clipboard.writeText(email).then(() => {
                alert("Correo copiado: " + email);
            }).catch(() => {
                prompt("Copia este correo:", email);
            });
        };

        // 1. BOTON IR A PAYPAL
        document.getElementById('continue-to-paypal-btn').onclick = function() {
            navigator.clipboard.writeText("yeratty8@gmail.com");
            window.open('https://www.paypal.com/myaccount/transfer/homepage', '_blank');
        };

        // 2. BOTON VERIFICAR PAGO (Simulación)
        document.getElementById('verify-payment-btn').onclick = function() {
            const btn = document.getElementById('verify-payment-btn');
            const text = document.getElementById('verify-text');
            const spinner = document.getElementById('verify-spinner');
            const msg = document.getElementById('verify-msg');

            // Estado Cargando
            text.innerText = "Verificando...";
            spinner.style.display = 'block';
            btn.classList.add('opacity-75', 'cursor-wait');
            msg.style.display = 'none';

            // Simulación de 3 segundos
            setTimeout(() => {
                // Detectar éxito (Simulado para que el usuario pueda continuar)
                // Si quieres que falle la primera vez, podríamos añadir lógica, pero
                // para asegurar que obtengan la Key, lo haremos exitoso.
                
                // 1. Generar Key
                const key = Math.floor(1000 + Math.random() * 9000);
                document.getElementById('generated-key').innerText = key;

                // 2. Cambiar vista
                document.getElementById('payment-step-email').style.display = 'none';
                document.getElementById('payment-step-2').style.display = 'block';

                // Resetear botón para la próxima
                text.innerText = "2. Pago Realizado";
                spinner.style.display = 'none';
                btn.classList.remove('opacity-75', 'cursor-wait');
            }, 3000);
        };

        // VOLVER ATRAS
        document.getElementById('back-to-step1-btn').onclick = function() {
            document.getElementById('payment-step-email').style.display = 'none';
            document.getElementById('payment-step-1').style.display = 'block';
        };

        // FINALIZAR (Discord)
        document.getElementById('finish-discord-btn').onclick = function() {
            window.open('https://discord.gg/XHehzGrH', '_blank');
            paymentModal.classList.add('hidden');
            document.body.style.overflow = 'auto';
        };

        // Close modals on outside click
        window.onclick = (e) => {
            if (e.target === tosModal) tosModal.classList.add('hidden');
            if (e.target === paymentModal) {
                paymentModal.classList.add('hidden');
                resetPayment();
            }
            if (e.target === guideModal) guideModal.classList.add('hidden');
        };

    </script>
</body>
</html>
