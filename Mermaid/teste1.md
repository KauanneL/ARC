```mermaid
flowchart TD
  A[Escolher produto] --> B[Adicionar ao carrinho]
  B --> C[Fazer checkout]
  C --> D[Inserir dados de pagamento]
  D --> E{Pagamento aprovado?}
  E -- Sim --> F[Pedido confirmado]
  E -- Não --> G[Mostrar erro]
```