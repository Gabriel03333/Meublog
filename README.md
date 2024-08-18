<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog Financeiro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header, nav, main, footer {
            padding: 20px;
            margin: 10px;
        }
        header {
            background: #333;
            color: #fff;
            text-align: center;
        }
        nav {
            background: #f4f4f4;
            padding: 15px;
            text-align: center;
        }
        nav a {
            margin-right: 10px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        section {
            margin-bottom: 20px;
            background: #fff;
            padding: 20px;
            border-radius: 5px;
        }
        h1, h2, h3 {
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
        }
        .tags {
            display: flex;
            flex-wrap: wrap;
        }
        .tag {
            background: #e0e0e0;
            margin: 5px;
            padding: 5px 10px;
            border-radius: 3px;
            font-size: 12px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Meu Blog Financeiro</h1>
        <p>Dicas e conselhos para administrar suas finanças</p>
    </header>

    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#artigos">Artigos</a>
        <a href="#dicas">Dicas</a>
        <a href="#contato">Contato</a>
    </nav>

    <main class="container">
        <section id="sobre">
            <h2>Sobre o Blog</h2>
            <p>Bem-vindo ao Meu Blog Financeiro! Aqui você encontrará dicas e orientações sobre como administrar suas finanças pessoais, investir com sabedoria, e alcançar a independência financeira.</p>
        </section>

        <section id="artigos">
            <h2>Artigos Recentes</h2>
            <article>
                <h3>Como Começar a Investir em Ações</h3>
                <p>Investir em ações pode parecer intimidante para iniciantes, mas com as dicas certas, você pode começar a construir um portfólio sólido...</p>
                <a href="#">Leia mais</a>
            </article>

            <article>
                <h3>Planejamento Financeiro para 2024</h3>
                <p>O novo ano é uma excelente oportunidade para revisar suas finanças e estabelecer metas claras para o futuro...</p>
                <a href="#">Leia mais</a>
            </article>
            <!-- Adicione mais artigos conforme necessário -->
        </section>

        <section id="dicas">
            <h2>Dicas de Finanças</h2>
            <div class="tags">
                <div class="tag">Investimentos</div>
                <div class="tag">Orçamento</div>
                <div class="tag">Economia</div>
                <div class="tag">Poupança</div>
                <div class="tag">Renda Extra</div>
                <!-- Continue adicionando tags até atingir o número desejado -->
                <!-- Repita a estrutura abaixo para adicionar mais tags -->
                <!-- Use JavaScript para adicionar tags dinamicamente, se necessário -->
            </div>
        </section>

        <section id="contato">
            <h2>Entre em Contato</h2>
            <form action="#" method="post">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="5" required></textarea>

                <input type="submit" value="Enviar">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Meu Blog Financeiro. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
