# Claude Code Configuration

This repository contains my custom Claude Code configuration, including slash commands and agent definitions.

## Contents

- **commands/** - Custom slash commands for common workflows
- **agents/** - Specialized agent definitions for research and code analysis

## Commands

Key slash commands include:

- `/create_issue` - Create issues through Socratic questioning to expose gaps in thinking
- `/create_plan` - Create detailed implementation plans through interactive research
- `/research_codebase` - Document codebase as-is with thoughts directory integration
- `/implement_plan` - Implement technical plans with verification
- `/validate_plan` - Validate implementation against plan
- `/debug` - Debug issues by investigating logs and git history
- `/linear` - Manage Linear tickets with workflow patterns
- `/commit` - Create git commits with user approval
- `/describe_pr` - Generate comprehensive PR descriptions

## Agents

Specialized agents for targeted research:

- **codebase-locator** - Find files and components
- **codebase-analyzer** - Understand implementation details
- **codebase-pattern-finder** - Find similar implementations
- **thoughts-locator** - Discover relevant documents in thoughts directory
- **thoughts-analyzer** - Extract insights from thoughts documents
- **web-search-researcher** - Research modern information from the web

## Usage

Clone this repo to your `~/.claude` directory or copy individual commands/agents as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
