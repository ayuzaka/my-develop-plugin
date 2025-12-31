# Agent Plugins

A collection of Claude Code plugins for development workflows.

## Plugins

This repository contains the following plugins:

### [owasp-security-review](./owasp-security-review)

Security review and implementation support based on OWASP Cheat Sheet Series. Covers XSS, SQL Injection, CSRF, authentication, authorization, and other security topics.

### [skill-review](./skill-review)

Review Agent Skills for specification compliance and best practices.

### [ask-plan](./ask-plan)

A command that analyzes PLAN files and refines them through interactive questioning. Automatically detects ambiguities and implementation gaps, then updates the PLAN file based on user responses.

## Installation

Each plugin can be installed independently:

```bash
# Install owasp-security-review
claude plugin add ayuzaka/agent-plugins/owasp-security-review

# Install skill-review
claude plugin add ayuzaka/agent-plugins/skill-review

# Install ask-plan
claude plugin add ayuzaka/agent-plugins/ask-plan
```

## Development

Validate plugin configuration:

```bash
# Validate individual plugin
claude plugin validate ./owasp-security-review
claude plugin validate ./skill-review
claude plugin validate ./ask-plan
```

## License

MIT
