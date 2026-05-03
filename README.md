# Spice-aura
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="SpiceAura Kitchen - Premium Indian modern dining experience with curated menu, elegant ambience, and easy reservations." />
  <meta name="keywords" content="SpiceAura Kitchen, Indian restaurant, fine dining, reservations, menu" />
  <meta name="author" content="SpiceAura Kitchen" />
  <meta property="og:title" content="SpiceAura Kitchen | Premium Indian Modern Dining" />
  <meta property="og:description" content="Discover a premium Indian modern dining experience with handcrafted dishes, elegant ambience, and quick table booking." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://spiceaura-kitchen.vercel.app" />
  <title>SpiceAura Kitchen</title>

  <link rel="icon" type="image/svg+xml" href="public/favicon.svg" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            charcoal: '#0e0e0e',
            gold: '#d4af37',
            goldsoft: '#f3d98a'
          },
          fontFamily: {
            elegant: ['"Playfair Display"', 'serif'],
            clean: ['Inter', 'sans-serif']
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="components/chatbot.css" />
</head>
<body class="bg-charcoal text-white font-clean antialiased">
  <div id="navbar-placeholder"></div>

  <main>
    <section id="home" class="relative min-h-screen flex items-center justify-center px-6">
      <div class="absolute inset-0 bg-black/70 z-10"></div>
      <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=1920&q=80" alt="Restaurant interior" class="absolute inset-0 w-full h-full object-cover" />
      <div class="relative z-20 text-center max-w-3xl fade-up">
        <p class="uppercase tracking-[0.3em] text-gold text-sm mb-4">SpiceAura Kitchen</p>
        <h1 class="font-elegant text-4xl md:text-6xl mb-5 leading-tight">Where Heritage Spices Meet Modern Elegance</h1>
        <p class="text-gray-200 mb-8">A premium Indian modern dining destination crafted for unforgettable flavors and soulful moments.</p>
        <div class="flex flex-wrap justify-center gap-4">
          <a href="#menu" class="btn-gold">Order Now</a>
          <a href="#reservation" class="btn-outline">Book Table</a>
        </div>
      </div>
    </section>

    <section id="menu" class="py-20 px-6 max-w-7xl mx-auto">
      <h2 class="section-title">Signature Menu</h2>
      <p class="section-subtitle">Curated dishes from our chef's kitchen.</p>
      <div class="grid md:grid-cols-2 gap-10">
        <div>
          <h3 class="menu-heading">Starters</h3>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1571197119738-26123cb81845?auto=format&fit=crop&w=600&q=80" alt="Paneer Tikka"><div><h4>Smoked Paneer Tikka <span>₹420</span></h4><p>Chargrilled cottage cheese with saffron yogurt glaze.</p></div></div>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1604152135912-04a022e23696?auto=format&fit=crop&w=600&q=80" alt="Prawns"><div><h4>Coastal Chili Prawns <span>₹560</span></h4><p>Pan-seared prawns with curry leaf and chili tempering.</p></div></div>

          <h3 class="menu-heading mt-10">Main Course</h3>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1666190092159-3171cf0fbb12?auto=format&fit=crop&w=600&q=80" alt="Butter Chicken"><div><h4>Royal Butter Chicken <span>₹690</span></h4><p>Silky tomato fenugreek gravy with tender chicken morsels.</p></div></div>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1567188040759-fb8a883dc6d8?auto=format&fit=crop&w=600&q=80" alt="Biryani"><div><h4>Nawabi Dum Biryani <span>₹740</span></h4><p>Fragrant basmati layered with aromatic spices and herbs.</p></div></div>
        </div>
        <div>
          <h3 class="menu-heading">Desserts</h3>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1488477181946-6428a0291777?auto=format&fit=crop&w=600&q=80" alt="Kulfi"><div><h4>Pistachio Kulfi Crumble <span>₹290</span></h4><p>Frozen reduced milk delight with roasted nuts.</p></div></div>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1481391032119-d89fee407e44?auto=format&fit=crop&w=600&q=80" alt="Gulab Jamun"><div><h4>Rose Gulab Jamun <span>₹260</span></h4><p>Soft dumplings soaked in rose-cardamom syrup.</p></div></div>

          <h3 class="menu-heading mt-10">Drinks</h3>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1556881286-fc6915169721?auto=format&fit=crop&w=600&q=80" alt="Mojito"><div><h4>Saffron Citrus Cooler <span>₹220</span></h4><p>Fresh citrus, saffron, mint and sparkling finish.</p></div></div>
          <div class="menu-card"><img src="https://images.unsplash.com/photo-1515823662972-da6a2e4d3002?auto=format&fit=crop&w=600&q=80" alt="Masala chai"><div><h4>Signature Masala Chai <span>₹160</span></h4><p>Hand-brewed tea with house spice blend.</p></div></div>
        </div>
      </div>
    </section>

    <section id="gallery" class="py-20 px-6 bg-[#151515]">
      <div class="max-w-7xl mx-auto">
        <h2 class="section-title">Food Gallery</h2>
        <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-4 mt-10">
          <img class="gallery-img" src="https://images.unsplash.com/photo-1512058564366-18510be2db19?auto=format&fit=crop&w=500&q=80" alt="Indian platter">
          <img class="gallery-img" src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7?auto=format&fit=crop&w=500&q=80" alt="Curry bowl">
          <img class="gallery-img" src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?auto=format&fit=crop&w=500&q=80" alt="Fine dining dish">
          <img class="gallery-img" src="https://images.unsplash.com/photo-1505253716362-afaea6d3d1af?auto=format&fit=crop&w=500&q=80" alt="Dessert plate">
        </div>
      </div>
    </section>

    <section id="about" class="py-20 px-6 max-w-6xl mx-auto">
      <h2 class="section-title">About Us</h2>
      <div class="grid md:grid-cols-2 gap-10 items-center">
        <div>
          <p class="mb-4 text-gray-200">SpiceAura Kitchen began with a dream to reinterpret Indian classics through modern culinary artistry. Every plate reflects regional authenticity elevated with premium ingredients and contemporary techniques.</p>
          <p class="mb-4 text-gray-200"><strong class="text-gold">Mission:</strong> To offer an immersive dining journey rooted in hospitality, culture, and excellence.</p>
          <p class="text-gray-200"><strong class="text-gold">Chef Aarav Malhotra:</strong> Trained in Mumbai and London, Chef Aarav blends traditional spice wisdom with modern plating to create bold, balanced flavors.</p>
        </div>
        <img src="https://images.unsplash.com/photo-1600891963935-c1a09f4c17d6?auto=format&fit=crop&w=900&q=80" alt="Chef preparing food" class="rounded-xl shadow-2xl" />
      </div>
    </section>

    <section id="testimonials" class="py-20 px-6 bg-[#151515]">
      <div class="max-w-6xl mx-auto">
        <h2 class="section-title">Guest Testimonials</h2>
        <div class="grid md:grid-cols-3 gap-6 mt-10">
          <div class="testimonial-card"><p>“An extraordinary dining experience! Every bite felt curated and luxurious.”</p><h4>— Priya S.</h4></div>
          <div class="testimonial-card"><p>“The ambiance is elegant, and the biryani is hands down the best in town.”</p><h4>— Daniel R.</h4></div>
          <div class="testimonial-card"><p>“Exceptional service and incredible flavors. Perfect spot for date nights.”</p><h4>— Meera K.</h4></div>
        </div>
      </div>
    </section>

    <section id="reservation" class="py-20 px-6 max-w-5xl mx-auto">
      <h2 class="section-title">Reserve Your Table</h2>
      <form class="grid md:grid-cols-3 gap-4 mt-10" id="reservationForm">
        <input class="form-input" type="date" required>
        <input class="form-input" type="time" required>
        <input class="form-input" type="number" min="1" max="20" placeholder="No. of People" required>
        <button class="btn-gold md:col-span-3" type="submit">Book Table</button>
      </form>
    </section>

    <section id="contact" class="py-20 px-6 bg-[#151515]">
      <div class="max-w-6xl mx-auto">
        <h2 class="section-title">Contact Us</h2>
        <div class="grid md:grid-cols-2 gap-8 mt-10">
          <form class="space-y-4" id="contactForm">
            <input class="form-input" type="text" placeholder="Your Name" required>
            <input class="form-input" type="email" placeholder="Email Address" required>
            <textarea class="form-input" rows="5" placeholder="Message" required></textarea>
            <button class="btn-gold" type="submit">Send Message</button>
          </form>
          <iframe class="w-full min-h-[320px] rounded-xl border border-gold/30" loading="lazy" allowfullscreen src="https://maps.google.com/maps?q=Connaught%20Place%20New%20Delhi&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>
        </div>
      </div>
    </section>
  </main>

  <div id="footer-placeholder"></div>
  <div id="chatbot-placeholder"></div>

  <script src="script.js"></script>
  <script src="components/chatbot.js"></script>
</body>
</html>
