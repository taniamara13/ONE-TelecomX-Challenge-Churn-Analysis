# 📊 TelecomX: Análise Estratégica de Churn e Retenção

![Capa do Projeto](perfil_risco.png)

## 📌 Contexto do Projeto
Este projeto faz parte do **Desafio Parte 1 do Programa ONE (Oracle Next Education)**. O objetivo foi analisar a base de dados da TelecomX para identificar os gatilhos que levam ao cancelamento de clientes (**Churn**) e propor soluções baseadas em dados para aumentar o tempo de permanência (LTV).

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10+
* **Bibliotecas:** `Pandas` (ETL), `Matplotlib` e `Seaborn` (Visualização), `JSON`.
* **Ambiente:** Google Colab

## 🛠️ Pipeline de Dados (ETL)
* **Extração:** Dados consumidos via API em formato JSON.
* **Transformação:** Desaninhamento de chaves complexas (Flattening) e normalização de tipos de dados.
* **Sanitização:** Tratamento de valores nulos e padronização de categorias.

## 📈 Principais Insights (Business Intelligence)
* **Fator Tempo (Causa Raiz):** O risco de evasão é crítico nos primeiros 12 meses. Após este período, a fidelização ocorre de forma orgânica.
* **Fator Preço (Gatilho):** Mensalidades acima de R$ 60,00 disparam a decisão de cancelamento.
* **Perfil de Risco:** Clientes **"Novos / Alto Valor"** representam a maior hemorragia financeira da operação.

## 💡 Recomendações Estratégicas
1. **Subsídio de Primeiro Ano:** Conceder benefícios exclusivos nos primeiros 12 meses para garantir a transição pela zona de risco inicial.
2. **Efeito Ancoragem:** Promover o cross-selling de serviços de segurança e backup para aumentar a dependência do ecossistema.
3. **Monitoramento Ativo:** Implantar alertas de CRM para identificar clientes de alto valor com baixo tempo de casa e agir proativamente.

---
🎨 **Analista Responsável: Tânia Mara F. de Andrade** [LinkedIn](https://www.linkedin.com/in/taniamara13) | [GitHub](https://github.com/taniamara13)
