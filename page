<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airtech Refrigeração</title>
    </head>S
    <style>
        :root {
            --primary-color: #08589e;
            --secondary-color: #636ceb;
            --text-color: #333;
            --light-color: #f5f5f5;
            --dark-color: #1e1e1e;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            color: var(--text-color);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            font-size: 28px;
            font-weight: 700;
            color: var(--primary-color);
        }
        
        .logo span {
            color: var(--secondary-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 30px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--secondary-color);
        }
        
        .cta-button {
            background-color: var(--secondary-color);
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: 600;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        
        .cta-button:hover {
            background-color: #7860e4;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("/api/placeholder/1200/600") center/cover no-repeat;
            height: 100vh;
            display: flex;
            align-items: center;
            color: white;
            text-align: center;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding-top: 70px;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
        }
        
        /* Services Section */
        .services {
            padding: 100px 0;
            background-color: var(--light-color);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }
        
        .section-title h2 {
            font-size: 36px;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .section-title p {
            color: var(--text-color);
            max-width: 700px;
            margin: 0 auto;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            font-size: 48px;
            color: var(--secondary-color);
            margin-bottom: 20px;
        }
        
        .service-card h3 {
            margin-bottom: 15px;
            color: var(--primary-color);
        }
        
        /* Portfolio Section */
        .portfolio {
            padding: 100px 0;
        }
        
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .portfolio-item {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            height: 300px;
        }
        
        .portfolio-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .portfolio-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(32, 107, 173, 0.8);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            opacity: 0;
            transition: opacity 0.3s;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        .portfolio-item:hover .portfolio-overlay {
            opacity: 1;
        }
        
        .portfolio-item:hover img {
            transform: scale(1.1);
        }
        
        /* Benefits Section */
        .benefits {
            padding: 100px 0;
            background-color: var(--light-color);
        }
        
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .benefit-card {
            display: flex;
            align-items: flex-start;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .benefit-icon {
            font-size: 24px;
            color: var(--secondary-color);
            margin-right: 20px;
            min-width: 24px;
        }
        
        .benefit-content h3 {
            margin-bottom: 10px;
            color: var(--primary-color);
        }
        
        /* Testimonials Section */
        .testimonials {
            padding: 100px 0;
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .testimonial-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            position: relative;
        }
        
        .testimonial-text {
            margin-bottom: 20px;
            font-style: italic;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .author-image {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
        }
        
        .author-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .author-details h4 {
            color: var(--primary-color);
        }
        
        .author-details p {
            font-size: 14px;
            color: #777;
        }
        
        /* Call to Action Section */
        .cta {
            padding: 100px 0;
            background-color: var(--primary-color);
            color: white;
            text-align: center;
        }
        
        .cta h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        
        .cta p {
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 18px;
        }
        
        .cta .cta-button {
            background-color: var(--secondary-color);
            font-size: 18px;
            padding: 15px 30px;
        }
        
        /* Contact Form Section */
        .contact {
            padding: 100px 0;
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
        }
        
        .contact-info {
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        
        .contact-info h3 {
            font-size: 28px;
            color: var(--primary-color);
            margin-bottom: 20px;
        }
        
        .contact-info p {
            margin-bottom: 30px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .contact-icon {
            color: var(--secondary-color);
            font-size: 24px;
            margin-right: 15px;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        
        .form-group textarea {
            height: 150px;
        }
        
        .form-button {
            background-color: var(--secondary-color);
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .form-button:hover {
            background-color: #584ee0;
        }
        
        /* FAQ Section */
        .faq {
            padding: 100px 0;
            background-color: var(--light-color);
        }
        
        .faq-item {
            background-color: white;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            overflow: hidden;
        }
        
        .faq-question {
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: pointer;
            font-weight: 600;
            color: var(--primary-color);
        }
        
        .faq-answer {
            padding: 0 20px 20px;
            display: none;
        }
        
        .faq-item.active .faq-answer {
            display: block;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 50px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-column h3 {
            font-size: 20px;
            margin-bottom: 20px;
            color: var(--secondary-color);
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 10px;
        }
        
        .footer-column ul li a {
            color: #ddd;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column ul li a:hover {
            color: var(--secondary-color);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-links a {
            color: white;
            font-size: 20px;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: var(--secondary-color);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 20px;
                justify-content: center;
                flex-wrap: wrap;
            }
            
            nav ul li {
                margin: 5px 10px;
            }
            
            .hero h1 {
                font-size: 36px;
            }
            
            .hero p {
                font-size: 18px;
            }
            
            .section-title h2 {
                font-size: 28px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">Airtech<span>Refrigeração</span></div>
                <nav>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#services">Serviços</a></li>
                        <li><a href="#portfolio">Galeria</a></li>
                        <li><a href="#benefits">Vantagens</a></li>
                        <li><a href="#testimonials">Depoimentos</a></li>
                        <li><a href="#contact">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
<div class="hero-content">
    <h1>Transforme Seu Ambiente com Ar-Condicionado de Alta Qualidade</h1>
    <p>Mais de 1000 opções de sistemas de ar-condicionado para proporcionar conforto e eficiência. Instalação profissional e garantia de qualidade.</p>
    <a href="#contact" class="cta-button">Solicite um Orçamento Grátis</a>
</div>
</div>
</section>

<!-- Services Section -->
<section id="services" class="services">
    <div class="container">
        <div class="section-title">
            <h2>Nossos Serviços</h2>
            <p>Oferecemos soluções completas em climatização, desde a escolha do sistema ideal até a instalação profissional.</p>
        </div>
        <div class="services-grid">
            <div class="service-card">
                <div class="service-icon">📋</div>
                <h3>Consultoria Personalizada</h3>
                <p>Nossa equipe de especialistas ajuda você a escolher o sistema de ar-condicionado ideal para o seu ambiente, considerando eficiência, conforto e economia de energia.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🛒</div>
                <h3>Venda de Ar-Condicionado</h3>
                <p>Ampla variedade de modelos e marcas de ar-condicionado, com soluções para todos os tipos de ambientes e necessidades.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🔧</div>
                <h3>Instalação Profissional</h3>
                <p>Equipe especializada em instalação de ar-condicionado, garantindo o funcionamento adequado e a melhor performance do seu equipamento.</p>
            </div>
        </div>
    </div>
</section>

<!-- Portfolio Section -->
<section id="portfolio" class="portfolio">
    <div class="container">
        <div class="section-title">
            <h2>Nossa Galeria</h2>
            <p>Confira alguns dos nossos projetos realizados e inspire-se para climatizar o seu espaço.</p>
        </div>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="/api/placeholder/400/400" alt="Ar-condicionado em sala de estar">
                <div class="portfolio-overlay">
                    <h3>Sala de Estar Confortável</h3>
                    <p>Instalação de ar-condicionado com baixo consumo de energia para um ambiente agradável e eficiente.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="/api/placeholder/400/400" alt="Ar-condicionado em quarto">
                <div class="portfolio-overlay">
                    <h3>Quarto Aconchegante</h3>
                    <p>Sistema de ar-condicionado com controle de temperatura ideal para noites de descanso tranquilas.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="/api/placeholder/400/400" alt="Ar-condicionado em escritório">
                <div class="portfolio-overlay">
                    <h3>Escritório Moderno</h3>
                    <p>Instalação de ar-condicionado em ambiente corporativo para conforto e produtividade no trabalho.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="/api/placeholder/400/400" alt="Ar-condicionado em cozinha">
                <div class="portfolio-overlay">
                    <h3>Cozinha Estilosa</h3>
                    <p>Sistemas de climatização para ambientes gourmets, proporcionando conforto e bem-estar.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="/api/placeholder/400/400" alt="Ar-condicionado em banheiro">
                <div class="portfolio-overlay">
                    <h3>Banheiro Confortável</h3>
                    <p>Ar-condicionado para banheiros, com modelos que oferecem eficiência e resistência à umidade.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="/api/placeholder/400/400" alt="Ar-condicionado em quarto infantil">
                <div class="portfolio-overlay">
                    <h3>Quarto Infantil Fresquinho</h3>
                    <p>Instalação de ar-condicionado para quartos de crianças, com modelos que proporcionam um ambiente saudável e confortável.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Benefits Section -->
<section id="benefits" class="benefits">
    <div class="container">
        <div class="section-title">
            <h2>Por Que Escolher a Air Tech Refrigeração?</h2>
            <p>Conheça as vantagens de trabalhar com a líder em soluções de climatização e ar-condicionado.</p>
        </div>
        <div class="benefits-grid">
            <div class="benefit-card">
                <div class="benefit-icon">✓</div>
                <div class="benefit-content">
                    <h3>Qualidade Premium</h3>
                    <p>Trabalhamos apenas com sistemas de ar-condicionado de alta qualidade, com eficiência comprovada e durabilidade garantida.</p>
                </div>
            </div>
            <div class="benefit-card">
                <div class="benefit-icon">✓</div>
                <div class="benefit-content">
                    <h3>Instalação Profissional</h3>
                    <p>Nossa equipe é especializada e certificada, garantindo o melhor desempenho e a instalação correta do seu ar-condicionado.</p>
                </div>
            </div>
            <div class="benefit-card">
                <div class="benefit-icon">✓</div>
                <div class="benefit-content">
                    <h3>Garantia de Serviço</h3>
                    <p>Oferecemos garantia de 2 anos para os serviços de instalação e assistência técnica.</p>
                </div>
            </div>
            <div class="benefit-card">
                <div class="benefit-icon">✓</div>
                <div class="benefit-content">
                    <h3>Variedade de Modelos</h3>
                    <p>Temos opções para todos os tipos de ambientes, com modelos econômicos, silenciosos e de alto desempenho.</p>
                </div>
            </div>
            <div class="benefit-card">
                <div class="benefit-icon">✓</div>
                <div class="benefit-content">
                    <h3>Atendimento Personalizado</h3>
                    <p>Consultoria gratuita para ajudar você a escolher o ar-condicionado ideal para o seu espaço.</p>
                </div>
            </div>
            <div class="benefit-card">
                <div class="benefit-icon">✓</div>
                <div class="benefit-content">
                    <h3>Entrega Rápida</h3>
                    <p>Produtos em estoque com entrega expressa ou importação ágil para garantir que sua instalação seja feita no tempo desejado.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Testimonials Section -->
<section id="testimonials" class="testimonials">
    <div class="container">
        <div class="section-title">
            <h2>O Que Dizem Nossos Clientes</h2>
            <p>A satisfação de nossos clientes é o nosso maior patrimônio. Veja alguns depoimentos.</p>
        </div>
        <div class="testimonials-grid">
            <div class="testimonial-card">
                <div class="testimonial-text">
                    <p>"A Air Tech Refrigeração transformou completamente o conforto do meu lar. O ar-condicionado instalado tem uma performance excelente, e o serviço de instalação foi impecável. Super recomendo!"</p>
                </div>
                <div class="testimonial-author">
                    <div class="author-image">
                        <img src="/api/placeholder/100/100" alt="Cliente Ana">
                    </div>
                    <div class="author-details">
                        <h4>Ana Oliveira</h4>
                        <p>São Paulo, SP</p>
                    </div>
                </div>
            </div>
            <div class="testimonial-card">
                <div class="testimonial-text">
                    <p>"Contratei a Air Tech para instalar ar-condicionado em toda a minha casa. Fiquei impressionado com a qualidade e o profissionalismo. O resultado ficou além das expectativas!"</p>
                </div>
                <div class="testimonial-author">
                    <div class="author-image">
                        <img src="/api/placeholder/100/100" alt="Cliente Carlos">
                    </div>
                    <div class="author-details">
                        <h4>Carlos Mendes</h4>
                        <p>Rio de Janeiro, RJ</p>
                    </div>
                </div>
            </div>
            <div class="testimonial-card">
                <div class="testimonial-text">
                    <p>"A consultoria da Air Tech foi fundamental para escolhermos o sistema ideal para o quarto do nosso bebê. O ar-condicionado deixou o ambiente agradável e todos que visitam elogiam muito!"</p>
                </div>
                <div class="testimonial-author">
                    <div class="author-image">
                        <img src="/api/placeholder/100/100" alt="Cliente Mariana">
                    </div>
                    <div class="author-details">
                        <h4>Mariana Santos</h4>
                        <p>Belo Horizonte, MG</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Call to Action Section -->
<section class="cta">
    <div class="container">
        <h2>Transforme Seu Espaço Hoje Mesmo!</h2>
        <p>Entre em contato e solicite um orçamento gratuito <br>
             Estamos aqui para tornar seu ambiente mais confortável e eficiente.</p>
<a href="#contact" class="cta-button">Solicite seu Orçamento</a>
</div>

</section> 
```
