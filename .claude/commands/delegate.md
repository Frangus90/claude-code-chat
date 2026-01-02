---
description: Smart task execution using best-fit subagents
---

# Delegate - Smart Task Execution

Execute the given task (or current ToDo list if none specified) using the most appropriate subagent(s).

## Behavior

- **If arguments provided**: Execute that specific task
- **If no arguments**: Execute pending items from current ToDo list
- **Always**: Select best-fit subagent(s) and parallelize when possible

## Agent Selection

- **csharp-developer**: C#/.NET code
- **python-pro**: Python code
- **sql-pro**: Database/SQL
- **agent-organizer**: Complex multi-step orchestration
- **Explore**: Codebase research, finding files
- **general-purpose**: Everything else
- **electron-pro**: Desktop application expert
- **react-specialist**: React 18+ modern patterns expert
- **rust-engineer**: Systems programming expert
- **database-administrator**: Database management expert
- **code-reviewer**: Code quality guardian
- **performance-engineer**: Performance optimization expert
- **api-documenter**: API documentation specialist
- **context-manager**: 

## Rules

- Never test unless explicitly asked
- Only make requested changes
- Mark ToDo items complete as finished

$ARGUMENTS
