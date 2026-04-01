# LinkedIn Authority Posts — Claude Skill

Skill para o Claude criar posts de LinkedIn no estilo e voz do Leonardo Alves — Head of Product com foco em IA, agentes autônomos e fintech.

O objetivo de cada post é gerar autoridade, atrair leads para projetos e chamar atenção de recrutadores. Não é conteúdo genérico de LinkedIn. É posicionamento de especialista.

## Como usar

1. Importe o arquivo `linkedin-authority-posts.skill` no [Claude Cowork](https://cowork.claude.ai)
2. Peça ao Claude para escrever um post de LinkedIn sobre qualquer tema do seu domínio
3. Itere até aprovação

Triggers: "post", "LinkedIn", "conteúdo de autoridade", "thought leadership", "provocação", "artigo curto", brainstorming de temas.

## Estrutura dos arquivos

```
├── README.md                              # Este arquivo
├── linkedin-authority-posts.skill         # Skill empacotada (ZIP) para importar no Claude Cowork
├── SKILL.md                               # Instruções completas da skill
└── references/
    ├── artigos-publicados.md              # Referência de estilo dos artigos já publicados
    └── posts-aprovados.md                 # Posts modelo aprovados
```

## Perfil do autor

Leonardo é Head of Product numa fintech de agentes autônomos na América Latina. 8+ anos construindo produtos digitais em startups e grandes empresas em mercados regulados (fintech, pagamentos, B2B). MBA pela FGV, formação em engenharia e product design.

**Temas de domínio:** IA aplicada, agentes autônomos financeiros, produto em mercados regulados, distribuição vs tecnologia, vibe coding, futuro do trabalho em produto, stablecoins, infraestrutura financeira.

## Regras absolutas

- NUNCA mencionar o nome da empresa onde o autor trabalha
- NUNCA usar tom corporativo, jargão de consultoria ou linguagem de press release
- NUNCA usar emojis
- NUNCA escrever parágrafos longos (máximo 2-3 linhas por bloco)

## Tom e voz

Direto, provocador e acessível. Alguém no front das trincheiras explicando o que está vendo pro mercado.

- **Frases curtas e cortantes.** Ritmo de conversa, não de artigo.
- **Provocação com substância.** Cada provocação vem com dado, observação real ou experiência.
- **Simplicidade agressiva.** Explica coisas complexas de forma que qualquer pessoa entende.
- **Opinião forte sem arrogância.** Toma posição clara. Ataca ideias fracas, não pessoas.
- **Português brasileiro natural.** Termos em inglês quando são do mercado (go-to-market, vibe coding, edge cases).

## Anatomia do post

### 1. Hook (primeiras 2 linhas)

O que aparece antes do "ver mais". Deve causar: "concordo totalmente", "discordo e quero responder" ou "preciso saber mais".

**Contraste direto:**
```
Nunca foi tão fácil construir um produto de IA.

E nunca foi tão difícil vender um.
```

**Provocação pessoal:**
```
Se o seu dia ainda é priorizar backlog e escrever user stories, tenho uma notícia ruim.
```

**Pergunta retórica forte:**
```
If tech is no longer the barrier, what makes a product win?
```

### 2. Corpo (desenvolvimento)

Ritmo rápido alternando entre:
- Observação do mercado
- Dado de fonte grande (McKinsey, Bain, CB Insights, a16z, HBR)
- Frase de impacto que sintetiza

Usa repetição rítmica:
```
Antes: discovery com usuários. Agora: discovery com os edge cases que o agente encontra em produção.

Antes o risco era entregar a feature errada. Agora é o agente executar a ação certa no momento errado.
```

Usa paralelismo para tensão:
```
Quem tem base de usuários está plugando IA na infraestrutura que já existe.

Quem não tem base está brigando por atenção num mercado onde todo mundo grita a mesma coisa.
```

### 3. Dado de fonte grande

Pelo menos 1 dado de fonte reconhecida por post. Embutido na argumentação, não como citação formal. Link da fonte no final do post.

### 4. Fechamento provocador

Pergunta direta, sentença de impacto ou divisão de mundos. Objetivo: gerar comentários.

```
Você confiaria num agente de IA pra mover seu dinheiro? Sem você aprovar. Sem você ver.
```

```
Porque em 2026, produto sem canal é portfolio no GitHub.
```

### 5. Hashtags

5-8 hashtags. Sempre incluir #IA. Mesclar amplas (#Fintech, #Startups) com específicas (#AIAgents, #GoToMarket).

## Tamanho

150-250 palavras. Até 400 para artigos mais longos. Mesmo ritmo de frases curtas.

## O que NÃO fazer

- Não começar com "No cenário atual..." ou "É inegável que..."
- Não listar benefícios genéricos de IA
- Não fazer post motivacional
- Não citar mais de 2 fontes por post
- Não usar bullet points formais
- Não colocar o autor como herói — o mercado é o protagonista
- Não falar como se estivesse explicando IA pra leigos

## Temas recorrentes

- Distribuição > tecnologia (quem tem canal ganha, não quem tem tech)
- Agentes que movem dinheiro vs agentes que respondem perguntas
- O papel do PM na era de agentes autônomos
- Riscos e regulação como vantagem competitiva
- Vibe coding e a democratização da criação (mas não da distribuição)
- KYA: Know Your Agent como novo paradigma
- Infraestrutura financeira da próxima década
- Gap entre hype e operação real (quem fala vs quem faz)
- Futuro do trabalho em produto/tech

## Workflow

1. Receber o tema/ângulo
2. Buscar 1-2 dados atualizados de fontes grandes
3. Escrever o post seguindo a estrutura
4. Apresentar para feedback
5. Iterar até aprovação
6. Salvar o post final em markdown
