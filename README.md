<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página do Ian</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #0a0202;
        }
        header {
            background: url('https://via.placeholder.com/1200x300') no-repeat center center;
            background-size: cover;
            color: #fff;
            padding: 30px 0;
            text-align: center;
            position: relative;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin-top: 15px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 90%;
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h2 {
            color: #aa0407;
        }
        footer {
            background-color: #83020c;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: relative;
        }
        footer p {
            margin: 0;
            font-size: 0.9em;
        }
        .contact-info {
            margin-top: 20px;
            font-size: 1.1em;
        }
        .contact-info a {
            color: #03518d;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Olá, eu sou o Ian!</h1>
        <nav>
            <a href="#home">Início</a>
            <a href="#about">Sobre</a>
            <a href="#contact">Contato</a>
        </nav>
    </header>
    
    <div class="container">
        <section id="home">
            <h2>Bem-vindo ao meu site!</h2>
            <p>Fico feliz que você esteja aqui. Este é um espaço onde compartilho meus interesses e ideias. Explore as seções abaixo para saber mais sobre mim e como podemos nos falar e conhecer.</p>
        </section>
        
        <section id="about">
            <h2>Sobre Mim</h2>
            <p>Sou apaixonado por tecnologia, arte e música. Neste site, você encontrará informações sobre meus projetos, interesses e um pouco mais sobre minha trajetória pessoal. Espero que você encontre algo que ressoe com você!</p>
        </section>
        
        <section id="contact">
            <h2>Vamos Conversar</h2>
            <p>Se você quiser bater um papo ou tiver alguma pergunta, não hesite em me contatar. Estou sempre aberto a novas conexões!</p>
            <div class="contact-info">
                <p>Envie um e-mail para <a href="mailto:ian@exemplo.com">ian@exemplo.com</a> ou me siga nas redes sociais.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Página do Ian. Todos os direitos reservados. Feito com carinho.</p>
    </footer>
</body>
</html>
