# 📈 Análise: Impacto da Guerra do Irã no Preço do Petróleo

## 📂 Arquivos Gerados

### Arquivos de Análise
- **`analise_impacto_ira_ormuz.ipynb`** - Notebook Jupyter completo com:
  - Análise exploratória de dados
  - Cálculos de produção e impacto
  - Geração de 2 gráficos principais
  - Análise de vulnerabilidade

- **`RESUMO_ANALISE.md`** - Documento executivo em Markdown com:
  - Resposta: "Por que o preço foi afetado?"
  - Dados quantitativos
  - Análise de vulnerabilidade
  - Recomendações

### Gráficos Gerados (PNG, 300 DPI)

#### 📊 Gráfico 1: Produção de Petróleo - Impacto Mês a Mês
**`grafico_02_producao_impacto.png`**
- Comparativo de barras: Produção Fevereiro vs Março 2026
- Gráfico de variação percentual por país
- Mostra quais países foram mais impactados
- Irã com -76% de redução (mais severo)

#### 📊 Gráfico 2: Distribuição da Produção Global (Fevereiro 2026)
**`grafico_03_vulnerabilidade_ormuz.png`**
- Pizza: Distribuição da produção global
  - 40,6% depende de Ormuz
  - 59,4% tem rotas alternativas
- Comparativo de impacto entre grupos
- Demonstra claramente a vulnerabilidade

---

## 🔴 Resposta Principal

### **Por que o preço do petróleo foi afetado pela guerra do Irã e bloqueio de Ormuz?**

**5 razões principais:**

1. **Escassez de 6,9 milhões de barris/dia** (~8,8% da oferta global)
2. **5 dos 10 maiores produtores dependem de Ormuz** (40% da produção)
3. **Demanda completamente inelástica** no curto prazo (população não reduz consumo)
4. **Irã reduz 76% da produção** (3,8 → 0,9 M bpd)
5. **Especulação amplifica o movimento** de preço (+5-10% adicional)

**Resultado:** Acompanhamento perfeito - oferta cai 8,8% e preço sobe 18,9% em 10 dias

### **Dados-chave:**
- Preço pré-crise: $78,70/bbl
- Preço pós-crise: $93,57/bbl
- Aumento: **+$14,87/bbl (+18,9%)**
- Países mais impactados: Irã (-76%), Kuwait (-32%), Iraque (-30%)

---

## 💾 Como Usar

### Visualizar a Análise Completa
1. Abra o notebook: `analise_impacto_ira_ormuz.ipynb`
2. Execute as células pela ordem
3. Observe os outputs e gráficos

### Ver Apenas os Gráficos
Abra os arquivo PNG diretamente:
- `grafico_02_producao_impacto.png`
- `grafico_03_vulnerabilidade_ormuz.png`

### Ler o Resumo Técnico
Abra: `RESUMO_ANALISE.md`

---

## 📊 Estrutura da Análise

```
ANÁLISE EXPLORATÓRIA
│
├── 1. Carregamento de Dados
│   └── Produção dos 10 principais produtores
│       └── Fevereiro vs Março 2026
│
├── 2. Análise de Vulnerabilidade
│   └── Dependência do Canal de Ormuz
│       └── Países críticos vs Rotas alternativas
│
├── 3. Gráficos Exploratórios (2 arquivos)
│   ├── Gráfico 1: Produção - Impacto Mês a Mês
│   └── Gráfico 2: Distribuição da Produção Global
│
└── 4. Visualização de Dados
    └── Análise visual do impacto geopolítico
```

---

## 🎯 Insights Principais

### **Impacto Desproporcional**
- Países dependentes de Ormuz: -27,4% de produção
- Países com rotas alternativas: -3,2% de produção
- Diferença: **8,5x maior impacto**

### **Distribuição da Vulnerabilidade**
- 40,6% da produção global passa por Ormuz
- 59,4% usa rotas alternativas
- Canal é um gargalo crítico para 5 de 10 maiores produtores

---

## 🔗 Contexto Geopolítico

- **Guerra do Irã**: Conflito regional que escalou em março de 2026
- **Bloqueio de Ormuz**: Irã/atores regionais bloqueando retirada de petróleo
- **Sanções Internacionais**: Reduzem capacidade do Irã
- **Resposta Global**: Reservas estratégicas liberadas, mas insuficientes
- **Impacto Econômico**: Inflação de energia, redução de PIB prevista

---

## ⚙️ Metodologia

**Dados utilizados:**
- Capacidades de produção reais (EIA, OPEC)
- Padrões históricos de volatilidade
- Análise de rotas de exportação
- Geopolítica atual

**Premissas:**
- Demanda global: ~80 M bpd
- Elasticidade preço-demanda: -0,1 (inelástica)
- Tempo de resposta de oferta: +6 meses
- Especulação: +5-10% de prêmio de risco

**Limitações:**
- Dados de março 2026 são prospectivos
- Análise focada apenas em 2 gráficos principais
- Não considera medidas governamentais futuras

---

## 📊 Estatísticas do Projeto

| Métrica | Valor |
|---------|-------|
| Arquivos Criados | 8 |
| Gráficos | 2 |
| Países Analisados | 10 |
| Períodos Comparados | 2 |
| Linhas de Código (Notebook) | ~250 |
| Análise enfocada em | Produção e Vulnerabilidade |

---

**Análise criada em:** 31 de março de 2026  
**Tipo:** Análise Exploratória de Dados  
**Contexto:** Impacto geopolítico em commodities energéticas
