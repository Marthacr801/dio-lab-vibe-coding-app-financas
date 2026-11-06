# 💸 App de Organização de Finanças Pessoais com Vibe Coding - Martha

```markdown
# Build Specification

Crie um aplicativo SaaS de Finanças Pessoais chamado **Agente Financeiro**.

## Objetivo

Permitir que usuários controlem receitas, despesas e metas financeiras através de conversas em linguagem natural, eliminando a necessidade de formulários tradicionais.

A experiência deve ser centrada em um chat com IA que interpreta mensagens do usuário e registra automaticamente informações financeiras.

## Público-Alvo

Pessoas que desejam organizar suas finanças de forma simples, especialmente iniciantes que não gostam de planilhas ou aplicativos financeiros complexos.

---

## Stack Tecnológica

- Frontend: React + TypeScript
- Backend: Supabase
- Banco de Dados: PostgreSQL (Supabase)
- Autenticação: Supabase Auth
- IA: OpenAI GPT-4o ou equivalente
- Gráficos: Recharts
- Hospedagem: Vercel

---

## Design System

### Estilo Visual

- Moderno e minimalista
- Mobile-first
- Interface limpa e intuitiva
- Pouca carga cognitiva
- Priorizar a conversa acima de formulários
- Feedback visual imediato para todas as ações

### Paleta

- Verde como cor principal (confiança financeira)
- Tons neutros para superfícies
- Destaques para insights e alertas
- Visual semelhante a produtos SaaS modernos

---

# Telas Principais

## 1. Onboarding

### Objetivo

Apresentar o produto e criar o perfil inicial do usuário.

### Campos

- Nome
- Objetivo financeiro principal
- Faixa de renda (opcional)

### Fluxo

1. Boas-vindas
2. Explicação rápida do produto
3. Coleta de dados iniciais
4. Redirecionamento para o Chat Principal

---

## 2. Tela Principal (Chat)

### Esta é a funcionalidade central da aplicação.

### Componentes

- Histórico da conversa
- Campo de mensagem
- Sugestões rápidas
- Cards de resumo financeiro
- Respostas do Agente Financeiro

### Exemplos de Entrada

- "Gastei R$ 45 no mercado"
- "Recebi R$ 3.000 de salário"
- "Paguei R$ 120 de internet"
- "Quero guardar R$ 5.000 para viajar"
- "Quanto gastei este mês?"

### A IA deve ser capaz de

- Extrair valor monetário
- Identificar categoria
- Identificar data
- Identificar descrição
- Detectar receita ou despesa
- Registrar automaticamente
- Confirmar o registro

### Exemplo de Resposta

✅ Despesa registrada!

Categoria: Alimentação  
Valor: R$ 45,00  
Descrição: Mercado  
Data: Hoje

---

## 3. Dashboard Financeiro

### Exibir

#### Cards

- Saldo Atual
- Receitas do Mês
- Despesas do Mês
- Economia Acumulada

#### Gráficos

- Gastos por Categoria
- Evolução Mensal
- Receitas vs Despesas
- Progresso das Metas

#### Seção de Insights

Exemplos:

- Você gastou 15% mais com alimentação este mês.
- Transporte representa sua maior 
```
Interações com o Lovable
> Envio do {PRD}

> Sim, siga com o dashboard e implemente primeiro os gráficos de gastos por categoria e por mês. (Quer que eu siga para o dashboard com os gráficos? Lembre de apagar a conta de teste "Martha Silva" em Users antes de publicar.)

> Onde eu consulto minhas metas e o extrato? Inclua a possibilidade de alterar as informações diretamente, além do chat

Resultado final no Lovable: https://firstflight-growth-dashboard.lovable.app/

<img width="1108" height="865" alt="image" src="https://github.com/user-attachments/assets/8319ffcd-86e0-4173-ac14-c495f7020444" />

<img width="685" height="841" alt="image" src="https://github.com/user-attachments/assets/76d36d06-f5c1-40a4-b56e-faa6b103b6ac" />

# Resumo do Aplicativo

O **Agente Financeiro** é um aplicativo de finanças pessoais que utiliza inteligência artificial conversacional para simplificar o controle financeiro. Em vez de preencher formulários ou planilhas, o usuário registra receitas, despesas e metas por meio de mensagens em linguagem natural.

Por exemplo, ao digitar *"Gastei R$ 45 no mercado"* ou *"Recebi R$ 3.000 de salário"*, o sistema identifica automaticamente o valor, a categoria e o tipo da transação, registrando as informações de forma organizada.

O aplicativo também permite visualizar saldo, receitas, despesas, extrato financeiro e acompanhar metas de economia em tempo real. Seu principal objetivo é tornar a gestão financeira mais simples, acessível e intuitiva para pessoas que desejam organizar melhor suas finanças.

# Reflexão sobre o Processo

## O que funcionou bem?

O desenvolvimento utilizando o Lovable permitiu criar rapidamente um protótipo funcional a partir de um PRD detalhado. As principais funcionalidades planejadas foram implementadas, incluindo a landing page, o chat conversacional, o registro de transações por linguagem natural e o gerenciamento de metas financeiras.

Também funcionou muito bem a capacidade da IA de transformar requisitos de negócio em interfaces visuais e fluxos funcionais, acelerando significativamente a criação do MVP.

## O que não funcionou como o esperado?


Embora o Lovable tenha acelerado bastante a construção do MVP, algumas limitações surgiram durante o desenvolvimento. Em vários momentos foi necessário refinar os prompts para que a IA compreendesse exatamente o comportamento esperado da aplicação, principalmente em funcionalidades que envolviam regras de negócio mais específicas.

Outro desafio foi a limitação de créditos da plataforma. Como cada ajuste, correção ou refinamento consumia créditos, foi necessário planejar melhor as solicitações e evitar tentativas excessivas. Isso reforçou a importância de elaborar prompts mais completos e detalhados desde o início, reduzindo retrabalho e otimizando o uso dos recursos disponíveis.

Também foi possível perceber que algumas funcionalidades foram geradas inicialmente com foco na interface visual, exigindo iterações adicionais para aproximá-las da lógica de negócio definida no PRD.

## O que aprendi sobre conversar com IAs?

Aprendi que a qualidade dos resultados depende diretamente da clareza e do nível de detalhamento das instruções fornecidas. Quanto mais contexto, requisitos e exemplos forem apresentados, melhores tendem a ser as respostas e implementações geradas pela IA.

Também percebi que o processo é iterativo: os melhores resultados surgem a partir de refinamentos sucessivos, ajustando prompts e requisitos conforme o projeto evolui.

Por fim, entendi que a IA pode ser uma poderosa parceira para prototipação e desenvolvimento de produtos digitais, acelerando a transformação de ideias em aplicações funcionais, desde que exista uma boa definição dos objetivos e uma validação contínua dos resultados.
