Claro! Aqui está a versão melhorada do seu README formatada diretamente para ser usada no GitHub, sem precisar baixar nenhum arquivo:

---

# 📊 Projeto de Análise de Dados de Recursos Humanos

Este projeto tem como objetivo realizar uma análise exploratória e estatística dos dados de Recursos Humanos de uma empresa, com foco na compreensão dos fatores que influenciam a saída de funcionários. A partir dessa análise, espera-se fornecer insights que possam auxiliar na tomada de decisões estratégicas para retenção de talentos.

## 🚀 Tecnologias e Bibliotecas Utilizadas

- **Pandas**: Manipulação e análise de dados  
- **Matplotlib & Seaborn**: Visualização de dados  
- **Statsmodels**: Modelagem estatística (regressão linear)  
- **Jupyter Notebook** ou ambiente Python equivalente  

---

## 📌 Etapas do Projeto

### 1. 📥 Leitura e Pré-processamento dos Dados
- Importação do dataset `Base_RH.csv`
- Renomeação das colunas para nomes mais intuitivos
- Verificação e limpeza de dados (remoção de duplicatas e valores nulos)
- Criação da variável `salario_com_juros`, considerando o percentual de aumento salarial

### 2. 🔍 Análise Exploratória de Dados (EDA)
- Contagem e visualização de funcionários que saíram ou permaneceram na empresa
- Análise de saída por gênero e estado civil com gráficos de barras
- Tabela de frequência da variável `frequência_de_viagens`, com frequência relativa e acumulada
- Estudo da distribuição etária dos funcionários que saíram (histograma com curva de densidade)

### 3. 📈 Análise de Correlação
- Seleção de colunas numéricas
- Cálculo da matriz de correlação de Pearson
- Visualização com mapa de calor (heatmap) para identificação de relações entre variáveis

### 4. 📊 Modelagem Estatística
- Transformação da variável resposta `saiu_da_empresa` para valores binários (`Sim` = 1, `Não` = 0)
- Escolha da variável explicativa: `tempo_de_carreira`
- Ajuste de um modelo de Regressão Linear utilizando `statsmodels`
- Avaliação e interpretação dos coeficientes e do desempenho do modelo com `.summary()`

---

## 🎯 Objetivo do Projeto

Identificar padrões e variáveis associadas à rotatividade de funcionários, fornecendo subsídios analíticos para o setor de RH tomar decisões estratégicas baseadas em dados.

---

## ✅ Resultados Esperados

- Entendimento dos principais fatores que influenciam a saída de colaboradores  
- Visualizações informativas que facilitam a apresentação para gestores  
- Base inicial para futuros modelos preditivos de turnover (como regressão logística ou machine learning)

---

## 📌 Observações Finais

Este projeto representa uma etapa introdutória na análise de dados de RH. Futuramente, pode-se aplicar modelos preditivos mais robustos para ampliar o poder de análise e previsão.

---

---


