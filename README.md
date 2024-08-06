[Diálogo](https://efficient-sloth-d85.notion.site/Atividade-Mapeando-o-dom-nio-38963358ffd74289b824ff73b187165d)

### Entidades de Domínio
1. **Produto**
   - Atributos:
     - Número de identificação único
     - Nome
     - Tamanho
     - Cor
     - Quantidade em estoque
     - Quantidade mínima de estoque
     - Informações adicionais (se necessário)

2. **Movimentação de Estoque**
   - Atributos:
     - Produto (referência)
     - Data da movimentação
     - Quantidade movida
     - Tipo de movimentação (entrada/saída)
     - Motivo da movimentação (venda, devolução, reposição, etc.)

3. **Histórico de Vendas**
   - Atributos:
     - Produto (referência)
     - Data da venda
     - Quantidade vendida
     - Preço de venda
     - Lucro gerado

4. **Ordem de Compra**
   - Atributos:
     - Produto (referência)
     - Quantidade solicitada
     - Data de solicitação
     - Data de entrega prevista
     - Fornecedor

5. **Fornecedor**
   - Atributos:
     - Nome
     - Contato
     - Informações de entrega

### Ações (Casos de Uso)
1. **Rastrear Produto**
   - Atribuir número de identificação único a cada produto.
   - Adicionar informações detalhadas (tamanho, cor, etc.) para cada produto.
   - Registrar movimentações de estoque (entrada/saída).

2. **Definir Quantidade Mínima de Estoque**
   - Configurar limite mínimo de estoque para cada produto.
   - Atualizar e gerenciar essas quantidades mínimas conforme necessário.

3. **Receber Alertas de Estoque Baixo**
   - Enviar alertas por e-mail quando o estoque de um produto atingir a quantidade mínima.
   - Mostrar notificações no sistema de gerenciamento de estoque.

4. **Visualizar Histórico de Vendas e Estoque**
   - Exibir vendas de produtos em um determinado período.
   - Mostrar lucro gerado por produto.
   - Identificar produtos mais vendidos em cada período.
   - Analisar tendências de estoque ao longo do tempo.

5. **Gerenciar Ordens de Compra**
   - Criar ordens de compra automaticamente com base nas quantidades mínimas de estoque e tendências de vendas.
   - Manter um registro de ordens de compra, incluindo datas de solicitação e entrega prevista.
   - Integrar com fornecedores para atualizações automáticas sobre prazos de entrega.

6. **Integração com Fornecedores**
   - Manter informações de contato e detalhes de entrega dos fornecedores.
   - Atualizar prazos de entrega automaticamente com base nas informações recebidas dos fornecedores.
