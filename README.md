# Desafio Criativo: Prompt de um Agente de Atendimento ao Cliente

Projeto do desafio de criar o prompt que define o comportamento de um Agente de atendimento ao cliente, do que ele resolve sozinho até o que ele nunca deve fazer.

## Cenário escolhido

Agente de atendimento de uma **operadora de telefonia móvel**, atuando no **WhatsApp**, para clientes pessoa física de planos pré-pago e controle.

## O que o Agente faz

- Informa como consultar saldo de dados e data de renovação do plano
- Explica como recarregar ou pagar a fatura
- Orienta o passo a passo para trocar de plano pelo aplicativo
- Orienta o que fazer quando está sem sinal ou sem internet

## Decisões principais do prompt

- **Formato curto:** no máximo 4 linhas por resposta, com lista numerada quando há mais de uma etapa.
- **Sem invenção:** o Agente nunca inventa valor, prazo, promoção ou protocolo. Se não tem a informação, diz isso e indica onde o cliente encontra.
- **Dados sensíveis:** nunca pede senha, código de SMS, CPF completo ou dados de cartão.
- **Encaminhamento para humano:** contestação de cobrança, reembolso, fraude, clonagem de chip, roubo de aparelho, cancelamento, portabilidade e falta de sinal por mais de 48 horas.
- **Pergunta antes de errar:** se faltar informação para responder com segurança, o Agente pergunta antes de responder.

## Arquivos

- [`prompt-final.md`](prompt-final.md): o prompt completo do Agente
- [`testes.md`](testes.md): as três conversas de teste e os ajustes feitos

## Como usar

Cole o conteúdo de `prompt-final.md` como primeira mensagem em uma conversa nova de uma IA (Claude, ChatGPT, Gemini etc.) e converse como se fosse o cliente.

Desenvolvedor: Leanderson Viana 🚀
