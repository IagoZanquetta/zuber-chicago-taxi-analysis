# zuber-chicago-taxi-analysis
Projeto de análise de dados e SQL sobre corridas de táxi em Chicago para identificar padrões de mercado e testar hipóteses relacionadas a clima e duração das viagens.

## Visão Geral

Este projeto analisa dados de corridas de táxi em Chicago para apoiar decisões de negócio da empresa fictícia **Zuber**. A proposta combina consultas SQL, análise exploratória de dados e testes estatísticos para entender o comportamento do mercado, a distribuição das viagens entre empresas e bairros, e os efeitos do clima na duração das corridas.

O foco principal é transformar dados operacionais em insights úteis para planejamento, posicionamento e avaliação de padrões de demanda.

## Problema de Negócio

A Zuber deseja compreender melhor o mercado de táxis em Chicago, identificando quais empresas concentram mais corridas, quais bairros apresentam maior volume de viagens e se fatores externos, como condições climáticas, afetam a duração das corridas em rotas específicas.

Neste projeto, a análise busca gerar evidências quantitativas que possam apoiar decisões estratégicas e operacionais.

## Conjunto de Dados

O projeto utiliza dados extraídos por meio de consultas SQL e arquivos CSV com resultados agregados relacionados a corridas de táxi em Chicago.

Os arquivos utilizados no projeto estão organizados na pasta `datasets/`:

- `project_sql_result_01.csv`
- `project_sql_result_04.csv`
- `project_sql_result_07.csv`

Esses dados incluem informações como:

- número de corridas por empresa
- média de corridas finalizadas por bairro
- duração de corridas em rotas específicas
- condições climáticas associadas às viagens

## Objetivo do Projeto

Analisar dados de corridas de táxi em Chicago para identificar padrões de mercado, comparar empresas e bairros e testar a hipótese de influência do clima sobre a duração das corridas em rotas específicas.

## Objetivos da Análise

Este projeto busca responder perguntas como:

- Quais empresas concentram maior número de corridas?
- Quais bairros apresentam maior volume médio de viagens encerradas?
- Existem padrões relevantes na distribuição de corridas entre bairros e empresas?
- A duração média das corridas do Loop para o Aeroporto O'Hare muda em sábados chuvosos?
- Como consultas SQL e análise estatística podem apoiar decisões de negócio nesse contexto?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. extração de dados com consultas SQL
2. carregamento e inspeção inicial dos arquivos
3. validação e preparação dos dados
4. análise exploratória das corridas por empresa
5. análise exploratória das corridas por bairro
6. visualização dos principais padrões encontrados
7. teste de hipótese sobre duração das corridas em sábados chuvosos
8. conclusões finais de negócio

## Ferramentas e Bibliotecas

- Python
- SQL
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

## Estrutura do Repositório

```text
zuber-chicago-taxi-analysis/
├── .gitignore
├── README.md
├── requirements.txt
├── zuber_chicago_taxi_analysis.ipynb
└── datasets/
    ├── project_sql_result_01.csv
    ├── project_sql_result_04.csv
    └── project_sql_result_07.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/zuber-chicago-taxi-analysis.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd zuber-chicago-taxi-analysis
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `zuber_chicago_taxi_analysis.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* extração de dados com SQL
* comparação do volume de corridas por empresa
* análise de bairros com maior média de viagens
* visualização de padrões de distribuição
* formulação e teste de hipótese estatística
* interpretação dos resultados em contexto de negócio

## Resultados

Combinação de consultas SQL, análise exploratória e teste estatístico para investigação do comportamento do mercado de táxis. Identificação de concentração de corridas por empresa e por bairro, além de avaliação quantitativa do efeito de sábados chuvosos na duração de viagens do Loop para o Aeroporto O'Hare.

O notebook inclui:

* preparação e validação dos dados
* análise exploratória com visualizações
* comparação entre empresas e bairros
* teste estatístico sobre corridas em sábados chuvosos
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como SQL, análise exploratória de dados e testes estatísticos podem ser combinados para investigar padrões de mobilidade urbana e apoiar decisões estratégicas. A análise permite identificar concentração de mercado, comportamento das viagens por bairro e possíveis efeitos do clima sobre a duração das corridas.

## O que foi aprendido

Desenvolvimento e consolidação de habilidades em:
- extração de dados com SQL
- análise exploratória com foco em mobilidade urbana
- construção de visualizações comparativas
- formulação e teste de hipóteses
- interpretação estatística aplicada ao negócio

## Melhorias Futuras

Possibilidades de evolução do projeto:
- incluir mais rotas e períodos na análise
- aprofundar o estudo do impacto do clima
- incorporar variáveis adicionais sobre trânsito e horário
- construir painéis visuais para comparação dinâmica

## Autor

**Iago Zanquetta**
