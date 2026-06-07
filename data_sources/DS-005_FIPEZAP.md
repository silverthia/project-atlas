# DS-005 - FipeZap

Status:

Pesquisa Inicial

Categoria:

Mercado Imobiliário

Prioridade:

Alta

---

# Objetivo

Utilizar os índices FipeZap como referência de mercado para comparação de preços imobiliários.

Esta fonte não tem como objetivo identificar oportunidades diretamente, mas servir como benchmark para avaliação relativa de imóveis, bairros e cidades.

---

# Fonte

FipeZap

Descrição:

Índice que acompanha a evolução dos preços de venda e locação de imóveis residenciais e comerciais em diversas cidades brasileiras.

---

# Perguntas que esta fonte deve ajudar a responder

* O imóvel está acima ou abaixo do mercado?
* O bairro está valorizando ou desvalorizando?
* Como a região evoluiu historicamente?
* O ativo está performando acima ou abaixo da média local?
* Existe divergência entre preço anunciado e comportamento do mercado?

---

# Dados Disponíveis

## Venda

* preço médio por m²
* evolução mensal
* evolução anual
* histórico de valorização

---

## Locação

* aluguel médio por m²
* evolução mensal
* evolução anual

---

## Geografia

Dependendo da disponibilidade:

* Brasil
* Estado
* Cidade
* Bairro

---

# Cobertura

Geográfica:

Principais cidades brasileiras.

---

Temporal:

Histórico de vários anos.

---

# Método de Acesso

A validar.

Possibilidades:

* relatórios públicos
* bases históricas
* APIs
* parceiros institucionais

---

# Utilização no Atlas

## Discovery

Baixa relevância.

Não identifica oportunidades diretamente.

---

## Analysis

Alta relevância.

Utilizada para comparar ativos contra o comportamento médio do mercado.

---

## Indicadores Possíveis

### Market Premium

Diferença percentual entre preço observado e benchmark local.

---

### Relative Appreciation

Valorização relativa do ativo frente ao índice local.

---

### Yield Comparison

Comparação entre rendimento estimado e rendimento médio da região.

---

# Valor Estratégico

4/5

Justificativa:

Fundamental para contextualizar preços e validar hipóteses de valorização.

Entretanto, não fornece granularidade suficiente para identificar oportunidades individualmente.

---

# Limitações

* dados agregados
* baixa granularidade
* não contém anúncios individuais
* não permite monitorar liquidez
* não permite detectar pressão vendedora

---

# Dependências

city

market_snapshot

price_index

---

# Questões em Aberto

* Existe API oficial?
* Qual o nível máximo de detalhamento geográfico disponível?
* Qual a frequência de atualização?
* Existe acesso programático ao histórico completo?
* Há custos de licenciamento?

---

# Critérios de Sucesso

A fonte será considerada validada se permitir:

* construção de benchmarks regionais;
* comparação de preço por m²;
* análise histórica de valorização;
* geração de indicadores relativos para o Alpha Score.

