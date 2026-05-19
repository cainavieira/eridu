```markdown
# Como contribuir com o ERIDU

## Padrão de commits (Conventional Commits)

Este projeto usa [Conventional Commits](https://www.conventionalcommits.org).

O template de mensagem está em [.github/.gitmessage](.github/.gitmessage).

> Para configurar localmente:

git config --local commit.template .github/.gitmessage


## Branches

- `main` → produção, nunca commit direto
- `develop` → branch principal de desenvolvimento
- `seu-nome/feat-nome` → novas funcionalidades
- `seu-nome/fix-nome` → correções de bug
- `seu-nome/refactor-nome` → refatorações
- `seu-nome/docs-nome` → documentação

Sempre trabalhe em branches e delete após o merge. Nunca commite diretamente em `develop` ou `main`.

> Exemplo
- caina/feat-tela-login
- caina/fix-estoque-negativo
- caina/docs-endpoints

## Fluxo de trabalho
1. Cria branch a partir de `develop`
2. Desenvolve com commits pequenos e descritivos
3. Abre PR para `develop`
4. PR precisa passar em pipeline de CI/CD
5. Revisão e merge

## Definition of Done
Uma tarefa está concluída quando:
- Código escrito, revisado e funcionando
- PR aprovado e mergeado em develop
- Issue fechada
```