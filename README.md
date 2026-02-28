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
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
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

PLANO DE MVP: APLICATIVO DE FINANÇAS POR CHAT

FASE 1: AS PRINCIPAIS TELAS (A JORNADA DO USUÁRIO)

1. A Tela de Chat (O Coração do App)
- Como funciona: Interface estilo WhatsApp. O usuário envia mensagens de texto (ex: "Gastei 45 reais de Uber hoje").
- O que o App faz: O "Agente Financeiro" processa a mensagem, classifica automaticamente e responde confirmando (ex: "Anotado! R$ 45,00 categorizados em Transporte. Faltam R$ 150,00 no seu limite dessa categoria.").

2. Dashboard Simplificado (Visão Geral)
- Como funciona: Tela visual e livre de jargões contábeis.
- O que o App faz: Exibe saldo atual, total gasto no mês e um gráfico simples com as principais categorias de despesas (Alimentação, Moradia, Transporte).

3. Metas e Dicas
- Como funciona: Área para acompanhar objetivos de economia.
- O que o App faz: Mostra barras de progresso visuais (ex: "Reserva de Emergência: 40% concluído") e armazena o histórico de dicas do Agente Financeiro.


FASE 2: RECURSOS NECESSÁRIOS (POR TRÁS DAS CÂMERAS)

- Processamento de Linguagem Natural (PLN): Tecnologia para "ler" o texto e extrair valor, ação e categoria do gasto.
- Motor de Regras Simples: Gatilhos para dicas. Exemplo: se o usuário gastar mais de 80% do limite de "Lazer", o sistema envia uma dica de economia.
- Banco de Dados na Nuvem: Armazenamento seguro de histórico, saldos e metas para sincronização.


FASE 3: ESBOÇO DE VALIDAÇÃO INICIAL (TESTANDO A IDEIA)
Técnica: "Mágico de Oz" (simulação manual de um sistema automatizado).

Passo 1: O Teste do WhatsApp (Semanas 1 e 2). Recrute de 5 a 10 pessoas do público-alvo. Peça para enviarem os gastos para o seu número. Você lê, anota em uma planilha e responde como se fosse o robô.
Passo 2: Análise de Padrões. Observe como as pessoas escrevem, se usam áudio, se esquecem de anotar algo. Isso guiará a construção da IA.
Passo 3: Entrevistas de Feedback. Ao final de duas semanas, pergunte aos usuários sobre a praticidade e a utilidade das dicas.
Passo 4: Ajuste e Construção. Com a ideia validada, inicie o desenvolvimento do app sabendo exatamente o que o usuário quer.
> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
