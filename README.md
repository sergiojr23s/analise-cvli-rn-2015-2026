# Análise de Crimes Violentos Letais Intencionais (CVLI) — Brasil e RN (2015–2026)

Projeto de Ciência de Dados desenvolvido no Instituto Metrópole Digital (IMD/UFRN) com foco na coleta, limpeza e análise exploratória (EDA) da letalidade violenta no Rio Grande do Norte em comparação ao cenário nacional.

## Autores
- Carlos Henrique da Silva Guimarães
- Enzo Araújo de Souza e Oliveira
- Sérgio Soares da Silva Júnior
- Vinicius Alexandre Melo

## Estrutura do Repositório
- `notebooks/analise_eda_rn.ipynb`: Notebook principal contendo a ingestão dos dados, limpeza, validação, cruzamento demográfico e geração dos gráficos.
- `requirements.txt`: Lista de bibliotecas Python necessárias para execução.

## Fonte dos Dados
1. **SINESP-VDE (MJSP):** Registros anuais/históricos de ocorrências criminais (2015 a 2026), disponíveis no portal oficial de estatísticas do [Ministério da Justiça e Segurança Pública](https://www.gov.br/mj/pt-br/assuntos/sua-seguranca/seguranca-publica/estatistica/dados-nacionais-1/base-de-dados-e-notas-metodologicas-dos-gestores-estaduais-sinesp-vde-2022-e-2023).
2. **IBGE (Censo Demográfico 2022):** Dados populacionais utilizados para normalização das taxas por 100 mil habitantes.

## Como Executar
1. Para executar o código no Google Colab, será necessário fazer o upload do arquivo enviado pelo Google Forms.
