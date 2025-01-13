# demo 1

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta name="description" content="AI-generated website">
      <meta name="theme-color" content="#ffffff">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="robots" content="index, follow">
      
      <!-- Performance optimization: Preload critical resources -->
      <link rel="preload" href="https://cdn.tailwindcss.com" as="script">
      <link rel="preload" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@400;500;600;700&display=swap" as="style">
      
      <!-- Core CSS -->
      <script src="https://cdn.tailwindcss.com"></script>
      <script>
        tailwind.config = {
          theme: {
            extend: {
             colors: {
                primary: {
                  50: '#f8f8f8',
                  100: '#e8e8e8',
                  200: '#d3d3d3',
                  300: '#a3a3a3',
                  400: '#737373',
                  500: '#525252',
                  600: '#404040',
                  700: '#262626',
                  800: '#171717',
                  900: '#0a0a0a',
                  950: '#030303',
                },
                secondary: {
                  50: '#f8f8f8',
                  100: '#e8e8e8',
                  200: '#d3d3d3',
                  300: '#a3a3a3',
                  400: '#737373',
                  500: '#525252',
                  600: '#404040',
                  700: '#262626',
                  800: '#171717',
                  900: '#0a0a0a',
                  950: '#030303',
                },
                accent: {
                  50: '#f8f8f8',
                  100: '#e8e8e8',
                  200: '#d3d3d3',
                  300: '#a3a3a3',
                  400: '#737373',
                  500: '#525252',
                  600: '#404040',
                  700: '#262626',
                  800: '#171717',
                  900: '#0a0a0a',
                  950: '#030303',
                },
              },
              fontFamily: {
                sans: ['Inter', 'system-ui', '-apple-system', 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica Neue', 'Arial', 'sans-serif'],
                heading: ['Montserrat', 'Inter', 'system-ui', 'sans-serif'],
              },
              spacing: {
                '18': '4.5rem',
                '22': '5.5rem',
                '30': '7.5rem',
              },
              maxWidth: {
                '8xl': '88rem',
                '9xl': '96rem',
              },
              animation: {
                'fade-in': 'fadeIn 0.5s ease-in',
                'fade-out': 'fadeOut 0.5s ease-out',
                'slide-up': 'slideUp 0.5s ease-out',
                'slide-down': 'slideDown 0.5s ease-out',
                'slide-left': 'slideLeft 0.5s ease-out',
                'slide-right': 'slideRight 0.5s ease-out',
                'scale-in': 'scaleIn 0.5s ease-out',
                'scale-out': 'scaleOut 0.5s ease-out',
                'spin-slow': 'spin 3s linear infinite',
                'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                'bounce-slow': 'bounce 3s infinite',
                'float': 'float 3s ease-in-out infinite',
              },
              keyframes: {
                fadeIn: {
                  '0%': { opacity: '0' },
                  '100%': { opacity: '1' },
                },
                fadeOut: {
                  '0%': { opacity: '1' },
                  '100%': { opacity: '0' },
                },
                slideUp: {
                  '0%': { transform: 'translateY(20px)', opacity: '0' },
                  '100%': { transform: 'translateY(0)', opacity: '1' },
                },
                slideDown: {
                  '0%': { transform: 'translateY(-20px)', opacity: '0' },
                  '100%': { transform: 'translateY(0)', opacity: '1' },
                },
                slideLeft: {
                  '0%': { transform: 'translateX(20px)', opacity: '0' },
                  '100%': { transform: 'translateX(0)', opacity: '1' },
                },
                slideRight: {
                  '0%': { transform: 'translateX(-20px)', opacity: '0' },
                  '100%': { transform: 'translateX(0)', opacity: '1' },
                },
                scaleIn: {
                  '0%': { transform: 'scale(0.9)', opacity: '0' },
                  '100%': { transform: 'scale(1)', opacity: '1' },
                },
                scaleOut: {
                  '0%': { transform: 'scale(1.1)', opacity: '0' },
                  '100%': { transform: 'scale(1)', opacity: '1' },
                },
                float: {
                  '0%, 100%': { transform: 'translateY(0)' },
                  '50%': { transform: 'translateY(-10px)' },
                },
              },
              aspectRatio: {
                'portrait': '3/4',
                'landscape': '4/3',
                'ultrawide': '21/9',
              },
            },
          },
          variants: {
            extend: {
              opacity: ['disabled'],
              cursor: ['disabled'],
              backgroundColor: ['active', 'disabled'],
              textColor: ['active', 'disabled'],
            },
          },
        }
      </script>

      <!-- Utilities and Components -->
      <script defer src="https://cdnjs.cloudflare.com/ajax/libs/alpinejs/3.13.3/cdn.min.js"></script>
      <script defer src="https://cdnjs.cloudflare.com/ajax/libs/apexcharts/3.45.1/apexcharts.min.js"></script>
      
      <!-- Optimized Font Loading -->
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
      
      <!-- Icons -->
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" 
            integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
            crossorigin="anonymous" referrerpolicy="no-referrer" />

      <!-- Base Styles -->
      <style>

      * {
  -ms-overflow-style: none;  /* IE and Edge */
  scrollbar-width: none;     /* Firefox */
}

/* Webkit browsers like Chrome, Safari, newer Edge */
*::-webkit-scrollbar {
  display: none;
  width: 0;
  height: 0;
}
        /* Custom scrollbar */
        ::-webkit-scrollbar {
          width: 0px;
        }
        
        ::-webkit-scrollbar-track {
          background: #f1f1f1;
          border-radius: 4px;
        }
        
        ::-webkit-scrollbar-thumb {
          background: #888;
          border-radius: 4px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
          background: #666;
        }

        /* Remove tap highlight on mobile */
        * {
          -webkit-tap-highlight-color: transparent;
        }

        /* Improve text rendering */
        body {
          text-rendering: optimizeLegibility;
          -webkit-font-smoothing: antialiased;
          -moz-osx-font-smoothing: grayscale;
        }

        /* Focus outline styles */
        :focus-visible {
          outline: 2px solid currentColor;
          outline-offset: 2px;
        }

        /* Print styles */
        @media print {
          .no-print {
            display: none !important;
          }
          
          a[href]:after {
            content: " (" attr(href) ")";
          }
        }
      </style>

      <!-- Enhanced Image Handler -->
      <script>
        document.addEventListener('DOMContentLoaded', () => {
          const imageObserver = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
              if (entry.isIntersecting) {
                const img = entry.target;
                if (img.dataset.src) {
                  const tempImage = new Image();
                  tempImage.onload = () => {
                    img.src = img.dataset.src;
                    img.classList.remove('opacity-0');
                    img.classList.add('opacity-100');
                  };
                  tempImage.src = img.dataset.src;
                  img.removeAttribute('data-src');
                  observer.unobserve(img);
                }
              }
            });
          }, {
            rootMargin: '50px 0px',
            threshold: 0.01
          });

          const loadImage = (img) => {
            if ('loading' in HTMLImageElement.prototype) {
              img.loading = 'lazy';
            }
            
            img.classList.add('transition-opacity', 'duration-300', 'opacity-0');
            
            img.onerror = () => {
              const width = img.getAttribute('width') || img.clientWidth || 300;
              const height = img.getAttribute('height') || img.clientHeight || 200;
              img.src = `https://placehold.co/${width}x${height}/DEDEDE/555555?text=Image+Unavailable`;
              img.alt = 'Image unavailable';
              img.classList.remove('opacity-0');
              img.classList.add('opacity-100', 'error-image');
            };

            if (img.dataset.src) {
              imageObserver.observe(img);
            } else {
              img.classList.remove('opacity-0');
              img.classList.add('opacity-100');
            }
          };

          document.querySelectorAll('img[data-src], img:not([data-src])').forEach(loadImage);

          // Watch for dynamically added images
          new MutationObserver((mutations) => {
            mutations.forEach(mutation => {
              mutation.addedNodes.forEach(node => {
                if (node.nodeType === 1) {
                  if (node.tagName === 'IMG') {
                    loadImage(node);
                  }
                  node.querySelectorAll('img').forEach(loadImage);
                }
              });
            });
          }).observe(document.body, {
            childList: true,
            subtree: true
          });
        });

        // Performance monitoring
        if ('performance' in window && 'PerformanceObserver' in window) {
          // Create performance observer
          const observer = new PerformanceObserver((list) => {
            const entries = list.getEntries();
            entries.forEach((entry) => {
              if (entry.entryType === 'largest-contentful-paint') {
                // console.log(`LCP: ${entry.startTime}ms`);
              }
              if (entry.entryType === 'first-input') {
                // console.log(`FID: ${entry.processingStart - entry.startTime}ms`);
              }
              if (entry.entryType === 'layout-shift') {
                // console.log(`CLS: ${entry.value}`);
              }
            });
          });

          // Observe performance metrics
          observer.observe({ entryTypes: ['largest-contentful-paint', 'first-input', 'layout-shift'] });

          // Log basic performance metrics
          window.addEventListener('load', () => {
            const timing = performance.getEntriesByType('navigation')[0];
            console.log({
              'DNS Lookup': timing.domainLookupEnd - timing.domainLookupStart,
              'TCP Connection': timing.connectEnd - timing.connectStart,
              'DOM Content Loaded': timing.domContentLoadedEventEnd - timing.navigationStart,
              'Page Load': timing.loadEventEnd - timing.navigationStart
            });
          });
        }

        // Handle offline/online status
        window.addEventListener('online', () => {
          document.body.classList.remove('offline');
          console.log('Connection restored');
        });
        
        window.addEventListener('offline', () => {
          document.body.classList.add('offline');
          console.log('Connection lost');
        });
      </script>
   </head>
   <body class="antialiased text-gray-800 min-h-screen flex flex-col">
      <!-- Skip to main content link for accessibility -->
      <a href="#main-content" 
         class="sr-only focus:not-sr-only focus:absolute focus:top-0 focus:left-0 focus:z-50 focus:p-4 focus:bg-white focus:text-black">
         Skip to main content
      </a>

      <!-- Header -->
      <header class="relative z-50 bg-white dark:bg-gray-900">
        <!-- Header content goes here -->
      </header>

      <!-- Main content area -->
      <main id="main-content" class="flex-1 relative ">
        <!-- Content will be injected here -->
      </main>

   </body>
</html><htmlcode>
<div id="root" class="antialiased">
    <section id="navbar_hero" class="relative min-h-screen bg-white dark:bg-neutral-900 transition-colors duration-300">
        <!-- Navbar -->
        <div x-data="{ isOpen: false }" class="relative">
            <nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 dark:bg-neutral-900/80 backdrop-blur-lg border-b border-neutral-200 dark:border-neutral-800">
                <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                    <div class="flex justify-between items-center h-16">
                        <!-- Logo -->
                        <div class="flex-shrink-0">
                            <a href="#" class="text-lg font-semibold text-neutral-900 dark:text-white">Portfolio</a>
                        </div>

                        <!-- Desktop Navigation -->
                        <div class="hidden lg:flex lg:items-center lg:space-x-8">
                            <a href="#about" class="text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white transition-colors duration-300">About</a>
                            <a href="#projects" class="text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white transition-colors duration-300">Projects</a>
                            <a href="#contact" class="text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white transition-colors duration-300">Contact</a>
                            <button class="px-4 py-2 rounded-lg bg-neutral-900 text-white dark:bg-white dark:text-neutral-900 hover:opacity-90 transition-opacity duration-300">Resume</button>
                        </div>

                        <!-- Mobile menu button -->
                        <div class="lg:hidden">
                            <button @click="isOpen = !isOpen" type="button" class="text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white focus:outline-none">
                                <svg x-show="!isOpen" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                                </svg>
                                <svg x-show="isOpen" x-cloak="" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                                </svg>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Mobile menu -->
                <div x-show="isOpen" x-cloak="" class="lg:hidden" x-transition:enter="transition ease-out duration-100 transform" x-transition:enter-start="opacity-0 scale-95" x-transition:enter-end="opacity-100 scale-100" x-transition:leave="transition ease-in duration-75 transform" x-transition:leave-start="opacity-100 scale-100" x-transition:leave-end="opacity-0 scale-95">
                    <div class="px-2 pt-2 pb-3 space-y-1">
                        <a href="#about" class="block px-3 py-2 rounded-md text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white">About</a>
                        <a href="#projects" class="block px-3 py-2 rounded-md text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white">Projects</a>
                        <a href="#contact" class="block px-3 py-2 rounded-md text-neutral-600 hover:text-neutral-900 dark:text-neutral-400 dark:hover:text-white">Contact</a>
                        <button class="w-full mt-4 px-4 py-2 rounded-lg bg-neutral-900 text-white dark:bg-white dark:text-neutral-900 hover:opacity-90 transition-opacity duration-300">Resume</button>
                    </div>
                </div>
            </nav>
        </div>

        <!-- Hero Section -->
        <div class="pt-16 min-h-screen flex items-center justify-center">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24 text-center">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold text-neutral-900 dark:text-white mb-6">
                    Hello, I'm <span class="bg-clip-text text-transparent bg-gradient-to-r from-neutral-900 to-neutral-600 dark:from-white dark:to-neutral-400">Lochan S</span>
                </h1>
                <p class="text-xl sm:text-2xl text-neutral-600 dark:text-neutral-400 mb-12 max-w-3xl mx-auto">
                    A passionate student developer dedicated to leveraging AI to create intuitive and transformative digital experiences.
                </p>
                <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                    <button class="px-8 py-3 rounded-lg bg-neutral-900 text-white dark:bg-white dark:text-neutral-900 hover:opacity-90 transition-opacity duration-300">
                        View Projects
                    </button>
                    <button class="px-8 py-3 rounded-lg border border-neutral-300 dark:border-neutral-700 text-neutral-900 dark:text-white hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                        Download Resume
                    </button>
                </div>
            </div>
        </div>
    </section>
</div>
</htmlcode><htmlcode>
<div id="root">
    <section id="about" class="min-h-screen bg-white dark:bg-neutral-900 transition-colors duration-300 py-24">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <!-- Profile Image -->
                <div class="flex justify-center lg:justify-start">
                    <div class="relative w-64 h-64 rounded-2xl overflow-hidden border border-neutral-200 dark:border-neutral-800">
                        <img src="https://avatar.iran.liara.run/public" alt="Profile" class="w-full h-full object-cover">
                    </div>
                </div>

                <!-- About Content -->
                <div class="space-y-6">
                    <div class="space-y-2">
                        <h2 class="text-3xl font-bold text-neutral-900 dark:text-white">About Me</h2>
                        <div class="h-1 w-20 bg-neutral-900 dark:bg-white rounded"></div>
                    </div>

                    <p class="text-lg text-neutral-600 dark:text-neutral-400">
                        I'm a passionate Computer Science student with a keen interest in software development and problem-solving. Currently pursuing my degree, I'm actively seeking internship opportunities where I can apply my theoretical knowledge to real-world challenges.
                    </p>

                    <div class="space-y-4">
                        <div class="flex items-center space-x-4">
                            <span class="text-neutral-900 dark:text-white font-medium">Education:</span>
                            <span class="text-neutral-600 dark:text-neutral-400">Computer Science Major</span>
                        </div>
                        <div class="flex items-center space-x-4">
                            <span class="text-neutral-900 dark:text-white font-medium">Focus Areas:</span>
                            <span class="text-neutral-600 dark:text-neutral-400">Web Development, Software Engineering, AI</span>
                        </div>
                        <div class="flex items-center space-x-4">
                            <span class="text-neutral-900 dark:text-white font-medium">Location:</span>
                            <span class="text-neutral-600 dark:text-neutral-400">Available for Remote Opportunities</span>
                        </div>
                    </div>

                    <div class="pt-6 flex flex-wrap gap-4">
                        <button class="px-6 py-3 rounded-lg bg-neutral-900 text-white dark:bg-white dark:text-neutral-900 hover:opacity-90 transition-opacity duration-300">
                            Download Resume
                        </button>
                        <button class="px-6 py-3 rounded-lg border border-neutral-300 dark:border-neutral-700 text-neutral-900 dark:text-white hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                            View Projects
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>
</htmlcode><htmlcode>
<div id="root">
    <section id="skills" class="py-24 bg-neutral-50 dark:bg-neutral-800/50 transition-colors duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Section Header -->
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-neutral-900 dark:text-white mb-4">Technical Skills</h2>
                <p class="text-lg text-neutral-600 dark:text-neutral-400 max-w-2xl mx-auto">
                    A collection of technologies and tools I've worked with during my academic journey
                </p>
            </div>

            <!-- Skills Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Programming Languages -->
                <div class="p-8 bg-white dark:bg-neutral-900 rounded-xl border border-neutral-200 dark:border-neutral-700 hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-white mb-4">Programming Languages</h3>
                    <div class="space-y-3">
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">JavaScript</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">90%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">Python</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">85%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 85%"></div>
                            </div>
                        </div>
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">Java</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">80%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 80%"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Web Technologies -->
                <div class="p-8 bg-white dark:bg-neutral-900 rounded-xl border border-neutral-200 dark:border-neutral-700 hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-white mb-4">Web Technologies</h3>
                    <div class="space-y-3">
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">React</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">85%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 85%"></div>
                            </div>
                        </div>
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">HTML/CSS</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">95%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 95%"></div>
                            </div>
                        </div>
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">Node.js</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">80%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 80%"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Tools & Other -->
                <div class="p-8 bg-white dark:bg-neutral-900 rounded-xl border border-neutral-200 dark:border-neutral-700 hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                    <h3 class="text-xl font-semibold text-neutral-900 dark:text-white mb-4">Tools &amp; Others</h3>
                    <div class="space-y-3">
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">Git</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">90%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">VS Code</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">95%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 95%"></div>
                            </div>
                        </div>
                        <div class="relative pt-1">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">Docker</span>
                                <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">75%</span>
                            </div>
                            <div class="w-full bg-neutral-200 dark:bg-neutral-700 rounded-full h-2">
                                <div class="bg-neutral-900 dark:bg-white h-2 rounded-full" style="width: 75%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>
</htmlcode><htmlcode>
<div id="root">
    <section id="projects" class="py-24 bg-white dark:bg-neutral-900 transition-colors duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Section Header -->
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-neutral-900 dark:text-white mb-4">Projects</h2>
                <p class="text-lg text-neutral-600 dark:text-neutral-400 max-w-2xl mx-auto">
                    A showcase of my upcoming work and projects
                </p>
            </div>

            <!-- Projects Coming Soon Card -->
            <div class="max-w-3xl mx-auto">
                <div class="relative p-8 md:p-12 bg-neutral-50 dark:bg-neutral-800/50 rounded-2xl border border-neutral-200 dark:border-neutral-700 overflow-hidden group">
                    <!-- Background Pattern -->
                    <div class="absolute inset-0 bg-grid-neutral-900/[0.03] dark:bg-grid-neutral-100/[0.03] bg-[size:20px_20px] -z-10"></div>
                    
                    <!-- Content -->
                    <div class="text-center space-y-6">
                        <div class="inline-flex items-center justify-center w-16 h-16 rounded-full bg-neutral-200 dark:bg-neutral-700 mb-4">
                            <div class="w-8 h-8 bg-neutral-400 dark:bg-neutral-500 rounded-full animate-pulse"></div>
                        </div>
                        
                        <h3 class="text-2xl font-semibold text-neutral-900 dark:text-white">
                            Projects Coming Soon
                        </h3>
                        
                        <p class="text-neutral-600 dark:text-neutral-400 max-w-lg mx-auto">
                            I'm currently working on exciting projects that showcase my skills and passion for development. Check back soon to see my latest work!
                        </p>

                        <!-- Status Indicator -->
                        <div class="inline-flex items-center space-x-2 text-sm text-neutral-500 dark:text-neutral-400">
                            <span class="relative flex h-3 w-3">
                                <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-neutral-400 dark:bg-neutral-500 opacity-75"></span>
                                <span class="relative inline-flex rounded-full h-3 w-3 bg-neutral-500 dark:bg-neutral-400"></span>
                            </span>
                            <span>In Development</span>
                        </div>

                        <!-- Action Button -->
                        <div class="pt-6">
                            <button class="px-6 py-3 rounded-lg bg-neutral-900 dark:bg-white text-white dark:text-neutral-900 hover:opacity-90 transition-opacity duration-300">
                                Notify Me When Live
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Additional Info -->
                <div class="mt-8 text-center">
                    <p class="text-sm text-neutral-500 dark:text-neutral-400">
                        Want to see what I'm working on? Connect with me on 
                        <a href="#" class="text-neutral-900 dark:text-white hover:underline">GitHub</a>
                    </p>
                </div>
            </div>
        </div>
    </section>
</div>
</htmlcode><htmlcode>
<div id="root">
    <section id="resume_download" class="py-24 bg-neutral-50 dark:bg-neutral-800/50 transition-colors duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mx-auto">
                <!-- Resume Download Card -->
                <div class="bg-white dark:bg-neutral-900 rounded-2xl border border-neutral-200 dark:border-neutral-700 overflow-hidden">
                    <div class="p-8 md:p-12">
                        <!-- Header -->
                        <div class="text-center mb-8">
                            <h2 class="text-3xl font-bold text-neutral-900 dark:text-white mb-4">Download Resume</h2>
                            <p class="text-neutral-600 dark:text-neutral-400">
                                Access my complete professional background and technical qualifications
                            </p>
                        </div>

                        <!-- Resume Preview -->
                        <div class="mb-8 p-6 bg-neutral-50 dark:bg-neutral-800/50 rounded-xl border border-neutral-200 dark:border-neutral-700">
                            <div class="space-y-4">
                                <div class="flex items-center justify-between">
                                    <span class="text-sm font-medium text-neutral-600 dark:text-neutral-400">Resume.pdf</span>
                                    <span class="text-sm text-neutral-500 dark:text-neutral-500">156 KB</span>
                                </div>
                                <div class="w-full bg-neutral-200 dark:bg-neutral-700 h-2 rounded-full">
                                    <div class="bg-neutral-900 dark:bg-white h-2 rounded-full w-full"></div>
                                </div>
                            </div>
                        </div>

                        <!-- Download Options -->
                        <div class="space-y-4">
                            <button class="w-full px-6 py-4 bg-neutral-900 dark:bg-white text-white dark:text-neutral-900 rounded-xl hover:opacity-90 transition-opacity duration-300 flex items-center justify-center space-x-2">
                                <span>Download PDF Version</span>
                            </button>
                            
                            <button class="w-full px-6 py-4 border border-neutral-300 dark:border-neutral-700 text-neutral-900 dark:text-white rounded-xl hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300 flex items-center justify-center space-x-2">
                                <span>View Online Version</span>
                            </button>
                        </div>

                        <!-- Additional Info -->
                        <div class="mt-6 text-center">
                            <p class="text-sm text-neutral-500 dark:text-neutral-400">
                                Last updated: June 2024
                            </p>
                        </div>
                    </div>

                    <!-- Bottom Banner -->
                    <div class="px-8 py-4 bg-neutral-50 dark:bg-neutral-800/50 border-t border-neutral-200 dark:border-neutral-700">
                        <p class="text-sm text-center text-neutral-600 dark:text-neutral-400">
                            Looking for a different format? 
                            <a href="#contact" class="text-neutral-900 dark:text-white hover:underline">Contact me</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>
</htmlcode><htmlcode>
<div id="root">
    <section id="contact" class="py-24 bg-white dark:bg-neutral-900 transition-colors duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Section Header -->
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-neutral-900 dark:text-white mb-4">Get in Touch</h2>
                <p class="text-lg text-neutral-600 dark:text-neutral-400 max-w-2xl mx-auto">
                    Let's discuss potential opportunities or collaborations
                </p>
            </div>

            <div class="grid lg:grid-cols-2 gap-12">
                <!-- Contact Form -->
                <div class="space-y-8">
                    <div class="bg-white dark:bg-neutral-800/50 p-8 rounded-2xl border border-neutral-200 dark:border-neutral-700">
                        <form class="space-y-6">
                            <div class="space-y-4">
                                <div>
                                    <label for="name" class="block text-sm font-medium text-neutral-900 dark:text-white mb-2">Name</label>
                                    <input type="text" id="name" name="name" class="w-full px-4 py-3 rounded-lg bg-neutral-50 dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-700 text-neutral-900 dark:text-white focus:outline-none focus:border-neutral-400 dark:focus:border-neutral-600 transition-colors duration-300" placeholder="Your name">
                                </div>

                                <div>
                                    <label for="email" class="block text-sm font-medium text-neutral-900 dark:text-white mb-2">Email</label>
                                    <input type="email" id="email" name="email" class="w-full px-4 py-3 rounded-lg bg-neutral-50 dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-700 text-neutral-900 dark:text-white focus:outline-none focus:border-neutral-400 dark:focus:border-neutral-600 transition-colors duration-300" placeholder="your@email.com">
                                </div>

                                <div>
                                    <label for="subject" class="block text-sm font-medium text-neutral-900 dark:text-white mb-2">Subject</label>
                                    <input type="text" id="subject" name="subject" class="w-full px-4 py-3 rounded-lg bg-neutral-50 dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-700 text-neutral-900 dark:text-white focus:outline-none focus:border-neutral-400 dark:focus:border-neutral-600 transition-colors duration-300" placeholder="What's this about?">
                                </div>

                                <div>
                                    <label for="message" class="block text-sm font-medium text-neutral-900 dark:text-white mb-2">Message</label>
                                    <textarea id="message" name="message" rows="4" class="w-full px-4 py-3 rounded-lg bg-neutral-50 dark:bg-neutral-900 border border-neutral-200 dark:border-neutral-700 text-neutral-900 dark:text-white focus:outline-none focus:border-neutral-400 dark:focus:border-neutral-600 transition-colors duration-300" placeholder="Your message"></textarea>
                                </div>
                            </div>

                            <button type="submit" class="w-full px-6 py-3 bg-neutral-900 dark:bg-white text-white dark:text-neutral-900 rounded-lg hover:opacity-90 transition-opacity duration-300">
                                Send Message
                            </button>
                        </form>
                    </div>
                </div>

                <!-- Contact Info -->
                <div class="space-y-8">
                    <!-- Social Links -->
                    <div class="bg-white dark:bg-neutral-800/50 p-8 rounded-2xl border border-neutral-200 dark:border-neutral-700">
                        <h3 class="text-xl font-semibold text-neutral-900 dark:text-white mb-6">Connect with Me</h3>
                        <div class="space-y-4">
                            <a href="#" class="block p-4 bg-neutral-50 dark:bg-neutral-900 rounded-lg border border-neutral-200 dark:border-neutral-700 hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                                <div class="flex items-center justify-between">
                                    <span class="text-neutral-900 dark:text-white">LinkedIn</span>
                                    <span class="text-neutral-500 dark:text-neutral-400">→</span>
                                </div>
                            </a>
                            <a href="#" class="block p-4 bg-neutral-50 dark:bg-neutral-900 rounded-lg border border-neutral-200 dark:border-neutral-700 hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                                <div class="flex items-center justify-between">
                                    <span class="text-neutral-900 dark:text-white">GitHub</span>
                                    <span class="text-neutral-500 dark:text-neutral-400">→</span>
                                </div>
                            </a>
                            <a href="#" class="block p-4 bg-neutral-50 dark:bg-neutral-900 rounded-lg border border-neutral-200 dark:border-neutral-700 hover:border-neutral-400 dark:hover:border-neutral-600 transition-colors duration-300">
                                <div class="flex items-center justify-between">
                                    <span class="text-neutral-900 dark:text-white">X</span>
                                    <span class="text-neutral-500 dark:text-neutral-400">→</span>
                                </div>
                            </a>
                        </div>
                    </div>

                    <!-- Response Time -->
                    <div class="bg-white dark:bg-neutral-800/50 p-8 rounded-2xl border border-neutral-200 dark:border-neutral-700">
                        <div class="flex items-center space-x-4">
                            <div class="flex-1">
                                <h4 class="text-lg font-medium text-neutral-900 dark:text-white mb-2">Quick Response Time</h4>
                                <p class="text-neutral-600 dark:text-neutral-400">I typically respond within 24 hours during weekdays</p>
                            </div>
                            <div class="h-12 w-12 rounded-full bg-neutral-100 dark:bg-neutral-700 flex items-center justify-center">
                                <div class="h-6 w-6 rounded-full bg-neutral-900 dark:bg-white animate-pulse"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</div>
</htmlcode><htmlcode>
<div id="root">
    <footer id="footer" class="bg-neutral-50 dark:bg-neutral-800/50 border-t border-neutral-200 dark:border-neutral-700 transition-colors duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <!-- Main Footer Content -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-12">
                <!-- Brand Column -->
                <div class="space-y-4">
                    <div class="text-2xl font-bold text-neutral-900 dark:text-white">Portfolio</div>
                    <p class="text-neutral-600 dark:text-neutral-400">
                        Software Developer | Student
                    </p>
                    <div class="pt-2">
                        <button class="px-4 py-2 bg-neutral-900 dark:bg-white text-white dark:text-neutral-900 rounded-lg hover:opacity-90 transition-opacity duration-300">
                            Download Resume
                        </button>
                    </div>
                </div>

                <!-- Quick Links -->
                <div>
                    <h3 class="text-sm font-semibold text-neutral-900 dark:text-white uppercase tracking-wider mb-4">Quick Links</h3>
                    <ul class="space-y-3">
                        <li>
                            <a href="#about" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">About</a>
                        </li>
                        <li>
                            <a href="#projects" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">Projects</a>
                        </li>
                        <li>
                            <a href="#skills" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">Skills</a>
                        </li>
                        <li>
                            <a href="#contact" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">Contact</a>
                        </li>
                    </ul>
                </div>

                <!-- Contact Info -->
                <div>
                    <h3 class="text-sm font-semibold text-neutral-900 dark:text-white uppercase tracking-wider mb-4">Connect</h3>
                    <ul class="space-y-3">
                        <li>
                            <a href="#" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">LinkedIn</a>
                        </li>
                        <li>
                            <a href="#" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">GitHub</a>
                        </li>
                        <li>
                            <a href="#" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">X</a>
                        </li>
                        <li>
                            <a href="mailto:contact@example.com" class="text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">Email</a>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- Bottom Footer -->
            <div class="pt-8 border-t border-neutral-200 dark:border-neutral-700">
                <div class="flex flex-col md:flex-row justify-between items-center space-y-4 md:space-y-0">
                    <div class="text-neutral-600 dark:text-neutral-400 text-sm">
                        © 2024 Portfolio. All rights reserved.
                    </div>
                    <div class="flex items-center space-x-6">
                        <a href="#" class="text-sm text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">Privacy Policy</a>
                        <a href="#" class="text-sm text-neutral-600 dark:text-neutral-400 hover:text-neutral-900 dark:hover:text-white transition-colors duration-300">Terms of Service</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</div>
</htmlcode>
