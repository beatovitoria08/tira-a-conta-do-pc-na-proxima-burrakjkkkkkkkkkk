VK MODAS 
html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Loja de Desapegos</title>
  <style>
    /* Adicione estilos CSS de sua preferência para personalizar o site */
  </style>
</head>
<body>
  <header>
    <h1>Loja de Desapegos</h1>
    <nav>
      <ul>
        <li><a href="#">Início</a></li>
        <li><a href="#">Produtos</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Sobre Nós</h2>
      <p>Texto sobre a loja de desapegos e sua proposta.</p>
    </section>

    <section>
      <h2>Produtos</h2>
      <!-- Lista de produtos com fotos -->
      <div>
        <img src="caminho/para/imagem1.jpg" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>Descrição do Produto 1</p>
      </div>
      <div>
        <img src="caminho/para/imagem2.jpg" alt="Produto 2">
        <h3>Produto 2</h3>
        <p>Descrição do Produto 2</p>
      </div>
      <!-- Adicione mais produtos conforme necessário -->
    </section>

    <section>
      <h2>Contato</h2>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>

        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem" name="mensagem" required></textarea><br>

        <input type="submit" value="Enviar">
      </form>
    </section>
  </main>

  <footer>
    <p>Loja de Desapegos &copy; 2022</p>
  </footer>
</body>
</html>