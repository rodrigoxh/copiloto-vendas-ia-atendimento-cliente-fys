# Copiloto de Vendas com IA: Inspiração FYS

> Um repo pequeno para uma ideia grande: usar uma live como base de conhecimento para criar soluções de IA aplicadas a vendas. Sem complicar. Sem reunião de 3 horas que podia ser um prompt.

Este repositório é um apoio para o Desafio de Projeto Final **Copiloto de Vendas com IA para Atendimento ao Cliente**.

A ideia aqui **não é entregar uma solução pronta** e nem dizer que todo mundo precisa fazer o mesmo projeto. A proposta é usar a **FYS**, marca de refrigerantes do grupo **HEINEKEN**, como inspiração para criar soluções diferentes a partir de um contexto real apresentado em live.

A FYS tem uma comunicação mais leve, bem-humorada e um pouco ácida. Ela não tenta parecer perfeita, não força pose de marca número 1 e brinca com a própria posição no mercado. Esse tom pode inspirar soluções mais criativas, humanas e menos robóticas.

---

## A Sacada do Projeto

Normalmente, uma IA responde melhor quando tem contexto.

Neste repo, o contexto vem de uma live:

- Pessoas da FYS explicaram a marca;
- Apresentaram desafios reais de vendas;
- Comentaram sobre canais, consumidores e pontos de venda;
- Trouxeram o tom de voz da marca;
- E, de quebra, deram várias ideias que podem virar projeto.

A transcrição dessa live está em:

```text
knowledge/transcricao-live-fys.txt
```

Ou seja: a live virou uma **base de conhecimento**.

E a partir dela você pode criar um chatbot, copiloto, agente, simulador, análise simples, gerador de mensagens ou qualquer outra solução com IA voltada a vendas e atendimento.

---

## Live de Referência

Assista à live aqui:

https://web.dio.me/lives/fys-por-dentro-da-marca-desafios-e-ideias-para-o-projeto-final?back=/track/heineken-inteligencia-artificial-aplicada-vendas

Ela é a principal fonte de contexto deste repositório.

---

## Escolha Seu Desafio

A FYS trouxe vários desafios interessantes. Você não precisa resolver todos. Escolha um recorte simples e faça bem feito.

### 1. Quem é FYS mesmo?

Muita gente ainda não conhece a marca ou não sabe que ela faz parte do grupo **HEINEKEN**.

Ideias de projeto:

- Chatbot que apresenta a marca de forma simples;
- Agente que responde dúvidas sobre FYS;
- Gerador de mensagens para explicar a marca sem parecer propaganda chata.

---

### 2. Me dá uma chance aí

A marca quer que mais pessoas experimentem o produto. Não precisa convencer o mundo inteiro. Começa pelo primeiro gole.

Ideias de projeto:

- Copiloto que sugere argumentos para incentivar experimentação;
- Simulador de abordagem para oferecer FYS em uma padaria;
- Gerador de campanhas simples para degustação ou primeira compra.

---

### 3. Cadê a FYS na padaria?

Padarias são um canal importante, mas nem sempre recebem atenção da força de vendas tradicional.

Ideias de projeto:

- Agente para priorizar padarias com maior potencial;
- Checklist inteligente para avaliar um ponto de venda;
- Copiloto que sugere próximos passos para ativar uma padaria.

---

### 4. O vendedor não tem oito braços

A força de vendas precisa priorizar onde atuar. A IA pode ajudar a organizar oportunidades e sugerir abordagens.

Ideias de projeto:

- Copiloto para preparar argumentos de venda;
- Gerador de mensagens para WhatsApp comercial;
- Agente que sugere abordagem com base no perfil do cliente.

---

### 5. Visibilidade: porque produto escondido não performa milagre

Se o consumidor não vê, não lembra. Se não lembra, não pede. Simples assim.

Ideias de projeto:

- IA que sugere ações de visibilidade no ponto de venda;
- Checklist de exposição para balcão, geladeira ou cardápio;
- Gerador de ideias de ativação com baixo custo.

---

### 6. Objeções de balcão

Toda venda tem resistência: preço, marca desconhecida, hábito do cliente, espaço na geladeira, giro do produto.

Ideias de projeto:

- Agente que responde objeções comuns;
- Simulador de conversa entre vendedor e dono de padaria;
- Base de perguntas e respostas para treinamento comercial.

---

### 7. O tom FYS sem virar tiozão do pavê

A FYS usa humor, leveza e autoironia. Mas existe uma linha entre ser divertido e ser forçado.

Ideias de projeto:

- Assistente para revisar mensagens no tom da marca;
- Gerador de respostas comerciais com humor leve;
- Comparador entre mensagem formal, informal e “modo FYS”.

---

### 8. Dados públicos também jogam

Além da transcrição da live, você pode usar dados públicos sobre regiões, comércios, consumo ou comportamento do público.

Ideias de projeto:

- Análise simples para priorizar bairros ou regiões;
- Ranking de oportunidades por tipo de ponto de venda;
- Agente que combina contexto da live com dados públicos.

---

## Como Usar o DIO Agent

Você pode usar o **DIO Agent** como apoio para pensar, organizar e revisar seu projeto final:

https://github.com/digitalinnovationone/dio-agent

Neste repo:

- O `README.md` explica o contexto;
- O `AGENTS.md` orienta o comportamento do agente;
- O `CLAUDE.md` funciona como alias para o `AGENTS.md`;
- A pasta `knowledge/` guarda a transcrição da live.

### Prompt Para Começar

Copie e cole este prompt no DIO Agent:

```text
Leia o README deste repositório e a transcrição em knowledge/transcricao-live-fys.txt.

Depois, me ajude a escolher uma ideia simples para o Desafio de Projeto Final "Copiloto de Vendas com IA para Atendimento ao Cliente".

Quero uma solução inspirada nos desafios da FYS, com um tom criativo, simples e fácil de explicar.

Me entregue:
1. Uma ideia de projeto;
2. Qual desafio da FYS ela explora;
3. Quem usaria a solução;
4. Qual problema ela resolve;
5. Como a IA ajudaria;
6. Um exemplo de uso;
7. O que colocar no README da entrega final;
8. Uma versão mais simples da ideia, caso eu queira algo bem básico.
```

---

## Estrutura do Repositório

```text
copiloto-vendas-ia-atendimento-cliente-fys/
├── README.md
├── AGENTS.md
├── CLAUDE.md
└── knowledge/
    └── transcricao-live-fys.txt
```

A estrutura é mínima de propósito. A ideia é focar no projeto, não em criar pasta para guardar pasta.

---

## O Que Entregar no Projeto Final

No seu próprio repositório, explique:

- Qual desafio você escolheu;
- Quem usaria sua solução;
- Qual problema ela resolve;
- Como a IA ajuda;
- Qual base de conhecimento foi usada;
- Um exemplo de conversa, resposta ou análise;
- Possíveis melhorias futuras.

Você não precisa criar uma aplicação completa. Pode entregar um protótipo, prompt, agente, simulação ou documentação bem organizada.

O importante é mostrar que você entendeu o problema e usou IA para propor algo útil.

Bons estudos e bora tirar a FYS do modo “quem?” para o modo “ah, essa eu conheço” 🚀
