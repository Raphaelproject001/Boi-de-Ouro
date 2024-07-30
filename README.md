<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boi de Ouro</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logotipo Boi de Ouro">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#produtos">Produtos</a></li>
                <li><a href="#galeria">Galeria</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home -->
    <section id="home">
        <div class="slider">
            <img src="banner.jpg" alt="Imagem Principal">
        </div>
        <div class="intro">
            <h1>Bem-vindo ao Boi de Ouro</h1>
            <p>Oferecemos produtos de alta qualidade e serviços excepcionais. Conheça mais sobre nós e descubra o que torna o Boi de Ouro especial.</p>
            <a href="#produtos" class="cta">Veja Nossos Produtos</a>
        </div>
    </section>

    <!-- Sobre Nós -->
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <div class="historia">
            <h3>História</h3>
            <p>O Boi de Ouro foi fundado com o objetivo de oferecer produtos e serviços de qualidade. Nossa missão é...</p>
        </div>
        <div class="equipe">
            <h3>Equipe</h3>
            <div class="membro">
                <img src="equipe1.jpg" alt="Membro da Equipe">
                <p>Nome - Função</p>
            </div>
            <!-- Adicione mais membros da equipe conforme necessário -->
        </div>
        <div class="valores">
            <h3>Valores</h3>
            <p>Integridade, Qualidade, e Comprometimento são os nossos principais valores.</p>
        </div>
    </section>

    <!-- Produtos -->
    <section id="produtos">
        <h2>Produtos</h2>
        <div class="produto">
            <img src="produto1.jpg" alt="Produto 1">
            <p>Nome do Produto - Descrição e Preço</p>
        </div>
        <!-- Adicione mais produtos conforme necessário -->
    </section>

    <!-- Galeria -->
    <section id="galeria">
        <h2>Galeria</h2>
        <div class="imagens">
            <img src="imagem1.jpg" alt="Imagem 1">
            <img src="imagem2.jpg" alt="Imagem 2">
            <!-- Adicione mais imagens conforme necessário -->
        </div>
        <div class="videos">
            <video controls>
                <source src="video.mp4" type="video/mp4">
                Seu navegador não suporta a tag de vídeo.
            </video>
        </div>
    </section>

    <!-- Blog -->
    <section id="blog">
        <h2>Blog</h2>
        <article>
            <h3>Título do Post</h3>
            <p>Resumo do post...</p>
            <a href="#">Leia mais</a>
        </article>
        <!-- Adicione mais postagens conforme necessário -->
    </section>

    <!-- Contato -->
    <section id="contato">
        <h2>Contato</h2>
        <form action="send_message.php" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
        <div class="info">
            <p>Endereço: Rua Exemplo, 123, Cidade</p>
            <p>Telefone: (11) 1234-5678</p>
            <p>Email: contato@boideoouro.com</p>
            <div id="map"></div>
            <p>Redes Sociais: <a href="#">Facebook</a>, <a href="#">Instagram</a></p>
        </div>
    </section>

    <!-- Política de Privacidade e Termos de Uso -->
    <section id="politica">
        <h2>Política de Privacidade</h2>
        <p>Informações sobre como coletamos, usamos e protegemos os dados dos visitantes.</p>
        <h2>Termos de Uso</h2>
        <p>Detalhes sobre os termos e condições para o uso do site e dos serviços oferecidos.</p>
    </section>

    <footer>
        <p>&copy; 2024 Boi de Ouro. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
