# 🤖 Treinador de Balcão FYS - Copiloto de Vendas com IA

Este repositório contém a documentação e a estrutura do **Treinador de Balcão FYS**, um simulador de vendas inteligente desenvolvido como entrega para o desafio de projeto "Copiloto de Vendas com IA para Atendimento ao Cliente" da [DIO](https://dio.me).

---

## 🎯 1. Tema Escolhido
O projeto foi desenvolvido em cima do **Desafio 6: Objeções de Balcão**, focado na marca **FYS** (refrigerante do grupo HEINEKEN). A proposta é simular a resistência típica que donos de estabelecimentos comerciais tradicionais (como bares e padarias) apresentam ao serem abordados com uma marca nova de refrigerante.

## 👤 2. Usuário Principal
O usuário principal desta solução é a **força de vendas da HEINEKEN** (vendedores de campo e consultores comerciais), especialmente novos integrantes da equipe ou profissionais que precisam treinar argumentos rápidos e dinâmicos para a ativação de novos pontos de venda (PDV).

## 🛑 3. Problema Resolvido
Inserir um novo refrigerante no mercado é um desafio logístico e comercial. Os comerciantes costumam ser resistentes por três motivos centrais:
- **Medo do estoque encalhar:** Receio de que o consumidor não compre uma marca alternativa aos líderes de mercado.
- **Espaço físico limitado:** Falta de espaço nas geladeiras e prateleiras para novos displays.
- **Giro x Margem:** Dificuldade em entender se vale a pena trocar um produto consolidado por um com maior margem, mas menor conhecimento de marca.

O **Treinador de Balcão FYS** resolve isso oferecendo um ambiente seguro de simulação para o vendedor treinar o contorno dessas objeções antes de ir a campo.

## ⚙️ 4. Abordagem Utilizada
A solução utiliza a abordagem de **Simulador baseado em Engenharia de Prompt (Roleplaying)**. 
Através de um System Prompt altamente detalhado, qualquer LLM (como Gemini ou ChatGPT) assume a persona do **Seu Manuel**, um comerciante tradicional e desconfiado, permitindo uma dinâmica interativa de negociação em tempo real.

## 🧠 5. Base de Conhecimento Utilizada
Como contexto para alimentar a inteligência do simulador, foram utilizadas as informações extraídas da live oficial da FYS:
- **Chancela HEINEKEN:** O fato de a FYS pertencer ao grupo HEINEKEN como principal argumento de credibilidade e logística.
- **Fórmula Saudável:** Apelo de mercado focado em saudabilidade (fórmulas com 50% menos açúcar comparado aos concorrentes).
- **Posicionamento Divertido:** O tom autêntico e bem-humorado da marca FYS.
- **Estratégias de Entrada:** Oferta de displays compactos de balcão e lotes de experimentação/degustação.

---

## 💬 6. Exemplo de Conversa Gerada

Abaixo está um exemplo de interação real entre o vendedor (usuário) e o Seu Manuel (IA):

> **Seu Manuel (IA):** "Boa tarde, meu jovem! O que traz você aqui na padaria hoje?"
>
> **Vendedor (Usuário):** "Boa tarde, Seu Manuel! Tudo bem? Sou vendedor do grupo Heineken e trouxe hoje o FYS, nosso refrigerante oficial. Ele tem metade do açúcar dos refrigerantes comuns e vende muito bem!"
>
> **Seu Manuel (IA):** "Olha, meu jovem... FYS? Nunca ouvi falar desse nome. E outra: aqui na padaria o pessoal só quer Coca ou Guaraná. Se eu comprar isso, vai ficar encalhado na prateleira e vou acabar perdendo dinheiro. Não quero arriscar."
>
> **Vendedor (Usuário):** "Eu entendo perfeitamente sua preocupação, Seu Manuel. Mas o FYS é produzido pela própria Heineken, com o mesmo padrão de qualidade e entrega da cerveja que o senhor já vende aqui. Além disso, nós podemos começar com apenas duas caixas de teste e eu trago alguns displays de balcão para chamar a atenção dos clientes."
>
> **Seu Manuel (IA):** "Hum, é da Heineken mesmo? Disso eu não sabia. O display de balcão ajuda, mas a minha geladeira já está cheia. Para colocar essas caixas de FYS, eu teria que tirar produtos que já vendem todo dia. É difícil..."
>
> **Vendedor (Usuário):** "Nós podemos colocar um display compacto que não ocupa espaço na geladeira principal para o teste. Se o senhor aceitar fechar um lote pequeno de teste hoje, eu consigo te enviar uma caixa extra bonificada para o senhor oferecer como degustação gratuita para os seus clientes de almoço experimentarem. O que acha?"
>
> **Seu Manuel (IA):** "Pois pois... Uma caixa de degustação de graça para o povo testar? Aí começou a me interessar. Se o risco é menor, vamos fazer o seguinte: me manda 2 caixas do sabor limão e 2 de guaraná para eu testar nessas duas semanas. Se o povo gostar, a gente conversa sobre colocar na geladeira. Pode ser?"
>
> **Vendedor (Usuário):** "/avaliar"
>
> **Seu Manuel (IA):** *(Saindo do personagem)* 
> **Análise de Desempenho:**
> - **Pontos Fortes:** Muito bom ao usar a chancela da Heineken logo após a primeira objeção e excelente estratégia ao oferecer a bonificação para degustação como redutor de risco.
> - **Pontos a Melhorar:** Poderia ter enfatizado um pouco mais a margem de lucro que o Seu Manuel teria com a FYS em comparação aos líderes.
> - **Nota:** 9/10. Abordagem comercial sólida e contorno de objeções eficiente!

---

## 🚀 7. Melhorias Futuras
Para evoluir o projeto em etapas futuras, sugere-se:
1. **Integração por Voz:** Conectar o simulador a APIs de conversão de voz (como Gemini Live ou WhatsApp Audio) para treinar a oratória e velocidade de resposta do vendedor.
2. **Novos Perfis de Clientes:** Criar variações de prompts para simular outros tipos de clientes (como o comerciante focado estritamente em preço ou o comerciante moderno focado em produtos saudáveis).
3. **Plataforma Web Dedicada:** Criar uma interface web simples utilizando HTML/JS e APIs de modelos de linguagem para rodar o simulador em um portal interno de treinamento da Heineken.
