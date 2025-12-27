# 📊 Projeto TelecomX: Inteligência de Dados contra a Evasão de Clientes

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=python&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

## 📌 1. Visão Geral e Objetivo
Este projeto foi desenvolvido como parte do **Desafio Parte 1 do Programa ONE (Oracle Next Education) - Formação Data Science**. 

No contexto da **Telecom X**, empresa que enfrenta um alto índice de cancelamentos, este trabalho foca na análise do "Churn de Clientes". O objetivo central é a coleta, tratamento e análise de dados para identificar os fatores que levam à perda de clientes. Esta análise serve como fundação técnica para que a equipe de Data Science possa avançar na construção de modelos preditivos e estratégias de retenção.

## 🛠️ 2. Pipeline de Dados (Processo ETL)
Para transformar dados brutos em inteligência estratégica, foi implementado um pipeline de ETL (Extração, Transformação e Carga) estruturado:

1. **Extração (Extract):** Consumo de dados brutos provenientes de API em formato JSON.
2. **Transformação (Transform):**
    * **Flattening:** Desaninhamento de estruturas complexas para o formato tabular.
    * **Sanitização:** Limpeza, tratamento de tipos e padronização para garantir a precisão estatística.
3. **Carga e Análise (Load):** Estruturação final para geração de visualizações e extração de insights.

## 📈 3. Análise de Churn e Insights Principais
A análise exploratória revelou um padrão crítico: o perfil de **"Novo / Alto Valor"** possui a maior taxa de evasão, gerando prejuízo direto no CAC (Custo de Aquisição de Cliente).

### Insight Chave:
Clientes com menos de 12 meses de contrato e faturas acima da média apresentam um "gatilho de preço" elevado, exacerbado pela falta de serviços de segurança que aumentariam o valor percebido.

<div align="left">
  <img src="perfil_risco.png" width="65%" alt="Mapa de Risco Estratégico">
</div>

> 📄 **[Confira aqui o Relatório Executivo Completo (PDF)](./TelecomX_BR.ipynb%20-%20Colab%20-%20Relatorio%202.pdf)**

## 💡 4. Recomendações Estratégicas
* **Fidelização por Serviços:** Promoção de serviços de segurança e backup para aumentar a percepção de valor e a dependência do ecossistema.
* **Subsídio de Maturação:** Implementação de benefícios ou descontos durante o primeiro ano de contrato para ultrapassar a "janela crítica" de evasão.
* **Monitoramento Ativo:** Configuração de alertas no CRM para clientes de alto ticket com pouco tempo de permanência, permitindo intervenções proativas.

## 🚀 5. Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone [https://github.com/taniamara13/ONE-TelecomX-Challenge-Churn-Analysis.git](https://github.com/taniamara13/ONE-TelecomX-Challenge-Churn-Analysis.git)

   ## ✍️ Autoria e Contato

Este projeto foi desenvolvido por **Tânia Mara F. de Andrade** como parte da formação em Data Science no programa Oracle Next Education.

* **LinkedIn:** [linkedin.com/in/taniamara13](https://www.linkedin.com/in/taniamara13)
* **GitHub:** [github.com/taniamara13](https://github.com/taniamara13)
