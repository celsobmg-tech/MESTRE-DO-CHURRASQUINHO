# Skills do Superpowers

Estas skills foram copiadas de [obra/superpowers](https://github.com/obra/superpowers)
(licença MIT, © Jesse Vincent — veja `LICENSE-superpowers`), commit
`2ce8aa15d05bd57213e6f746f953aafb7ded7a8b`.

O Claude Code carrega automaticamente as skills em `.claude/skills/` quando
trabalha neste repositório.

## Skills incluídas

| Skill | Para que serve |
|-------|----------------|
| `using-superpowers` | Ensina o agente a procurar e usar as skills antes de agir |
| `brainstorming` | Refina a ideia com perguntas antes de escrever código |
| `writing-plans` | Escreve um plano de implementação detalhado |
| `executing-plans` | Executa um plano em etapas, com pontos de verificação |
| `subagent-driven-development` | Executa o plano com subagentes e revisão entre tarefas |
| `dispatching-parallel-agents` | Distribui trabalho independente entre agentes em paralelo |
| `test-driven-development` | Ciclo TDD: teste falhando → código → refatoração |
| `systematic-debugging` | Depuração em fases, buscando a causa raiz |
| `verification-before-completion` | Confirma que funciona antes de dizer que terminou |
| `requesting-code-review` / `receiving-code-review` | Pedir e responder revisões de código |
| `using-git-worktrees` | Trabalho isolado em worktrees do git |
| `finishing-a-development-branch` | Fechar a branch: merge, PR ou descarte |
| `writing-skills` | Criar novas skills |
| `diagnosing-superpowers` | Diagnosticar problemas no uso das skills |

## Atualizar

```bash
git clone --depth 1 https://github.com/obra/superpowers.git /tmp/superpowers
rm -rf .claude/skills/*/ && cp -r /tmp/superpowers/skills/* .claude/skills/
```
