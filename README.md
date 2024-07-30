<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pousada e Lanchonete Point da Nanda</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Pousada e Lanchonete Point da Nanda</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#pousada">Pousada</a></li>
                <li><a href="#lanchonete">Lanchonete</a></li>
                <li><a href="#contato">Contato</a></li>
                <li><a href="#sobre">Sobre Nós</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Bem-vindo ao Point da Nanda!</h2>
            <p>Desfrute de uma experiência única em nossa pousada e lanchonete.</p>
        </section>
        <section id="pousada">
            <h2>Pousada</h2>
            <p>Conheça nossas acomodações e preços.</p>
            <!-- Adicione fotos e detalhes aqui -->
        </section>
        <section id="lanchonete">
            <h2>Lanchonete</h2>
            <p>Confira nosso cardápio e horários de funcionamento.</p>
            <!-- Adicione o cardápio e fotos aqui -->
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form>
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Saiba mais sobre nossa história, missão e valores.</p>
            <!-- Adicione mais informações aqui -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Pousada e Lanchonete Point da Nanda. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}

header {
    background-color: #0044cc;
    color: #ffffff;
    padding: 10px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
    padding: 20px;
    background-color: #ffffff;
    border-radius: 5px;
}

section h2 {
    margin-top: 0;
}

form {
    display: grid;
    gap: 10px;
}

form label {
    font-weight: bold;
}

form input, form textarea {
    width: 100%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    background-color: #00cc66;
    color: #ffffff;
    border: none;
    padding: 10px;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #009944;
}

footer {
    background-color: #0044cc;
    color: #ffffff;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

