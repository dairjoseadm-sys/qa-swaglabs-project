# Plano de testes

## Objetivo
Validar manualmente os fluxos do catálogo e do carrinho definidos nas US-01 e US-02.

## Escopo
- Exibição de produtos.
- Navegação para produto.
- Adição ao carrinho.
- Conferência de produto, preço, quantidade e subtotal.

## Fora do escopo
Pagamento real, integrações externas, carga, segurança aprofundada e automação.

## Estratégia
- Tipo: funcional.
- Execução: manual.
- Abordagem: caixa-preta.
- Nível: sistema e aceite.
- Ambiente: navegador atualizado e ambiente de teste autorizado; registrar URL, navegador, versão e build.
- Dados: produtos disponíveis com preço conhecido; conta de teste, se login for necessário.

## Riscos
Dados ou catálogo podem mudar; ambiente pode ficar instável; preço do carrinho pode divergir; regras reais podem diferir das hipóteses do documento.

## Entrada
Ambiente acessível, build identificada, histórias refinadas e dados disponíveis.

## Saída
Todos os casos executados, evidências anexadas, bugs registrados e resultados comunicados.
