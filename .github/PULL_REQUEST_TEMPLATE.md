## Contexto e objetivo
Issue/tarefa: <!-- link ou ID -->

## Alteração
<!-- O que mudou e por quê -->

## Risco e impacto
- [ ] R0 documentação / baixo risco
- [ ] R1 código normal
- [ ] R2 segurança, estoque, financeiro, contrato ou migrations
- [ ] R3 acesso, produção, segredos ou dados reais

## Evidências
| Verificação | Comando | Resultado | Link/arquivo |
|---|---|---|---|
| Local |  | NÃO EXECUTADO |  |
| CI |  | NÃO EXECUTADO |  |

## Segurança e rollout
- [ ] Não introduz credenciais nem amplia permissões.
- [ ] Inclui testes para o risco apresentado.
- [ ] Rollback descrito quando relevante.
- [ ] Mudança sensível revisada por responsável distinto do autor, se exigida.

## Modo de entrega
- [ ] Rotina: branch de tarefa → `main`
- [ ] Iniciativa composta: único Draft PR `integration/*` → `main`, atualizado pelo coordenador até Ready for review
- [ ] Stacked PR opcional: revisão por camada dependente (documentar stack/trunk e predecessora)

Se iniciativa composta, preencher e atualizar **neste mesmo Draft PR**; ao marcar Ready, disparar full CI:
- Branch agregadora, Issue principal e SHA-base:
- Agentes e branches integradas (Issue → branch → SHA de origem → SHA de merge):
- Resoluções de conflitos / contratos / migrations:
- SHA validado após atualização com `main`:
- Full test do conjunto (comando, resultado e URL da CI):
- Plano de rollback do conjunto: