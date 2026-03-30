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
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sobre | Doces gourmet</title>
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
    <section class="sobre-empresa">
      <h2>Sobre Nós</h2>
      <p>
        Bem-vindo à <strong>Doces gourmet</strong>, seu destino para doces caseiros feitos com paixão e os melhores ingredientes! 
        Fundada em 2020, nossa empresa nasceu do amor pela confeitaria artesanal e do desejo de compartilhar momentos doces com você.
      </p>
      <p>
        Acreditamos que todo doce deve ser feito com carinho, usando apenas ingredientes de qualidade premium, sem conservantes artificiais. 
        Cada brownie, cookie e docinho é uma expressão do nosso compromisso com a excelência.
      </p>
    </section>

    <section class="nossa-historia">
      <h3>Nossa História</h3>
      <p>
        Tudo começou na cozinha de Graciele Rocha, apaixonada por confeitaria desde criança. 
        Com receitas criadas com dedicação e experiência, transformamos matérias-primas simples em doces extraordinários. 
        Hoje, nossa marca é sinônimo de qualidade, sabor e confiança.
      </p>
    </section>

    <section class="equipe">
      <h2>Nossa Equipe</h2>
      <div class="funcionarios">
        <div class="funcionario">
          <div class="avatar">👩‍🍳</div>
          <h4>Graciele Rocha</h4>
          <p class="cargo">Fundadora & Chef Confeiteira</p>
          <p class="descricao">Apaixonada por confeitaria, cria todas as receitas especiais com dedicação e inovação.</p>
        </div>

        <div class="funcionario">
          <div class="avatar">👩‍💼</div>
          <h4>Ana Paula Silva</h4>
          <p class="cargo">Gerente de Atendimento</p>
          <p class="descricao">Responsável por garantir que cada cliente receba o melhor atendimento e experiência.</p>
        </div>

        <div class="funcionario">
          <div class="avatar">👨‍💼</div>
          <h4>Lucas Gomes</h4>
          <p class="cargo">Logística & Entregas</p>
          <p class="descricao">Garante que seus doces cheguem frescos e perfeitos ao seu destino.</p>
        </div>

        <div class="funcionario">
          <div class="avatar">👩‍🔧</div>
          <h4>Camila Santos</h4>
          <p class="cargo">Auxiliar de Confeitaria</p>
          <p class="descricao">Ajuda na preparação e controle de qualidade de todos os nossos produtos.</p>
        </div>
      </div>
    </section>

    <section class="valores">
      <h2>Nossos Valores</h2>
      <div class="valores-grid">
        <div class="valor">
          <h4>🎯 Qualidade</h4>
          <p>Cada produto é feito com excelência</p>
        </div>
        <div class="valor">
          <h4>❤️ Paixão</h4>
          <p>Colocamos amor em cada receita</p>
        </div>
        <div class="valor">
          <h4>🌟 Inovação</h4>
          <p>Criamos novos sabores constantemente</p>
        </div>
        <div class="valor">
          <h4>🤝 Confiança</h4>
          <p>Você é nosso cliente mais importante</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Doces gourmet. Todos os direitos reservados.</p>
    <p>Contato: (XX) 9999-9999 | emailrocha.graciele@gmail.com</p>
  </footer>
</body>
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carrinho | Doces gourmet</title>
  <link rel="stylesheet" href="style.css">
  <script>
    let carrinho = JSON.parse(localStorage.getItem('carrinho')) || [];

    function carregarCarrinho() {
      const listaCarrinho = document.getElementById('lista-carrinho');
      const totalElement = document.getElementById('total');
      
      if (carrinho.length === 0) {
        listaCarrinho.innerHTML = '<p class="vazio">Seu carrinho está vazio. <a href="index.html">Volte e adicione produtos!</a></p>';
        totalElement.innerHTML = '';
        return;
      }

      let html = '';
      let total = 0;

      carrinho.forEach((item, index) => {
        total += item.preco;
        html += `
          <div class="item-carrinho">
            <span>${item.nome}</span>
            <span>R$ ${item.preco.toFixed(2)}</span>
            <button onclick="removerItem(${index})" class="btn-remover">Remover</button>
          </div>
        `;
      });

      listaCarrinho.innerHTML = html;
      totalElement.innerHTML = `<h3>Total: R$ ${total.toFixed(2)}</h3>`;
    }

    function removerItem(index) {
      carrinho.splice(index, 1);
      localStorage.setItem('carrinho', JSON.stringify(carrinho));
      carregarCarrinho();
    }

    function limparCarrinho() {
      carrinho = [];
      localStorage.setItem('carrinho', JSON.stringify(carrinho));
      carregarCarrinho();
    }

    function finalizarPedido() {
      if (carrinho.length === 0) {
        alert('Seu carrinho está vazio!');
        return;
      }

      let total = carrinho.reduce((sum, item) => sum + item.preco, 0);
      alert('Obrigado por sua compra!\n\nItens: ' + carrinho.length + '\nTotal: R$ ' + total.toFixed(2) + '\n\nSeu pedido foi registrado com sucesso!');
      limparCarrinho();
      window.location.href = 'index.html';
    }

    window.onload = carregarCarrinho;
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
    <h2>🛒 Seu Carrinho de Compras</h2>
    
    <div class="container-carrinho">
      <div id="lista-carrinho" class="lista-carrinho">
        <!-- Items do carrinho aparecem aqui -->
      </div>

      <div id="total" class="resumo-total">
        <!-- Total aparece aqui -->
      </div>

      <div class="botoes-acao">
        <button onclick="limparCarrinho()" class="btn-limpar">Limpar Carrinho</button>
        <button onclick="finalizarPedido()" class="btn-finalizar">Finalizar Pedido</button>
      </div>
    </div>

    <section class="info-entrega">
      <h3>Informações de Entrega</h3>
      <p>Após finalizar seu pedido, você receberá um e-mail com os detalhes e rastreamento.</p>
      <p><strong>Frete:</strong> Grátis para compras acima de R$ 50,00</p>
      <p><strong>Prazo de Entrega:</strong> 2 a 5 dias úteis</p>
      <p><strong>Formas de Pagamento:</strong> Cartão de Crédito, Débito, Pix e Boleto</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Doces gourmet. Todos os direitos reservados.</p>
    <p>Contato: (XX) 9999-9999 | emailrocha.graciele@escola.pr.gov.br.com</p>
  </footer>
</body>
</html>
