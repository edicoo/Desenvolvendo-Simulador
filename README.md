App Simulador de Entrevista de Tecnologia do Édico Almeida com Vibe Coding.

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Lovable e o Copilot Web. A proposta é criar um Agente de IA baseado, um simulador de processo seletivo para vaga de tecnologia.

PRD definido no Copilot Web:
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
markdown

PRD - Simulador Inteligente de Entrevista com Design Universal

Objetivo do Produto
Criar um simulador de entrevistas em linguagem natural para ajudar candidatos a se prepararem para processos seletivos na área de tecnologia. O sistema atuará como um entrevistador 
técnico especializado, conduzindo perguntas estruturadas e fornecendo um resumo analítico ao final. A solução deve seguir princípios de Design Universal, garantindo que o máximo de 
usuários possa utilizá-la com boa experiência, independentemente de suas habilidades, contextos ou limitações.

Funcionalidades Principais
- Condução de entrevistas simuladas com foco em vagas de tecnologia.
- Estruturação das perguntas em sequência lógica.
- Interação em linguagem natural, com apenas uma pergunta por vez.
- Geração de resumo analítico após confirmação explícita do usuário.
- Interface inclusiva e acessível, com linguagem clara e suporte a diferentes perfis de usuários.

Fluxo da Entrevista
1. Título da vaga: Perguntar "Qual é o título da vaga e qual o propósito principal desse cargo?"
2. Senioridade: Perguntar "Qual a senioridade esperada e por quê?"
3. Stack Tecnológico: Perguntar "Quais tecnologias, frameworks e práticas são essenciais?"
4. Soft Skills: Perguntar "Quais comportamentos ou atitudes são mais valorizados?"

Após todas as respostas, o sistema aguarda confirmação do usuário para gerar o resumo analítico.

Regras de Interação
- Nunca fazer mais de uma pergunta por vez.
- Só gerar o resumo após confirmação explícita.
- Iniciar sempre com: "Olá! Vou fazer perguntas sobre a vaga que você está estruturando. Para começar: qual é o título da vaga principal desse cargo?"
- Garantir que a interação seja acessível e compreensível para diferentes perfis de usuários.

---

Conceitos Explicados

O que é um PRD (Product Requirements Document)?
Um PRD é um documento que descreve os requisitos de um produto. Ele serve como guia para alinhar equipes sobre o que será construído, por que e como. Normalmente inclui:
- Objetivo do produto
- Funcionalidades principais
- Fluxo de uso
- Regras e restrições

No seu caso, o PRD organiza como o simulador de entrevista deve funcionar, garantindo clareza e consistência.

O que é Vibe Coding?
Vibe Coding é uma prática de programação e prototipagem rápida que foca em experimentar ideias de forma leve e iterativa, sem se prender a formalismos excessivos. A ideia é "sentir a vibe" do 
problema e testar soluções de maneira prática, criativa e interativa. É útil para:
- Explorar conceitos rapidamente
- Criar protótipos sem burocracia
- Aprender pela prática

No contexto do simulador, o Vibe Coding ajuda você a experimentar diferentes formas de conduzir entrevistas simuladas, ajustando o fluxo conforme a experiência do usuário.

O que é Design Universal?
Design Universal é um conceito de design que busca criar produtos, serviços e ambientes que possam ser utilizados pelo maior número possível de pessoas, sem necessidade de adaptações 
específicas. Os princípios incluem:
- Equidade: oferecer a mesma experiência para todos.
- Flexibilidade: permitir diferentes formas de uso.
- Simplicidade: tornar a interface clara e intuitiva.
- Perceptibilidade: garantir que informações sejam compreensíveis por diferentes meios (visual, auditivo, textual).
- Tolerância ao erro: reduzir riscos e consequências de ações incorretas.
- Baixo esforço físico e cognitivo: facilitar o uso sem exigir muito esforço.

Aplicar Design Universal ao simulador significa garantir que candidatos com diferentes perfis — iniciantes ou experientes, com ou sem limitações — possam ter uma boa experiência de preparação para entrevistas.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Interações com Lovable:
- Crie um agente de ia Simulador de Entrevista especializado em processo seletivo para vaga de tecnologia com base no seguinte PRD (Product Requirements Document)

- Após o resumo analítico das perguntas respondidas, permite que o sistema continue fazendo entrevistas mais profundas de acordo com o tema já discutido.

- Atualizar e permitir que as perguntas sejam feitas após o quadro de resumo analítico da entrevista.

- Após clicar no botão de aprofundar entrevista mantenha o quadro de feddback analitico no chat


Resultado final no Lovable: https://id-preview--1738705d-2e7e-4b23-8969-d915f8467a96.lovable.app/








## Funcionalidades do Agente Simulador Inteligente de Entrevista


## Objetivo
O simulador ajuda candidatos a se prepararem para entrevistas de tecnologia por meio de uma experiência guiada, acessível e inclusiva.

## Funcionalidades

### Entrevista Guiada
- Perguntas estruturadas sobre a vaga que está sendo criada.
- Fluxo de perguntas em ordem lógica:
  1. Título da vaga e propósito principal.
  2. Senioridade esperada e justificativa.
  3. Tecnologias, frameworks e práticas essenciais.
  4. Soft skills mais valorizadas.
- Regra: apenas uma pergunta por vez.

### Resumo Analítico
- Após todas as respostas e confirmação explícita do usuário, gera um resumo organizado.
- O resumo sintetiza os pontos principais da vaga, facilitando análise e preparação.

### Design Universal
- Interface inclusiva e acessível para diferentes perfis de usuários.
- Princípios aplicados:
  - Equidade: mesma experiência para todos.
  - Flexibilidade: diferentes formas de interação.
  - Simplicidade: linguagem clara e intuitiva.
  - Perceptibilidade: informações acessíveis em múltiplos formatos.
  - Tolerância ao erro: reduz riscos de uso incorreto.
  - Baixo esforço físico e cognitivo: uso fácil e confortável.

### Privacidade Local
- Nenhum dado é armazenado.
- Toda a sessão acontece de forma totalmente local.

## Fluxo Inicial
O simulador sempre inicia com a mensagem:
> "Olá! Vou fazer perguntas sobre a vaga que você está estruturando. Para começar: qual é o título da vaga principal deste cargo?"


Reflexão

O que funcionou bem?  
A clareza do PRD revisado e estruturado em Markdown ajudou a organizar o simulador de forma prática e compreensível.

O que não funcionou como o esperado?  
Alguns pontos exigiram ajustes de linguagem e formato para ficarem consistentes e fáceis de copiar, como o snippet em txt.

O que aprendi sobre conversar com IAs?  
Aprendi que a IA pode estruturar ideias de forma didática, mas precisa de instruções claras e detalhadas para alinhar ao objetivo.

