# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
# 📱 Plano de MVP – App de Finanças Pessoais Conversacional

## 🎯 Objetivo
Criar um aplicativo que ajude iniciantes a organizar suas finanças de forma simples, por meio de **conversas naturais**, com foco em **metas claras** e **simulação de crédito**.

---

## 🖼️ Principais Telas

| Tela | Descrição | Elementos-Chave |
|------|-----------|-----------------|
| **Tela de Boas-Vindas** | Apresenta o app e explica como funciona | Logo, mensagem amigável, botão "Começar Conversa" |
| **Chat Financeiro** | Onde o usuário interage com o “Agente Financeiro” | Caixa de diálogo, sugestões rápidas (“Registrar gasto”, “Definir meta”) |
| **Metas Financeiras** | Área dedicada para criar e acompanhar objetivos | Barra de progresso, metas visuais (ex: “Economizar R$ 500 até junho”) |
| **Relatórios Simples** | Visualização clara dos gastos e ganhos | Gráficos de pizza (categorias), linha do tempo de despesas |
| **Simulador de Financiamento/Empréstimos** | Ferramenta para calcular parcelas e juros | Campos: valor, prazo, taxa de juros; resultado com tabela de amortização |
| **Dicas de Economia** | Recomendações personalizadas | Cards com sugestões práticas (ex: “Reduza gastos com delivery”) |

---

## ⚙️ Recursos Necessários

- **Processamento de linguagem natural (NLP):** para interpretar mensagens do usuário (“gastei 50 reais no mercado”).
- **Classificação automática de transações:** categorização em alimentação, transporte, lazer etc.
- **Banco de dados leve (SQLite ou Firebase):** para armazenar gastos, metas e relatórios.
- **Gráficos interativos:** bibliotecas como Chart.js ou Recharts.
- **Módulo de simulação financeira:** cálculo de juros compostos e parcelas (ex: fórmula de financiamento Price).
- **Agente Financeiro:** chatbot que responde com dicas e orientações.

---

## 🏗️ Estrutura de Funcionalidades

1. **Registrar gastos via chat**  
   - Usuário digita: “gastei R$ 30 em transporte”  
   - App interpreta e salva automaticamente.

2. **Classificação automática**  
   - Algoritmo simples de palavras-chave (ex: “mercado” → alimentação).

3. **Metas financeiras visíveis**  
   - Exemplo: “Juntar R$ 1000 para viagem”  
   - Barra de progresso + notificações motivacionais.

4. **Relatórios personalizados**  
   - Gráfico de pizza para categorias.  
   - Linha do tempo para evolução dos gastos.

5. **Simulador de financiamento/empréstimos**  
   - Usuário informa valor, taxa e prazo.  
   - App calcula parcelas e mostra tabela de amortização.

6. **Dicas de economia**  
   - Baseadas nos gastos do usuário.  
   - Exemplo: “Você gastou muito em delivery este mês, que tal cozinhar mais em casa?”

---

## ✅ Esboço de Validação Inicial

- **Teste com 5 a 10 usuários iniciantes**  
  - Observar se conseguem registrar gastos sem dificuldade.  
  - Ver se entendem as metas e relatórios sem precisar de explicação.  
  - Avaliar se o simulador ajuda na tomada de decisão.

- **Métricas de sucesso**  
  - % de usuários que registram mais de 5 gastos na primeira semana.  
  - % que criam pelo menos uma meta.  
  - Feedback positivo sobre clareza dos relatórios.

---

## 📌 Diferenciais para não ser “copia e cola”

- Metas **visuais e motivacionais** (gamificação leve).  
- Simulador de crédito integrado (poucos apps iniciantes oferecem isso).  
- Conversa natural em vez de formulários.  
- Relatórios simples, sem excesso de gráficos complexos.  

---

## 📂 Estrutura do Repositório (Sugestão)


```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:


- Seu **prompt final** (PRD);  <img width="907" height="563" alt="Finny App" src="https://github.com/user-attachments/assets/9805ffd7-f1b1-4f54-a66c-e5847437c10d" />

- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
