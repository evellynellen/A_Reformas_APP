

# A REFORMAS APP

## Ideias Iniciais
O app será usado para ajudar na criação e organização de orçamentos para obras e projetos. Ele deve permitir o cadastro de clientes, materiais e serviços, e gerar automaticamente o orçamento final com todos os custos calculados.

## Funcionalidades Principais
1. **Cadastro de Cliente**: Adicionar informações básicas, como nome, contato e endereço.
2. **Cadastro de Materiais**: Informações de nome, preço unitário e quantidade.
3. **Cadastro de Serviço**: Descrição do serviço, horas trabalhadas e preço por hora.
4. **Geração de Orçamento**:
   - Cálculo total com base nos materiais e serviços adicionados.
   - Relatório detalhado com todas as informações.

## Fluxo do Usuário
1. O usuário abre o app e escolhe se deseja cadastrar um cliente, adicionar materiais, incluir serviços ou gerar um orçamento.
2. Cada etapa tem opções para visualizar e editar os dados antes de finalizar.
3. O orçamento gerado pode ser exibido e, em uma versão futura, exportado.

## O que Já Foi Feito
### Classe Cliente
- Contém nome, contato e endereço do cliente.
- Possui um método para exibir os dados do cliente.

### Classe Material
- Contém nome, preço unitário e quantidade.
- Possui métodos para calcular o custo total do material e exibir as informações.

### Teste Inicial
- Criadas instâncias de cliente e materiais na classe `main` e testados os métodos de exibição.

## Próximos Passos
1. Criar a classe `Servico`.
2. Criar a classe `Orcamento` para integrar clientes, materiais e serviços.
3. Testar o cálculo completo do orçamento.
