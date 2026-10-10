# Épicos e User Stories

> As histórias abaixo são propostas de estudo, não requisitos oficiais confirmados do ambiente. Revise-as após explorar o projeto.

## Épico E-01 — Descoberta e seleção de produtos

### US-01 — Visualizar catálogo
**Como** cliente da loja virtual, **quero** visualizar os produtos disponíveis com nome, preço e imagem, **para** comparar opções antes de decidir o que comprar.

**Valor:** apoiar a descoberta e comparação de produtos.  
**Atores:** cliente e sistema.  
**Interface/fluxo:** catálogo de produtos.  
**Dados:** nome, preço, imagem e disponibilidade.

**Critérios de aceite**
- **Dado** que o cliente acessa a página de produtos, **quando** o catálogo termina de carregar, **então** os produtos disponíveis são exibidos com nome e preço.
- **Dado** que o catálogo apresenta um produto, **quando** o cliente seleciona esse produto, **então** o sistema apresenta as informações correspondentes ao produto selecionado.

## Épico E-02 — Carrinho e preparação da compra

### US-02 — Adicionar produto ao carrinho
**Como** cliente da loja virtual, **quero** adicionar um produto ao carrinho, **para** reunir os itens que pretendo comprar antes de finalizar o pedido.

**Valor:** permitir seleção de itens para compra.  
**Atores:** cliente e sistema.  
**Interface/fluxo:** catálogo/detalhe do produto → carrinho.  
**Dados:** produto, preço unitário, quantidade e subtotal.

**Critérios de aceite**
- **Dado** que o cliente está visualizando um produto disponível, **quando** seleciona a opção de adicionar ao carrinho, **então** o produto aparece no carrinho com preço e quantidade corretos.
- **Dado** que há um produto no carrinho, **quando** o cliente visualiza o resumo, **então** o subtotal corresponde ao preço unitário multiplicado pela quantidade.

## Refinamento INVEST
Revisar com a equipe se as histórias são independentes, negociáveis, valiosas, estimáveis, pequenas e testáveis. Estimativas de story points são apenas ilustrativas até a discussão do time.
