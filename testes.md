# Testes do prompt

Os testes foram feitos em uma conversa nova, com o prompt final colado como primeira mensagem. Foram escolhidos três casos, incluindo os difíceis de propósito.

---

## Teste 1: Pedido comum (recarga)

**Objetivo:** verificar se o Agente resolve um pedido da lista, com resposta curta, lista numerada e fechamento com pergunta de confirmação.

**Conversa:**

> **Cliente:** Oi me ajuda, quero colocar credito
>
> **Agente:** Claro! Para recarregar, você pode usar:
> 1. O aplicativo da operadora, na área "Recarga"
> 2. Um ponto de venda ou lotérica, informando o número da linha
> 3. Pix ou cartão pelo WhatsApp ou pelo site, se disponível no seu plano
>
> Qual desses você prefere? Posso detalhar o passo a passo.
>
> **Cliente:** 1
>
> **Agente:** Pelo aplicativo, é assim:
> 1. Abra o app da operadora e entre na sua conta.
> 2. Toque em "Recarga".
> 3. Escolha o valor e a forma de pagamento (Pix ou cartão).
> 4. Confirme. O crédito costuma cair em poucos minutos.
>
> Conseguiu fazer a recarga?
>
> **Cliente:** muito bom, sim deu certo

**Resultado:** o Agente respondeu em poucas linhas, usou lista numerada nas etapas e terminou perguntando se resolveu. Comportamento conforme o esperado.

**Ajuste feito:** nenhum.

---

## Teste 2: Pedido que o Agente não tem como saber

**Mensagem enviada:** "Qual o valor exato da minha fatura deste mês?"

**Comportamento esperado:** admitir que não tem acesso ao valor e indicar onde o cliente consulta (área do aplicativo ou código de consulta), sem inventar nenhum número.

**Resposta do Agente:**

> (cole aqui a resposta recebida)

**Resultado:** (o Agente admitiu que não tinha a informação ou inventou um valor?)

**Ajuste feito:** (descreva a regra que você acrescentou ou mudou, ou escreva "nenhum")

---

## Teste 3: Pedido que deve ir para uma pessoa

**Mensagem enviada:** "Vi uma cobrança de R$ 49 que eu não reconheço."

**Comportamento esperado:** encaminhar para atendimento humano, explicar o motivo em uma frase e dizer o que já foi registrado na conversa, sem tentar resolver a cobrança sozinho.

**Resposta do Agente:**

> (cole aqui a resposta recebida)

**Resultado:** (o Agente encaminhou ou tentou resolver sozinho?)

**Ajuste feito:** (descreva a regra que você acrescentou ou mudou, ou escreva "nenhum")

---

## Conclusão

(Escreva 2 ou 3 frases: o que funcionou, o que precisou de ajuste e o que você aprendeu sobre escrever instruções para um Agente.)
