# PE_FinalBoss_UFG
Trabalho final da disciplina de Probabilidade e Estatística (UFG)

## **Dicionário de Dados: Características e Vendas de Videogames**

Esta seção detalha as variáveis presentes no conjunto de dados após o processo de limpeza, fornecendo contexto sobre sua medição, interpretação e classificação estatística.

---

### **Identificadores e Informações Básicas**

#### `title`
- **Descrição:** Nome oficial do videogame
- **Tipo:** Variável qualitativa nominal

#### `release_date`
- **Descrição:** Data completa de lançamento do jogo
- **Formato:** AAAA-MM-DD

---

### **Variáveis Qualitativas (Categóricas)**

#### `console` (Plataforma)
- **Descrição:** Plataforma de videogame onde o jogo foi lançado
- **Tipo:** Variável qualitativa nominal
- **Categorias:** 23 plataformas únicas no dataset analisado

#### `genre` (Gênero)
- **Descrição:** Categoria do jogo baseada em sua mecânica e estilo de gameplay
- **Tipo:** Variável qualitativa nominal
- **Categorias:** 18 gêneros únicos no dataset analisado

#### `publisher` (Publicadora)
- **Descrição:** Empresa responsável pela publicação e distribuição comercial do jogo
- **Tipo:** Variável qualitativa nominal
- **Quantidade:** 84 publishers únicos no dataset analisado

#### `developer` (Desenvolvedora)
- **Descrição:** Estúdio ou empresa responsável pelo desenvolvimento técnico do jogo
- **Tipo:** Variável qualitativa nominal
- **Quantidade:** 400 developers únicos no dataset analisado

---

### **Variáveis Quantitativas Discretas**

#### `year` (Ano de Lançamento)
- **Descrição:** Ano em que o jogo foi oficialmente lançado no mercado
- **Tipo:** Variável quantitativa discreta
- **Unidade:** Anos (formato numérico inteiro)
- **Intervalo no dataset analisado:** 1993 a 2018
- **Origem:** Extraída da coluna `release_date`
---

### **Variáveis Quantitativas Contínuas**

#### `critic_score` (Pontuação da Crítica)
- **Descrição:** Avaliação média agregada de críticos especializados, baseada em reviews profissionais (tipicamente do Metacritic)
- **Tipo:** Variável quantitativa contínua
- **Unidade:** Escala de 0 a 10

#### `total_sales` (Vendas Globais Totais)
- **Descrição:** Total de cópias vendidas mundialmente, somando todas as regiões
- **Tipo:** Variável quantitativa contínua
- **Unidade:** Milhões de cópias

#### `na_sales` (Vendas na América do Norte)
- **Descrição:** Número de cópias vendidas nos Estados Unidos, Canadá e México
- **Tipo:** Variável quantitativa contínua
- **Unidade:** Milhões de cópias

#### `pal_sales` (Vendas na Região PAL)
- **Descrição:** Número de cópias vendidas na Europa, África, Austrália e partes da Ásia (exceto Japão)
- **Tipo:** Variável quantitativa contínua
- **Unidade:** Milhões de cópias

#### `other_sales` (Vendas em Outras Regiões)
- **Descrição:** Vendas em regiões não cobertas pelas categorias anteriores (América Latina, Oriente Médio, China, etc.)
- **Tipo:** Variável quantitativa contínua
- **Unidade:** Milhões de cópias
---