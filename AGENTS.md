# Instruções para agentes

Estas regras se aplicam a todo o repositório.

## Antes de alterar

- Leia o README e a documentação próxima do código que será alterado.
- Preserve mudanças existentes que não fazem parte da tarefa.
- Nunca registre senhas, tokens, chaves, arquivos `.env` ou outros segredos.
- Confirme o estado atual antes de modificar e mantenha a mudança limitada ao objetivo solicitado.

## Antes de criar um commit

Revise as diferenças do Git e execute as verificações adequadas ao projeto.

A mensagem do commit deve permitir que outro agente entenda a mudança sem depender da conversa em que ela foi produzida.

Use este formato:

```text
<tipo>(<escopo>): resumo curto

Motivo:
Por que a alteração foi necessária.

Alterações:
O que foi alterado.

Validação:
Quais testes, comandos ou verificações foram executados e seus resultados.

Pendências:
O que ainda falta. Escreva "Nenhuma" quando não houver.
```

O Git já registra a versão exata, o autor, a data e as diferenças. Não crie outro arquivo em cada commit apenas para repetir esse histórico.

## Documentação

- Atualize o README quando a finalidade, instalação, operação ou estado real do projeto mudar.
- Registre limitações e riscos conhecidos de forma explícita.
- Não apresente como concluído ou validado algo que não foi testado.
