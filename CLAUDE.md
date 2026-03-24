# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Current Project Status

This is a newly initialized Claude Code workspace with no project-specific files yet. The directory currently contains only Claude Code configuration (`.claude/settings.json`).

## Claude Code Configuration

- **Model**: deepseek-chat (via DeepSeek API)
- **Base URL**: https://api.deepseek.com/anthropic
- **API Timeout**: 600000ms (10 minutes)
- **Non-essential traffic**: Disabled

## Next Steps

This CLAUDE.md should be updated once a project is initialized. When adding project-specific information, include:

1. **Project type and technology stack** (Node.js, Python, Rust, etc.)
2. **Common development commands** (build, test, lint, run)
3. **Project structure and architecture**
4. **Any existing rules or conventions** (from .cursorrules, .github/copilot-instructions.md, etc.)

To initialize a project:
- Use appropriate language-specific init command (e.g., `npm init`, `cargo init`, `go mod init`)
- Create source code directories and files
- Update this file with project-specific guidance

## General Claude Code Usage

- Always read existing code before making changes
- Use the Task tool with Explore agent for codebase exploration
- Follow the security guidelines in the Claude Code system prompt
- Avoid creating unnecessary files; prefer editing existing ones

---

*Last updated when project was empty. Update this file when adding project-specific content.*