# 🛍️ Alura Store – Análise de Desempenho e Recomendação

&#x20;  &#x20;

![Status](https://img.shields.io/badge/status-concluído-brightgreen)  
![Python](https://img.shields.io/badge/python-3.11-blue)  
![Jupyter Notebook](https://img.shields.io/badge/jupyter-notebook-orange)  

---

## 📌 Sobre

Este repositório contém a análise de desempenho de quatro lojas fictícias da **Alura Store**, desenvolvida como parte do Programa de Formação em Data Science da Alura. O objetivo é identificar, com base em dados de vendas, avaliações e logística, qual loja apresenta menor eficiência e deve ser vendida.

---

## 🎯 Objetivo

- Carregar e explorar dados de quatro unidades de venda.
- Avaliar métricas-chave: faturamento, avaliações de clientes, custos de frete, popularidade de produtos e distribuição geográfica.
- Recomendar, de forma clara e embasada, qual loja deve ser descontinuada/vendida.

---

## 🔗 Fonte dos Dados

Os conjuntos de dados são públicos e estão disponíveis no GitHub da Alura:

- [loja\_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
- [loja\_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
- [loja\_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
- [loja\_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

---

## ⚙️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.11**
- `pandas` – manipulação e análise de dados
- `matplotlib` – visualização estática
- `seaborn` – gráficos estatísticos avançados
- **Jupyter Notebook** – documentação e execução interativa da análise

---

## 📊 Etapas da Análise

1. **Importação e Ajustes Iniciais**
   - Leitura direta das URLs dos CSVs com `pandas`.
   - Verificação de tipos, valores ausentes e conversão de datas.
2. **Métricas de Desempenho**
   - **Faturamento Total**: soma dos preços por loja.
   - **Avaliação Média**: nota média dos clientes.
   - **Frete Médio**: custo médio de entrega por unidade vendida.
3. **Comportamento de Vendas**
   - **Categorias e Produtos**: principais categorias, produtos mais e menos vendidos.
   - Rankings e frequências para insights de mix de produtos.
4. **Análise Geográfica**
   - Mapeamento de pontos de venda por latitude e longitude.
   - Verificação de padrões regionais.
6. **Recomendação Final**
   - Consolidação dos resultados em justificativa clara para decisão de venda.

---

## 📈 Visualizações Geradas

- **Gráfico de Pizza**: comparação de faturamento por loja.
- **Gráfico de Linha**: evolução da média do frete.
- **Gráfico de Barra**: distribuição de vendas por categoria e por loja.
- **Gráfico de Disperção**: dispersão geográfica dos pontos de venda.

---

## 💡 Recomendação Final

> **Manter Loja 1** — com maior faturamento e avaliação média consistente;\
> **Vender Loja 4** — apresenta menor retorno financeiro e maior custo logístico.

A justificativa completa, com gráficos e interpretações, está detalhada no notebook principal.

---

## 🧠 Aprendizados

- Aplicação de diferentes tipos de visualizações para comunicar insights.
- Integração de análise estatística e geoespacial para decisões de negócios.

---

## 💾 Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/alura-store-analise.git
   ```
2. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Abra e execute** o Jupyter Notebook:
   ```bash
   jupyter notebook analise_lojas.ipynb
   ```

---

## 📬 Contato

Para dúvidas, sugestões ou feedback, entre em contato: nickolasstreibel@gmail.com

---
## 👨‍💻 Autor

| [<img src="https://avatars.githubusercontent.com/u/195215720?s=400&u=f536b6f2f37ec4af893cb10f0f872ee9588ff606&v=4" width=115><br><sub>Nickolas Streibel</sub>](https://github.com/Nickolas-Streibel) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | 
| **Desenvolvedor** |

---


