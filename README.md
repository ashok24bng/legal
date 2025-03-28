<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Legal Solutions India | Trusted Legal Services Nationwide</title>
    <meta name="description" content="India's premier legal service provider offering expert consultation, case management, and legal solutions across all practice areas.">
    
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Merriweather:wght@400;700&display=swap" rel="stylesheet">
    
    <!-- AOS Animation -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        :root {
            --primary: #1e3a8a;
            --secondary: #f59e0b;
            --accent: #3b82f6;
            --dark: #1e40af;
            --light: #eff6ff;
            --text: #374151;
            --white: #ffffff;
        }
        
        body {
            font-family: 'Montserrat', sans-serif;
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Merriweather', serif;
            color: var(--primary);
            font-weight: 700;
        }
        
        .navbar {
            background-color: var(--white);
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            padding: 15px 0;
            transition: all 0.3s;
        }
        
        .navbar.scrolled {
            padding: 10px 0;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        }
        
        .hero-section {
            background: linear-gradient(135deg, var(--primary) 0%, var(--dark) 100%);
            color: var(--white);
            padding: 150px 0 100px;
            position: relative;
            overflow: hidden;
        }
        
        .hero-section::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 50%;
            height: 100%;
            background: url('legal-solutions-logo.png') center/cover no-repeat;
            opacity: 0.1;
        }
        
        .btn-primary {
            background-color: var(--secondary);
            border-color: var(--secondary);
            color: var(--primary);
            font-weight: 600;
            padding: 12px 30px;
            border-radius: 8px;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-size: 14px;
        }
        
        .btn-primary:hover {
            background-color: #e69009;
            border-color: #e69009;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .section-title {
            position: relative;
            margin-bottom: 50px;
            text-align: center;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--secondary);
            border-radius: 2px;
        }
        
        .service-card {
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: all 0.4s;
            margin-bottom: 30px;
            border: none;
            background: var(--white);
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.1);
        }
        
        .service-icon {
            width: 80px;
            height: 80px;
            background: var(--light);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: -40px auto 20px;
            font-size: 32px;
            color: var(--secondary);
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .testimonial-card {
            background: var(--white);
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            margin: 15px;
            position: relative;
        }
        
        .testimonial-card::before {
            content: '\201C';
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 60px;
            color: var(--light);
            font-family: serif;
            line-height: 1;
            z-index: 0;
        }
        
        .testimonial-img {
            width: 70px;
            height: 70px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
            border: 3px solid var(--secondary);
            position: relative;
            z-index: 1;
        }
        
        .contact-info-box {
            background: var(--white);
            padding: 30px;
            border-radius: 12px;
            height: 100%;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            text-align: center;
        }
        
        .contact-info-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .contact-icon {
            width: 70px;
            height: 70px;
            background: var(--light);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 28px;
            color: var(--secondary);
        }
        
        footer {
            background: var(--primary);
            color: var(--white);
            padding: 80px 0 0;
            position: relative;
        }
        
        footer::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 10px;
            background: var(--secondary);
        }
        
        footer a {
            color: rgba(255,255,255,0.8);
            transition: all 0.3s;
        }
        
        footer a:hover {
            color: var(--white);
            text-decoration: none;
            padding-left: 5px;
        }
        
        .footer-bottom {
            background: var(--dark);
            padding: 20px 0;
            margin-top: 50px;
        }
        
        .floating-contact {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 999;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        
        .floating-btn {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: var(--secondary);
            color: var(--primary);
            font-size: 24px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            transition: all 0.3s;
        }
        
        .floating-btn:hover {
            transform: scale(1.1);
            color: var(--primary);
        }
        
        .pricing-card {
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: all 0.4s;
            margin-bottom: 30px;
            border: none;
            text-align: center;
            background: var(--white);
        }
        
        .pricing-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.1);
        }
        
        .pricing-header {
            background: var(--primary);
            color: var(--white);
            padding: 30px;
            position: relative;
            overflow: hidden;
        }
        
        .pricing-header::after {
            content: '';
            position: absolute;
            bottom: -20px;
            left: 0;
            width: 100%;
            height: 40px;
            background: var(--white);
            transform: skewY(-3deg);
        }
        
        .pricing-price {
            font-size: 42px;
            font-weight: 700;
            margin: 20px 0;
            color: var(--primary);
        }
        
        .pricing-features {
            padding: 30px;
        }
        
        .pricing-features ul {
            list-style: none;
            padding: 0;
        }
        
        .pricing-features li {
            padding: 12px 0;
            border-bottom: 1px solid #eee;
        }
        
        .feature-box {
            padding: 30px;
            background: var(--white);
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            margin-bottom: 30px;
            height: 100%;
            transition: all 0.3s;
            text-align: center;
        }
        
        .feature-box:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.1);
        }
        
        .feature-icon {
            width: 80px;
            height: 80px;
            background: var(--light);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 32px;
            color: var(--secondary);
        }
        
        .form-control {
            height: 50px;
            border-radius: 8px;
            border: 1px solid #ddd;
            padding-left: 20px;
        }
        
        .form-control:focus {
            box-shadow: none;
            border-color: var(--accent);
        }
        
        textarea.form-control {
            height: auto;
            padding-top: 15px;
        }
        
        .consultation-form {
            background: var(--white);
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 15px 40px rgba(0,0,0,0.1);
        }
        
        .stats-counter {
            font-size: 48px;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 10px;
        }
        
        .stats-label {
            font-size: 18px;
            color: var(--text);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        @media (max-width: 991.98px) {
            .hero-section {
                padding: 120px 0 80px;
                text-align: center;
            }
            
            .hero-section::before {
                display: none;
            }
            
            .section-title::after {
                bottom: -12px;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src="C:\Users\ASUS\Downloads\allindialegalservice.com\allindialegalservice.com\images\legal-solutions-logo.png" alt="Legal Solutions India" height="40">
                <span class="ms-2 d-none d-lg-inline">Legal Solutions India</span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="#pricing">Pricing</a></li>
                    <li class="nav-item"><a class="nav-link" href="#testimonials">Testimonials</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    <li class="nav-item ms-lg-3 mt-3 mt-lg-0"><a class="btn btn-primary" href="#consultation">Free Consultation</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section" id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6" data-aos="fade-right">
                    <h1 class="display-4 fw-bold mb-4">Your Trusted Legal Partner Across India</h1>
                    <p class="lead mb-5">We provide comprehensive legal solutions with a team of experienced advocates and legal advisors dedicated to protecting your rights.</p>
                    <div class="d-flex flex-wrap gap-3">
                        <a href="#consultation" class="btn btn-primary">Free Consultation</a>
                        <a href="#services" class="btn btn-outline-light">Our Services</a>
                    </div>
                </div>
                <div class="col-lg-6" data-aos="fade-left">
                    <img src="C:\Users\ASUS\Downloads\allindialegalservice.com\allindialegalservice.com\images\legal-hero-image.png" alt="Legal Services" class="img-fluid">
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-5 bg-light">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-3 col-6 mb-4 mb-md-0" data-aos="fade-up" data-aos-delay="100">
                    <div class="counter">
                        <div class="stats-counter"><span class="count" data-count="48758">0</span>+</div>
                        <div class="stats-label">Cases Solved</div>
                    </div>
                </div>
                <div class="col-md-3 col-6 mb-4 mb-md-0" data-aos="fade-up" data-aos-delay="200">
                    <div class="counter">
                        <div class="stats-counter"><span class="count" data-count="150">0</span>+</div>
                        <div class="stats-label">Legal Experts</div>
                    </div>
                </div>
                <div class="col-md-3 col-6" data-aos="fade-up" data-aos-delay="300">
                    <div class="counter">
                        <div class="stats-counter">24/7</div>
                        <div class="stats-label">Availability</div>
                    </div>
                </div>
                <div class="col-md-3 col-6" data-aos="fade-up" data-aos-delay="400">
                    <div class="counter">
                        <div class="stats-counter"><span class="count" data-count="98">0</span>%</div>
                        <div class="stats-label">Success Rate</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="py-5" id="about">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 mb-5 mb-lg-0" data-aos="fade-right">
                    <img src="images/about-legal-team.jpg" alt="About Us" class="img-fluid rounded-3 shadow">
                </div>
                <div class="col-lg-6" data-aos="fade-left">
                    <h2 class="section-title text-start">About Our Legal Service</h2>
                    <p>Legal Solutions India is a premier legal forum providing expert guidance for individuals and organizations. Our firm offers 24/7 services, making us the preferred choice for legal solutions across India.</p>
                    <p>With a team of experienced advocates and legal advisors, we simplify the legal process while ensuring your rights are protected at every step.</p>
                    <div class="row mt-4">
                        <div class="col-md-6 mb-4">
                            <div class="feature-box">
                                <div class="feature-icon">
                                    <i class="fas fa-shield-alt"></i>
                                </div>
                                <h4>Confidential</h4>
                                <p>All consultations are completely private and secure.</p>
                            </div>
                        </div>
                        <div class="col-md-6 mb-4">
                            <div class="feature-box">
                                <div class="feature-icon">
                                    <i class="fas fa-clock"></i>
                                </div>
                                <h4>Quick Response</h4>
                                <p>Get legal advice within hours of submitting your query.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="py-5 bg-light" id="services">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title">Our Legal Services</h2>
                <p class="lead">Comprehensive legal solutions for all your needs</p>
            </div>
            <div class="row">
                <div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="service-card card">
                        <img src="images/family-law-service.jpg" class="card-img-top" alt="Family Issues">
                        <div class="card-body text-center">
                            <div class="service-icon">
                                <i class="fas fa-users"></i>
                            </div>
                            <h4>Family Issues</h4>
                            <p>Expert legal assistance for divorce, child custody, alimony and other family law matters.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="service-card card">
                        <img src="images/cheque-bounce-service.jpg" class="card-img-top" alt="Cheque Bounce">
                        <div class="card-body text-center">
                            <div class="service-icon">
                                <i class="fas fa-file-invoice-dollar"></i>
                            </div>
                            <h4>Cheque Bounce</h4>
                            <p>Legal recourse for dishonored cheques under Section 138 of Negotiable Instruments Act.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="service-card card">
                        <img src="images/cyber-crime-service.jpg" class="card-img-top" alt="Cyber Crime">
                        <div class="card-body text-center">
                            <div class="service-icon">
                                <i class="fas fa-lock"></i>
                            </div>
                            <h4>Cyber Crime</h4>
                            <p>Protection against online fraud, hacking, identity theft and other cyber crimes.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="service-card card">
                        <img src="images/consumer-complaint-service.jpg" class="card-img-top" alt="Consumer Complaints">
                        <div class="card-body text-center">
                            <div class="service-icon">
                                <i class="fas fa-gavel"></i>
                            </div>
                            <h4>Consumer Complaints</h4>
                            <p>Legal remedies for defective products, deficient services and unfair trade practices.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="service-card card">
                        <img src="images/property-dispute-service.jpg" class="card-img-top" alt="Property Disputes">
                        <div class="card-body text-center">
                            <div class="service-icon">
                                <i class="fas fa-home"></i>
                            </div>
                            <h4>Property Disputes</h4>
                            <p>Resolution for property conflicts, landlord-tenant issues, and ownership matters.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="service-card card">
                        <img src="images/legal-notice-service.jpg" class="card-img-top" alt="Legal Notices">
                        <div class="card-body text-center">
                            <div class="service-icon">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <h4>Legal Notices</h4>
                            <p>Professional drafting and serving of legal notices for various civil and criminal matters.</p>
                            <a href="#" class="btn btn-primary">Learn More</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title">How It Works</h2>
                <p class="lead">Get legal help in just 4 simple steps</p>
            </div>
            <div class="row">
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="feature-box">
                        <div class="feature-icon">
                            <i class="fas fa-edit"></i>
                        </div>
                        <h4>Register Complaint</h4>
                        <p>Fill our simple form with details of your legal issue.</p>
                        <span class="badge bg-primary rounded-pill">Step 1</span>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="feature-box">
                        <div class="feature-icon">
                            <i class="fas fa-credit-card"></i>
                        </div>
                        <h4>Select Plan</h4>
                        <p>Choose a suitable plan and make secure payment.</p>
                        <span class="badge bg-primary rounded-pill">Step 2</span>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="feature-box">
                        <div class="feature-icon">
                            <i class="fas fa-comments"></i>
                        </div>
                        <h4>Legal Discussion</h4>
                        <p>Our expert will contact you to discuss your case.</p>
                        <span class="badge bg-primary rounded-pill">Step 3</span>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="400">
                    <div class="feature-box">
                        <div class="feature-icon">
                            <i class="fas fa-balance-scale"></i>
                        </div>
                        <h4>Resolution</h4>
                        <p>We take legal action to resolve your issue promptly.</p>
                        <span class="badge bg-primary rounded-pill">Step 4</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="py-5 bg-light" id="pricing">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title">Affordable Pricing Plans</h2>
                <p class="lead">Choose the perfect plan for your legal needs</p>
            </div>
            <div class="row">
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="pricing-card card">
                        <div class="pricing-header">
                            <h4>Basic</h4>
                            <p>For small claims</p>
                        </div>
                        <div class="pricing-price">
                            ₹1200 <small>+ GST</small>
                        </div>
                        <div class="pricing-features">
                            <ul>
                                <li>Claims up to ₹20,000</li>
                                <li>Legal Notice Drafting</li>
                                <li>Basic Consultation</li>
                                <li>Email Support</li>
                            </ul>
                            <a href="#" class="btn btn-primary w-100 mt-3">Choose Plan</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="pricing-card card">
                        <div class="pricing-header">
                            <h4>Standard</h4>
                            <p>Most Popular</p>
                        </div>
                        <div class="pricing-price">
                            ₹1999 <small>+ GST</small>
                        </div>
                        <div class="pricing-features">
                            <ul>
                                <li>Claims up to ₹50,000</li>
                                <li>Legal Notice Drafting</li>
                                <li>Priority Consultation</li>
                                <li>Phone & Email Support</li>
                            </ul>
                            <a href="#" class="btn btn-primary w-100 mt-3">Choose Plan</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="pricing-card card">
                        <div class="pricing-header">
                            <h4>Premium</h4>
                            <p>For larger claims</p>
                        </div>
                        <div class="pricing-price">
                            ₹2999 <small>+ GST</small>
                        </div>
                        <div class="pricing-features">
                            <ul>
                                <li>Claims up to ₹1,00,000</li>
                                <li>Legal Notice Drafting</li>
                                <li>24/7 Consultation</li>
                                <li>Dedicated Case Manager</li>
                            </ul>
                            <a href="#" class="btn btn-primary w-100 mt-3">Choose Plan</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="400">
                    <div class="pricing-card card">
                        <div class="pricing-header">
                            <h4>Enterprise</h4>
                            <p>For complex cases</p>
                        </div>
                        <div class="pricing-price">
                            ₹4999 <small>+ GST</small>
                        </div>
                        <div class="pricing-features">
                            <ul>
                                <li>Claims above ₹1,00,000</li>
                                <li>Full Documentation</li>
                                <li>Case Filing Support</li>
                                <li>Personalized Service</li>
                            </ul>
                            <a href="#" class="btn btn-primary w-100 mt-3">Choose Plan</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-5" id="testimonials">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title">What Our Clients Say</h2>
                <p class="lead">Success stories from our satisfied clients</p>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="owl-carousel testimonial-slider">
                        <div class="testimonial-card text-center" data-aos="fade-up">
                            <img src="images/client-1.jpg" alt="Client" class="testimonial-img mx-auto">
                            <div class="rating mb-3">
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                            </div>
                            <p class="mb-4">"Legal Solutions India helped me recover my money from a fraudulent investment scheme. Their team was professional and persistent. I got my full amount back within 2 months!"</p>
                            <h5>Arjun</h5>
                            <small>Bangalore</small>
                        </div>
                        <div class="testimonial-card text-center" data-aos="fade-up" data-aos-delay="100">
                            <img src="images/client-2.jpg" alt="Client" class="testimonial-img mx-auto">
                            <div class="rating mb-3">
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                            </div>
                            <p class="mb-4">"I was facing harassment from my landlord. The legal notice sent by Legal Solutions India resolved the issue within weeks without going to court. Highly recommended!"</p>
                            <h5>Priya</h5>
                            <small>Delhi</small>
                        </div>
                        <div class="testimonial-card text-center" data-aos="fade-up" data-aos-delay="200">
                            <img src="images/client-3.jpg" alt="Client" class="testimonial-img mx-auto">
                            <div class="rating mb-3">
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star-half-alt text-warning"></i>
                            </div>
                            <p class="mb-4">"The cheque bounce case was handled very professionally. I received updates regularly and the matter was settled out of court with full payment plus interest. Excellent service!"</p>
                            <h5>Aravind Das</h5>
                            <small>Chennai</small>
                        </div>
                        <div class="testimonial-card text-center" data-aos="fade-up" data-aos-delay="300">
                            <img src="images/client-4.jpg" alt="Client" class="testimonial-img mx-auto">
                            <div class="rating mb-3">
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                                <i class="fas fa-star text-warning"></i>
                            </div>
                            <p class="mb-4">"I registered a complaint for loss of money and within an hour I got response. My case manager helped me throughout to get money back. Every hour I got updates about my case."</p>
                            <h5>Emma K Paul</h5>
                            <small>Mumbai</small>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title">Frequently Asked Questions</h2>
                <p class="lead">Find answers to common legal questions</p>
            </div>
            <div class="row">
                <div class="col-lg-6">
                    <div class="accordion" id="faqAccordion">
                        <div class="card mb-3" data-aos="fade-up">
                            <div class="card-header" id="headingOne">
                                <h5 class="mb-0">
                                    <button class="btn btn-link w-100 text-start" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
                                        What is online legal consultation?
                                    </button>
                                </h5>
                            </div>
                            <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#faqAccordion">
                                <div class="card-body">
                                    Online legal consultation is a method to connect users and lawyers virtually. It's a convenient and easy way to get legal advice using our platform from the comfort of your home or office.
                                </div>
                            </div>
                        </div>
                        <div class="card mb-3" data-aos="fade-up" data-aos-delay="100">
                            <div class="card-header" id="headingTwo">
                                <h5 class="mb-0">
                                    <button class="btn btn-link w-100 text-start collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo">
                                        When should I file a consumer complaint?
                                    </button>
                                </h5>
                            </div>
                            <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#faqAccordion">
                                <div class="card-body">
                                    Consumer complaints should be filed within 2 years from when you became aware of the defective goods or deficient services. Our team can help determine the best course of action based on your specific situation.
                                </div>
                            </div>
                        </div>
                        <div class="card mb-3" data-aos="fade-up" data-aos-delay="200">
                            <div class="card-header" id="headingThree">
                                <h5 class="mb-0">
                                    <button class="btn btn-link w-100 text-start collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree">
                                        How long does it take to resolve a complaint?
                                    </button>
                                </h5>
                            </div>
                            <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#faqAccordion">
                                <div class="card-body">
                                    Resolution time varies depending on the complexity of the case and the response from the other party. Our panel advocates take immediate action upon receiving all details, and many cases are resolved within 4-8 weeks.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="accordion" id="faqAccordion2">
                        <div class="card mb-3" data-aos="fade-up">
                            <div class="card-header" id="headingFour">
                                <h5 class="mb-0">
                                    <button class="btn btn-link w-100 text-start" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour">
                                        Can I challenge a court decision?
                                    </button>
                                </h5>
                            </div>
                            <div id="collapseFour" class="collapse show" aria-labelledby="headingFour" data-parent="#faqAccordion2">
                                <div class="card-body">
                                    Yes, you can challenge decisions to higher courts depending on where the complaint was first filed. Our legal experts can advise you on the appropriate appellate forum and procedure for your specific case.
                                </div>
                            </div>
                        </div>
                        <div class="card mb-3" data-aos="fade-up" data-aos-delay="100">
                            <div class="card-header" id="headingFive">
                                <h5 class="mb-0">
                                    <button class="btn btn-link w-100 text-start collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFive">
                                        What payment methods do you accept?
                                    </button>
                                </h5>
                            </div>
                            <div id="collapseFive" class="collapse" aria-labelledby="headingFive" data-parent="#faqAccordion2">
                                <div class="card-body">
                                    We accept all major payment methods including credit/debit cards, net banking, UPI, and popular digital wallets. All transactions are secure and encrypted for your protection.
                                </div>
                            </div>
                        </div>
                        <div class="card mb-3" data-aos="fade-up" data-aos-delay="200">
                            <div class="card-header" id="headingSix">
                                <h5 class="mb-0">
                                    <button class="btn btn-link w-100 text-start collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSix">
                                        Is my consultation confidential?
                                    </button>
                                </h5>
                            </div>
                            <div id="collapseSix" class="collapse" aria-labelledby="headingSix" data-parent="#faqAccordion2">
                                <div class="card-body">
                                    Absolutely. All consultations with our legal experts are completely confidential and protected by attorney-client privilege. Your information is never shared without your explicit consent.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Consultation Form -->
    <section class="py-5 bg-primary text-white" id="consultation">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 mb-5 mb-lg-0" data-aos="fade-right">
                    <h2 class="mb-4">Free Legal Consultation</h2>
                    <p class="mb-4">Get expert legal advice without any obligation. Our team will review your case and suggest the best course of action.</p>
                    <div class="row">
                        <div class="col-6">
                            <div class="d-flex align-items-center mb-4">
                                <i class="fas fa-check-circle fa-2x me-3"></i>
                                <div>
                                    <h5 class="mb-0">No Hidden Fees</h5>
                                    <small>Transparent Pricing</small>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex align-items-center mb-4">
                                <i class="fas fa-check-circle fa-2x me-3"></i>
                                <div>
                                    <h5 class="mb-0">24/7 Support</h5>
                                    <small>Always Available</small>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex align-items-center mb-4">
                                <i class="fas fa-check-circle fa-2x me-3"></i>
                                <div>
                                    <h5 class="mb-0">Expert Lawyers</h5>
                                    <small>Experienced Professionals</small>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex align-items-center mb-4">
                                <i class="fas fa-check-circle fa-2x me-3"></i>
                                <div>
                                    <h5 class="mb-0">Confidential</h5>
                                    <small>100% Private</small>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6" data-aos="fade-left">
                    <div class="consultation-form">
                        <h4 class="mb-4 text-dark">Request Free Consultation</h4>
                        <form>
                            <div class="mb-3">
                                <input type="text" class="form-control" placeholder="Your Name" required>
                            </div>
                            <div class="mb-3">
                                <input type="email" class="form-control" placeholder="Email Address" required>
                            </div>
                            <div class="mb-3">
                                <input type="tel" class="form-control" placeholder="Phone Number" required>
                            </div>
                            <div class="mb-3">
                                <select class="form-select">
                                    <option selected>Select Legal Service</option>
                                    <option>Family Law</option>
                                    <option>Cheque Bounce</option>
                                    <option>Cyber Crime</option>
                                    <option>Consumer Complaint</option>
                                    <option>Property Dispute</option>
                                    <option>Legal Notice</option>
                                </select>
                            </div>
                            <div class="mb-3">
                                <textarea class="form-control" rows="4" placeholder="Brief about your legal issue"></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary w-100">Submit Request</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-5" id="contact">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="section-title">Contact Us</h2>
                <p class="lead">Get in touch with our legal experts</p>
            </div>
            <div class="row">
                <div class="col-lg-4 mb-4" data-aos="fade-up">
                    <div class="contact-info-box">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <h4>Our Office</h4>
                        <p>No 198, CMH Road, 2nd Floor<br>Indiranagar, Bangalore<br>Karnataka, India 560038</p>
                        <a href="#" class="btn btn-outline-primary">View Map</a>
                    </div>
                </div>
                <div class="col-lg-4 mb-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="contact-info-box">
                        <div class="contact-icon">
                            <i class="fas fa-phone-alt"></i>
                        </div>
                        <h4>Call Us</h4>
                        <p>+91 953 810 1799<br>+91 907 100 1484</p>
                        <a href="tel:+919538101799" class="btn btn-outline-primary">Call Now</a>
                    </div>
                </div>
                <div class="col-lg-4 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="contact-info-box">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <h4>Email Us</h4>
                        <p>support@legalsolutionsindia.com<br>info@legalsolutionsindia.com</p>
                        <a href="mailto:support@legalsolutionsindia.com" class="btn btn-outline-primary">Email Now</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-lg-4 mb-4">
                    <img src="images/legal-solutions-logo-white.png" alt="Legal Solutions India" height="40" class="mb-3">
                    <p>We provide comprehensive legal solutions with a team of experienced advocates across India.</p>
                    <div class="social-icons mt-4">
                        <a href="#" class="text-white me-3"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-white me-3"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="text-white"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="col-lg-2 col-md-4 mb-4">
                    <h5>Services</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="#">Family Law</a></li>
                        <li class="mb-2"><a href="#">Cheque Bounce</a></li>
                        <li class="mb-2"><a href="#">Cyber Crime</a></li>
                        <li class="mb-2"><a href="#">Consumer Complaints</a></li>
                        <li class="mb-2"><a href="#">Property Disputes</a></li>
                        <li><a href="#">Legal Notices</a></li>
                    </ul>
                </div>
                <div class="col-lg-2 col-md-4 mb-4">
                    <h5>Quick Links</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="#">Home</a></li>
                        <li class="mb-2"><a href="#">About Us</a></li>
                        <li class="mb-2"><a href="#">Services</a></li>
                        <li class="mb-2"><a href="#">Pricing</a></li>
                        <li class="mb-2"><a href="#">Testimonials</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="col-lg-4 col-md-4 mb-4">
                    <h5>Newsletter</h5>
                    <p>Subscribe to our newsletter for legal updates and tips.</p>
                    <form class="mt-3">
                        <div class="input-group mb-3">
                            <input type="email" class="form-control" placeholder="Your Email" aria-label="Your Email">
                            <button class="btn btn-secondary" type="button">Subscribe</button>
                        </div>
                    </form>
                </div>
            </div>
            <div class="footer-bottom">
                <div class="row">
                    <div class="col-md-6">
                        <p class="mb-0">&copy; 2023 Legal Solutions India. All rights reserved.</p>
                    </div>
                    <div class="col-md-6 text-md-end">
                        <a href="#" class="me-3">Privacy Policy</a>
                        <a href="#" class="me-3">Terms of Service</a>
                        <a href="#">Refund Policy</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating Contact Buttons -->
    <div class="floating-contact">
        <a href="tel:+919538101799" class="floating-btn" data-aos="fade-left" data-aos-delay="300">
            <i class="fas fa-phone"></i>
        </a>
        <a href="https://wa.me/919538101799" class="floating-btn" data-aos="fade-left" data-aos-delay="400">
            <i class="fab fa-whatsapp"></i>
        </a>
    </div>

    <!-- Back to Top Button -->
    <a href="#" class="back-to-top" data-aos="fade-up">
        <i class="fas fa-arrow-up"></i>
    </a>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <!-- AOS Animation -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <!-- Owl Carousel -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <!-- Custom JS -->
    <script>
        // Initialize AOS animation
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });
        
        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });
        
        // Counter animation
        document.addEventListener('DOMContentLoaded', () => {
            const counters = document.querySelectorAll('.count');
            const speed = 200;
            
            const animateCounters = () => {
                counters.forEach(counter => {
                    const target = +counter.getAttribute('data-count');
                    const count = +counter.innerText;
                    const increment = target / speed;
                    
                    if(count < target) {
                        counter.innerText = Math.ceil(count + increment);
                        setTimeout(animateCounters, 1);
                    } else {
                        counter.innerText = target;
                    }
                });
            };
            
            // Start animation when counters are in view
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        animateCounters();
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.5 });
            
            counters.forEach(counter => {
                observer.observe(counter);
            });
        });
        
        // Testimonial slider
        $(document).ready(function(){
            $('.testimonial-slider').owlCarousel({
                loop: true,
                margin: 30,
                nav: false,
                dots: true,
                autoplay: true,
                responsive: {
                    0: {
                        items: 1
                    },
                    768: {
                        items: 2
                    },
                    992: {
                        items: 3
                    }
                }
            });
        });
        
        // Back to top button
        const backToTopButton = document.querySelector('.back-to-top');
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.style.opacity = '1';
                backToTopButton.style.visibility = 'visible';
            } else {
                backToTopButton.style.opacity = '0';
                backToTopButton.style.visibility = 'hidden';
            }
        });
        
        backToTopButton.addEventListener('click', (e) => {
            e.preventDefault();
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>
</body>
</html>
