# Desafio Criativo: Planejando Automações com N8N

## Passo 1 — Definição da automação

```
Quero criar uma automação no N8N para responder automaticamente mensagens de clientes no Telegram usando IA.

Público ou responsável:
Atendimento ao cliente de um negócio.

Resultado esperado:
O cliente envia uma mensagem no Telegram e recebe uma resposta automática e inteligente (gerada por IA), sem precisar de um atendente humano imediatamente.
```

## Passo 2 — Contexto e regras

```
Ferramentas envolvidas:
Telegram (Bot API) e OpenAI (GPT).

Fluxo desejado:
1. Receber uma nova mensagem do cliente no Telegram.
2. Verificar se a mensagem contém palavras-chave como "falar com humano" ou "atendente".
3. Se contiver, encaminhar a conversa para um atendente humano (ex: notificar em outro canal, como e-mail ou Telegram interno).
4. Se não contiver, enviar o texto da mensagem para a OpenAI (GPT) gerar uma resposta.
5. Enviar a resposta gerada de volta ao cliente no Telegram.

Regras importantes:
- Se a mensagem contiver palavras-chave de escalonamento ("falar com humano", "atendente"), pular a IA e encaminhar direto para atendimento humano.
- Ignorar mensagens vazias.
- Não é necessário registrar as conversas em planilha ou banco de dados.
```

## Passo 3 — Prompt Final

```
Atue como um especialista em N8N.

Crie uma automação para responder automaticamente mensagens de clientes no Telegram usando IA.

Público:
Atendimento ao cliente de um negócio.

Ferramentas envolvidas:
Telegram (Bot API) e OpenAI (GPT).

Fluxo:
1. Receber uma nova mensagem do cliente no Telegram.
2. Verificar se a mensagem contém palavras-chave como "falar com humano" ou "atendente".
3. Se contiver, encaminhar a conversa para um atendente humano.
4. Se não contiver, enviar o texto da mensagem para a OpenAI (GPT) gerar uma resposta.
5. Enviar a resposta gerada de volta ao cliente no Telegram.

Regras:
- Mensagens com palavras-chave de escalonamento ("falar com humano", "atendente") pulam a IA e vão direto para atendimento humano.
- Ignorar mensagens vazias.
- Não é necessário registrar as conversas em planilha ou banco de dados.


```
