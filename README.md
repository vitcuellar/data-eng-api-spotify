# Desenvolvimento de Pipeline : API Spotify

[![Read in English](https://img.shields.io/badge/Read%20in-English-blue)](README_eng.md)

## 💼 Sobre o Projeto  
Esse projeto contém etapas de definição da fonte dos dados — no caso, foi utilizada a API de dados abertos do Spotify —, PoC do projeto, desenvolvimento com base em regras de segurança de dados para credenciais.

Além disso, também implementei um código robusto para ingestão e tratamento de dados, conexão direta com PostgreSQL para implementação de **arquitetura medalhão** em contexto de RDBMS. Considerando três camadas de dados, foi definida a utilização do **Airflow** como orquestrador dos processos. Por fim, foi desenvolvido um **Catálogo de Dados** com os metadados de interesse e documentações técnicas que estarão disponíveis em arquivos markdown (`.md`) aqui neste repositório.

## 🎯 Objetivos  

Para além da execução técnica desses scripts e conexão de sistemas, os principais objetivos são:

- Disponibilizar dados de fontes de dados abertas para facilitar o consumo por parte da Comunidade de Dados no desenvolvimento de análises e projetos pessoais;
- Aprendizado sobre processos de segurança de credenciais em máquina local;
- Garantir eficiência de um projeto mesmo não atuando com servidores em nuvem;
- Desenvolver código que possa ser utilizado como template para situações de ingestão e higienização de dados;
- Aprimorar conhecimento de arquitetura e desenvolvimento de PoCs;
- Consolidar conceitos sobre Governança de Dados em ferramenta open-source para garantir disseminação de aprendizados e facilidade de acessos.

## 🛠️ Ferramentas Utilizadas  

Várias ferramentas foram utilizadas, e aqui está o mapeamento delas:

- API do Spotify como fonte de dados;
- Bibliotecas Python, como: `cryptography.fernet`, `requests`, `json`, `pandas`, `psycopg2`, `sqlalchemy`;
- PostgreSQL;
- Airflow;
- DataHub;
- Excalidraw;
- GitHub.

## 🔎 Onde encontrar?

Você pode encontrar todos os arquivos e documentações neste repositório. Busque pelas pastas:
- `/scripts` – Scripts em Python para ingestão e transformação;
- `/docs` – Documentação técnica em Markdown;
- `/visuals` – Diagramas do Excalidraw e visualizações de dados.

## 👩🏻‍💻 Prova de Conceito – PoC  

Visto que a PoC é uma etapa necessária no desenvolvimento de projetos, realizei essa etapa com o intuito de garantir a melhor solução técnica para esse cenário e para cumprir com os objetivos estabelecidos.

Nesse sentido, testei a viabilidade técnica do que foi decidido ser feito e, em situações de gargalos técnicos, tudo será registrado com o objetivo de facilitar o compartilhamento dos aprendizados e o entendimento sobre a implementação de um projeto deste porte.

Utilizando o **Excalidraw** como ferramenta, desenhei o que seria o fluxo da solução técnica. A ideia aqui é poder registrar esse passo inicial e, em caso de mudanças, isso será informado, como mencionei.

Nesse fluxo, defini como etapas:
- Definição da fonte;
- Conexão com a API;
- Segurança das credenciais;
- Ingestão dos dados;
- Tratamento dos dados;
- Conexão com o PostgreSQL;
- Definição da **Arquitetura Medalhão** para criação de 3 camadas de dados com refinamentos utilizando SQL;
- Uso do **Airflow** como orquestrador;
- Geração de **Catálogo de Dados** e documentações técnicas para fins de **Governança dos Dados** e simulação de um cenário real com Cultura de Dados aplicada.

Por fim — mas definitivamente não menos importante —, também será desenvolvido um **relatório de Data Viz usando Python**, para mostrar essa possibilidade em caso de escassez de recursos mais estratégicos e, por vezes, pagos, para uso de ferramentas de BI.

![image](https://github.com/user-attachments/assets/6ae0a99c-e748-4771-9262-c6f661b276e2)
