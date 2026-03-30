<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Doces gourmet - Doces Caseiros</title>
  <link rel="stylesheet" href="style.css">
  <script>
    let carrinho = [];
    
    function adicionarAoCarrinho(nomeProduto, preco) {
      carrinho.push({nome: nomeProduto, preco: preco});
      alert(nomeProduto + ' adicionado ao carrinho!');
      localStorage.setItem('carrinho', JSON.stringify(carrinho));
    }
  </script>
</head>
<body>
  <header>
    <h1>🍰 Doces gourmet</h1>
    <nav>
      <a href="index.html">Produtos</a>
      <a href="sabores.html">Sabores</a>
      <a href="sobre.html">Sobre</a>
      <a href="carrinho.html">🛒 Carrinho</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h2>Bem-vindo ao nosso catálogo de doces deliciosos!</h2>
      <p>Brownies, cookies , docinhos os melhores ingredientes</p>
    </section>

    <h2 class="titulo-produtos">Nossos Produtos</h2>
    
    <div class="produtos">
      <div class="produto">
        <img src="https://images.unsplash.com/photo-1607623814075-e51df1bdc82f?auto=format&fit=crop&w=400&q=80" alt="Brownie de Chocolate">
        <h3>Brownie</h3>
        <p class="descricao">Brownie caseiro, macio e cremoso no ponto certo</p>
        <p class="preco">R$ 12,00</p>
        <button onclick="adicionarAoCarrinho('Brownie', 12.00)">Adicionar ao Carrinho</button>
      </div>

      <div class="produto">
        <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?auto=format&fit=crop&w=400&q=80" alt="Cookie">
        <h3>Cookie</h3>
        <p class="descricao">Cookie crocante por fora, macio por dentro com gotas de chocolate</p>
        <p class="preco">R$ 8,00</p>
        <button onclick="adicionarAoCarrinho('Cookie', 8.00)">Adicionar ao Carrinho</button>
      </div>

      <div class="produto">
        <img src="https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=400&q=80" alt="Docinhos">
        <h3>Docinhos Variados</h3>
        <p class="descricao">Brigadeiro, beijinho, cajuzinho e muito mais!</p>
        <p class="preco">R$ 15,00 / caixa</p>
        <button onclick="adicionarAoCarrinho('Docinhos Variados', 15.00)">Adicionar ao Carrinho</button>
      </div>

      <div class="produto">
        <img src="https://images.unsplash.com/photo-1607623814075-e51df1bdc82f?auto=format&fit=crop&w=400&q=80" alt="Brownie com Nozes">
        <h3>Brownie Premium</h3>
        <p class="descricao">Brownie com gotas de chocolate e nozes</p>
        <p class="preco">R$ 14,00</p>
        <button onclick="adicionarAoCarrinho('Brownie Premium', 14.00)">Adicionar ao Carrinho</button>
      </div>

      <div class="produto">
        <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?auto=format&fit=crop&w=400&q=80" alt="Cookie Branco">
        <h3>Cookie Branco</h3>
        <p class="descricao">Cookie com chocolate branco e cranberry</p>
        <p class="preco">R$ 9,00</p>
        <button onclick="adicionarAoCarrinho('Cookie Branco', 9.00)">Adicionar ao Carrinho</button>
      </div>

      <div class="produto">
        <img src="https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=400&q=80" alt="Docinho Premium">
        <h3>Kit Premium</h3>
        <p class="descricao">Seleção premium de docinhos finos</p>
        <p class="preco">R$ 25,00 / caixa</p>
        <button onclick="adicionarAoCarrinho('Kit Premium', 25.00)">Adicionar ao Carrinho</button>
      </div>
    </div>
  </main>

  <footer>
    <p>&copy; 2026 Doces gourmet. Todos os direitos reservados.</p>
    <p>Contato: (XX) 9999-9999 | emailrocha.graciele@escola.pr.gov.br
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sabores | Doces gourmet</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🍰 Doces gourmet</h1>
    <nav>
      <a href="index.html">Produtos</a>
      <a href="sabores.html">Sabores</a>
      <a href="sobre.html">Sobre</a>
      <a href="carrinho.html">🛒 Carrinho</a>
    </nav>
  </header>

  <main>
    <h2>Sabores Disponíveis</h2>
    
    <div class="sabores-container">
      <section class="sabor-grupo">
        <h3>🍫 Brownies</h3>
        <ul>
          <li>Chocolate Tradicional</li>
          <li>Chocolate com Nozes</li>
          <li>Chocolate Branco</li>
          <li>Duplo Chocolate</li>
          <li>Brownie com Calda</li>
        </ul>
      </section>

      <section class="sabor-grupo">
        <h3>🍪 Cookies</h3>
        <ul>
          <li>Chocolate Clássico</li>
          <li>Chocolate Branco com Cranberry</li>
          <li>Red Velvet</li>
          <li>Cookies and Cream</li>
          <li>Morango com Chocolate</li>
        </ul>
      </section>

      <section class="sabor-grupo">
        <h3>🍬 Docinhos</h3>
        <ul>
          <li>Brigadeiro Tradicional</li>
          <li>Brigadeiro Gourmet</li>
          <li>Beijinho de Coco</li>
          <li>Cajuzinho</li>
          <li>Dois Amores</li>
          <li>Bicho de Pé</li>
          <li>Romeu e Julieta</li>
          <li>Bombom de Amendoim</li>
        </ul>
      </section>
    </div>

    <section class="info-sabores">
      <h3>Ingredientes Premium</h3>
      <p>Todos os nossos produtos são feitos com:</p>
      <ul>
        <li>✓ Chocolate de qualidade premium</li>
        <li>✓ Frutas e ingredientes naturais</li>
        <li>✓ Sem conservantes artificiais</li>
        <li>✓ Feitos com amor e dedicação</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Doces gourmet. Todos os direitos reservados.</p>
    <p>Contato: (XX) 9999-9999 | emailrocha.graciele@escola.pr.gov.br.com</p>
  </footer>
</body>
</html>


