IND2622 - CIEN. DADOS PROC. DE NEGOCIO - 2024.2 - 3RA PUC-RIO
Aluna: Daniela Rosas 

Identificação de Fatores Socioambientais e Áreas Prioritárias para Intervenção na Mortalidade por Diarreia na Amazônia Legal
Descrição
Este repositório contém os arquivos e códigos desenvolvidos para o estudo que investiga os determinantes socioambientais da mortalidade por diarreia na Amazônia Legal. Utilizamos modelos avançados de aprendizado de máquina, como Random Forest, XGBoost, LightGBM e CatBoost, para prever padrões e identificar áreas de maior vulnerabilidade, alinhados aos Objetivos de Desenvolvimento Sustentável (ODS).

Conteúdo do Repositório
CDamazonia.ipynb: Notebook principal com a implementação do pipeline de análise de dados e aprendizado de máquina.
pcaipynb.ipynb: Notebook contendo a análise de componentes principais (PCA) para redução de dimensionalidade.
df_final041124.xlsx: Base de dados consolidada com as variáveis socioambientais e de saúde pública utilizadas no estudo.

Metodologia

O estudo seguiu as seguintes etapas:

Coleta de Dados: Integração de dados do DATASUS e Índice de Progresso Social (IPS) para construir a base utilizada.
Pré-Processamento: Imputação de dados ausentes, criação de variáveis derivadas e normalização.
Engenharia de Atributos: Criação de métricas para enriquecer a análise preditiva.
Modelagem: Aplicação de algoritmos de aprendizado de máquina (Random Forest, XGBoost, LightGBM, CatBoost) com validação cruzada.
Avaliação e Interpretação: Análise do desempenho dos modelos e identificação das variáveis mais importantes.

Resultados
Melhor Modelo: O XGBoost obteve o melhor desempenho (R² = 0,9997).
Principais Determinantes: Variáveis como saneamento básico, PIB per capita e hospitalizações por condições sensíveis à atenção primária foram identificadas como os principais fatores de mortalidade.
