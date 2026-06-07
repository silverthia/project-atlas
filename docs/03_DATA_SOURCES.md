# Project Atlas

Document: 03_DATA_SOURCES

Version: 0.1

Status: Draft

---

# Objetivo

Catalogar todas as fontes de dados potencialmente relevantes para validar as hipóteses do Project Atlas.

Este documento não tem como objetivo detalhar implementações técnicas.

Seu objetivo é responder:

* Quais dados existem?
* Onde eles estão?
* Como podem ser acessados?
* Qual seu custo?
* Qual seu valor para o Atlas?
* Quais hipóteses ajudam a validar?

---

# Critérios de Avaliação

Cada fonte receberá avaliações para:

| Critério                 | Escala               |
| ------------------------ | -------------------- |
| Valor Estratégico        | 1-5                  |
| Facilidade de Integração | 1-5                  |
| Cobertura Histórica      | 1-5                  |
| Escalabilidade           | 1-5                  |
| Prioridade               | Alta / Média / Baixa |

---

# Classificação das Fontes

## Categoria 1 - Demanda e Interesse

Objetivo:

Identificar sinais antecedentes de interesse por regiões, cidades ou destinos.

---

### DS-001

Fonte:
Google Trends

Tipo:
Interesse de busca

Dados:

* volume relativo de buscas
* evolução temporal
* sazonalidade
* comparação entre regiões

Cobertura:

Global

Histórico:

Alto

API:

Não oficial

Hipóteses:

* HYP-001
* HYP-002

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

A validar

---

### DS-002

Fonte:
Google Places

Tipo:
Pontos de interesse

Dados:

* atrações
* restaurantes
* hotéis
* avaliações
* crescimento da oferta local

Hipóteses:

* HYP-002

Valor Estratégico:

4/5

Prioridade:

Alta

Status:

A validar

---

## Categoria 2 - Turismo

Objetivo:

Medir crescimento turístico antes da valorização imobiliária.

---

### DS-003

Fonte:
Booking

Tipo:
Oferta e demanda turística

Dados:

* acomodações
* disponibilidade
* preços
* avaliações

Hipóteses:

* HYP-001
* HYP-002

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

Pesquisa inicial

---

### DS-004

Fonte:
Airbnb

Tipo:
Mercado de short stay

Dados:

* diária média
* ocupação
* receita estimada
* quantidade de anúncios

Hipóteses:

* HYP-001
* HYP-002

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

Pesquisa inicial

---

## Categoria 3 - Mercado Imobiliário

Objetivo:

Mensurar evolução de preços e liquidez.

---

### DS-005

Fonte:
FipeZap

Tipo:
Índice de preços

Dados:

* preço por cidade
* evolução temporal
* histórico

Hipóteses:

* HYP-001
* HYP-002

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

Pesquisa inicial

---

### DS-006

Fonte:
Zap Imóveis

Tipo:
Anúncios imobiliários

Dados:

* preço
* metragem
* localização
* tempo de anúncio

Hipóteses:

* HYP-003

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

Pesquisa inicial

---

## Categoria 4 - Leilões

Objetivo:

Identificar oportunidades de aquisição com desconto.

---

### DS-007

Fonte:
Leiloeiros e agregadores

Dados:

* valor de avaliação
* valor de arrematação
* desconto
* localização

Hipóteses:

* HYP-003

Valor Estratégico:

4/5

Prioridade:

Alta

Status:

Mapeamento

---

## Categoria 5 - Infraestrutura

Objetivo:

Identificar investimentos que possam antecipar valorização.

---

### DS-008

Fonte:
IBGE

Dados:

* população
* renda
* demografia

Hipóteses:

* HYP-002

Valor Estratégico:

4/5

Prioridade:

Alta

Status:

Mapeamento

---

# Backlog de Fontes

* Dados de voos
* Google Hotels
* Investimentos públicos
* Dados climáticos
* Dados de mobilidade
* Redes sociais
* Dados de crédito
* Dados de financiamento imobiliário
* Construção civil
* Licenciamento urbano
* Novos empreendimentos

---

# Próximo Objetivo

Transformar cada fonte catalogada em uma ficha técnica contendo:

* URL
* Tipo de acesso
* API
* Custo
* Limitações
* Cobertura geográfica
* Cobertura histórica
* Estrutura dos dados
* Frequência de atualização
* Complexidade de integração
