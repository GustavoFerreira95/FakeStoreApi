README - False Commerce API Estudo
Este projeto é um site de e-commerce simples que permite aos usuários navegar por produtos, adicioná-los ao carrinho e concluir uma compra. A interface do site interage com uma API fictícia (https://fakestoreapi.com/) para obter e exibir informações sobre produtos.

Sumário
Tecnologias Utilizadas
Estrutura do Projeto
Como Começar
Funcionalidades
Visão Geral do Código

Tecnologias Utilizadas

HTML
CSS
Bootstrap 5
JavaScript (Vanilla)
Fakestore API (https://fakestoreapi.com/)

Estrutura do Projeto
O projeto consiste em vários arquivos HTML, cada um representando uma página diferente do site. Os principais arquivos são:

index.html: Exibe uma lista de produtos, permite filtrar por categoria e fornece links para páginas individuais de produtos.

<!-- Função para carregar todos os produtos -->
function loadProducts()

<!-- Função para carregar produtos por categoria -->
function loadProductsByCategory(category)

<!-- Função para exibir os produtos na página -->
function displayProducts(products)

<!-- Função para redirecionar para a página do produto -->
function redirectToProduct(productId)
<!-------------------------------------------------------------------------------------------------->
produto.html: Apresenta informações detalhadas sobre um produto específico e permite aos usuários adicioná-lo ao carrinho.

<!-- Função para exibir detalhes do produto -->
function displayProduct(product)

<!-- Função para adicionar um produto ao carrinho -->
function addCart(productId)

<!-- Função para atualizar a contagem e exibição do carrinho -->
function updateCartCount()

<!-- Função para adicionar um item ao carrinho -->
function addToCartItems(product)

<!-- Função para atualizar a exibição dos itens no carrinho -->
function updateCartItems()

<!-- Função para buscar informações de frete por CEP -->
function searchCep()

<!-------------------------------------------------------------------------------------------------->
carrinho.html: Mostra o conteúdo do carrinho de compras, permite aos usuários atualizar a quantidade de itens e inserir um endereço de entrega.
<!-- Função para atualizar o container de checkout -->
function updateCheckoutContainer()

<!-- Função para exibir ou ocultar o carrinho -->
function toggleCart()

<!-- Função para finalizar a compra -->
function finalizePurchase()

<!-------------------------------------------------------------------------------------------------->
CompraEfetuada.html: Confirma uma compra bem-sucedida.
<!-------------------------------------------------------------------------------------------------->

Como Começar
Para executar este projeto localmente, siga estas etapas:

Clone o repositório: git clone <(https://github.com/GustavoFerreira95/FakeStoreApi)>
Abra o arquivo HTML desejado em um navegador da web.

Funcionalidades
Visualizar uma lista de produtos, categorizados por eletrônicos, joias, roupas masculinas e femininas.
Filtrar produtos por categoria.
Visualizar informações detalhadas sobre um produto específico.
Adicionar e remover itens do carrinho de compras.
Visualizar e atualizar o carrinho de compras.
Inserir um endereço de entrega e visualizar informações de entrega.
Concluir uma compra e receber uma mensagem de confirmação.

Visão Geral do Código
O projeto utiliza HTML para estruturar as páginas, CSS para estilização e JavaScript para interagir com a API e implementar funcionalidades. O Bootstrap é utilizado para design responsivo e estilização. O código está organizado em seções, incluindo cabeçalho, barra de navegação, exibição de produtos, carrinho e seções de checkout.
