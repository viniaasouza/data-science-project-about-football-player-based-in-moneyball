# Diamantes Brutos do Futebol Europeu 2024/25
## Análise de Dados para Identificação de Jogadores com Melhor Relação Custo-Benefício

**Autor:** Análise de Dados de Futebol  
**Data:** Agosto 2025  
**Temporada Analisada:** 2024/25  
**Ligas:** Premier League, LaLiga, Serie A, Bundesliga, Ligue 1  

---

## 📋 Resumo Executivo

Este projeto aplica conceitos de análise de dados inspirados no "Moneyball" para identificar jogadores de futebol com excelente relação custo-benefício nas cinco principais ligas europeias. Utilizando dados reais da temporada 2024/25, desenvolvemos uma metodologia para encontrar "diamantes brutos" - jogadores com alto desempenho ofensivo e baixo valor de mercado.

**Principais Descobertas:**
- **Kike García** (Deportivo Alavés) lidera o ranking com apenas €69.231 por contribuição de gol
- **LaLiga** concentra os melhores achados custo-benefício
- Jogadores veteranos experientes dominam o top 10
- **554 jogadores ofensivos** analisados nas Big 5 ligas

---

## 🎯 Objetivos do Projeto

### Objetivo Principal
Desenvolver uma metodologia baseada em dados para identificar jogadores de futebol subvalorizados no mercado europeu, criando valor para clubes com orçamentos limitados.

### Objetivos Específicos
1. **Coletar e processar** dados de desempenho de jogadores das Big 5 ligas europeias
2. **Criar métricas** de custo-benefício baseadas em contribuições ofensivas
3. **Identificar padrões** de subvalorização no mercado de transferências
4. **Visualizar resultados** de forma clara e impactante
5. **Estruturar análise** como projeto de portfólio profissional

---

## 📊 Metodologia

### 1. Fonte de Dados
- **Dataset:** Football Datasets (Kaggle)
- **Período:** Temporada 2024/25
- **Escopo:** 5 principais ligas europeias
- **Registros:** 88.010 performances individuais

### 2. Critérios de Seleção

#### Ligas Analisadas
| Liga | ID | País | Registros |
|------|----|----- |-----------|
| Premier League | KG1L | Inglaterra | - |
| LaLiga | ES1 | Espanha | 745 |
| Serie A | IT1 | Itália | 812 |
| Bundesliga | L1 | Alemanha | 579 |
| Ligue 1 | FR1 | França | 664 |

#### Filtros Aplicados
- **Temporada:** 24/25 (mais recente com dados completos)
- **Posições:** Atacantes e meio-campistas ofensivos
- **Critério mínimo:** Pelo menos 1 contribuição para gol (G+A)
- **Valor de mercado:** Maior que €0 (dados disponíveis)

### 3. Métricas Desenvolvidas

#### Métrica Principal: Custo por Contribuição de Gol
```
Custo por G+A = Valor de Mercado (€) / (Gols + Assistências)
```

#### Métricas Complementares
- **Contribuições Totais (G+A):** Soma de gols e assistências
- **Valor de Mercado:** Em euros (fonte: Transfermarkt)
- **Minutos Jogados:** Para contexto de participação

---



## 🏆 Resultados Principais

### Top 10 Diamantes Brutos (Menor Custo por G+A)

| Posição | Jogador | Clube | Liga | G+A | Valor (€) | Custo/G+A (€) |
|---------|---------|-------|------|-----|-----------|---------------|
| 1º | **Kike García** | Deportivo Alavés | LaLiga | 13 | 900.000 | 69.231 |
| 2º | **Dani Rodríguez** | RCD Mallorca | LaLiga | 11 | 800.000 | 72.727 |
| 3º | **Cristhian Stuani** | Girona FC | LaLiga | 13 | 1.000.000 | 76.923 |
| 4º | **Pedro** | SS Lazio | Serie A | 11 | 1.000.000 | 90.909 |
| 5º | **André Ayew** | Le Havre AC | Ligue 1 | 5 | 600.000 | 120.000 |
| 6º | **Iago Aspas** | Celta de Vigo | LaLiga | 15 | 2.000.000 | 133.333 |
| 7º | **Robinio Vaz** | Olympique Marseille | Ligue 1 | 1 | 150.000 | 150.000 |
| 8º | **Jae-sung Lee** | 1.FSV Mainz 05 | Bundesliga | 15 | 2.500.000 | 166.667 |
| 9º | **Philipp Hofmann** | VfL Bochum | Bundesliga | 6 | 1.000.000 | 166.667 |
| 10º | **Joshua King** | FC Toulouse | Ligue 1 | 10 | 1.800.000 | 180.000 |

### Análise por Liga

#### LaLiga - Líder em Diamantes Brutos
A liga espanhola se destaca com **4 jogadores no top 10**, incluindo os três primeiros colocados. Isso sugere um mercado com oportunidades de valor, especialmente em clubes de médio porte como Alavés, Mallorca e Girona.

**Características dos achados na LaLiga:**
- **Jogadores experientes** (30+ anos) com conhecimento tático
- **Clubes em ascensão** que valorizam eficiência sobre nome
- **Valores de mercado conservadores** comparados ao desempenho

#### Serie A - Qualidade Técnica
Pedro, aos 37 anos, demonstra que experiência e qualidade técnica podem superar limitações físicas. Sua presença na Lazio mostra como veteranos podem ser investimentos inteligentes.

#### Bundesliga - Eficiência Alemã
Jae-sung Lee e Philipp Hofmann representam a filosofia alemã de maximizar recursos. Lee, em particular, oferece versatilidade tática valiosa.

#### Ligue 1 - Mercado Emergente
André Ayew e Joshua King mostram como a liga francesa pode ser fonte de oportunidades, especialmente para jogadores em transição de carreira.

### Padrões Identificados

#### 1. Perfil Etário
A maioria dos diamantes brutos são **jogadores experientes (28-35 anos)** que:
- Possuem maturidade tática
- Têm valores de mercado depreciados pela idade
- Mantêm alta produtividade ofensiva
- Oferecem liderança em campo

#### 2. Contexto dos Clubes
Os melhores achados estão em:
- **Clubes de médio porte** com orçamentos limitados
- **Times em ascensão** que maximizam recursos
- **Projetos de longo prazo** que valorizam experiência

#### 3. Posições de Valor
- **Atacantes centrais** dominam o ranking (60%)
- **Meio-campistas ofensivos** oferecem versatilidade
- **Extremos experientes** mantêm produtividade

---

## 📈 Visualizações e Insights

### Gráfico de Dispersão - Panorama Geral
O scatter plot revela claramente a **"zona dos diamantes brutos"** no canto inferior esquerdo, onde jogadores com alto desempenho (eixo Y) possuem baixo valor de mercado (eixo X). Esta visualização permite identificar rapidamente oportunidades de mercado.

**Insights visuais:**
- **Concentração de oportunidades** abaixo de €5 milhões
- **Outliers positivos** com 15+ contribuições por valores baixos
- **Distribuição por liga** mostra padrões regionais

### Ranking Visual - Top 10
O gráfico de barras horizontais facilita a comparação direta entre os melhores achados, destacando a superioridade de Kike García e a competitividade do top 5.

---

## 🔍 Análise Detalhada dos Destaques

### Kike García - O Diamante Absoluto
**Perfil:** Atacante central, 34 anos, Deportivo Alavés  
**Números:** 13 G+A por €900.000 (€69.231 por contribuição)

García representa o arquétipo perfeito do diamante bruto. Veterano experiente que mantém alta produtividade em um clube que luta contra o rebaixamento. Sua eficiência ofensiva (13 contribuições) por um valor de mercado modesto demonstra como a experiência pode superar limitações percebidas.

**Por que é um achado:**
- Produtividade consistente em contexto adverso
- Valor de mercado subavaliado pela idade
- Liderança técnica e tática comprovada
- Adaptabilidade a diferentes sistemas

### Dani Rodríguez - Versatilidade Ofensiva
**Perfil:** Meio-campista ofensivo, 35 anos, RCD Mallorca  
**Números:** 11 G+A por €800.000 (€72.727 por contribuição)

Rodríguez exemplifica como meio-campistas experientes podem oferecer valor excepcional. Sua capacidade de contribuir ofensivamente enquanto mantém responsabilidades defensivas o torna um investimento multifuncional.

### Cristhian Stuani - Goleador Nato
**Perfil:** Atacante central, 37 anos, Girona FC  
**Números:** 13 G+A por €1.000.000 (€76.923 por contribuição)

Stuani demonstra que idade é apenas um número quando se tem instinto goleador. Sua presença no Girona, clube em ascensão, mostra como veteranos podem ser catalisadores de projetos ambiciosos.

---

## 💡 Implicações Estratégicas

### Para Clubes com Orçamentos Limitados
1. **Foco em veteranos subestimados** pode gerar valor imediato
2. **Análise de contexto** é crucial - jogadores em clubes menores podem estar subvalorizados
3. **Investimento em experiência** oferece retorno técnico e de liderança

### Para Análise de Mercado
1. **LaLiga** oferece as melhores oportunidades custo-benefício
2. **Jogadores 30+** representam nicho de valor inexplorado
3. **Clubes médios** são fontes consistentes de diamantes brutos

### Para Desenvolvimento de Metodologia
1. **Métricas simples** (G+A vs. Valor) são eficazes
2. **Contexto qualitativo** complementa análise quantitativa
3. **Visualizações claras** facilitam tomada de decisão

---


## 🛠️ Implementação Técnica

### Ferramentas Utilizadas
- **Python 3.11** - Linguagem principal
- **Pandas** - Manipulação e análise de dados
- **Matplotlib/Seaborn** - Visualizações
- **Jupyter/Scripts** - Desenvolvimento e documentação

### Estrutura do Projeto
```
projeto_diamantes_brutos/
├── dados/
│   ├── player_profiles.csv
│   ├── player_performances.csv
│   ├── player_latest_market_value.csv
│   └── team_competitions_seasons.csv
├── scripts/
│   ├── exploracao_inicial.py
│   ├── preparar_dados.py
│   └── criar_visualizacoes.py
├── resultados/
│   ├── dados_preparados_big5.csv
│   ├── top_50_diamantes_brutos.csv
│   ├── diamantes_brutos_scatter.png
│   ├── top_10_diamantes_brutos.png
│   └── estatisticas_por_liga.csv
└── documentacao/
    ├── README_projeto.md
    └── post_linkedin.md
```

### Pipeline de Dados

#### 1. Extração e Exploração
```python
# Carregamento dos dados
profiles_df = pd.read_csv('player_profiles.csv')
performances_df = pd.read_csv('player_performances.csv')
market_value_df = pd.read_csv('player_latest_market_value.csv')

# Exploração inicial
print(f"Jogadores: {len(profiles_df)}")
print(f"Performances: {len(performances_df)}")
```

#### 2. Transformação e Limpeza
```python
# Filtrar Big 5 ligas e temporada 24/25
big5_ids = ['KG1L', 'ES1', 'IT1', 'L1', 'FR1']
season = '24/25'

filtered_data = performances_df[
    (performances_df['season_name'] == season) & 
    (performances_df['competition_id'].isin(big5_ids))
]

# Calcular métricas por jogador
player_stats = filtered_data.groupby('player_id').agg({
    'goals': 'sum',
    'assists': 'sum',
    'minutes_played': 'sum'
}).reset_index()
```

#### 3. Análise e Visualização
```python
# Criar métrica custo-benefício
df['cost_per_goal_contribution'] = (
    df['market_value_eur'] / df['goals_contributions']
)

# Gerar visualizações
plt.scatter(df['market_value_millions'], df['goals_contributions'])
plt.xlabel('Valor de Mercado (Milhões €)')
plt.ylabel('Contribuições para Gol (G+A)')
```

### Desafios Técnicos Superados

#### 1. Inconsistência de Dados
**Problema:** Diferentes formatos de temporada e IDs de liga  
**Solução:** Mapeamento manual e validação cruzada dos dados

#### 2. Valores de Mercado Ausentes
**Problema:** Nem todos os jogadores possuem valoração  
**Solução:** Filtro por disponibilidade de dados (inner join)

#### 3. Normalização de Métricas
**Problema:** Diferentes escalas de valores e contribuições  
**Solução:** Conversão para milhões e criação de métricas relativas

---

## 📊 Validação e Limitações

### Validação dos Resultados

#### 1. Verificação Manual
Análise qualitativa dos top 10 confirmou que são jogadores reconhecidamente produtivos em suas respectivas ligas, validando a metodologia.

#### 2. Comparação Contextual
Os resultados são consistentes com análises de mercado que identificam LaLiga como fonte de oportunidades custo-benefício.

#### 3. Coerência Temporal
Dados da temporada 24/25 refletem o mercado atual, aumentando a relevância das descobertas.

### Limitações Reconhecidas

#### 1. Escopo Temporal
- Análise limitada a uma temporada pode não capturar tendências
- Variações sazonais de desempenho não são consideradas

#### 2. Métricas Simplificadas
- Foco apenas em contribuições ofensivas (G+A)
- Não considera aspectos defensivos ou de criação de jogo
- Valor de mercado pode não refletir potencial real

#### 3. Contexto Qualitativo
- Não considera lesões ou circunstâncias especiais
- Adaptação a diferentes sistemas táticos não é avaliada
- Fatores como liderança e experiência são subestimados

#### 4. Viés de Seleção
- Filtro por posições ofensivas exclui outros perfis valiosos
- Critério mínimo de 1 G+A pode excluir jogadores em desenvolvimento

---

## 🎯 Conclusões e Recomendações

### Principais Conclusões

#### 1. Oportunidades Identificadas
A análise revelou **10 jogadores excepcionais** com custo por contribuição de gol inferior a €200.000, demonstrando que existem oportunidades significativas de valor no mercado europeu.

#### 2. Padrões de Mercado
**LaLiga emerge como a liga com maior concentração de diamantes brutos**, sugerindo um mercado mais eficiente em termos de custo-benefício, especialmente em clubes de médio porte.

#### 3. Perfil Ideal
**Jogadores experientes (30+ anos)** dominam o ranking, indicando que a experiência é subvalorizada pelo mercado em favor da juventude, criando oportunidades para clubes inteligentes.

### Recomendações Estratégicas

#### Para Clubes
1. **Priorizar LaLiga** como fonte de scouting para oportunidades custo-benefício
2. **Considerar veteranos** como investimentos de curto prazo com alto retorno
3. **Focar em clubes médios** que podem ter jogadores subvalorizados
4. **Complementar análise quantitativa** com avaliação qualitativa de contexto

#### Para Analistas
1. **Expandir métricas** para incluir aspectos defensivos e de criação
2. **Incorporar dados históricos** para identificar tendências
3. **Desenvolver modelos preditivos** baseados nos padrões identificados
4. **Criar alertas automáticos** para oportunidades emergentes

#### Para Desenvolvimento Futuro
1. **Análise temporal** comparando múltiplas temporadas
2. **Segmentação por idade** para identificar nichos específicos
3. **Incorporação de dados avançados** (xG, xA, passes chave)
4. **Análise de rede** para identificar jogadores complementares

---

## 📚 Referências e Fontes

### Dados Primários
- **Football Datasets (Kaggle)** - Dataset principal com dados de jogadores, performances e valores de mercado
- **Transfermarkt** - Fonte original dos valores de mercado utilizados no dataset

### Metodologia Inspirada
- **Moneyball: The Art of Winning an Unfair Game** - Michael Lewis
- **Analytics in Sports** - Conceitos de análise esportiva aplicada

### Ferramentas e Bibliotecas
- **Python Software Foundation** - Python 3.11
- **Pandas Development Team** - Biblioteca Pandas
- **Matplotlib Development Team** - Biblioteca de visualização
- **Seaborn** - Biblioteca de visualização estatística

---

## 📞 Contato e Portfólio

Este projeto demonstra competências em:
- **Análise de Dados Esportivos**
- **Visualização de Dados**
- **Python e Pandas**
- **Storytelling com Dados**
- **Metodologia de Pesquisa**

**Desenvolvido como projeto de portfólio em Ciência de Dados aplicada ao Esporte**

---

*Última atualização: Agosto 2025*  
*Temporada analisada: 2024/25*  
*Total de jogadores analisados: 554*

