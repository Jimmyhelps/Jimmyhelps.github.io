<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jimmy Assignment Help Services - Top Rated Academic Assistance</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Global Styles */
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 28px;
            font-weight: 700;
        }
        
        .logo span {
            color: var(--accent);
        }
        
        /* Hero Section */
        .hero {
            background: url('https://images.unsplash.com/photo-1434030216411-0b793f4b4173?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            height: 500px;
            display: flex;
            align-items: center;
            position: relative;
            color: white;
            text-align: center;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            width: 100%;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 30px;
        }
        
        .btn {
            display: inline-block;
            background: var(--accent);
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 2px solid var(--accent);
        }
        
        .btn:hover {
            background: transparent;
            color: var(--accent);
        }
        
        .btn-outline {
            background: transparent;
            border: 2px solid white;
            margin-left: 15px;
        }
        
        .btn-outline:hover {
            background: white;
            color: var(--dark);
        }
        
        /* Services Section */
        .section {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: var(--primary);
            position: relative;
            display: inline-block;
            padding-bottom: 15px;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background: var(--accent);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-card i {
            font-size: 2.5rem;
            color: var(--secondary);
            margin-bottom: 20px;
        }
        
        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--primary);
        }
        
        /* Subjects Section */
        .subjects-container {
            background: var(--light);
            padding: 50px;
            border-radius: 10px;
        }
        
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .subject-item {
            background: white;
            padding: 20px;
            border-left: 4px solid var(--secondary);
            border-radius: 5px;
        }
        
        /* Guarantees Section */
        .guarantees {
            background: var(--primary);
            color: white;
        }
        
        .guarantees .section-title h2 {
            color: white;
        }
        
        .guarantees-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .guarantee-card {
            text-align: center;
            padding: 30px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        
        .guarantee-card:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: scale(1.05);
        }
        
        .guarantee-card i {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--accent);
        }
        
        /* Contact Section */
        .contact {
            background: var(--light);
        }
        
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
        }
        
        .contact-info {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        
        .contact-method {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .contact-method i {
            font-size: 1.5rem;
            color: var(--secondary);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background: var(--secondary);
            color: white;
            border-radius: 50%;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--accent);
            transform: translateY(-5px);
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            
            .btn {
                display: block;
                width: 80%;
                margin: 0 auto 15px;
            }
            
            .btn-outline {
                margin-left: auto;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-content">
            <div class="logo">Jimmy <span>Assignment Help</span></div>
            <div class="cta">
                <a href="https://wa.me/254100852064" class="btn">Chat on WhatsApp</a>
            </div>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero">
        <div class="container hero-content">
            <h1>Top-Rated Assignment Help Worldwide</h1>
            <p>Trusted by thousands of students for expert guidance, timely delivery, and plagiarism-free work. Get A+ grades with our professional assistance.</p>
            <div class="hero-btns">
                <a href="https://wa.me/254100852064" class="btn">Get Instant Help</a>
                <a href="#services" class="btn btn-outline">Our Services</a>
            </div>
        </div>
    </section>
    
    <!-- Services Section -->
    <section id="services" class="section">
        <div class="container">
            <div class="section-title">
                <h2>Our Assignment Help Services</h2>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-graduation-cap"></i>
                    <h3>Thesis & Dissertation</h3>
                    <p>Comprehensive assistance from topic selection to final submission with expert guidance.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-laptop-code"></i>
                    <h3>Online Exams & Coursework</h3>
                    <p>Professional help with all your online tests, quizzes, and coursework assignments.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-file-alt"></i>
                    <h3>Research Papers</h3>
                    <p>High-quality, well-researched papers tailored to your specific requirements.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-book-open"></i>
                    <h3>Literature Reviews</h3>
                    <p>Thorough analysis and synthesis of existing research on your topic.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-pen-fancy"></i>
                    <h3>Reflective Writing</h3>
                    <p>Professional assistance with reflective journals and portfolios.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-chart-bar"></i>
                    <h3>Research Summary</h3>
                    <p>Concise and accurate summaries of complex research materials.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Core Subjects Section -->
    <section class="section">
        <div class="container">
            <div class="section-title">
                <h2>Our Core Subjects</h2>
            </div>
            <div class="subjects-container">
                <div class="subjects-grid">
                    <div class="subject-item">
                        <h3>Economics & Marketing</h3>
                    </div>
                    <div class="subject-item">
                        <h3>Finance & Accounting</h3>
                    </div>
                    <div class="subject-item">
                        <h3>Supply Chain Management</h3>
                    </div>
                    <div class="subject-item">
                        <h3>Law (All Specializations)</h3>
                    </div>
                    <div class="subject-item">
                        <h3>Engineering (All Disciplines)</h3>
                    </div>
                    <div class="subject-item">
                        <h3>Programming & Tech</h3>
                        <p>C++, C Language, JavaScript, SQL, Android Apps, HTML/CSS, R Coding, Web Development, AI & ML</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Guarantees Section -->
    <section class="section guarantees">
        <div class="container">
            <div class="section-title">
                <h2>We Guarantee You</h2>
            </div>
            <div class="guarantees-grid">
                <div class="guarantee-card">
                    <i class="fas fa-star"></i>
                    <h3>Excellent Grades</h3>
                    <p>A+ quality work guaranteed to help you achieve top marks.</p>
                </div>
                <div class="guarantee-card">
                    <i class="fas fa-clock"></i>
                    <h3>On-Time Delivery</h3>
                    <p>Never miss a deadline with our punctual service.</p>
                </div>
                <div class="guarantee-card">
                    <i class="fas fa-check-circle"></i>
                    <h3>100% Original Work</h3>
                    <p>0% AI, No plagiarism - just custom-written solutions.</p>
                </div>
                <div class="guarantee-card">
                    <i class="fas fa-headset"></i>
                    <h3>24/7 Support</h3>
                    <p>Always available to assist you with your academic needs.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contact" class="section contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us (Instant Reply)</h2>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-method">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h3>Email Us</h3>
                            <p><a href="mailto:billygroupofwriters@gmail.com">billygroupofwriters@gmail.com</a></p>
                        </div>
                    </div>
                    <div class="contact-method">
                        <i class="fab fa-whatsapp"></i>
                        <div>
                            <h3>WhatsApp</h3>
                            <p><a href="https://wa.me/254100852064">+254100852064</a></p>
                        </div>
                    </div>
                    <div class="contact-method">
                        <i class="fas fa-link"></i>
                        <div>
                            <h3>Quick Links</h3>
                            <p><a href="https://wa.me/qr/4PKBWS2XMM4VF1">WhatsApp Quick Chat</a></p>
                            <p><a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ">Join Our WhatsApp Group</a></p>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="https://wa.me/254100852064"><i class="fab fa-whatsapp"></i></a>
                        <a href="mailto:billygroupofwriters@gmail.com"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
                <div class="contact-form">
                    <form>
                        <div class="form-group">
                            <input type="text" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" placeholder="Subject">
                        </div>
                        <div class="form-group">
                            <textarea placeholder="Your Message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Jimmy Assignment Help Services. All Rights Reserved.</p>
            <p>Excellence in Academic Support</p>
        </div>
    </footer>
</body>
</html>
