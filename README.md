
# 📊 Relatório Financeiro com Foco na Experiência do Usuário (Power BI)

Projeto do **Desafio de Projeto da DIO – Formação Power BI Analyst**: atualização de um relatório financeiro criativo, aplicando princípios de **UX** e **navegação interativa** no Power BI.

---

## 🎯 Objetivo

Reformular o primeiro relatório criado no curso, melhorando a experiência de quem o utiliza. Para isso foram considerados:

- **Posicionamento** – hierarquia visual: título e filtros no topo, KPIs em destaque, detalhes abaixo.
- **Contraste** – cores e fontes que separam claramente fundo, painéis, textos e visuais.
- **Proporção áurea** – divisão da página em blocos com proporções harmônicas (área principal maior + área secundária menor).
- **Segmentação de dados** – filtros (slicers) acessíveis e de uso intuitivo.

> Como comentado no curso, essas diretrizes não são regras rígidas: o importante é entendê-las e saber quando quebrá-las para dar criatividade ao relatório.

---

## 🗂️ Estrutura do relatório

O relatório tem **3 páginas** (tela 1280 × 720) com menus de navegação em cada uma.

### 1️⃣ Sales (página inicial)
- **Cartões (KPIs):** Sales e Units Sold.
- **Gráficos de barras agrupadas:** vendas por **Segmento** e por **Produto**, alternados pelos botões **“Visão Segmento”** e **“Visão Produto”**.
- **Gráfico de área:** evolução das vendas por Ano/Mês.
- **Matriz:** descrição de vendas por Ano e Mês.
- **Segmentação de data:** “Selecione a data” (intervalo entre datas).
- **Navegação:** menu lateral com `pageNavigator` e botões estilizados.

### 2️⃣ Profit — *Report de Lucro Detalhado*
- **Árvore de decomposição:** análise de Profit por Ano, País e outras dimensões.
- **Gráfico de cascata:** Profit por Trimestre.
- **Gráfico de radar** (visual personalizado): Profit por Produto.
- **Treemap:** Profit por Segmento.
- **Chiclet Slicer** (visual personalizado): filtro por Ano.
- **Botões:** voltar e **Home Page**.

### 3️⃣ Report — *Report de Vendas Detalhado*
- **Gráfico de colunas + linhas:** Sales × Gross Sales por mês.
- **Gráfico de área:** vendas por Trimestre/Mês.
- **Matriz:** Trimestre × Ano.
- **Botões:** voltar e **Home Page**.

---

## 🧭 Navegação e interatividade

- Botões de navegação em todas as páginas.
- Estados de **foco (hover)** e **seleção** destacados nos botões (negrito ao passar o mouse, cor de fonte diferente quando selecionado).
- Botão **Home Page** para retornar à página inicial.
- Menu de navegação lateral na página inicial.
- Estilo livre dos botões, com cabeçalhos, logos e formas personalizadas.

---

## 🛠️ Tecnologias e recursos

- **Power BI Desktop**
- Base de dados **financials** (Financial Sample)
- Tema base: *CY22SU09*
- Visuais personalizados: **Chiclet Slicer** e **Radar Chart**
- Hierarquia de datas (Ano › Trimestre › Mês)

---

## 📁 Estrutura do repositório

```
├── README.md
├── relatorio-financeiro-ux.pbix     # arquivo do Power BI
├── docs/
│   ├── enunciado-desafio.docx       # enunciado e ementa das aulas
│   └── prints/                      # capturas de tela das páginas
│       ├── 01-sales.png
│       ├── 02-profit.png
│       └── 03-report.png
```

---

## 🖼️ Prévia

> _Adicione aqui as capturas de tela de cada página (Sales, Profit e Report)._

```md
![Página Sales](docs/prints/01-sales.png)
![Página Profit](docs/prints/02-profit.png)
![Página Report](docs/prints/03-report.png)
```

---

## ▶️ Como usar

1. Baixe o arquivo `relatorio-financeiro-ux.pbix`.
2. Abra no **Power BI Desktop**.
3. Navegue pelas páginas usando o menu e os botões.
4. Use os filtros de data e de ano para explorar os dados.

---

## 📚 Aprendizados

- Organização visual de um relatório (posicionamento, contraste, proporção áurea).
- Uso de segmentadores para melhorar a exploração dos dados.
- Criação de botões de navegação com estados de foco e seleção.
- Uso de visuais avançados: árvore de decomposição, cascata, radar e treemap.
- Boas práticas de UX aplicadas a dashboards.

---

## 👤 Autor

**[Seu nome]** — [LinkedIn](https://linkedin.com/in/seu-usuario) · [GitHub](https://github.com/seu-usuario)

Projeto desenvolvido no bootcamp/curso **Formação Power BI Analyst** — [DIO](https://www.dio.me/).
