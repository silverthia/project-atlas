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

# Priorização Estratégica

As fontes serão classificadas em três níveis de prioridade.

## Tier 1 - Core Dataset

Fontes sem as quais o Atlas não consegue gerar valor relevante.

Exemplos:

- Portais imobiliários
- Dados de aluguel
- Airbnb
- FipeZap
- Leilões

---

## Tier 2 - Contexto de Mercado

Fontes utilizadas para contextualizar e enriquecer análises.

Exemplos:

- Google Trends
- Google Places
- Booking
- IBGE

---

## Tier 3 - Diferenciais

Fontes capazes de aumentar o poder preditivo dos modelos, mas não essenciais para a validação inicial da tese.

Exemplos:

- Dados de voos
- Mobilidade
- Redes sociais
- Dados climáticos
- Eventos

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

## Categoria 6 - Demografia e Migração

Objetivo:

Identificar regiões em crescimento ou declínio estrutural.

---

### DS-009

Fonte:
IBGE / Eurostat / ISTAT

Tipo:
Demografia

Dados:

* população histórica
* migração líquida
* renda
* idade média
* formação de domicílios

Hipóteses:

* HYP-001
* HYP-002

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

Mapeamento
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
## Categoria 7 - Distress e Pressão Vendedora

Objetivo:

Identificar ativos com potencial de aquisição abaixo do valor de mercado.

---

### DS-010

Fonte:
Leilões Caixa, Mega Leilões, Zuk e agregadores

Tipo:
Distress

Dados:

* valor de avaliação
* valor de venda
* desconto
* histórico de leilões
* localização

Hipóteses:

* HYP-003

Valor Estratégico:

5/5

Prioridade:

Alta

Status:

Mapeamento

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

* # Aplicação das Fontes no Produto

As fontes deverão ser classificadas também de acordo com a funcionalidade que suportam dentro do Atlas.

| Fonte | Discovery | Analysis |
|---------|---------|---------|
| Google Trends | Sim | Não |
| Google Places | Sim | Não |
| Airbnb | Sim | Parcial |
| Booking | Sim | Parcial |
| FipeZap | Não | Sim |
| Portais Imobiliários | Sim | Sim |
| Leilões | Sim | Sim |
| IBGE | Sim | Parcial |

Onde:

Discovery:
Identificação de oportunidades e regiões promissoras.

Analysis:
Avaliação detalhada de um ativo específico.
