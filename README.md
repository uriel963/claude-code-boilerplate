# Claude Code Boilerplate

Universal coding standards and AI agent configurations for Claude Code projects.

## What is Included

- **CLAUDE.md** - Universal coding standards template
- **.claude/agents/** - AI agent configurations

## Quick Start

1. Copy CLAUDE.md to your project root
2. Copy .claude/agents/ to your project
3. Fill in the placeholder values in CLAUDE.md

## Features

### Multi-Language Support

- TypeScript/JavaScript (React, Hono, Elysia, Drizzle)
- Python (FastAPI, SQLAlchemy, pytest)
- Go (Gin, GORM, go test)
- Rust (Axum, SeaORM, cargo test)

### AI Agent Workflow

1. Codebase Exploration (mandatory before implementation)
2. Task Planning with small, atomic tasks
3. Priority System (P0 security alerts first)
4. Quality Gates that cannot be skipped
5. Multi-round Code Reviews (minimum 3)

### Agents Included

| Agent | Purpose |
|-------|---------|
| fullstack-developer | Implements features |
| principal-engineer | Code review and investigation |
| qa-engineer | Testing and coverage |
| business-analyst | Requirements analysis |
| solution-architect | Architecture design |
| uiux-designer | UI/UX review |

## License

MIT License
