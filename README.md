# 📊 Dashboard Interativo de Faturamento

Dashboard interativo desenvolvido em **Python com Plotly** para análise de faturamento e quantidade de produtos vendidos por loja e produto.  
O projeto permite explorar os dados de forma dinâmica, facilitando a identificação de padrões de vendas e desempenho por unidade.

🔗 **Acesse o dashboard online:**  
https://edsondamasceno.github.io/dashboard-faturamento/

---

## 🎯 Objetivo do Projeto
Criar um dashboard interativo para apoiar a análise de vendas, permitindo:
- Comparar o desempenho entre lojas
- Avaliar quantidade vendida por produto
- Analisar faturamento por produto de forma visual e intuitiva

---

## 📈 Funcionalidades
- Filtro dinâmico por **Loja**
- Visualização de:
  - Quantidade vendida por produto
  - Faturamento por produto (R$)
- Gráficos interativos com **hover informativo**
- Interface acessível diretamente pelo navegador (GitHub Pages)

---

## 🧠 Técnicas Utilizadas
- Agregação de dados com `groupby`
- Limpeza e preparação de dados com Pandas
- Visualização interativa com Plotly (`graph_objects` e `subplots`)
- Atualização dinâmica de gráficos via `updatemenus`

---

## 🛠️ Tecnologias
- Python
- Pandas
- Plotly
- GitHub Pages

---

## 📂 Estrutura do Projeto
```text
dashboard-faturamento/
│
├── index.html # Dashboard publicado (GitHub Pages)
├── dashboard_faturamento.py # Código Python para geração do dashboard
├── data/
│ └── faturamento.xlsx # Dataset utilizado na análise
└── README.md # Documentação do projeto


