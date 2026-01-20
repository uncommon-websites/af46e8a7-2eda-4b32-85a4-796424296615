<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-cream overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">East Africa's E-Commerce & Ticketing Enabler</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Making commerce social <br class="hidden md:block" /> across East Africa
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      The fastest and easiest way to sell tickets and products online in Kenya, Rwanda, and Uganda.
      Accept M-PESA, cards, and international payments – all in one platform.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Get started &rarr;</Button>
      <Button href="#" type="outline">See how it works</Button>
    </div>

    <!-- Hero Image Placeholder -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16 group">
      <!-- Mock UI -->
      <div class="absolute inset-0 bg-gray-50 p-4">
        <div class="h-full w-full bg-white rounded-xl border border-gray-200 shadow-sm p-6 flex flex-col">
            <!-- Header of Mock UI -->
            <div class="flex items-center justify-between mb-6 border-b border-gray-100 pb-4">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full bg-orange-100"></div>
                    <div class="h-4 w-32 bg-gray-100 rounded"></div>
                </div>
                <div class="flex gap-2">
                    <div class="h-8 w-20 bg-gray-100 rounded"></div>
                    <div class="h-8 w-20 bg-gray-100 rounded"></div>
                </div>
            </div>
            <!-- Content of Mock UI -->
            <div class="flex-1 grid grid-cols-12 gap-6">
                <div class="col-span-3 space-y-3">
                    <div class="h-4 w-full bg-gray-100 rounded"></div>
                    <div class="h-4 w-3/4 bg-gray-100 rounded"></div>
                    <div class="h-4 w-5/6 bg-gray-100 rounded"></div>
                </div>
                <div class="col-span-9 bg-gray-50 rounded-lg p-4 grid grid-cols-2 gap-4">
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                </div>
            </div>
        </div>
      </div>
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-orange-brand rounded-full blur-2xl opacity-20"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-purple-400 rounded-full blur-2xl opacity-20"></div>

      <!-- Cartoon Character (Orange Blob) -->
      <div class="absolute bottom-[-20px] left-[-40px] w-32 h-32 z-10 hidden md:block">
          <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M50 90C75 90 90 70 90 50C90 30 70 10 50 10C30 10 10 30 10 50C10 70 25 90 50 90Z" fill="#FF5D2A"/>
            <circle cx="35" cy="40" r="5" fill="white"/>
            <circle cx="65" cy="40" r="5" fill="white"/>
            <path d="M35 60 Q50 70 65 60" stroke="white" stroke-width="3" stroke-linecap="round"/>
            <!-- Arms -->
            <path d="M10 50 Q-5 30 15 20" stroke="#FF5D2A" stroke-width="8" stroke-linecap="round"/>
          </svg>
      </div>
    </div>

    <!-- Trust Indicators -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Trusted by East Africa's leading event organizers and artists</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-60 hover:opacity-100 transition-all duration-500">
        <span class="font-bold text-lg">Nairobi Comedy Collective</span>
        <span class="font-bold text-lg">Kenya Nights</span>
        <span class="font-bold text-lg">PrayzzZ</span>
        <span class="font-bold text-lg">MUZE Club</span>
        <span class="font-bold text-lg">KODA Nairobi</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        Powering events and commerce across East Africa
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">1,700+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Events Serviced</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">450,000+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Tickets Sold</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">$4.17M</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Total Ticket Value</div>
        </div>
      </div>

      <!-- Event Categories Carousel -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-white to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-white to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 -->
            <div class="w-64 h-80 bg-pink-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-pink-500 rounded-full"></div> Concerts
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">GHEDIBAE at MUZE</div>
                    <div class="text-xs opacity-80">Afro Club Sounds</div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="w-64 h-80 bg-orange-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-orange-500 rounded-full"></div> Festivals
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Motion Conservation</div>
                    <div class="text-xs opacity-80">Safari & Cultural Festival</div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="w-64 h-80 bg-red-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-red-500 rounded-full"></div> Theater
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Katanga</div>
                    <div class="text-xs opacity-80">Dance of the Scorpions</div>
                </div>
            </div>
             <!-- Card 4 -->
            <div class="w-64 h-80 bg-blue-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-blue-500 rounded-full"></div> Conferences
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">INDEX ONE</div>
                    <div class="text-xs opacity-80">Business Events</div>
                </div>
            </div>
             <!-- Card 5 -->
            <div class="w-64 h-80 bg-purple-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-purple-500 rounded-full"></div> Sports
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Sports Tournaments</div>
                    <div class="text-xs opacity-80">Live Events</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Payment Trust Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Traditional ticketing holds <br /> you back</h2>
      <p class="text-center text-gray-400 mb-16">We're making online commerce accessible to every event organizer in East Africa.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Old Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The old way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Event organizers print physical tickets with security measures to prevent fakes, deal with manual sales, and struggle with payment collection.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="space-y-3">
                <div class="flex items-center gap-3">
                    <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                    <span class="text-sm text-gray-300">Printed tickets with security measures</span>
                </div>
                <div class="flex items-center gap-3">
                    <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                    <span class="text-sm text-gray-300">Manual payment collection</span>
                </div>
                <div class="flex items-center gap-3">
                    <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                    <span class="text-sm text-gray-300">Fake ticket distribution</span>
                </div>
                <div class="flex items-center gap-3">
                    <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                    <span class="text-sm text-gray-300">Limited payment options</span>
                </div>
                <div class="flex items-center gap-3">
                    <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                    <span class="text-sm text-gray-300">No online presence</span>
                </div>
             </div>
          </div>
        </div>

        <!-- The New Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Mookh way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Go live in minutes with secure digital ticketing, M-PESA integration, and multi-channel distribution. We handle payments, security, and settlements.
          </p>
          <div class="relative h-64 flex items-center justify-center">
             <!-- Central M-PESA Icon -->
             <div class="relative z-10 w-24 h-24 bg-green-500 rounded-2xl flex items-center justify-center">
                <span class="text-white font-bold text-2xl">M</span>
             </div>
             <!-- Orbiting Payment Methods -->
             <div class="absolute inset-0 animate-spin-slow">
                <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-4 w-12 h-12 bg-blue-500 rounded-lg flex items-center justify-center text-white text-xs font-bold">Card</div>
                <div class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-4 w-12 h-12 bg-purple-500 rounded-lg flex items-center justify-center text-white text-xs font-bold">Web</div>
                <div class="absolute left-0 top-1/2 -translate-x-4 -translate-y-1/2 w-12 h-12 bg-orange-500 rounded-lg flex items-center justify-center text-white text-xs font-bold">App</div>
                <div class="absolute right-0 top-1/2 translate-x-4 -translate-y-1/2 w-12 h-12 bg-pink-500 rounded-lg flex items-center justify-center text-white text-xs font-bold">Social</div>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Everything you need to sell tickets and products online
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: M-PESA Integration -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">M-PESA and multiple payment options</h3>
                <p class="text-gray-500 text-sm">Accept M-PESA, debit cards, credit cards, and international payments. We handle all payment processing, security, and fraud prevention.</p>
            </div>
            <div class="bg-green-50 rounded-xl p-6 h-64 relative border border-green-100 flex items-center justify-center">
                <div class="grid grid-cols-2 gap-4 w-full max-w-md">
                    <div class="bg-white p-4 rounded-xl shadow-sm text-center">
                        <div class="w-12 h-12 bg-green-500 rounded-lg mx-auto mb-2"></div>
                        <div class="text-xs font-bold">M-PESA</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-sm text-center">
                        <div class="w-12 h-12 bg-blue-500 rounded-lg mx-auto mb-2"></div>
                        <div class="text-xs font-bold">Debit Card</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-sm text-center">
                        <div class="w-12 h-12 bg-purple-500 rounded-lg mx-auto mb-2"></div>
                        <div class="text-xs font-bold">Credit Card</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-sm text-center">
                        <div class="w-12 h-12 bg-orange-500 rounded-lg mx-auto mb-2"></div>
                        <div class="text-xs font-bold">International</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 2: East Africa Coverage -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Serving all of East Africa</h3>
                <p class="text-gray-500 text-sm">Operating across Kenya, Rwanda, and Uganda with local payment support and customer service.</p>
            </div>
            <div class="bg-blue-50 rounded-xl h-48 relative overflow-hidden flex items-center justify-center">
                <div class="flex flex-col gap-2 p-4">
                    <span class="bg-white px-3 py-2 rounded shadow-sm text-sm font-medium">🇰🇪 Kenya</span>
                    <span class="bg-white px-3 py-2 rounded shadow-sm text-sm font-medium">🇷🇼 Rwanda</span>
                    <span class="bg-white px-3 py-2 rounded shadow-sm text-sm font-medium">🇺🇬 Uganda</span>
                </div>
            </div>
        </div>

        <!-- Card 3: Dashboard -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 relative">
                <div class="bg-white rounded-xl shadow-sm p-4 h-full w-full">
                    <div class="flex items-center justify-between mb-3">
                        <div class="h-3 w-20 bg-gray-200 rounded"></div>
                        <div class="h-6 w-16 bg-green-500 rounded text-white text-[8px] flex items-center justify-center">Live</div>
                    </div>
                    <div class="space-y-2 mt-4">
                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                        <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                        <div class="h-2 w-5/6 bg-gray-100 rounded"></div>
                    </div>
                    <div class="flex gap-2 mt-4">
                        <div class="h-12 w-1/3 bg-orange-100 rounded-lg"></div>
                        <div class="h-12 w-1/3 bg-blue-100 rounded-lg"></div>
                        <div class="h-12 w-1/3 bg-purple-100 rounded-lg"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Powerful merchant dashboard</h3>
             <p class="text-gray-500 text-sm">Monitor sales in real-time, manage promotions, track analytics, and handle settlements from one easy dashboard.</p>
        </div>

        <!-- Card 4: Multi-Channel -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-orange-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[200px]">
                    <div class="text-xs text-gray-400 mb-3 text-center">Sell everywhere</div>
                    <div class="flex flex-wrap gap-2 justify-center">
                        <span class="bg-blue-100 px-2 py-1 rounded text-[10px]">Website</span>
                        <span class="bg-green-100 px-2 py-1 rounded text-[10px]">WhatsApp</span>
                        <span class="bg-purple-100 px-2 py-1 rounded text-[10px]">Instagram</span>
                        <span class="bg-orange-100 px-2 py-1 rounded text-[10px]">App</span>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Multi-channel distribution</h3>
             <p class="text-gray-500 text-sm">Sell on your website, Mookh app, social media platforms, and more - all from one backend.</p>
        </div>

        <!-- Card 5: Go Live Fast -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-green-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="bg-white p-6 rounded-xl shadow-sm w-full max-w-[220px] text-center">
                    <div class="text-3xl font-serif font-bold text-green-600 mb-2">Minutes</div>
                    <div class="text-xs text-gray-500">to go live</div>
                    <div class="mt-4 h-8 bg-green-500 rounded-lg flex items-center justify-center text-white text-xs font-bold">
                        Start selling
                    </div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Go live in minutes</h3>
             <p class="text-gray-500 text-sm">Easy setup with no coding required. Create your store, add events or products, and start selling immediately.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-cream">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="flex items-center gap-2 font-bold text-xl opacity-80">
                Nairobi Comedy Collective
            </div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "MOOKH has been such a great help in the management of our events and shows. The support team is also highly responsive, supportive, very helpful and quite knowledgeable about their work and mine. I also like how straightforward it is to sign up and actually manage my store."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-12 h-12 rounded-full bg-gray-300"></div>
            <div class="text-left">
                <div class="font-bold text-sm">Nairobi Comedy Collective</div>
                <div class="text-xs text-gray-500">Event Organizer</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Manage your events <br /> with confidence
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden">
                <!-- Event Management Mockup -->
                <div class="flex gap-4 h-full">
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-16 bg-blue-200 rounded"></div>
                        <div class="bg-white p-2 rounded shadow-sm h-16 flex flex-col justify-center items-center">
                            <div class="text-[10px] font-bold">Concert</div>
                            <div class="text-[8px] text-gray-400">120 sold</div>
                        </div>
                        <div class="bg-white p-2 rounded shadow-sm h-16 flex flex-col justify-center items-center">
                            <div class="text-[10px] font-bold">Festival</div>
                            <div class="text-[8px] text-gray-400">85 sold</div>
                        </div>
                    </div>
                    <div class="w-2/3 bg-white/50 rounded-lg p-2">
                        <div class="h-2 w-20 bg-blue-200 rounded mb-2"></div>
                        <div class="space-y-1">
                            <div class="h-1 w-full bg-gray-200 rounded"></div>
                            <div class="h-1 w-3/4 bg-gray-200 rounded"></div>
                            <div class="h-1 w-5/6 bg-gray-200 rounded"></div>
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Manage multiple events</h3>
            <p class="text-gray-500 text-sm">Run concerts, conferences, festivals, and more from one dashboard. Track sales, manage inventory, and monitor performance in real-time.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-green-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="bg-white rounded-xl shadow-lg p-4 w-3/4">
                    <div class="flex justify-between items-center mb-4">
                        <div class="text-xs font-bold">Promo Codes</div>
                        <div class="h-6 w-16 bg-green-500 rounded text-white text-[10px] flex items-center justify-center">Create</div>
                    </div>
                    <div class="space-y-2">
                        <div class="bg-gray-50 p-2 rounded flex justify-between items-center">
                            <span class="text-[10px] font-mono">EARLY20</span>
                            <span class="text-[8px] text-green-600">20% off</span>
                        </div>
                        <div class="bg-gray-50 p-2 rounded flex justify-between items-center">
                            <span class="text-[10px] font-mono">VIP50</span>
                            <span class="text-[8px] text-green-600">50% off</span>
                        </div>
                    </div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Promotions and discounts</h3>
            <p class="text-gray-500 text-sm">Create promo codes, early bird discounts, and special offers. Allocate complimentary tickets and manage VIP access with ease.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-purple-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Analytics Mockup -->
                <div class="bg-white rounded-xl shadow-sm p-4 w-3/4">
                    <div class="text-xs font-bold mb-3">Sales Analytics</div>
                    <div class="flex items-end gap-2 h-32">
                        <div class="w-1/5 bg-purple-200 rounded-t h-[40%]"></div>
                        <div class="w-1/5 bg-purple-300 rounded-t h-[60%]"></div>
                        <div class="w-1/5 bg-purple-400 rounded-t h-[80%]"></div>
                        <div class="w-1/5 bg-purple-500 rounded-t h-[90%]"></div>
                        <div class="w-1/5 bg-purple-600 rounded-t h-full"></div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Real-time analytics</h3>
            <p class="text-gray-500 text-sm">Track ticket sales, revenue, and customer data in real-time. Get insights to optimize your events and grow your business.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-orange-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Team Management Mockup -->
                <div class="w-full max-w-sm space-y-2">
                    <div class="bg-white p-3 rounded-xl shadow-sm flex items-center gap-3">
                        <div class="w-8 h-8 bg-blue-200 rounded-full"></div>
                        <div class="flex-1">
                            <div class="text-[10px] font-bold">Admin</div>
                            <div class="text-[8px] text-gray-400">Full access</div>
                        </div>
                    </div>
                    <div class="bg-white p-3 rounded-xl shadow-sm flex items-center gap-3">
                        <div class="w-8 h-8 bg-green-200 rounded-full"></div>
                        <div class="flex-1">
                            <div class="text-[10px] font-bold">Manager</div>
                            <div class="text-[8px] text-gray-400">Event management</div>
                        </div>
                    </div>
                    <div class="bg-white p-3 rounded-xl shadow-sm flex items-center gap-3">
                        <div class="w-8 h-8 bg-purple-200 rounded-full"></div>
                        <div class="flex-1">
                            <div class="text-[10px] font-bold">Agent</div>
                            <div class="text-[8px] text-gray-400">Sales only</div>
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Team collaboration</h3>
            <p class="text-gray-500 text-sm">Assign roles to your team members - Admin, Manager, or Agent. Control access levels and collaborate seamlessly on events.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Social Proof Section -->
  <section class="py-24 bg-cream relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-green-500 rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-blue-500 rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-pink-500 rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-orange-500 rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-green-100 text-green-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Join Mookh today
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Trusted by East Africa's <br /> leading event organizers</h2>
        <p class="text-gray-500 mb-10">Only 6% commission - you keep more of your revenue</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Start selling &rarr;</Button>
            <Button href="#" type="white">See pricing</Button>
        </div>
    </div>
  </section>

  <!-- Payments & Security Section -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Secure payments & <br /> guaranteed settlements
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Post-event settlement guarantee</h3>
                <p class="text-gray-500 text-sm">We hold funds until your event concludes, then settle directly to your account. We manage all reversals, chargebacks, and disputes on your behalf.</p>
            </div>
            <div class="flex-1 bg-green-50 rounded-2xl relative overflow-hidden min-h-[300px] flex items-center justify-center">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-green-200/50 to-transparent"></div>
                <!-- Settlement Flow -->
                <div class="relative z-10 flex flex-col items-center gap-6">
                    <div class="bg-white p-4 rounded-xl shadow-lg text-center">
                        <div class="text-xs text-gray-400 mb-1">Event Date</div>
                        <div class="text-sm font-bold">Dec 25, 2024</div>
                    </div>
                    <div class="h-12 w-0.5 bg-green-300"></div>
                    <div class="bg-white p-4 rounded-xl shadow-lg text-center">
                        <div class="text-xs text-gray-400 mb-1">Settlement</div>
                        <div class="text-sm font-bold text-green-600">Dec 26, 2024</div>
                    </div>
                    <div class="h-12 w-0.5 bg-green-300"></div>
                    <div class="bg-green-500 text-white p-4 rounded-xl shadow-lg text-center font-bold">
                        KES 450,000
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="flex justify-between items-start mb-4">
                <div>
                     <h3 class="text-xl font-serif mb-2">Fraud prevention and security</h3>
                     <p class="text-gray-500 text-sm">We handle ticket security, payment processing, and fraud prevention so you can focus on creating amazing events.</p>
                </div>
                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-bold">Protected</span>
            </div>
            <div class="bg-green-50 rounded-xl h-40 flex items-center justify-center p-4">
                <div class="grid grid-cols-2 gap-3 w-full">
                    <div class="bg-white p-3 rounded-lg text-center">
                        <div class="text-2xl mb-1">🔒</div>
                        <div class="text-[10px] text-gray-500">Secure payments</div>
                    </div>
                    <div class="bg-white p-3 rounded-lg text-center">
                        <div class="text-2xl mb-1">✓</div>
                        <div class="text-[10px] text-gray-500">Verified tickets</div>
                    </div>
                    <div class="bg-white p-3 rounded-lg text-center">
                        <div class="text-2xl mb-1">🛡️</div>
                        <div class="text-[10px] text-gray-500">Fraud protection</div>
                    </div>
                    <div class="bg-white p-3 rounded-lg text-center">
                        <div class="text-2xl mb-1">💳</div>
                        <div class="text-[10px] text-gray-500">Chargeback handling</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Bottom Card (Testimonial) -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 flex gap-6 items-center">
            <div class="w-24 h-24 bg-gray-200 rounded-full flex-shrink-0 overflow-hidden">
                <!-- Placeholder for person -->
                <svg class="w-full h-full text-gray-400" fill="currentColor" viewBox="0 0 24 24"><path d="M24 24H0V0h24v24z" fill="none"/><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>
            </div>
            <div>
                <div class="text-green-600 text-4xl font-serif leading-none mb-2">"</div>
                <p class="text-sm text-gray-600 italic mb-4">Payments from MOOKH Africa are so seamless and stress free. And their customer service is easily THE best in the business. Y'all have come through so many times and have gone over and beyond for me.</p>
                <div class="text-xs font-bold">PrayzzZ</div>
                <div class="text-[10px] text-gray-400">Music Artist</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Customer Stories Grid -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Powering East Africa's most exciting events
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gradient-to-br from-pink-400 to-purple-500 rounded-2xl relative overflow-hidden group flex items-center justify-center">
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors"></div>
            <div class="relative z-10 text-white text-center p-4">
                <div class="font-bold text-lg mb-1">MUZE Club</div>
                <div class="text-xs opacity-80">Nairobi Nightlife</div>
            </div>
         </div>
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-6">
            <div class="text-center">
                <div class="text-2xl font-bold mb-2">Kenya Nights</div>
                <div class="text-xs text-gray-500">Event Series</div>
            </div>
         </div>
         <div class="col-span-2 bg-[#FFF9C4] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-yellow-600">"</div>
            <p class="text-lg font-serif leading-relaxed">Back in the day we printed tickets to our events and added ridiculous amounts of security measures on them in an attempt to stop fake tickets being distributed. We've come a long way!</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Kenya Nights</div>
                    <div class="text-gray-500">Event Organizer</div>
                </div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-gradient-to-br from-blue-400 to-cyan-500 rounded-2xl flex items-center justify-center p-8">
            <div class="text-white text-center">
                <div class="text-3xl font-bold mb-2">KODA Nairobi</div>
                <div class="text-sm opacity-90">Premium Events</div>
            </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-orange-400 to-red-500 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="relative z-10 text-white text-center p-4">
                <div class="font-bold text-lg mb-1">Unseen Nairobi</div>
                <div class="text-xs opacity-80">Cultural Events</div>
             </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-green-400 to-emerald-500 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="relative z-10 text-white text-center p-4">
                <div class="font-bold text-lg mb-1">Braeburn</div>
                <div class="text-xs opacity-80">School Events</div>
             </div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-[#E6F0FF] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-blue-600">"</div>
            <p class="text-lg font-serif leading-relaxed">MOOKH has been such a great help in the management of our events and shows. The support team is also highly responsive, supportive, very helpful and quite knowledgeable.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Nairobi Comedy Collective</div>
                    <div class="text-gray-500">Event Organizer</div>
                </div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
                <div class="text-2xl font-bold mb-2">Mt. Ololokwe Festival</div>
                <div class="text-sm text-gray-500">Conservation & Culture</div>
             </div>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-gradient-to-br from-purple-400 to-pink-500 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="relative z-10 text-white text-center p-4">
                <div class="font-bold text-lg mb-1">PrayzzZ</div>
                <div class="text-xs opacity-80">Music Artist</div>
             </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-yellow-400 to-orange-500 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="relative z-10 text-white text-center p-4">
                <div class="font-bold text-lg mb-1">Rigga</div>
                <div class="text-xs opacity-80">Hip-Hop Artist</div>
             </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
                <div class="text-2xl font-bold mb-2">SONDELA 2025</div>
                <div class="text-sm text-gray-500">Annual Festival</div>
             </div>
         </div>
      </div>
    </div>
  </section>

  <!-- Orange CTA Section -->
  <section class="bg-orange-brand py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-dark">Start selling tickets <br /> in minutes</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-dark/80">
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                No setup fees or monthly charges
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Only 6% commission per sale
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Create your store &rarr;</Button>
            <Button href="#" type="white">Contact support</Button>
        </div>
    </div>

    <!-- Bottom Illustration -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-20 pointer-events-none flex items-end justify-center overflow-hidden">
        <svg width="1200" height="100" viewBox="0 0 1200 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 100 C 50 50, 100 50, 150 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="75" cy="80" r="10" stroke="black" stroke-width="2"/>
            <path d="M150 100 C 200 60, 250 60, 300 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="225" cy="85" r="12" stroke="black" stroke-width="2"/>
            <path d="M300 100 C 350 40, 400 40, 450 100" stroke="black" stroke-width="2" fill="none"/>
             <circle cx="375" cy="70" r="15" stroke="black" stroke-width="2"/>
             <path d="M450 100 C 500 50, 550 50, 600 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M600 100 C 650 60, 700 60, 750 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M750 100 C 800 40, 850 40, 900 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M900 100 C 950 50, 1000 50, 1050 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M1050 100 C 1100 60, 1150 60, 1200 100" stroke="black" stroke-width="2" fill="none"/>
        </svg>
    </div>
  </section>

  <!-- Event Categories -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Perfect for every type of event</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-gradient-to-br from-purple-500 to-pink-500 rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1 text-white">
                <div class="text-5xl font-bold mb-4">Concerts & Music</div>
                <p class="text-lg opacity-90">From intimate gigs to massive festivals, sell tickets and merchandise for any music event.</p>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Featured Events</div>
                <div class="space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-pink-100 rounded-lg"></div>
                        <div>
                            <div class="font-bold text-sm">GHEDIBAE at MUZE</div>
                            <div class="text-xs text-gray-500">Afro Club Sounds</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-purple-100 rounded-lg"></div>
                        <div>
                            <div class="font-bold text-sm">SONDELA NAIROBI 2025</div>
                            <div class="text-xs text-gray-500">Annual Music Festival</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-gradient-to-br from-blue-400 to-cyan-500 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="text-white mb-8">
                <div class="text-3xl font-bold mb-2">Conferences</div>
                <p class="opacity-90">Professional events, business conferences, and networking sessions.</p>
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Popular for</div>
                <div class="flex flex-wrap gap-2">
                    <span class="bg-blue-100 text-blue-700 px-2 py-1 rounded text-xs">Business</span>
                    <span class="bg-blue-100 text-blue-700 px-2 py-1 rounded text-xs">Tech</span>
                    <span class="bg-blue-100 text-blue-700 px-2 py-1 rounded text-xs">Networking</span>
                </div>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-gradient-to-br from-orange-400 to-red-500 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="text-white mb-8">
                <div class="text-3xl font-bold mb-2">Cultural & Sports</div>
                <p class="opacity-90">Festivals, theater, sports tournaments, and cultural celebrations.</p>
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Event Types</div>
                <div class="flex flex-wrap gap-2">
                    <span class="bg-orange-100 text-orange-700 px-2 py-1 rounded text-xs">Festivals</span>
                    <span class="bg-orange-100 text-orange-700 px-2 py-1 rounded text-xs">Theater</span>
                    <span class="bg-orange-100 text-orange-700 px-2 py-1 rounded text-xs">Sports</span>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently asked questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is Mookh?",
            "What payment methods do you support?",
            "How much does Mookh cost?",
            "When do I receive my money?",
            "Can I sell in multiple countries?",
            "How does M-PESA integration work?",
            "Can I customize my online store?",
            "How do I get started with Mookh?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-orange-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-orange-brand transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>

