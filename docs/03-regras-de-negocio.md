```markdown

# Regras de Negócio

## Estoque
- RN01: Estoque não pode ficar com quantidade negativa
- RN02: Qualquer modificação manual de estoque requer aprovação do Gerente
- RN03: Entrada de estoque criada pelo Operador fica com status pendente até aprovação

## Venda
- RN04: Venda não pode ser finalizada com produto sem estoque suficiente
- RN05: Produto inativo não aparece para venda
- RN06: Sistema aceita valores decimais para peso (gramas) e preço (centavos)
- RN07: Sistema aceita múltiplas formas de pagamento
- RN08: Apenas Gerente ou Admin pode cancelar uma venda
- RN09: Ao finalizar a venda o estoque é atualizado automaticamente

## Usuários
- RN10: Apenas Admin pode criar, editar ou desativar usuários
- RN11: Usuários não são deletados, apenas desativados
- RN12: Usuário desativado não consegue fazer login
- RN13: Operador não acessa relatórios nem logs
- RN14: Apenas Admin acessa logs do sistema

## Produtos
- RN15: Apenas Admin e Gerente podem criar, editar ou excluir produtos
- RN16: Perda de produto registrada pelo Operador fica com status pendente
- RN17: Gerente aprova ou rejeita a perda registrada pelo Operador
```
