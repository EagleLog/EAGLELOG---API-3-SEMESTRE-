# Aprendizagem Baseada em Projetos Integradores (API)
A aprendizagem baseada em projetos integradores (API) segue uma abordagem dinâmica e interativa, inspirada nas metodologias ágeis. Os alunos desenvolvem conhecimentos e habilidades ao longo de projetos práticos, divididos em ciclos de planejamento, execução e retrospectiva. A metodologia valoriza a interdisciplinaridade, promovendo a colaboração entre diferentes áreas para resolver desafios do mundo real, com entregas incrementais e adaptação contínua — alinhadas às práticas do mercado.

# Project-Based Learning with Integrative Projects
Project-based learning with integrative projects follows a dynamic and interactive approach, inspired by agile methodologies. Students build knowledge and skills by working on practical projects, organized into cycles of planning, execution, and reflection. The approach emphasizes interdisciplinarity, encouraging collaboration across different fields to solve real-world challenges, with incremental delivery and continuous adaptation, aligned with real industry practices.

# :dart: Índice
* [Projeto](#Projeto)
* [Objetivo](#Objetivo)
* [Resultado esperado](#Resultado-esperado)
* [Equipe](#equipe)
* [Cronograma das Sprints](#Cronograma-das-Sprints)
* [Base de Dados](#Base-de-Dados)
* [Dashboard](#Dashboard)
* [Documentação](#Documentação)
* [Apresentação em *slide*](#apresentação-em-slide)
* [Tecnologias utilizadas](#Tecnologias-utilizadas)
* [Canais de comunicação](#Canais-de-comunicação)
* [Linguagem _Python_](#Linguagem-Python)
* [Serviços utilizados](#Serviços-utilizados)
* [Agradecimentos](#Agradecimentos) 



# <h1 align="center"> Projeto

# Objetivo 
Este projeto tem como foco o desenvolvimento de uma API para análise de acidentes de trânsito, com o objetivo de fornecer indicadores, visualizações e comparações úteis para entender os padrões e impactos dos acidentes em diferentes regiões.
# Resultado esperado
Desenvolver um dashboard interativo para analisar os dados de acidentes de trânsito e identificar os cinco municípios com maior número de acidentes e fatalidades nos anos de 2023 e 2024, permitindo uma comparação entre os dois anos. O projeto também inclui a criação de indicadores, rankings, mapas de calor e filtros interativos, facilitando a visualização de padrões e tendências ao longo do tempo.

   # Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |  Joyce Barros       |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joyce-moura-barros-ab0286284?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoyceMBP)        |
| Scrum Master  | João P.|       [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-pedro-vargas-dos-santos-973b44329?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joao-p-vargas) |
| Team Member   | Fernanda S             |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/emilly-ajala-15a34622a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Imyouremi)     |
|  Team Member  | Emilly Ajala                |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alana-ro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Alana-Rodrigues-01)        |
|  Team Member  | Cauan C.                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://br.linkedin.com/in/cauan-cesar-214b77251) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/C4U4N) |

# Cronograma das Sprints
📂[*User story*](https://github.com/user-attachments/files/22650639/User.Story.EagleLog.pdf)

## 📌 Sprint 1 - Exploração e Indicadores Básicos
- :white_check_mark: Reuniões;
- :white_check_mark: Atribuição das atividades para a Sprint 1.
- :white_check_mark: Backlog do produto;
- :white_check_mark: GitHub estruturado com link disponibilizado;
- :white_check_mark: Jira Software estruturado;
- :white_check_mark: Calcular taxa de acidentes/fatalidades por tipo de veículo (acidentes / número de veículos registrados;
- :white_check_mark: Gerar comparativo de acidentes/fatalidades por município e por região;
- :white_check_mark: Calcular taxa de acidentes por habitantes (acidentes / população).

- ## 📌 Sprint 2 - Análises Avançadas e Prototipagem
- :white_check_mark: Criar ranking de municípios com maior número de acidentes/fatalidades.
- :white_check_mark: Realizar análise de sazonalidade e picos de acidentes/fatalidades (feriados, férias, eventos especiais).
- :white_check_mark: Construir mapa de calor para identificar regiões com maior concentração de acidentes/fatalidades.
- :white_check_mark: Implementar filtros interativos (ano, município, tipo de acidente, tipo de veículo).
- :white_check_mark: Classificar acidentes por tipo e gravidade: fatais, com feridos, sem vítimas.
- :white_check_mark: Início do design do dashboard (layout e estrutura de navegação).

## 📌 Sprint 3 - Visualização Final e Insights 
- :white_check_mark: Exibir participação de cada município no total de acidentes e fatalidades do estado, usando gráfico de Pareto.
- :white_check_mark: Incluir no gráfico de taxa de acidentes/fatalidades por tipo de veículo a metodologia de curva ABC.
- :white_check_mark: Comparar municípios/regiões ao longo do tempo utilizando mapas de calor para identificar evolução (melhorias ou agravamento).
- :white_check_mark: Finalizar design completo do dashboard, garantindo usabilidade e interatividade.

  # Desenvolvimento
  # *Bases de Dados*  
📂[Python/PRF](https://colab.research.google.com/drive/10rXi25YbGXLl_hrYuM0QtNKBB6y5qjq6?usp=sharing)

📂[Python/Detran](https://colab.research.google.com/drive/1JpYrpkOfICLygIKvswA5UacUfihdUtz9?usp=sharing)

📂[Detran](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)

📂[IBGE](https://www.ibge.gov.br/cidades-e-estados/sp/)

# *Dashboard*

📂[*Dashboard* executavel]

# Documentação 

# Apresentação em *slide*

# Tecnologias Utilizadas
* <img src="https://github.com/user-attachments/assets/605548ba-69fb-4fde-bfbf-e077f919fcb7" width="40"/>  *Github*
* <img src="https://github.com/user-attachments/assets/f8501508-ccc6-4e91-a346-697986a138a8" width="40"/> *Jira Software*
* <img src="https://github.com/user-attachments/assets/bf25df7a-bd70-482f-8cc6-8a28e014151b" width="40"/> *PowerBI*
* <img src="https://github.com/user-attachments/assets/d3cc67f6-258f-47bf-a1b8-4cd6cf8841fd" width="40"/>  *Phyton*
* <img src="(https://github.com/user-attachments/assets/924049b9-ad5e-432f-9ca1-9e53c9cf5735)" width="40"/> *Pandas*

  

  
