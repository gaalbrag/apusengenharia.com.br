<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apus Engenharia - Construindo o Futuro</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #004080; color: white; padding: 15px 0; text-align: center; }
        nav { display: flex; justify-content: center; background: #002244; padding: 10px; }
        nav a { color: white; text-decoration: none; padding: 10px 20px; }
        nav a:hover { background: #0055AA; }
        .container { width: 80%; margin: auto; padding: 20px; }
        .hero { text-align: center; padding: 50px 0; background: #e0e0e0; }
        .services, .about, .contact { padding: 40px 0; text-align: center; }
        .services div { display: flex; justify-content: space-around; }
        .services div div { width: 30%; background: #f0f0f0; padding: 20px; }
        footer { background: #004080; color: white; text-align: center; padding: 10px 0; margin-top: 20px; }
        input, textarea { width: 100%; padding: 10px; margin-top: 10px; }
        button { background: #004080; color: white; padding: 10px 20px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Apus Engenharia</h1>
        <p>Construindo o futuro com excelência e qualidade</p>
    </header>
    <nav>
        <a href="#home">Início</a>
        <a href="#services">Serviços</a>
        <a href="#about">Sobre Nós</a>
        <a href="#contact">Contato</a>
    </nav>
    <section id="home" class="hero">
        <h2>Bem-vindo à Apus Engenharia</h2>
        <p>Casas de médio e alto padrão, serviços de engenharia sob medida.</p>
    </section>
    <section id="services" class="services">
        <h2>Nossos Serviços</h2>
        <div>
            <div>
                <h3>Casas de Médio Padrão</h3>
                <p>Projetos modernos e eficientes para sua casa dos sonhos.</p>
            </div>
            <div>
                <h3>Casas de Alto Padrão</h3>
                <p>Luxo e sofisticação com alta qualidade construtiva.</p>
            </div>
            <div>
                <h3>Serviços Sob Encomenda</h3>
                <p>Projetos e execuções personalizados para qualquer necessidade.</p>
            </div>
        </div>
    </section>
    <section id="about" class="about">
        <h2>Sobre Nós</h2>
        <p>A Apus Engenharia é referência na construção de casas de médio e alto padrão, oferecendo projetos personalizados e soluções inovadoras para cada cliente.</p>
    </section>
    <section id="contact" class="contact">
        <h2>Contato</h2>
        <p>Entre em contato conosco para saber mais sobre nossos serviços.</p>
        <form action="mailto:seuemail@exemplo.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <textarea name="message" placeholder="Sua Mensagem" rows="5" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Apus Engenharia. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
