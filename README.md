<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Solutions - Consultoria em Tecnologia</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Tech Solutions</h1>
        <p>Consultoria em Tecnologia</p>
    </header>

    <section class="services">
        <h2>Nossos Serviços</h2>
        <ul>
            <li>Desenvolvimento Web</li>
            <li>Desenvolvimento de Aplicativos Móveis</li>
            <li>Consultoria em TI</li>
        </ul>
    </section>

    <section class="contact">
        <h2>Entre em Contato</h2>
        <p>Preencha o formulário abaixo e entraremos em contato com você em breve.</p>
        <form>
            <input type="text" placeholder="Seu Nome">
            <input type="email" placeholder="Seu E-mail">
            <textarea placeholder="Sua Mensagem"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Tech Solutions. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 50px 0;
}

.services {
    padding: 50px 20px;
    text-align: center;
}

.services ul {
    list-style-type: none;
    padding: 0;
}

.contact {
    background-color: #f2f2f2;
    padding: 50px 20px;
    text-align: center;
}

.contact form {
    display: flex;
    flex-direction: column;
}

.contact form input,
.contact form textarea,
.contact form button {
    margin-bottom: 10px;
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
