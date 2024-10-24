
# Projeto de ETL para Dados de Clubes de Futebol

Este projeto foi desenvolvido como parte da disciplina **Integração de Sistemas de Informação (ISI)** e tem como objetivo demonstrar a aplicação de processos ETL (Extract, Transform, Load) usando ferramentas como **Microsoft SQL Server Integration Services (MSSIS)** e **Power BI**.

## Autor
- João Rafael Azevedo Cunha (a21598)
- Licenciatura em Engenharia de Sistemas Informáticos (Pós-Laboral)
- Outubro de 2024

## Descrição do Projeto

O foco deste projeto foi a construção de um processo ETL completo utilizando dados no formato JSON sobre clubes de futebol, ligas e jogos. As principais ferramentas utilizadas foram o **Microsoft SQL Server Integration Services (MSSIS)** para a extração e transformação dos dados e o **Power BI** para a visualização e análise.

Os dados utilizados são públicos e foram integrados a uma base de dados MySQL utilizando a ferramenta FreeSQLDatabase. O processo envolveu a limpeza, transformação e organização de dados, incluindo expressões regulares (Regex) e joins, para gerar insights sobre o desempenho de equipas e estatísticas dos jogos.

## Estrutura de Pastas

- `scripts/`: Scripts SQL para a criação de tabelas e transformações dos dados.
- `etl_jobs/`: Definições dos pacotes ETL (Jobs) utilizados no Microsoft SQL Server Integration Services (MSSIS).
- `visualizations/`: Dashboards e gráficos criados no Power BI.

## Principais Componentes do Processo ETL

1. **Extração de Dados**: Os dados foram extraídos de arquivos JSON contendo informações sobre ligas e jogos de futebol.
2. **Transformação de Dados**: Utilizando o MSSIS, os dados foram transformados, limpos e organizados. Algumas das principais operações realizadas incluem:
   - Uso de **expressões regulares (Regex)** para limpar e formatar os dados.
   - Aplicação de **joins** para combinar informações de diferentes fontes.
   - Filtros e regras condicionais para garantir a qualidade dos dados.
3. **Carregamento de Dados**: Os dados transformados foram carregados em uma base de dados MySQL hospedada no FreeSQLDatabase.
4. **Visualização de Dados**: O Power BI foi utilizado para criar relatórios e dashboards que apresentam insights sobre o desempenho das equipas e estatísticas dos jogos.

## Requisitos

- **Microsoft SQL Server Integration Services (MSSIS)**
- **Power BI**
- **MySQL**

## Execução

1. Configure o ambiente MSSIS e MySQL de acordo com as instruções nos scripts.
2. Execute os pacotes ETL disponíveis na pasta `etl_jobs/`.
3. Use os dashboards em `visualizations/` para analisar os resultados.

## Trabalhos Futuros

Como melhorias futuras, o projeto pode ser expandido para incluir novos tipos de dados e ser integrado com outras APIs e fontes de dados em tempo real para fornecer análises mais detalhadas e dinâmicas.

## Licença

Este projeto foi desenvolvido para fins acadêmicos.

## Contato

Em caso de dúvidas, entre em contato:
- João Rafael Azevedo Cunha (a21598)
