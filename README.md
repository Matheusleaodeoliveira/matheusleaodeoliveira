<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechBoost - Impulsionando Seu Negócio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>TechBoost - Impulsionando Seu Negócio</h1>
        <p>Descrição da Empresa: A TechBoost é uma startup inovadora que oferece soluções de software personalizadas para ajudar outras empresas a alcançar seu potencial máximo. Desde aplicativos móveis até plataformas de comércio eletrônico, estamos aqui para impulsionar o crescimento do seu negócio.</p>
    </header>

    <section class="product">
        <h2>Nosso Produto</h2>
        <img src="https://via.placeholder.com/600x400.png" alt="TechBoost">
        <p>O TechBoost é uma plataforma de análise avançada que fornece insights valiosos para impulsionar o crescimento do seu negócio. Com recursos poderosos e uma interface intuitiva, ajudamos empresas de todos os tamanhos a tomar decisões informadas e estratégicas.</p>
    </section>

    <section class="team">
        <h2>Conheça Nossa Equipe</h2>
        <div class="team-member">
            <img src="https://via.placeholder.com/150" alt="Alice Silva - CEO">
            <h3>Alice Silva - CEO</h3>
            <p>CEO e fundadora da TechBoost, Alice lidera nossa equipe com visão e paixão pelo sucesso dos clientes.</p>
        </div>
        <div class="team-member">
            <img src="https://via.placeholder.com/150" alt="Pedro Santos - CTO">
            <h3>Pedro Santos - CTO</h3>
            <p>Como nosso CTO, Pedro é o cérebro por trás da inovação tecnológica que impulsiona o TechBoost.</p>
        </div>
        <div class="team-member">
            <img src="https://via.placeholder.com/150" alt="Carla Oliveira - Desenvolvedora Sênior">
            <h3>Carla Oliveira - Desenvolvedora Sênior</h3>
            <p>Carla é uma desenvolvedora talentosa que trabalha duro para criar soluções de software de qualidade para nossos clientes.</p>
        </div>
    </section>

    <section class="signup">
        <h2>Inscreva-se para uma Demonstração Gratuita</h2>
        <form action="seu-script-de-processamento.php" method="post">
            <input type="text" name="nome" placeholder="Nome" required><br>
            <input type="email" name="email" placeholder="E-mail" required><br>
            <button type="submit">Inscreva-se</button>
        </form>
    </section>

    <footer>
        <h3>Sobre Nós</h3>
        <p>TechBoost é uma startup focada em fornecer soluções de software para impulsionar o crescimento empresarial. Nós nos esforçamos para oferecer produtos de alta qualidade e um serviço excepcional aos nossos clientes.</p>
        <h3>Contate-nos</h3>
        <p>Para mais informações sobre como o TechBoost pode ajudar sua empresa, entre em contato conosco em <a href="mailto:email@techboost.com">email@techboost.com</a>.</p>
    </footer>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header, footer, section {
    padding: 20px;
}

h1, h2, h3 {
    margin-top: 0;
}

.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.team-member {
    text-align: center;
    margin-bottom: 20px;
}

.team-member img {
    border-radius: 50%;
    margin-bottom: 10px;
}

form input, form button {
    margin-bottom: 10px;
}

form input, form button {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #007bff;
    color: #fff;
    cursor: pointer;
}

form button:hover {
    background-color: #0056b3;
}
