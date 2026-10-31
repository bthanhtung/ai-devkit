# Third-party skills

These skills are adapted from MIT-licensed community repositories that the AI DevKit
skill registry does not cover yet. Each folder keeps
its original license and source link in `LICENSE.txt`. They are not part of the
built-in set (`built-in.json`); install one with:

```bash
ai-devkit skill add bthanhtung/ai-devkit <skill-name>
```

| Skill | Source | What it does |
| --- | --- | --- |
| `codebase-design` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/codebase-design) | Shared vocabulary for designing deep modules |
| `improve-codebase-architecture` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture) | Find deepening opportunities and report them as HTML |
| `domain-modeling` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/domain-modeling) | Build and sharpen the domain model, glossary, and ADRs |
| `prototype` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/prototype) | Build a throwaway prototype to answer a design question |
| `research` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/engineering/research) | Investigate a question against primary sources and save the findings |
| `git-guardrails-claude-code` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/misc/git-guardrails-claude-code) | Hooks that block destructive git commands in Claude Code |
| `setup-pre-commit` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/misc/setup-pre-commit) | Husky + lint-staged pre-commit hooks with type checks and tests |
| `writing-for-agents` | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/skills/productivity/writing-for-agents) | Write skills, AGENTS.md, and CLAUDE.md that agents follow well |
| `drawio` | [sparklabx/drawio-ai-kit](https://github.com/sparklabx/drawio-ai-kit/tree/main/skills/drawio) | Cloud architecture and BPMN diagrams as .drawio files |

## Already in the AI DevKit registry

Skills from registries that AI DevKit already indexes are not copied here; install them
from the source so they stay up to date. For example, `addyosmani/agent-skills`:

```bash
ai-devkit skill add addyosmani/agent-skills performance-optimization
ai-devkit skill add addyosmani/agent-skills api-and-interface-design
```
