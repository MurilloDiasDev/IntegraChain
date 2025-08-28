<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IntegraChain - Integração e Consultoria para E-commerce</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #1abc9c;
            --secondary-color: #2980b9;
            --dark-color: #2c3e50;
            --light-color: #ecf0f1;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: var(--dark-color);
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 2rem 0;
            text-align: center;
        }

        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 4rem 0;
        }

        .hero-content {
            flex: 1;
            padding-right: 2rem;
        }

        .hero-image {
            flex: 1;
            text-align: right;
        }

        .hero-image img {
            max-width: 100%;
            height: auto;
        }

        .btn {
            display: inline-block;
            background: var(--secondary-color);
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: var(--primary-color);
        }

        .services {
            background: var(--light-color);
            padding: 4rem 0;
            text-align: center;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .service-card:hover {
            transform: translateY(-10px);
        }

        .service-card i {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        footer {
            background: var(--dark-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        @media (max-width: 768px) {
            .hero {
                flex-direction: column;
                text-align: center;
            }

            .hero-content {
                padding-right: 0;
                margin-bottom: 2rem;
            }

            .hero-image {
                text-align: center;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>IntegraChain</h1>
            <p>Transformando Integrações em Oportunidades de Negócio</p>
        </div>
    </header>

    <section class="hero container">
        <div class="hero-content">
            <h2>Potencialize Suas Vendas com Integração Inteligente</h2>
            <p>Conectamos seus produtos aos principais marketplaces, otimizando sua estratégia de e-commerce com tecnologia de ponta.</p>
            <a href="#contato" class="btn">Fale Conosco</a>
        </div>
        <div class="hero-image">
            <img src="https://cdn.pixabay.com/photo/2020/05/18/14/08/network-5187675_1280.jpg" alt="Integração de Sistemas">
        </div>
    </section>

    <section class="services container">
        <h2>Nossos Serviços</h2>
        <p>Soluções completas para sua estratégia de vendas online</p>
        
        <div class="services-grid">
            <div class="service-card">
                <i class="fas fa-sync"></i>
                <h3>Integração de Fornecedores</h3>
                <p>Conectamos seus fornecedores aos principais marketplaces de forma simples e eficiente.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-chart-line"></i>
                <h3>Consultoria de Vendas</h3>
                <p>Análise estratégica para maximizar seus resultados e identificar novas oportunidades.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-laptop-code"></i>
                <h3>Soluções Tecnológicas</h3>
                <p>Desenvolvemos tecnologias personalizadas para automatizar e otimizar seus processos.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-shopping-cart"></i>
                <h3>Gestão de Marketplaces</h3>
                <p>Gerenciamento completo de suas vendas em múltiplas plataformas de e-commerce.</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 IntegraChain. Todos os direitos reservados.</p>
            <p>Transformando dados em estratégias, estratégias em vendas.</p>
        </div>
    </footer>
</body>
</html>
