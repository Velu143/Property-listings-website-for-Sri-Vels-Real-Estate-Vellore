<!DOCTYPE html>
<html lang="ta">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SRI VEL'S REAL ESTATE | வேலூர் சொத்துக்கள்</title>
    <meta name="description" content="SRI VEL'S REAL ESTATE - Adukkamparai, Vellore. வீடுகள், ப்ளோட்டுகள், அடுக்குமாடி வீடுகள்">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Latha', 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .nav-links {
            list-style: none;
            display: flex;
            gap: 2rem;
            flex-wrap: wrap;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #f39c12;
        }
        
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1560518883-ce09059eeffa?ixlib=rb-4.0.3');
            background-size: cover;
            background-position: center;
            height: 550px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 2rem;
        }
        
        .hero h1 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .hero h2 {
            font-size: 1.4rem;
            margin-bottom: 1.5rem;
            font-weight: 400;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .btn {
            background: #e74c3c;
            color: white;
            padding: 1rem 2.5rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: transform 0.3s, box-shadow 0.3s;
            font-weight: bold;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(231, 76, 60, 0.4);
        }
        
        .btn-secondary {
            background: transparent;
            border: 2px solid white;
            margin-left: 1rem;
        }
        
        .btn-secondary:hover {
            background: white;
            color: #2c3e50;
        }
        
        .btn-whatsapp {
            background: #25D366;
            margin-top: 1rem;
            display: inline-block;
            text-align: center;
            width: 100%;
        }
        
        .btn-whatsapp:hover {
            background: #128C7E;
        }
        
        .services {
            padding: 3rem 0;
            background: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: #2c3e50;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .service-card {
            text-align: center;
            padding: 2rem;
            background: #f8f9fa;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .service-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        
        .service-card h3 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
        }
        
        .about {
            padding: 3rem 0;
            background: #f8f9fa;
        }
        
        .about-content {
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .about-content h3 {
            color: #2c3e50;
            margin-bottom: 1rem;
            font-size: 1.8rem;
        }
        
        .about-content p {
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: #e74c3c;
        }
        
        .stat-label {
            color: #666;
            font-size: 0.95rem;
        }
        
        .properties {
            padding: 3rem 0;
            background: #f8f9fa;
        }
        
        .property-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .property-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .property-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }
        
        .property-image {
            height: 220px;
            position: relative;
        }
        
        .property-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .property-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background: #e74c3c;
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: bold;
        }
        
        .property-info {
            padding: 1.5rem;
        }
        
        .property-type {
            color: #3498db;
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .property-title {
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: #343a40;
        }
        
        .property-price {
            color: #e74c3c;
            font-size: 1.5rem;
            font-weight: bold;
            margin: 1rem 0;
        }
        
        .property-location {
            color: #7f8c8d;
            font-size: 0.95rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.3rem;
        }
        
        .property-features {
            display: flex;
            gap: 1.5rem;
            padding: 1rem 0;
            border-top: 1px solid #eee;
            margin-top: 1rem;
            flex-wrap: wrap;
        }
        
        .property-features span {
            font-size: 0.9rem;
            color: #555;
        }
        
        .contact {
            padding: 3rem 0;
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
        }
        
        .contact .section-title h2 {
            color: white;
        }
        
        .contact-info {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }
        
        .phone-number {
            font-size: 1.4rem;
            font-weight: bold;
            margin: 0.5rem 0;
            color: #fff;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            color: #333;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
            color: #2c3e50;
        }
        
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            font-family: inherit;
        }
        
        .form-group textarea {
            resize: vertical;
            min-height: 100px;
        }
        
        .map-container {
            max-width: 600px;
            margin: 2rem auto 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.2);
        }
        
        .map-container iframe {
            width: 100%;
            height: 350px;
            border: none;
        }
        
        footer {
            background: #2c3e50;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        footer p {
            margin: 0.3rem 0;
        }
        
        @media (max-width: 768px) {
            .nav-links {
                flex-direction: column;
                gap: 1rem;
                text-align: center;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero h2 {
                font-size: 1.1rem;
            }
            
            .property-grid {
                grid-template-columns: 1fr;
            }
            
            .services-grid {
                grid-template-columns: 1fr;
            }
            
            .btn-secondary {
                margin-left: 0;
                margin-top: 1rem;
            }
            
            .stats {
                gap: 2rem;
            }
            
            .contact-form {
                margin: 0 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">🏢 SRI VEL'S REAL ESTATE</div>
                <ul class="nav-links">
                    <li><a href="#home">முகப்பு</a></li>
                    <li><a href="#services">சேவைகள்</a></li>
                    <li><a href="#properties">சொத்துக்கள்</a></li>
                    <li><a href="#about">தகவல்</a></li>
                    <li><a href="#contact">தொடர்பு</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <h1>SRI VEL'S REAL ESTATE</h1>
            <h2>வேலூரில் உங்கள் கனவு சொத்தைக் கண்டறியவும்</h2>
            <p>நம்பிக்கை, தெளிவு, சிறப்பு - Adukkamparai, Arni Main Road, Vellore-ல் 15+ ஆண்டுகள் அனுபவம்</p>
            <a href="#properties" class="btn">சொத்துக்களைப் பார்க்க</a>
            <a href="#contact" class="btn btn-secondary">தொடர்பு கொள்ளவும்</a>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <h2 class="section-title">எங்கள் சேவைகள்</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">🏠</div>
                    <h3>வீடு விற்பனை</h3>
                    <p>3 BHK, 2 BHK, தனி வீடுகள்</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">📍</div>
                    <h3>நிலம்/ப்ளோட்</h3>
                    <p>DTCP அனுமதி பெற்ற ப்ளோட்டுகள்</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🏢</div>
                    <h3>அடுக்குமாடி</h3>
                    <p>ஆஃப்ட் அடுக்குமாடி வீடுகள்</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">💼</div>
                    <h3>வணிகச் சொத்து</h3>
                    <p>Shops, Offices, Commercial spaces</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🤝</div>
                    <h3>சொத்து ஆலோசனை</h3>
                    <p>விலை மதிப்பீடு, பதிவு</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🏗️</div>
                    <h3>கட்டுமானம்</h3>
                    <p>வீடு கட்டுதல், மறுசீரமைப்பு</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-content">
                <h3>SRI VEL'S REAL ESTATE பற்றி</h3>
                <p>2010-ஆம் ஆண்டு தொடங்கப்பட்ட SRI VEL'S REAL ESTATE, வேலூர் மாவட்டத்தில் நம்பிக்கையான ரியல் எஸ்டேட் நிறுவனமாக விளங்குகிறது.</p>
                <p>நமது நெறிமுறை: <strong>நேர்மை, தெளிவு, வாடிக்கையாளர் மகிழ்ச்சி</strong>. 500+ குடும்பங்கள் their கனவு இல்லங்களைப் பெற்றுள்ளன.</p>
                <div class="stats">
                    <div class="stat-item">
                        <div class="stat-number">15+</div>
                        <div class="stat-label">ஆண்டுகள்</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">500+</div>
                        <div class="stat-label">விற்பனைகள்</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">98%</div>
                        <div class="stat-label">தொடர்பு</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Properties Section -->
    <section class="properties" id="properties">
        <div class="container">
            <h2 class="section-title">சிறந்த சொத்துக்கள்</h2>
            <div class="property-grid">
                <!-- Property 1 -->
                <div class="property-card">
                    <div class="property-image">
                        <img src="https://images.unsplash.com/photo-1600596542815-6ad4c728fd27?ixlib=rb-4.0.3" alt="3 BHK வீடு">
                        <span class="property-badge">புதியது</span>
                    </div>
                    <div class="property-info">
                        <div class="property-type">வீடு • 3 BHK</div>
                        <h3 class="property-title">நவீன அடுக்குமாடி வீடு</h3>
                        <p class="property-price">₹1.35 கோடி</p>
                        <p class="property-location">📍 Adukkamparai, Arni Road, Vellore</p>
                        <div class="property-features">
                            <span>🛏️ 3 படுக்கைகள்</span>
                            <span>🚿 3 குளியலறைகள்</span>
                            <span>📐 1650 sq.ft</span>
                        </div>
                    </div>
                </div>

                <!-- Property 2 -->
                <div class="property-card">
                    <div class="property-image">
                        <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-4.0.3" alt="2 BHK வீடு">
                        <span class="property-badge">விரைவில்</span>
                    </div>
                    <div class="property-info">
                        <div class="property-type">அடுக்குமாடி • 2 BHK</div>
                        <h3 class="property-title">சிறந்த அடுக்குமாடி வீடு</h3>
                        <p class="property-price">₹82 லட்சம்</p>
                        <p class="property-location">📍 Govt Medical College அருகில், Vellore</p>
                        <div class="property-features">
                            <span>🛏️ 2 படுக்கைகள்</span>
                            <span>🚿 2 குளியலறைகள்</span>
                            <span>📐 1180 sq.ft</span>
                        </div>
                    </div>
                </div>

                <!-- Property 3 -->
                <div class="property-card">
                    <div class="property-image">
                        <img src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?ixlib=rb-4.0.3" alt="Plot">
                        <span class="property-badge">DTCP அனுமதி</span>
                    </div>
                    <div class="property-info">
                        <div class="property-type">நிலம் • Plot</div>
                        <h3 class="property-title">DTCP ப்ளோட்</h3>
                        <p class="property-price">₹45 லட்சம்</p>
                        <p class="property-location">📍 Arni Main Road, Adukkamparai</p>
                        <div class="property-features">
                            <span>📐 1200 sq.ft</span>
                            <span>✅ அனுமதி பெற்றது</span>
                            <span>🅿️ பார்க் ஸ்பேஸ்</span>
                        </div>
                    </div>
                </div>

                <!-- Property 4 -->
                <div class="property-card">
                    <div class="property-image">
                        <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?ixlib=rb-4.0.3" alt="வணிகம்">
                        <span class="property-badge">விற்பனை</span>
                    </div>
                    <div class="property-info">
                        <div class="property-type">வணிகம் • Shop</div>
                        <h3 class="property-title">Main Road Shop</h3>
                        <p class="property-price">₹1.8 கோடி</p>
                        <p class="property-location">📍 Arni Main Road, Vellore</p>
                        <div class="property-features">
                            <span>📐 800 sq.ft</span>
                            <span>🅿️ 2 கார்கள்</span>
                            <span>📍 மையம்</span>
                        </div>
                    </div>
                </div>

                <!-- Property 5 -->
                <div class="property-card">
                    <div class="property-image">
                        <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?ixlib=rb-4.0.3" alt="Villa">
                        <span class="property-badge">பிரீமியம்</span>
                    </div>
                    <div class="property-info">
                        <div class="property-type">Villa • 4 BHK</div>
                        <h3 class="property-title">பிரீமியம் Villa</h3>
                        <p class="property-price">₹2.9 கோடி</p>
                        <p class="property-location">📍 VIT University அருகில், Vellore</p>
                        <div class="property-features">
                            <span>🛏️ 4 படுக்கைகள்</span>
                            <span>🚿 4 குளியலறைகள்</span>
                            <span>📐 2500 sq.ft</span>
                        </div>
                    </div>
                </div>

                <!-- Property 6 -->
                <div class="property-card">
                    <div class="property-image">
                        <img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?ixlib=rb-4.0.3" alt="Flat">
                        <span class="property-badge">விரைவு</span>
                    </div>
                    <div class="property-info">
                        <div class="property-type">Flat • 2 BHK</div>
                        <h3 class="property-title">சரியான விலை Flat</h3>
                        <p class="property-price">₹68 லட்சம்</p>
                        <p class="property-location">📍 Kennathapuram, Vellore</p>
                        <div class="property-features">
                            <span>🛏️ 2 படுக்கைகள்</span>
                            <span>🚿 2 குளியலறைகள்</span>
                            <span>📐 1050 sq.ft</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2 class="section-title">எங்களுடன் தொடர்பு கொள்ளவும்</h2>
            <div class="contact-info">
                <p>📍 <strong>Arni Main Road, Adukkamparai</strong>, Vellore - 632057, Tamil Nadu</p>
                <p style="margin-top: 1rem; font-size: 1.2rem;">📞 <strong>தொலைபேசி:</strong></p>
                <div class="phone-number">📱 +91 82955 76895</div>
                <div class="phone-number">📱 +91 89031 57217</div>
                <p style="margin-top: 0.5rem;">📧 <strong>மின்னஞ்சல்:</strong> info@srivelsrealestate.com</p>
                <p>🕐 <strong>வேளையம்:</strong> மு.க. 9:00 - இரவு 8:00 (எல்லா நாட்களும்)</p>
                <p>🏥 <strong>அருகில்:</strong> Government Medical College, VIT University - 10 நிமிடங்கள்</p>
                
                <!-- WhatsApp Buttons -->
                <a href="https://wa.me/918295576895?text=Hi%2C%20I%20want%20property%20information%20from%20SRI%20VEL%27S%20REAL%20ESTATE" 
                   class="btn btn-whatsapp" 
                   target="_blank">
                   💬 WhatsApp: 82955 76895
                </a>
                <a href="https://wa.me/918903157217?text=Hi%2C%20I%20want%20property%20information%20from%20SRI%20VEL%27S%20REAL%20ESTATE" 
                   class="btn btn-whatsapp" 
                   target="_blank"
                   style="background: #128C7E;">
                   💬 WhatsApp: 89031 57217
                </a>
            </div>
            
            <form class="contact-form">
                <div class="form-group">
                    <label for="name">பெயர் *</label>
                    <input type="text" id="name" placeholder="உங்கள் பெயர்" required>
                </div>
                <div class="form-group">
                    <label for="phone">கைப்பேசி எண் *</label>
                    <input type="tel" id="phone" placeholder="9876543210" required>
                </div>
                <div class="form-group">
                    <label for="email">மின்னஞ்சல்</label>
                    <input type="email" id="email" placeholder="example@email.com">
                </div>
                <div class="form-group">
                    <label for="property-type">சொத்து வகை *</label>
                    <select id="property-type" required>
                        <option value="">தேர்ந்தெடுக்கவும்</option>
                        <option value="buy">வாங்க வேண்டும்</option>
                        <option value="sell">விற்றுக்க வேண்டும்</option>
                        <option value="rent">பாட்டுக்கு தர வேண்டும்</option>
                        <option value="rent-want">பாட்டுக்கு வேண்டும்</option>
                        <option value="consultation">ஆலோசனை</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="message">செய்தி *</label>
                    <textarea id="message" placeholder="உங்கள் தேவை விவரிக்கவும்..." required></textarea>
                </div>
                <button type="submit" class="btn" style="width: 100%;">அனுப்பவும்</button>
            </form>
            
            <!-- Google Maps -->
            <div class="map-container">
                <iframe 
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3914.567890123456!2d79.1234567!3d12.9165432!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bad4a8f8f8f8f8f%3A0x1234567890abcdef!2sAdukkamparai%2C%20Vellore%2C%20Tamil%20Nadu%20632057!5e0!3m2!1sen!2sin!4v1234567890123!5m2!1sen!2sin" 
                    allowfullscreen="" 
                    loading="lazy" 
                    referrerpolicy="no-referrer-when-downgrade">
                </iframe>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2026 <strong>SRI VEL'S REAL ESTATE</strong>. அனைத்து உரிமைகளும் பாதுகாக்கப்பட்டவை.</p>
            <p>📍 Arni Main Road, Adukkamparai, Vellore - 632057, Tamil Nadu</p>
            <p>📞 +91 82955 76895 | +91 89031 57217 | 📧 info@srivelsrealestate.com</p>
            <p>🌐 வேலூரில் நம்பிக்கையான ரியல் எஸ்டேட் | 15+ ஆண்டுகள் அனுபவம் | 500+ வெற்றிகரமான விற்பனைகள்</p>
        </div>
    </footer>
</body>
</html>
