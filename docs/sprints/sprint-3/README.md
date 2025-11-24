# Relatório - 3º Sprint

## 🎯 Objetivo da Sprint

Desenvolver e aprimorar funcionalidades para melhorar a extração de
documentos, padronização de dados, otimização da IA e evolução da
infraestrutura do sistema.

## 📋 Backlog da Sprint

  ------------------------------------------------------------------------
  Rank           Prioridade                   User Story
  -------------- ---------------------------- ----------------------------
  1              Alta                         Como analista, quero que o
                                              sistema melhore a extração
                                              de PDFs variados para
                                              garantir consistência nas
                                              informações.

  2              Alta                         Como usuário, quero gerar o
                                              relatório final em Excel
                                              diretamente do sistema para
                                              agilizar meu processo.

  3              Média                        Como analista, quero que a
                                              arquitetura da IA seja
                                              otimizada para obter
                                              desempenho mais estável.

  4              Média                        Como usuário, quero
                                              visualizar histórico e
                                              detalhes dos dados do banco
                                              de forma clara.

  5              Baixa                        Como usuário, quero que o
                                              sistema trate erros de forma
                                              clara e permita atualizar e
                                              excluir registros.

  ------------------------------------------------------------------------

## 🏅 DoR - Definition of Ready

  -----------------------------------------------------------------------
  Critério                        Descrição
  ------------------------------- ---------------------------------------
  Dados Disponíveis               Dados de entrada, amostras ou testes
                                  necessários estão disponíveis para uso.

  Critérios Técnicos Acordados    Funcionalidades, rotas, serviços e
                                  integrações definidas e validadas pelo
                                  time.

  Estrutura Definida              Banco de dados, campos obrigatórios ou
                                  estrutura de relatórios confirmados.

  Ambiente Preparado              Backend e Frontend funcional, automação
                                  inicial pronta.

  Estimativa e Planejamento       Esforço estimado ou prioridade definida
                                  para execução.
  -----------------------------------------------------------------------

## 🏅 DoD - Definition of Done

  -----------------------------------------------------------------------
  Critério                          Descrição
  --------------------------------- -------------------------------------
  Critérios de Aceitação atendidos  Todos os cenários da história foram
                                    testados e aprovados.

  Funcionalidade Implementada       Backend, frontend e componentes
                                    entregues conforme esperado e
                                    integrados.

  Feedback e Interação Validados    Interfaces funcionando como esperado.

  Automação e Containers            Scripts de build, Docker e integração
                                    contínua implementados.

  Documentação Atualizada           Documentação técnica revisada e
                                    atualizada.

  Validação do PO                   O Product Owner validou a entrega.
  -----------------------------------------------------------------------

## 📈 Critérios de Aceitação

### Melhoria na extração e diversificação de PDFs

-   Deve extrair corretamente dados essenciais mesmo com layouts
    diferentes.
-   Deve lidar com Invoices variadas sem quebra de fluxo.

### Tradução e padronização das descrições (supplier_desc)

-   Descrições devem ser traduzidas para PT-BR.
-   Campos devem seguir o mesmo padrão textual.

### Refatoração do pipeline com tratamento de exceções

-   O sistema deve registrar erros e continuar processando.
-   Logs devem estar claros e acessíveis.

### Exportação do Excel

-   Sistema deve gerar Excel fiel aos dados do banco.
-   Deve conter todos os campos obrigatórios combinados com o cliente.

### Otimização da arquitetura da IA

-   Respostas mais rápidas e estáveis.
-   Processamento deve ocorrer sem travamentos.

### Histórico e gerenciamento de dados

-   Páginas de histórico e entidades devem exibir dados corretamente.
-   Navegação deve ser simples e clara.

### Operações de update e delete

-   Atualizações devem refletir no banco imediatamente.
-   Exclusões devem funcionar sem inconsistências.

### Testes automatizados

-   Testes Pytest devem validar partes essenciais do sistema.
-   Pipeline deve executá-los automaticamente.


