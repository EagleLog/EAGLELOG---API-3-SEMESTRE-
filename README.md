# Aprendizagem Baseada em Projetos Integradores (API)
A aprendizagem baseada em projetos integradores (API) segue uma abordagem dinâmica e interativa, inspirada nas metodologias ágeis. Os alunos desenvolvem conhecimentos e habilidades ao longo de projetos práticos, divididos em ciclos de planejamento, execução e retrospectiva. A metodologia valoriza a interdisciplinaridade, promovendo a colaboração entre diferentes áreas para resolver desafios do mundo real, com entregas incrementais e adaptação contínua — alinhadas às práticas do mercado.

# :dart: Índice
* [Objetivo do Projeto](#Objetivo)
* [Equipe](#equipe)
* [Backlog do Produto](#Cronograma-das-Sprints)
* [Dashboard](#Dashboard)
* [Competências desenvolvidas](#competências-desenvolvidas)

# Projeto (API)
Este projeto tem como foco o desenvolvimento de uma API para análise de acidentes de trânsito, com o objetivo de fornecer indicadores, visualizações e comparações úteis para entender os padrões e impactos dos acidentes em diferentes regiões.

   # Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |  Joyce Barros       |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joyce-moura-barros-ab0286284?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoyceMBP)        |
| Scrum Master  | João P.|       [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-pedro-vargas-dos-santos-973b44329?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joao-p-vargas) |
| Team Member   | Fernanda S             |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/emilly-ajala-15a34622a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Imyouremi)     |
|  Team Member  | Emilly Ajala                |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alana-ro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Alana-Rodrigues-01)        |
|  Team Member  | Cauan C.                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://br.linkedin.com/in/cauan-cesar-214b77251) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/C4U4N) |

# Objetivo do Projeto

Este projeto tem como objetivo desenvolver uma API para análise de acidentes de trânsito, visando:

- Fornecer indicadores, visualizações e comparações sobre acidentes de trânsito;
- Compreender os padrões e impactos dos acidentes em diferentes regiões;
- Integrar bases de dados públicas (PRF, DATASUS, DENATRAN e IBGE);
- Apresentar métricas por estado e em nível nacional;
- Disponibilizar informações como mortalidade, severidade dos sinistros, índice de motorização, frota, população e uso de motocicletas.

# Tecnologias Utilizadas
- Jira Software
- Power BI
- WhatsApp
- Python (Colab)
- Mysql
- Jira

# # Product Backlog
  
| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
Rank Prioridade User Story Estimativa Sprint
1 |Alta | Como tomador de decisões de políticas públicas, pretendo realizar a análise de dados para compreender melhor os dados abertos. |5| 1 
2 |Alta|  Como tomador de decisões de políticas públicas, pretendo tratar e preparar as bases utilizando Python para garantir que as informações fiquem limpas, padronizadas e consistentes. |8| 1 |
3 | Média | Como tomador de decisões de políticas públicas, pretendo gerar comparativos de acidentes e fatalidades por município e por região para identificar áreas críticas e direcionar ações. |3 | 1 |
4 | Média | Como tomador de decisões de políticas públicas, pretendo calcular a taxa de acidentes por habitantes, relacionando acidentes à população, para medir a exposição ao risco.|  3|  1 |
5 | Média | Como tomador de decisões de políticas públicas, pretendo criar um ranking de municípios com maior número de acidentes e fatalidades para priorizar ações preventivas.| 3| 1 |
6 |Média | Como tomador de decisões de políticas públicas, pretendo criar um ranking de municípios com maior número de acidentes e fatalidades para apoiar o planejamento de ações preventivas e priorização de recursos.| 3 | 2 |
7|  Alta | Como tomador de decisões de políticas públicas, pretendo analisar a sazonalidade e identificar picos de acidentes e fatalidades, como em feriados, férias ou eventos, para apoiar campanhas preventivas.|3 | 2 | 
8 | Alta | Como tomador de decisões de políticas públicas, pretendo construir mapas de calor que identifiquem regiões com maior concentração de acidentes e fatalidades para facilitar a visualização geográfica.| 7 | 2 |
9 | Alta | Como tomador de decisões de políticas públicas, pretendo utilizar filtros interativos por ano, município, tipo de acidente e tipo de veículo para explorar os dados de maneira personalizada.| 3 | 2 |
10 | Média | Como tomador de decisões de políticas públicas, pretendo classificar os acidentes por tipo e gravidade fatais, com feridos ou sem vítimas para entender melhor o impacto de cada ocorrência. |3 | 2 |
11 | Baixo | Como tomador de decisões de políticas públicas, pretendo iniciar o design do dashboard definindo layout e estrutura de navegação para garantir uma experiência de uso clara e eficiente. |3 |2 |
12 | Baixo | Como tomador de decisões de políticas públicas, pretendo exibir a participação de cada município no total de acidentes e fatalidades do estado, usando gráfico de Pareto, para identificar os maisrelevantes.| 4| 3 | 
13| Baixo | Como tomador de decisões de políticas públicas, pretendo incluir a metodologia de curva ABC no gráfico de taxa de acidentes e fatalidades por tipo de veículo para evidenciar os tipos mais críticos.| 4 | 3 |
14 | Médio | Como tomador de decisões de políticas públicas, pretendo comparar municípios e regiões ao longo do tempo por meio de mapas de calor para detectar melhorias ou agravamentos.| 3 | 3 |
15 | Baixo | Como tomador de decisões de políticas públicas, pretendo finalizar o design do dashboard garantindo usabilidade, interatividade e consistência visual.| 3 | 3 |


# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 03/10/2025 | Concluida | [MVP](MVP/sp1.md)  |
| 02                | 31/10/2025 | Em progresso  | [MVP](MVP/sp2.md)  |
| 03                | 31/10/2025 | Em progresso  | [MVP](MVP/sp2.md)  |
| Feira de Soluções               | dd/mm/aaaa | a fazer  | [MVP](MVP/sp3.md)  |


# *Dashboard*

📂[*Dashboard* executavel](https://app.powerbi.com/view?r=eyJrIjoiNDc3M2VkYTItZDI4MC00ZjBkLWFjMGUtYTM0YzkzNmU2MjQxIiwidCI6ImNmNzJlMmJkLTdhMmItNDc4My1iZGViLTM5ZDU3YjA3Zjc2ZiIsImMiOjR9)


![Imagem do WhatsApp de 2025-10-03 à(s) 02 05 49_9ae3f153](https://github.com/user-attachments/assets/1ba0059a-d496-43f9-9e68-1699a34f5ba5)


# Competências desenvolvidas

# Agradecimentos 

Agradecemos a todos os colegas e professores envolvidos na realização deste projeto, pelo apoio, orientações e colaboração ao longo do desenvolvimento. Este trabalho é resultado de um esforço coletivo e da aplicação prática dos conhecimentos adquiridos durante o semestre.
  

<p align="center">
  <img src="https://github.com/user-attachments/assets/b50cfb6f-79b2-490e-b4bb-d29228ccdbbe" alt="Imagem exemplo">
</p>
