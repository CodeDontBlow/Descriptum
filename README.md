<h1 align="center">  Projeto API - 4º Semestre </h1>
<h3 align="center">  Agente de Inteligência Artificial para Registro de Importação </h3>

---

## 🎯 Objetivo do Projeto  
O desafio proposto consiste no desenvolvimento de um agente de Inteligência
Artificial capaz de elaborar a instrução de registro aduaneiro com as informações pertinentes do
material que relacione: <b> Part-Number, classificação fiscal, fabricante, origem do fabricante com
endereço completo, </b> gerando a informação da descrição do material, de forma que permita a receita
federal entender o que é o produto e não gere dúvidas sobre o item o e não acarrete penalidades
e/ou multas sobre o material declarado.


## 🔎 MVP (Minimum Viable Product)
Como solução para esse desafio, o <b> Descriptum </b> será uma aplicação desenvolvida para automatizar a análise de documentos de importação, assegurando maior consistência, confiabilidade e agilidade no processo. A plataforma permitirá padronizar descrições técnicas, validar classificações fiscais e garantir conformidade regulatória, reduzindo a complexidade e eliminando incertezas no Registro de Importação.
Com isso, o sistema não apenas minimiza riscos de penalidades e evita retrabalho, mas também fortalece a segurança, a precisão e a transparência nas transações aduaneiras, contribuindo diretamente para a eficiência, a competitividade e a sustentabilidade das operações de comércio exterior.

## 📽️ Demonstração 
### • Sprint 1

https://github.com/user-attachments/assets/378220d2-17e4-4a09-a1b0-96ca7a894956

### • [Protótipo](https://www.figma.com/design/xC29fr9OYcenj38FBQtABY/Descriptum-API-4?node-id=0-1&p=f&t=4Q1Pb8eyAVg8t0u2-0)

## 🛣️ RoadMap

<div style="display: flex; justify-content: center;">
  <img src="./docs/assets/ROADMAP.png" style="width: 90%">
</div>

## 📑 Backlog do Produto
<div align="center">

|Rank |Prioridade|                    User Story                    | Sprint |
|:---:|:--------:|:------------------------------------------------:|:------:|
|  1  |  Alta   |  Como analista, quero carregar documentos (nota fiscal, pedido de compra, catálogo, etc.), para que o sistema extraia automaticamente as informações relevantes.     |  1 |
|  2  |  Alta   |  Como analista, quero que o sistema identifique e padronize dados-chave (part number, fabricante e endereço de origem), para reduzir erros manuais. | 1 |
|  3 |  Alta   |  Como analista, quero que o sistema gere automaticamente uma descrição detalhada e clara do produto, para atender às exigências da Receita Federal.               | 1 |
|  4 |  Alta   |   Como analista, quero que o sistema sugira o NCM mais provável do produto, para agilizar o preenchimento do Registro de Importação.      | 2|
|  5 |  Média   |  Como cliente, quero que o sistema permita exportar relatórios  para facilitar a comunicação com órgãos reguladores.   | 2 |
|  6 |  Média   |  Como usuário, quero visualizar uma interface simples e intuitiva para upload de documentos e validação dos resultados, para facilitar meu dia a dia.   | 2 |
|  7 |  Baixa    |   Como analista, quero que o sistema guarde as informações extraídas de forma organizada, para poder consultá-las quando necessário.  | 3 |


</div>

## 🛠️ Tecnologias

<div align="center">

![Ollama](https://img.shields.io/badge/-Ollama-0D1117?style=for-the-badge&logo=ollama&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Poetry](https://img.shields.io/badge/poetry-000000?style=for-the-badge&logo=python&logoColor=fff)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5C2D91?style=for-the-badge&logo=datadog&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)


![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</h4>
</div>


## 📅 Cronograma e Sprints

| Sprint            | Período     | Status        |
| ----------------- | ---------- | -----------|
| Kick Off          | 25/08/2025 |  Concluído         | 
| 01                | 08/09 - 28/09 | [Concluída - Docs](./docs/sprints/sprint-1/README.md)  | 
| 02                | 06/10 - 26/10 | [Concluída - Docs](./docs/sprints/sprint-2/README.md)   | 
| 03                | 03/11 - 28/11 | [Concluída - Docs](./docs/sprints/sprint-3/README.md)| 
| Feira de Soluções | 04/12/2025 |   Concluída | 

---

 ### 👥 Fatec São José dos Campos - Prof. Jessen Vidal

| Cliente          | Período/Curso                                  | Professor M2      | Professora P2     | Contato Cliente                    |
| ---------------- | ---------------------------------------------- | ----------------- | ---------------- | ---------------------------------- |
| Creonice Honório - Empresa TecSys | 4º Análise e Desenvolvimento de Sistemas | Giuliano Bertoti  | Juliana Pasquini | <creonice@tecsysbrasil.com.br> |


## 💣 A Equipe Code Don´t Blow


| Integrante | Função | GitHub | 
|---|---|---|
| Mariana Lins | **Product Owner** | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/mariana-lins) |
| Ygor Pereira |  **Scrum Master** | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/YgorPereira)
| Henrique Tadeu | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/henrySilverIX) | 
| Leonardo Cristiano | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Leonardo-dSouza) |
| Luana Souza | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/luanaapms) | 
| Matheus di Sabatino | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Omathzao) |
| Rafael Gonçalves | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/EstupendoG)  |  
| Vanessa da Costa | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Doryumi) | 
| Victor Godoy | Dev Team | [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/victorrgodoy) |
