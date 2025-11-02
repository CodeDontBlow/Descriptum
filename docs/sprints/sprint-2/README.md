<h1 align="center">  Relatório - 2º Sprint </h1>
<br>

## 🎯 Objetivo da Sprint
Desenvolver Aplicação Web para automatizar a análise de documentos de importação, padronizar descrições técnicas e validar classificações fiscais, garantindo conformidade no processo de Registro de Importação.

## 📋 Backlog da Sprint
  
|   Rank  | Prioridade  | User Story | 
| :-----: | :------------------------------------------------------: | :----: | 
|  1    | Alta  |Como analista, quero que o sistema sugira o NCM mais provável do produto, para agilizar o preenchimento do Registro de Importação. |
|  2   | Média  | Como usuário, quero visualizar uma interface simples e intuitiva para upload de documentos e validação dos resultados, para facilitar meu dia a dia. |

## 🏅 DoR - Definition of Ready

|             Critério             | Descrição                                                                                         |
| :------------------------------: | ------------------------------------------------------------------------------------------------- |
|       Dados Disponíveis       | Dados de entrada, amostras ou testes necessários estão disponíveis para uso.  |
| Critérios Técnicos Acordados | Funcionalidades, rotas, serviços e integrações definidas e validadas pelo time. |
|    Estrutura Definida     | Banco de dados, campos obrigatórios ou estrutura de relatórios confirmados.           |
|          Ambiente Preparado             | Backend e Frontend funcional, automação inicial pronta.  |
|   Estimativa e Planejamento   | Esforço estimado ou prioridade definida para execução.   |

## 🏅 DoD - Definition of Done

|                 Critério                 | Descrição                                                                            |
| :--------------------------------------: | ------------------------------------------------------------------------------------ |
|     Critérios de Aceitação atendidos     | Todos os cenários da história foram testados e aprovados.   |
|     Funcionalidade Implementada             | Backend, frontend e componentes entregues conforme esperado e integrados. |
|  Feedback e Interação Validados  | Interfaces e interações (drag & drop, step map, checklist) funcionando.  |
|   Automação e Containers         | Scripts de build, Docker e integração contínua implementados e testados.    |
|  Documentação Atualizada                | Artefatos, aprendizado e documentação técnica adicionados ao repositório. |
|             Validação do PO              | O Product Owner validou a entrega com base nos critérios definidos.                  |

## 📈 Critérios de Aceitação

### Desenvolver script de webscraping

Cenário: Coleta automática de dados de fontes externas. <br>
Dado que o sistema precisa extrair informações de catálogos e sites externos, <br>
Quando o script de webscraping for executado, <br>
Então ele deve coletar os dados de forma estruturada e salvar os resultados em formato padrão. <br>

### Dockerização do backend

Cenário: Padronização do ambiente de execução. <br>
Dado que o backend já está funcional em ambiente local, <br>
Quando o Dockerfile e o docker-compose forem criados e executados, <br>
Então o sistema deverá rodar completamente dentro de containers, reproduzindo o ambiente de produção. <br>

### Tratamento e estruturação dos dados recebidos do webscraping

Cenário: Limpeza e padronização dos dados coletados. <br>
Dado que os dados brutos foram extraídos via webscraping, <br>
Quando o script de tratamento for executado, <br>
Então as informações deverão estar estruturadas e prontas para análise. <br>

### Implementar filas de processamento utilizando WebSocket

Cenário: Processamento assíncrono e feedback em tempo real. <br>
Dado que múltiplos documentos podem ser processados simultaneamente, <br>
Quando novas requisições forem feitas, <br>
Então o sistema deverá gerenciar as filas e enviar feedbacks de progresso via WebSocket. <br>

### Desenvolvimento dos componentes do frontend

Cenário: Implementação da interface visual do sistema. <br>
Dado que o sistema precisa de uma interface funcional e padronizada, <br>
Quando os componentes forem desenvolvidos, <br>
Então deverão estar integrados, responsivos e alinhados ao design definido. <br>

- Header e footer implementados e responsivos. <br>

- Botões e inputs funcionais conforme guia de estilo. <br>

- Upload de PDF via drag and drop com feedback visual. <br>

- Step map e checklist exibem etapas e status corretamente. <br>

- Páginas de input e tabela final integradas ao backend. <br>

- Interface validada em diferentes telas e navegadores. <br>