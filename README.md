<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Solutions - Sua Solução em Tecnologia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2 {
            margin-top: 0;
        }
        .team {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 40px;
        }
        .member {
            text-align: center;
        }
        .member img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        footer {
            background-color: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            margin-top: 40px;
        }
        form {
            margin-top: 40px;
        }
        input[type="text"], input[type="email"], select {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tech Solutions</h1>
        <p>Sua Solução em Tecnologia</p>
    </header>
    <div class="container">
        <h2>Descrição</h2>
        <p>Somos uma empresa líder em tecnologia e soluções, oferecendo serviços abrangentes em segurança da informação, inteligência artificial, desenvolvimento de sistemas, governança em tecnologia, computação em nuvem, desenvolvimento mobile, engenharia de software, engenharia DevOps, segurança cibernética e UX design.</p>

        <h2>Equipe</h2>
        <div class="team">
            <div class="member">
                <img src="team_member1.jpg" alt="Membro da Equipe 1">
                <h3>João Silva</h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="team_member2.jpg" alt="Membro da Equipe 2">
                <h3>Maria Santos</h3>
                <p>CTO</p>
            </div>
            <div class="member">
                <img src="team_member3.jpg" alt="Membro da Equipe 3">
                <h3>Pedro Almeida</h3>
                <p>Engenheiro de Software</p>
            </div>
        </div>

        <h2>Formulário de Inscrição</h2>
        <form action="#" method="post">
            <input type="text" name="nome" placeholder="Nome" required><br>
            <input type="email" name="email" placeholder="E-mail" required><br>
            <input type="text" name="cidade" placeholder="Cidade" required><br>
            <select name="estado" required>
                <option value="" disabled selected>Selecione o Estado</option>
                <option value="AC">Acre</option>
                <option value="AL">Alagoas</option>
                <!-- Adicione mais estados aqui -->
            </select><br>
            <input type="submit" value="Enviar">
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Tech Solutions. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
