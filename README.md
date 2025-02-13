# 🔍 Análise de A/B Test: Decisões Baseadas em Dados para Campanhas de Marketing  
**por [Maxwilliam Gomes](https://www.linkedin.com/in/maxwilliam-gomes-74b01716a/)**  
[![LinkedIn](https://img.shields.io/badge/-Conectar_no_LinkedIn-%230A66C2)](https://www.linkedin.com/in/maxwilliam-gomes-74b01716a/)
[![Email](https://img.shields.io/badge/-Enviar_Email-%23EA4335)](mailto:maxwilliamgomes@gmail.com)
[![Análise Completa](https://img.shields.io/badge/-Ver_Análise_Completa-%2300B388)](https://github.com/MaxwilliamGomes/AB-test/blob/main/%5BAB%20Testing%5D%20CTR%20Campaing/%5BAB_Testing%5D_CTR_Campaing.ipynb)

---

## 🚀 **Visão Geral do Projeto**  
Este projeto de **A/B Test** analisou o desempenho de duas versões de uma campanha de marketing para determinar qual obteve maior **Taxa de Clique (CTR)**. Utilizando **Python e estatística**, identifiquei a versão mais eficaz, gerando insights para otimizar investimentos em marketing e aumentar o ROI.  

**Resultado Chave:**  
✅ **Versão B superou a A** com um aumento de **4% no CTR** (p-value < 0.05).  


---

## 📌 **Destaques Técnicos**  
- **Bibliotecas:** Pandas, NumPy, SciPy, Matplotlib, Statsmodels.  
- **Análise Estatística:** Teste Z, intervalo de confiança, cálculo de p-value.  
- **Visualização:** Gráficos comparativos (barras, distribuição) para comunicação clara de resultados.  
- **Reprodutibilidade:** Código modular e documentado para aplicação em outros cenários.  

---

## 📊 **Metodologia**  
### **Passo a Passo**  
1. **Coleta e Limpeza de Dados:**  
   - 2 Dataset com 30 registros de cliques e impressões cada.  
2. **Análise Estatística:**  
   - **Teste de Hipótese:** Comparação das médias de CTR entre grupos (Z-test, Teste Qui-Quadrado).  
   - **Significância:** p-value de **0.05** (resultado estatisticamente significativo).  
   - **Intervalo de Confiança:** 95% para diferença entre versões.  
3. **Visualização:**  
   - Gráficos de barras comparando CTR.  
   - Distribuição de cliques por grupo.  

### 📈 **Resultados Detalhados**  
| Métrica           | Versão A | Versão B | 
|-------------------|----------|----------|
| CTR Médio         | 4.9%     | 8.2%     |  


---

## 🛠️ **Tecnologias Utilizadas**  
<div align="center">  
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">  
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">  
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">  
  <img src="https://img.shields.io/badge/Statsmodels-8CAAE6?style=for-the-badge&logo=statsmodels&logoColor=white" alt="Statsmodels">  
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">  
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">  
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">  
</div>  

---

## 📂 **Estrutura do Repositório**  
```plaintext
AB-test/  
├── dados/                  
│   ├── raw/               # Dados brutos (CSV)  
│   └── processed/         # Dados tratados  
├── notebooks/              
│   └── [AB_Testing]_CTR_Campaing.ipynb  # Análise completa  
├── relatorios/            # Gráficos exportados (PNG/PDF)  
├── requirements.txt       # Dependências  
└── README.md              # Documentação  
