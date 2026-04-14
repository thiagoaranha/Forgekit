# QWEN.md - forgeKit Project Context

## Active Technologies
- (feature-branch-001)

## Recent Changes
- feature-branch-001: Initial project setup with Spec Kit

## Project Overview
- **Project Name**: forgeKit
- **Spec Kit Version**: 0.7.1.dev0
- **AI Agent**: Qwen Code
- **Script Type**: PowerShell (ps)
- **Branch Numbering**: Sequential

## Spec-Kit Workflow Commands

The following slash commands are available in this project. They should be used in this order:

| Step | Command | Purpose |
|:---|:---|:---|
| **1** | `/speckit.constitution` | Define project governance, quality standards, and principles |
| **2** | `/speckit.specify` | Create functional specification (focus on requirements, not stack) |
| **3** | `/speckit.clarify` | (Optional) Refine vague points in the specification before planning |
| **4** | `/speckit.plan` | Define tech stack, architecture, contracts, and implementation plan |
| **5** | `/speckit.tasks` | Generate ordered tasks with dependencies and parallel markers |
| **6** | `/speckit.analyze` | (Optional) Validate consistency between spec, plan, and tasks |
| **7** | `/speckit.implement` | Execute tasks sequentially/parallely to generate code |

### Optional Commands:
- `/speckit.checklist` - Generate quality checklists to validate requirements completeness
- `/speckit.taskstoissues` - Convert tasks to GitHub Issues

## Git Integration
- Branch naming: Sequential (001, 002, ..., 1000, ...)
- Auto-hooks: 22 hooks configured (before/after for each command)
- Auto-commit: Disabled by default

## Scripts Location
All PowerShell scripts are located in `.specify/scripts/powershell/`:
- `check-prerequisites.ps1` - Verify prerequisites before commands
- `common.ps1` - Shared helper functions
- `create-new-feature.ps1` - Feature branch creation
- `setup-plan.ps1` - Implementation plan setup
- `update-agent-context.ps1` - Update this file with plan data

## Next Steps
1. Start with `/speckit.constitution` to establish project principles
2. Then use `/speckit.specify` to create your feature specification
3. Follow the workflow commands in order

---

*Last updated: 2026-04-14*
