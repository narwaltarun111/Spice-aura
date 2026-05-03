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
html { scroll-behavior: smooth; }
body { overflow-x: hidden; }

.section-title {
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  color: #d4af37;
  text-align: center;
  margin-bottom: .75rem;
}
@media (min-width: 768px) {
  .section-title { font-size: 2.25rem; }
}
.section-subtitle {
  text-align: center;
  color: #d1d5db;
  margin-bottom: 3rem;
}

.btn-gold {
  display: inline-block;
  background: #d4af37;
  color: #000;
  font-weight: 600;
  padding: .75rem 1.5rem;
  border-radius: 999px;
  transition: .25s;
}
.btn-gold:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 30px rgba(212,175,55,.3);
}
.btn-outline {
  display: inline-block;
  border: 1px solid #d4af37;
  color: #d4af37;
  padding: .75rem 1.5rem;
  border-radius: 999px;
  transition: .25s;
}
.btn-outline:hover {
  background: #d4af37;
  color: #000;
}

.menu-heading {
  font-family: 'Playfair Display', serif;
  font-size: 1.6rem;
  color: #d4af37;
  margin-bottom: 1rem;
}
.menu-card {
  display: flex;
  gap: 1rem;
  align-items: center;
  background: #1c1c1c;
  padding: .75rem;
  border-radius: .5rem;
  margin-bottom: 1rem;
  transition: .25s;
}
.menu-card:hover { transform: translateX(4px); }
.menu-card img {
  width: 80px;
  height: 80px;
  object-fit: cover;
  border-radius: .5rem;
}
.menu-card h4 {
  font-weight: 600;
  font-size: 1.08rem;
  margin-bottom: .25rem;
  display: flex;
  justify-content: space-between;
  gap: .5rem;
}
.menu-card p {
  font-size: .9rem;
  color: #d1d5db;
}

.gallery-img {
  width: 100%;
  height: 13rem;
  object-fit: cover;
  border-radius: .5rem;
  transition: .5s;
}
.gallery-img:hover { transform: scale(1.05); }

.testimonial-card {
  background: #1e1e1e;
  padding: 1.5rem;
  border-radius: .5rem;
  border: 1px solid rgba(212,175,55,.2);
}
.testimonial-card p { color: #e5e7eb; margin-bottom: 1rem; }
.testimonial-card h4 { color: #d4af37; }

.form-input {
  width: 100%;
  background: #222;
  border: 1px solid rgba(212,175,55,.3);
  border-radius: .375rem;
  padding: .75rem 1rem;
  color: #fff;
}
.form-input:focus {
  outline: none;
  box-shadow: 0 0 0 2px #d4af37;
}

.fade-up { animation: fadeUp 1s ease both; }
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(24px); }
  to { opacity: 1; transform: translateY(0); }
}
const navbarPlaceholder = document.getElementById('navbar-placeholder');
const footerPlaceholder = document.getElementById('footer-placeholder');

navbarPlaceholder.innerHTML = `
<header class="fixed top-0 left-0 right-0 z-50 bg-black/70 backdrop-blur border-b border-gold/20">
  <nav class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
    <a href="#home" class="font-elegant text-2xl text-gold">SpiceAura</a>
    <button id="menuToggle" class="md:hidden text-gold text-2xl">☰</button>
    <ul id="navLinks" class="hidden md:flex gap-6 text-sm uppercase tracking-wide">
      <li><a href="#home" class="hover:text-gold">Home</a></li>
      <li><a href="#menu" class="hover:text-gold">Menu</a></li>
      <li><a href="#about" class="hover:text-gold">About</a></li>
      <li><a href="#reservation" class="hover:text-gold">Reservation</a></li>
      <li><a href="#contact" class="hover:text-gold">Contact</a></li>
    </ul>
  </nav>
  <ul id="mobileNav" class="hidden md:hidden px-6 pb-4 space-y-2 bg-black/90">
    <li><a href="#home">Home</a></li>
    <li><a href="#menu">Menu</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#reservation">Reservation</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</header>`;

footerPlaceholder.innerHTML = `
<footer class="py-8 text-center border-t border-gold/20 bg-black">
  <p class="text-sm text-gray-300">© 2026 SpiceAura Kitchen. Crafted with flavor and elegance.</p>
</footer>`;

document.addEventListener('click', (e) => {
  if (e.target.id === 'menuToggle') {
    document.getElementById('mobileNav').classList.toggle('hidden');
  }
});

document.getElementById('reservationForm').addEventListener('submit', (e) => {
  e.preventDefault();
  alert('Thank you! Your table request has been received.');
});

document.getElementById('contactForm').addEventListener('submit', (e) => {
  e.preventDefault();
  alert('Message sent successfully. We will contact you shortly.');
});
<div id="aura-chatbot" class="aura-chatbot">
  <button id="aura-toggle" class="aura-toggle" aria-label="Open AURA chatbot">💬</button>
  <div id="aura-window" class="aura-window hidden">
    <div class="aura-header">AURA Assistant</div>
    <div id="aura-messages" class="aura-messages"></div>
    <div class="aura-input-row">
      <input id="aura-input" type="text" placeholder="Ask about menu, timings, location..." />
      <button id="aura-send">Send</button>
    </div>
  </div>
</div>
.aura-chatbot {
  position: fixed;
  right: 1.25rem;
  bottom: 1.25rem;
  z-index: 100;
}
.aura-toggle {
  background: #d4af37;
  color: #000;
  border: none;
  width: 56px;
  height: 56px;
  border-radius: 50%;
  cursor: pointer;
  font-size: 1.5rem;
  box-shadow: 0 10px 25px rgba(212,175,55,.35);
}
.aura-window {
  width: 320px;
  background: #131313;
  border: 1px solid rgba(212,175,55,.35);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 14px 36px rgba(0,0,0,.45);
  margin-bottom: .75rem;
}
.aura-header {
  background: #d4af37;
  color: #111;
  padding: .7rem 1rem;
  font-weight: 700;
}
.aura-messages {
  height: 260px;
  overflow: auto;
  padding: .8rem;
  color: #e5e5e5;
  font-size: .9rem;
}
.aura-msg {
  margin-bottom: .7rem;
  padding: .55rem .65rem;
  border-radius: 8px;
  max-width: 85%;
}
.aura-user {
  background: #2b2b2b;
  margin-left: auto;
}
.aura-bot {
  background: #1e1e1e;
  border: 1px solid rgba(212,175,55,.2);
}
.aura-input-row {
  display: flex;
  border-top: 1px solid #2a2a2a;
}
#aura-input {
  flex: 1;
  background: #101010;
  color: white;
  border: none;
  padding: .75rem;
}
#aura-send {
  background: #d4af37;
  color: black;
  border: none;
  padding: 0 1rem;
  font-weight: 600;
}
.hidden { display: none; }
(async function initAura() {
  const host = document.getElementById('chatbot-placeholder');
  const html = await fetch('components/chatbot.html').then(r => r.text());
  host.innerHTML = html;

  const toggle = document.getElementById('aura-toggle');
  const win = document.getElementById('aura-window');
  const input = document.getElementById('aura-input');
  const sendBtn = document.getElementById('aura-send');
  const messages = document.getElementById('aura-messages');

  const botReplies = {
    menu: 'We offer Starters, Main Course, Desserts, and Drinks. Try our Royal Butter Chicken and Nawabi Dum Biryani!',
    hours: 'We are open daily from 12:00 PM to 11:00 PM.',
    reservation: 'You can reserve a table in the Reservation section. Share your preferred date, time, and guest count.',
    location: 'We are located near Connaught Place, New Delhi. Check the map in the Contact section.'
  };

  function addMessage(text, type = 'bot') {
    const div = document.createElement('div');
    div.className = `aura-msg ${type === 'user' ? 'aura-user' : 'aura-bot'}`;
    div.textContent = text;
    messages.appendChild(div);
    messages.scrollTop = messages.scrollHeight;
  }

  function getReply(q) {
    const query = q.toLowerCase();
    if (/(menu|dish|food|eat|starter|dessert|drink)/.test(query)) return botReplies.menu;
    if (/(time|hour|open|close|timing)/.test(query)) return botReplies.hours;
    if (/(reserve|reservation|book|table)/.test(query)) return botReplies.reservation;
    if (/(where|location|address|map)/.test(query)) return botReplies.location;
    return 'I can help with menu, timings, reservations, and location. Please ask one of these!';
  }

  function sendMessage() {
    const text = input.value.trim();
    if (!text) return;
    addMessage(text, 'user');
    input.value = '';
    setTimeout(() => addMessage(getReply(text), 'bot'), 300);
  }

  toggle.addEventListener('click', () => win.classList.toggle('hidden'));
  sendBtn.addEventListener('click', sendMessage);
  input.addEventListener('keydown', (e) => e.key === 'Enter' && sendMessage());

  addMessage('Namaste! I’m AURA. Ask me about menu, opening hours, reservation help, or location.');
})();
<header class="fixed top-0 left-0 right-0 z-50 bg-black/70 backdrop-blur border-b border-gold/20">
  <!-- Navbar is injected dynamically from script.js for easier mobile interaction -->
</header>
<footer class="py-8 text-center border-t border-gold/20 bg-black">
  <p class="text-sm text-gray-300">© 2026 SpiceAura Kitchen. Crafted with flavor and elegance.</p>
</footer>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64">
  <rect width="64" height="64" rx="10" fill="#0e0e0e"/>
  <path d="M32 12c8 7 13 14 13 22 0 8-6 14-13 14s-13-6-13-14c0-8 5-15 13-22z" fill="#d4af37"/>
  <circle cx="32" cy="34" r="6" fill="#0e0e0e"/>
</svg>
{
  "cleanUrls": true
}
