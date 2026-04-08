# Projeto de Integração de Dados – Criminalidade e Meteorologia

## Integrantes
- Alex Rodrigues Gonçalves – 1136919  
- Eduardo Cardoso Debona – 1121865  
- Gabriel Augusto Andrioli – 1136706  
- João Vitor Bastos dos Santos – 1136345  
- Leonardo Ross Dapper – 1136153  
- Vinicius Gehring Capellari – 1138972  

---

## Resumo

O projeto de Integração de Dados de Criminalidade e Meteorologia tem como objetivo analisar se há influência das condições meteorológicas sobre a ocorrência de crimes, por meio da combinação de bases de dados públicas.

O desenvolvimento foi realizado em ambiente Google Colab, incluindo etapas de importação de dados, leitura de arquivos CSV e integração com o Google Drive.

Inicialmente, foi realizado o pré-processamento dos dados, incluindo limpeza, tratamento de valores nulos, padronização de colunas e ajuste de formatos de datas.

Em seguida, os datasets foram integrados por meio de operações de junção (merge), utilizando principalmente critérios temporais para alinhar registros de criminalidade com variáveis meteorológicas, como temperatura, precipitação e umidade.

Como resultado, foi gerada uma base de dados unificada, permitindo análises conjuntas e a construção de visualizações para identificação de padrões.

A análise exploratória dos dados (EDA) possibilitou observar tendências ao longo do tempo, identificar possíveis comportamentos sazonais e analisar relações entre variáveis.

---

## Estrutura do Projeto

- Importação e leitura de datasets (CSV / Google Drive)  
- Pré-processamento (limpeza, tratamento de nulos e padronização)  
- Integração dos dados via merge temporal  
- Análise exploratória (EDA) com visualizações  

---

## Resultados

- Dataset unificado contendo variáveis climáticas e ocorrências criminais  
- Identificação de padrões ao longo do tempo  
- Geração de gráficos para análise de tendência e sazonalidade  

---

## Insights

- Possível relação entre condições climáticas e tipos de crime  
- Evidência de padrões sazonais em determinados períodos  
- Base estruturada pronta para aplicações futuras, como modelos preditivos e apoio à tomada de decisão em políticas públicas  

---

## Tecnologias Utilizadas

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  
- Google Drive  

---

## Observações

Os dados utilizados são provenientes de bases públicas e foram tratados para garantir consistência, qualidade e integridade durante o processo de integração.
