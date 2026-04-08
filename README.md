# Projeto de Integração, Análise e Insights de Dados – Criminalidade e Meteorologia

## Componentes
- Alex Rodrigues Gonçalves - 1136919  
- Eduardo Cardoso Debona - 1121865  
- Gabriel Augusto Andrioli - 1136706  
- João Vitor Bastos dos Santos - 1136345  
- Leonardo Ross Dapper - 1136153  
- Vinicius Gehring Capellari - 1138972  

---

## Link dos Dados utilizados

https://drive.google.com/drive/folders/1SAi2JR1rAIfWbtSieo5mchved9_F8nc2?usp=drive_link

---

## Resumo

O projeto de Integração, Análise e Insights de Dados de Criminalidade e Meteorologia, proposto pelo Prof. Fernando Posser na disciplina de Machine Learning e Inteligência Artificial, tem como objetivo principal investigar a existência de relações entre variáveis climáticas e a ocorrência de crimes, por meio da integração e análise de bases de dados públicas.

O desenvolvimento foi conduzido por seis alunos do curso de Ciência da Computação, utilizando o ambiente Google Colab como plataforma de execução. O projeto envolveu etapas estruturadas de ingestão de dados, leitura de arquivos em formato CSV e integração com o Google Drive, garantindo acessibilidade e organização dos dados ao longo do processo.

Na etapa inicial, foi realizado um rigoroso pré-processamento dos dados, contemplando limpeza, tratamento de valores ausentes, padronização de nomenclaturas de colunas e normalização de formatos de data. Essas etapas foram fundamentais para assegurar a consistência e a qualidade dos dados antes da integração.

Posteriormente, os datasets de criminalidade e meteorologia foram integrados por meio de operações de junção (merge), com base em critérios temporais. Essa abordagem permitiu o alinhamento entre registros de ocorrências criminais e variáveis meteorológicas, tais como temperatura, precipitação e umidade, possibilitando a construção de uma base analítica consolidada.

Como resultado, foi gerada uma base de dados unificada, adequada para análises exploratórias e extração de padrões. A análise exploratória de dados (EDA) permitiu identificar tendências ao longo do tempo, além de evidenciar possíveis comportamentos sazonais associados às ocorrências criminais. A utilização de gráficos e visualizações contribuiu significativamente para a interpretação dos dados e compreensão das relações entre variáveis.

A partir dessas análises, foram obtidos insights relevantes, incluindo a possível influência de fatores climáticos na incidência de determinados tipos de crime, a identificação de padrões sazonais em períodos específicos e o potencial uso da base integrada como suporte para modelos preditivos e aplicações em políticas públicas de segurança.

O trabalho compreendeu, principalmente, as etapas descritas a seguir:

---

## Arquivo .ipynb

O arquivo .ipynb deste repositório realiza o processo completo de integração e análise de dados de criminalidade e meteorologia do município de Passo Fundo. Inicialmente, são carregados os arquivos originais, com verificação de estrutura e existência dos diretórios, seguida da padronização dos dados, tratamento de valores ausentes, remoção de duplicatas e correção de tipos, especialmente a conversão da coluna de data para formato adequado. Em seguida, os dados são agregados em uma base analítica diária, permitindo a análise temporal das ocorrências, e posteriormente integrados com as variáveis meteorológicas por meio de operações de merge. Como resultado, são geradas bases finais tratadas (normalizada, analítica diária e integrada), além de visualizações gráficas e análises de correlação, possibilitando a identificação de padrões e possíveis relações entre fatores climáticos e a variação dos índices de criminalidade ao longo do tempo.

---

## Estrutura

- Importação e leitura de datasets (CSV/Google Drive)  
- Pré-processamento dos dados (limpeza, tratamento de valores nulos e padronização)  
- Integração dos dados por meio de merge com base temporal  
- Análise exploratória de dados (EDA) com construção de visualizações  

---

## Resultados

- Construção de um dataset unificado contendo variáveis climáticas e registros de ocorrências criminais  
- Identificação de padrões temporais ao longo do período analisado  
- Geração de gráficos e visualizações voltados à análise de tendências e sazonalidade  

---

## Insights

- Indícios de relação entre condições climáticas e determinados tipos de crime  
- Evidência de padrões sazonais em períodos específicos  
- Base de dados estruturada e preparada para aplicação em modelos preditivos, ainda em fase inicial, com possibilidade de ajustes e aprimoramentos  

---

Ressalta-se que, por se tratar de um projeto inserido no contexto de Machine Learning, os modelos e análises desenvolvidos são passíveis de evolução contínua. Dessa forma, o trabalho não deve ser interpretado como uma solução final e definitiva, mas sim como uma etapa inicial voltada à aplicação prática dos conceitos estudados.

Considerando a complexidade do tema, a constante evolução das técnicas de análise de dados e o desenvolvimento acadêmico dos participantes, existe amplo espaço para futuras melhorias, incluindo refinamento de modelos, ampliação das bases de dados e aprofundamento das análises, caso o projeto venha a ser expandido.
