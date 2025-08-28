# Registromobile
# EcoPlanner – Protótipo de Página de Tarefas

## Design Adaptativo
- Usei **media queries** para ajustar a visualização em telas pequenas (mobile) e maiores (tablet/desktop).
- No mobile, os painéis ficam empilhados.
- A partir de 600px, os painéis ficam lado a lado.

## Acessibilidade
- Adicionei **skip link** para pular direto ao conteúdo.
- Campos de formulário possuem **label** associados.
- Botões têm foco visível.
- Estrutura semântica com `header`, `main`, `section`, `footer`.

## Auditoria de Acessibilidade
- Simulado via Lighthouse: contraste e navegação por teclado estão adequados.
- Problema encontrado: botão "Remover" pode ser pequeno no mobile → foi garantido tamanho mínimo (44px).

## Teste de Usabilidade
- Usuário convidado testou a adição e remoção de uma tarefa.
- Conseguiu adicionar facilmente, mas no início não percebeu o campo de prioridade.
- Mostra a importância de destacar opções visuais.
