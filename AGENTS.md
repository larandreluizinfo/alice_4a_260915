# AGENTS — Regras do Repositório

## Regra obrigatória: commit + push a cada alteração

Toda alteração feita neste repositório (código, docs, config) DEVE ser commitada e pushada para `origin/main` ao final da tarefa.

Fluxo obrigatório:
1. `git status` para conferir o que mudou
2. `git add` apenas dos arquivos intencionais (nunca commitar segredos)
3. `git commit -m "<tipo>: <descrição curta>"` (ex: `feat: ...`, `fix: ...`, `chore: ...`, `docs: ...`)
4. `git push origin main` (ou `git push` com upstream configurado)
5. Confirmar com `git status` limpo e log do push

Não finalizar nenhuma tarefa sem commit + push. Se o push falhar, corrigir (pull/rebase se preciso) e tentar de novo até o remoto estar atualizado.
