# Casos de teste

## CT-01 — Visualizar catálogo (step-by-step)
**Pré-condição:** ambiente acessível.  
**Dados:** catálogo com ao menos um produto disponível.

**Passos**
1. Abrir a URL da loja.
2. Navegar até a página de produtos, se necessário.
3. Aguardar o carregamento.
4. Conferir nome e preço dos produtos.

**Esperado:** produtos disponíveis são exibidos com nome e preço legíveis, coerentes com os dados disponíveis.  
**Pós-condição:** nenhuma alteração de dados.

## CT-02 — Adicionar produto ao carrinho e validar subtotal (step-by-step)
**Pré-condição:** catálogo acessível e produto disponível.  
**Dados:** produto com preço conhecido.

**Passos**
1. Selecionar um produto.
2. Registrar nome e preço exibidos.
3. Acionar “Adicionar ao carrinho”.
4. Abrir o carrinho.
5. Conferir produto, preço unitário e quantidade.
6. Calcular preço × quantidade e comparar com o subtotal.

**Esperado:** o produto correto aparece no carrinho e o subtotal corresponde ao cálculo.  
**Pós-condição:** carrinho contém o item; limpar se a aplicação permitir.

## CT-03 — Catálogo apresenta produtos (BDD)
**Funcionalidade:** Catálogo de produtos  
**Cenário:** Exibir informações essenciais  
- **Dado** que o cliente acessa a página de produtos
- **Quando** o catálogo é carregado
- **Então** cada produto disponível apresenta nome e preço
- **E** as informações são legíveis

## CT-04 — Adicionar produto ao carrinho (BDD)
**Funcionalidade:** Carrinho de compras  
**Cenário:** Adicionar produto disponível  
- **Dado** que o cliente visualiza um produto disponível
- **Quando** adiciona o produto ao carrinho
- **Então** o produto aparece no carrinho
- **E** o preço unitário corresponde ao produto selecionado
- **E** o subtotal corresponde ao preço unitário multiplicado pela quantidade

## Ciclo de testes
| ID | Caso | Status inicial | Evidência |
|---|---|---|---|
| CT-01 | Catálogo | Pendente | Captura e navegador/build |
| CT-02 | Carrinho | Pendente | Produto, preço, quantidade, subtotal |
| CT-03 | BDD catálogo | Pendente | Evidência da execução |
| CT-04 | BDD carrinho | Pendente | Evidência da execução |

Use Pendente, Aprovado, Reprovado ou Bloqueado após a execução real.
