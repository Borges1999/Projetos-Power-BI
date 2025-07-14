# 📦 Amazon Delivery Dashboard

Este projeto consiste na construção de um **dashboard interativo** no Power BI, com foco na **análise de entregas realizadas** por agentes da Amazon. Foram utilizados dados com informações geográficas, operacionais e meteorológicas.

---

## 📊 Principais Análises

### 1. **Indicadores Chave (KPI Cards)**
- **Qtd. Orders**: Total de pedidos realizados.
- **Qtd. Category**: Quantidade de categorias de produtos distintas.
- **Avg. Delivery Time**: Tempo médio de entrega (em dias).
- **Avg. Agent Age**: Idade média dos entregadores.
- **Avg. Agent Rating**: Nota média dos agentes.

### 2. **Gráficos e Visuais**
- 📅 **Contagem de Pedidos por Mês** – Para análise de sazonalidade.
- 🏆 **Top 3 Categorias de Produto** – Maiores volumes de entregas.
- 📦 **Tempo Médio de Entrega por Categoria** – Comparativo entre tipos de produto.
- 🌍 **Mapa por Latitude e Longitude** – Distribuição geográfica das entregas.

---

## 🧹 Tratamento de Dados (Excel / Power Query)

### ✔️ Etapas Realizadas:
- **Padronização de texto**: Ajuste de capitalização para colunas como `Vehicle`.
- **Conversão de tempo**: Cálculo de `Delivery Time` com correção de diferenças entre dias.
- **Filtragem de dados nulos**:
  - Remoção de valores `"NaN"` nas colunas `Weather`, `Vehicle` e `Traffic`.
- **Conversão de tipo**:
  - Valores decimais de tempo foram convertidos em dias inteiros para visualização.

---

## 🌐 Dados Geográficos

- Foram utilizadas colunas `Store_Latitude` e `Store_Longitude` para plotagem em mapas.
- Validação de faixas aceitáveis:
  - Latitude: -90 a 90
  - Longitude: -180 a 180

---

## 📈 Imagens do Dashboard

### 💡 Versão Final

<img width="1245" height="677" alt="image" src="https://github.com/user-attachments/assets/8aeb9261-2a03-4ee8-9f3a-e0f0c4fb5e31" />

<img width="1242" height="695" alt="image" src="https://github.com/user-attachments/assets/0be29054-bf93-4326-abfd-e1b315475b6f" />

## 🖼️ Estilo Visual

### 🎨 Paleta de Cores
- Fundo: Azul escuro (`#1f2633`)
- Destaques: Azul ciano para KPIs, dourado suave para gráficos e cartões.

### 🔤 Fonte Utilizada
- **Segoe UI Semibold** – Fonte nativa do PowerPoint/Power BI, moderna, legível e elegante.

---

## 🧩 Dados Utilizados

- **Fonte:** [(https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset)](https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset)
- Os dados foram tratados diretamente no Excel e Power BI.

---

## 🛠 Tecnologias e Ferramentas

- Excel
- [Power BI Desktop (.pbix)](https://powerbi.microsoft.com/)
- Power Point para criação dos layouts
- GitHub para versionamento e documentação
