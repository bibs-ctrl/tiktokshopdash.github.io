# mindbodygreen · TikTok Shop Dashboard

Dashboard em HTML para visualização de performance de Paid Media do TikTok Shop da mindbodygreen, com foco em campanhas GMV Max e análise por período, produto e tendência diária. O arquivo atual usa uma estética inspirada na identidade visual da mbg, com layout clean, tons neutros e acentos sage green. :contentReference[oaicite:0]{index=0}

---

## Objetivo

Este dashboard foi criado para apresentar a performance de campanhas de TikTok Shop de forma visualmente organizada, fácil de consumir e alinhada ao universo visual da mindbodygreen.

Ele serve principalmente para:

- visualização executiva rápida
- acompanhamento diário de spend, revenue, orders, CPO e ROI
- comparação de períodos
- análise por produto
- uso externo via hospedagem
- possível incorporação em Looker Studio via URL embed

---

## Estrutura do dashboard

O dashboard atual inclui as seguintes seções: :contentReference[oaicite:1]{index=1}

### 1. Header
Contém:
- identificação visual `mbg`
- título do dashboard
- campanha em análise
- selo TikTok Shop
- data de última atualização

### 2. Tabs visuais
As abas atuais são:
- Overview
- By Product
- By Campaign
- Daily Trend

No arquivo atual, essas tabs são visuais e não possuem navegação dinâmica implementada em JavaScript. :contentReference[oaicite:2]{index=2}

### 3. Period Comparison
Bloco com comparação entre:
- Yesterday
- Last Week
- Month To Date

Cada card exibe:
- Spend
- Revenue
- Orders
- ROI
- Cost Per Order

### 4. Last Week · Daily Performance
Área com gráficos para:
- Spend vs Revenue
- ROI by Day

No modelo atual, os gráficos foram construídos manualmente em SVG/HTML. :contentReference[oaicite:3]{index=3}

### 5. Product Breakdown
Tabela de performance por produto no período selecionado, com:
- Spend
- Revenue
- Orders
- CPO
- ROI

### 6. Daily Breakdown
Tabelas de detalhamento diário para:
- Last Week
- Month To Date

### 7. Footer
Rodapé com contexto de fonte e assinatura da marca.

---

## Stack utilizada

Este dashboard foi construído em:

- **HTML**
- **CSS**
- **SVG estático**
- **Google Fonts (Inter)** :contentReference[oaicite:4]{index=4}

Atualmente, o arquivo **não utiliza JavaScript**, backend ou conexão dinâmica com planilha/API. Os dados estão escritos diretamente no HTML. :contentReference[oaicite:5]{index=5}

---

## Identidade visual

A interface segue uma direção inspirada na estética da mindbodygreen, com:

- fundos claros e quentes
- tipografia limpa
- contraste suave
- bordas discretas
- visual editorial e premium
- acentos em sage/olive green

### Variáveis de cor atuais
As variáveis CSS definidas no arquivo incluem: :contentReference[oaicite:6]{index=6}

- `--bg-primary: #F7F5EF`
- `--bg-secondary: #EFEADF`
- `--bg-card: #FFFFFF`
- `--text-primary: #1F1F1B`
- `--text-secondary: #5F5B54`
- `--accent-sage: #8F9A84`
- `--accent-olive: #6F7865`
- `--border: #D9D4CB`
- `--sand: #D8CFBF`
- `--pale: #E5E8DF`

### Tipografia
- Fonte principal: **Inter**
- Pesos usados: 300, 400, 500, 600, 700 :contentReference[oaicite:7]{index=7}

---

## Arquivo principal

```bash
index.html
