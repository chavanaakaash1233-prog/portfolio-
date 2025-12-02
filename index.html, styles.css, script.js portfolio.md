# portfolio-
new  portfolio   01 
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Comment: This is your single-page portfolio site. To customize:
     - Replace placeholders (e.g., 'Your Name', bio text, image srcs) with your own.
     - Add real project images to an 'images/' folder and update paths.
     - For dark mode toggle: Click the sun/moon icon in header.
     - Deploy: Upload to Netlify (drag folder) or GitHub Pages for free hosting.
     - Preview: Open this file in any browser. Test mobile by resizing window.
     -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Freelance web developer crafting standout websites for small businesses and coaches. Affordable, responsive designs from $299.">
    <title>Your Name - Freelance Web Developer</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <nav class="nav">
            <div class="nav-brand">Your Name</div>
            <ul class="nav-menu">
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <button id="theme-toggle" class="theme-toggle" aria-label="Toggle dark mode">🌙</button>
        </nav>
    </header>

    <section id="hero" class="hero">
        <div class="hero-content">
            <h1 class="hero-title">I craft standout websites that turn visitors into customers</h1>
            <p class="hero-subtitle">Helping small businesses and coaches build affordable, high-converting sites from $299. Let's make your online presence unforgettable.</p>
            <a href="#contact" class="cta-button">Get Started Free Consult</a>
        </div>
        <div class="hero-scroll">↓</div>
    </section>

    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-grid">
                <div class="about-image">
                    <img src="https://via.placeholder.com/400x400/1E3A8A/white?text=Your+Photo" alt="Your professional photo" loading="lazy">
                </div>
                <div class="about-text">
                    <p>Hey, I'm a passionate web developer who started freelancing in 2025. With a focus on clean, responsive designs, I help small business owners and coaches get online fast—without the tech headaches.</p>
                    <p>Skills: HTML/CSS/JS, Responsive Design, SEO Basics. I've delivered 5+ projects already, and I'm all about results that grow your business.</p>
                    <div class="skills">
                        <span class="skill-tag">HTML/CSS</span>
                        <span class="skill-tag">JavaScript</span>
                        <span class="skill-tag">Responsive UI</span>
                        <span class="skill-tag">SEO</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="section">
        <div class="container">
            <h2 class="section-title">Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">🎨</div>
                    <h3>Basic Website</h3>
                    <p>Clean, single-page site with contact form and mobile optimization.</p>
                    <div class="price">$299</div>
                </div>
                <div class="service-card">
                    <div class="service-icon">🚀</div>
                    <h3>Pro Website</h3>
                    <p>Multi-page with custom design, animations, and basic SEO.</p>
                    <div class="price">$599</div>
                </div>
                <div class="service-card">
                    <div class="service-icon">⭐</div>
                    <h3>Premium Package</h3>
                    <p>Full site + e-commerce setup, ongoing support, and performance tweaks.</p>
                    <div class="price">$999</div>
                </div>
            </div>
        </div>
    </section>

    <section id="portfolio" class="section">
        <div class="container">
            <h2 class="section-title">Portfolio</h2>
            <div class="portfolio-grid">
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250/7C3AED/white?text=Project+1" alt="Project 1: Local Bakery Redesign" loading="lazy">
                    <div class="project-overlay">
                        <h3>Local Bakery Site</h3>
                        <p>Redesigned for better mobile sales—boosted inquiries by 40%.</p>
                        <a href="#" class="project-link">View Case Study</a>
                    </div>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250/F59E0B/white?text=Project+2" alt="Project 2: Coach Landing Page" loading="lazy">
                    <div class="project-overlay">
                        <h3>Coach Landing Page</h3>
                        <p>Conversion-focused design with Calendly integration.</p>
                        <a href="#" class="project-link">View Case Study</a>
                    </div>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250/1E3A8A/white?text=Project+3" alt="Project 3: E-commerce Starter" loading="lazy">
                    <div class="project-overlay">
                        <h3>E-commerce Starter</h3>
                        <p>Shopify-like setup for small brands—easy to scale.</p>
                        <a href="#" class="project-link">View Case Study</a>
                    </div>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/400x250/7C3AED/white?text=Project+4" alt="Project 4: Personal Brand Site" loading="lazy">
                    <div class="project-overlay">
                        <h3>Personal Brand Site</h3>
                        <p>Minimalist portfolio that highlights storytelling.</p>
                        <a href="#" class="project-link">View Case Study</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2 class="section-title">Let's Work Together</h2>
            <p class="section-subtitle">Available for new projects. Book a free 15-min call to discuss your vision.</p>
            <form class="contact-form" id="contact-form">
                <input type="text" placeholder="Your Name" required aria-label="Name">
                <input type="email" placeholder="Your Email" required aria-label="Email">
                <textarea placeholder="Tell me about your project..." rows="5" required aria-label="Message"></textarea>
                <button type="submit" class="cta-button">Send Message</button>
            </form>
            <div class="contact-links">
                <a href="mailto:your.email@example.com" class="contact-link">📧 Email</a>
                <a href="https://wa.me/1234567890" class="contact-link">💬 WhatsApp</a>
                <a href="https://calendly.com/yourcalendly/15min" class="contact-link">📅 Book Call</a>
            </div>
        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2025 Your Name. Built with ❤️ for the web.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* styles.css - Customizable: Edit CSS variables at top for quick theme changes.
   - Colors: Update --primary, --accent, etc.
   - Fonts: Sizes via rem units—scale globally by changing root font-size.
   - Animations: All subtle CSS-only where possible; JS enhances scroll reveals.
   - Responsive: Mobile-first media queries below.
   - Dark Mode: Toggles body class; overrides defined in :root(.dark).
*/

/* CSS Custom Properties (Variables) */
:root {
    --bg-primary: #F8FAFC; /* Soft gray bg */
    --bg-secondary: #FFFFFF;
    --text-primary: #0F172A; /* Dark text */
    --text-secondary: #475569;
    --primary: #1E3A8A; /* Deep indigo */
    --secondary: #7C3AED; /* Purple */
    --accent: #F59E0B; /* Warm gold */
    --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --border-radius: 8px;
    --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); /* Smooth ease */
    font-family: 'Inter', sans-serif;
    font-weight: 400;
    font-size: 1rem;
    line-height: 1.6;
    color: var(--text-primary);
    background-color: var(--bg-primary);
}

:root.dark {
    --bg-primary: #0F172A;
    --bg-secondary: #1E293B;
    --text-primary: #F8FAFC;
    --text-secondary: #CBD5E1;
}

/* Global Styles */
* { box-sizing: border-box; margin: 0; padding: 0; }
body { scroll-behavior: smooth; overflow-x: hidden; }
.container { max-width: 1200px; margin: 0 auto; padding: 0 1rem; }
.section { padding: 4rem 0; }
.section-title { font-size: clamp(2rem, 5vw, 3rem); font-weight: 700; text-align: center; margin-bottom: 2rem; letter-spacing: -0.025em; }
.section-subtitle { text-align: center; max-width: 600px; margin: 0 auto 2rem; font-size: 1.1rem; }

/* Header & Nav */
.header { position: sticky; top: 0; background: var(--bg-secondary); backdrop-filter: blur(10px); z-index: 100; border-bottom: 1px solid rgba(0,0,0,0.05); }
.nav { display: flex; justify-content: space-between; align-items: center; padding: 1rem 2rem; max-width: 1200px; margin: 0 auto; }
.nav-brand { font-size: 1.5rem; font-weight: 700; color: var(--primary); }
.nav-menu { display: flex; list-style: none; gap: 2rem; }
.nav-menu a { text-decoration: none; color: var(--text-primary); font-weight: 500; transition: var(--transition); }
.nav-menu a:hover { color: var(--accent); }
.theme-toggle { background: none; border: none; font-size: 1.5rem; cursor: pointer; transition: var(--transition); }
@media (max-width: 768px) { .nav-menu { display: none; } /* Add mobile menu JS if needed */ }

/* Hero */
.hero { min-height: 100vh; display: flex; align-items: center; justify-content: center; background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%); color: white; text-align: center; position: relative; }
.hero-content { max-width: 800px; padding: 0 2rem; }
.hero-title { font-size: clamp(2.5rem, 6vw, 4rem); font-weight: 700; margin-bottom: 1rem; }
.hero-subtitle { font-size: 1.25rem; margin-bottom: 2rem; opacity: 0.95; }
.cta-button { display: inline-block; background: var(--accent); color: var(--text-primary); padding: 1rem 2rem; border-radius: var(--border-radius); text-decoration: none; font-weight: 600; transition: var(--transition); box-shadow: var(--shadow); }
.cta-button:hover { transform: translateY(-2px); box-shadow: 0 8px 15px rgba(245, 158, 11, 0.3); }
.hero-scroll { position: absolute; bottom: 2rem; left: 50%; transform: translateX(-50%); animation: bounce 2s infinite; font-size: 2rem; opacity: 0.7; }
@keyframes bounce { 0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); } 40% { transform: translateX(-50%) translateY(-10px); } 60% { transform: translateX(-50%) translateY(-5px); } }

/* About */
.about-grid { display: grid; grid-template-columns: 1fr 2fr; gap: 3rem; align-items: center; }
.about-image img { width: 100%; border-radius: var(--border-radius); box-shadow: var(--shadow); }
.about-text p { margin-bottom: 1rem; font-size: 1.1rem; }
.skills { display: flex; flex-wrap: wrap; gap: 0.5rem; margin-top: 1rem; }
.skill-tag { background: var(--primary); color: white; padding: 0.5rem 1rem; border-radius: 20px; font-size: 0.9rem; font-weight: 500; }

/* Services */
.services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
.service-card { background: var(--bg-secondary); padding: 2rem; border-radius: var(--border-radius); text-align: center; box-shadow: var(--shadow); transition: var(--transition); position: relative; overflow: hidden; }
.service-card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 4px; background: linear-gradient(90deg, var(--primary), var(--secondary)); }
.service-card:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.15); }
.service-icon { font-size: 3rem; margin-bottom: 1rem; }
.service-card h3 { font-size: 1.5rem; margin-bottom: 1rem; }
.price { font-size: 2rem; font-weight: 700; color: var(--accent); margin-top: 1rem; }

/* Portfolio */
.portfolio-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
.project-card { position: relative; border-radius: var(--border-radius); overflow: hidden; box-shadow: var(--shadow); transition: var(--transition); }
.project-card img { width: 100%; height: 250px; object-fit: cover; }
.project-overlay { position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 2rem; transform: translateY(100%); transition: var(--transition); }
.project-card:hover .project-overlay { transform: translateY(0); }
.project-overlay h3 { font-size: 1.25rem; margin-bottom: 0.5rem; }
.project-link { color: var(--accent); text-decoration: none; font-weight: 500; }

/* Contact */
.contact-form { max-width: 600px; margin: 0 auto 2rem; display: grid; gap: 1rem; }
.contact-form input, .contact-form textarea { padding: 1rem; border: 1px solid var(--text-secondary); border-radius: var(--border-radius); font-family: inherit; font-size: 1rem; transition: var(--transition); background: var(--bg-secondary); color: var(--text-primary); }
.contact-form input:focus, .contact-form textarea:focus { outline: none; border-color: var(--accent); box-shadow: 0 0 0 3px rgba(245, 158, 11, 0.1); }
.contact-links { display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; }
.contact-link { color: var(--primary); text-decoration: none; font-size: 1.1rem; transition: var(--transition); }
.contact-link:hover { color: var(--accent); transform: scale(1.1); }

/* Footer */
.footer { background: var(--bg-secondary); text-align: center; padding: 2rem; border-top: 1px solid rgba(0,0,0,0.05); }

/* Animations: Subtle fade-in on scroll (JS triggers 'animate' class) */
@keyframes fadeInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
.animate { animation: fadeInUp 0.6s ease-out forwards; }

/* Hover Effects */
.service-card:hover .service-icon, .cta-button:hover, .project-card:hover { transform: scale(1.02); } /* Gentle scale */

/* Responsive */
@media (max-width: 768px) {
    .about-grid { grid-template-columns: 1fr; text-align: center; }
    .nav { padding: 1rem; }
    .hero { padding: 2rem 0; min-height: auto; }
    .services-grid, .portfolio-grid { grid-template-columns: 1fr; }
    .contact-links { flex-direction: column; align-items: center; gap: 1rem; }
}

/* Accessibility: High contrast, focus styles */
@media (prefers-reduced-motion: reduce) { * { animation-duration: 0.01ms !important; transition: none !important; } }
a:focus, button:focus { outline: 2px solid var(--accent); outline-offset: 2px; }
// script.js - Handles: Dark mode toggle, scroll animations, form submission.
// Customizable: Update email/WhatsApp links, add real Calendly embed.
// No external libs—vanilla JS for lightweight (under 5KB).

// Dark Mode Toggle
const themeToggle = document.getElementById('theme-toggle');
const body = document.body;
themeToggle.addEventListener('click', () => {
    body.classList.toggle('dark');
    themeToggle.textContent = body.classList.contains('dark') ? '☀️' : '🌙';
    localStorage.setItem('theme', body.classList.contains('dark') ? 'dark' : 'light');
});

// Load saved theme
const savedTheme = localStorage.getItem('theme') || 'light';
if (savedTheme === 'dark') {
    body.classList.add('dark');
    themeToggle.textContent = '☀️';
}

// Smooth Scroll Animations (Subtle fade-in)
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('animate');
        }
    });
}, observerOptions);

// Observe sections for fade-in
document.querySelectorAll('.section, .service-card, .project-card').forEach(el => {
    observer.observe(el);
});

// Contact Form Submission (Simulate send; replace with real backend like Formspree)
const form = document.getElementById('contact-form');
form.addEventListener('submit', (e) => {
    e.preventDefault();
    // Basic validation already via HTML required
    alert('Thanks! Your message is on its way. (In production, integrate with EmailJS or similar.)');
    form.reset();
});

// Nav Links Smooth Scroll
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', (e) => {
        e.preventDefault();
        const target = document.querySelector(anchor.getAttribute('href'));
        if (target) {
            target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
    });
});

// Mobile Nav (If needed—expand for hamburger menu)
if (window.innerWidth <= 768) {
    // Add hamburger logic here if desired
}

// Performance: Lazy load images already in HTML
console.log('Portfolio loaded! Ready for clients 🚀');
