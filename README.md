# Projeto PaySmart Solutions - Validação de Cobranças

## 📌 Introdução
A **PaySmart Solutions** (empresa fictícia do setor de adquirência) enfrenta o desafio de garantir que a cobrança da taxa de transação — seu principal produto — está sendo realizada corretamente, respeitando as regras de isenção aplicáveis.  

Este projeto simula e analisa um conjunto de transações, identificando **erros de cobrança** e **impactos financeiros**, além de propor um algoritmo de **monitoramento recorrente** para reduzir falhas.

---

## 🎯 Objetivo
- Verificar se as taxas estão sendo cobradas corretamente.  
- Identificar transações com erros e analisar seu impacto financeiro.  
- Criar um **método automatizado** para monitoramento contínuo, utilizando **Machine Learning (ML)**.  

---

## 📂 Estrutura do Projeto
- `transacoes_ficticias.csv` → Base fictícia de transações criada para o desafio.  
- `analise_transacoes.ipynb` → Notebook com toda a análise exploratória, gráficos e cálculos.  
- `requirements.txt` → Dependências necessárias para executar o projeto.  
- `README.md` → Documentação do projeto.  

---

## 🔎 Principais Análises
1. **Taxa de isenções** → Quantos clientes/transações não pagaram taxa.  
2. **Diferença entre valor esperado e valor cobrado** → Erros de cobrança.  
3. **Classificação dos erros** → Tipos de falha (taxa incorreta, não cobrada etc.).  
4. **Impacto financeiro** → Soma dos valores cobrados a mais e a menos.  
5. **Outliers** → Identificação visual e estatística de anomalias.  
6. **Machine Learning** → Uso do algoritmo *Isolation Forest* para detectar anomalias complexas.  

---

## 🛠️ Metodologia
- Base fictícia simulada com regras de isenção e falhas propositais.  
- Análises estatísticas + visualização de dados (gráficos de dispersão, histogramas).  
- Comparação entre métodos de outlier detection (estatística vs. ML).  
- Estimativa do impacto financeiro líquido das falhas.  

---

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/Desafio-Banco.git
   cd projeto-paysmart
