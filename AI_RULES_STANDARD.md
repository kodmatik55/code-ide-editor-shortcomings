# AI_RULES Standard (Draft)

This document proposes a simple, tool-agnostic standard
for controlling AI behavior in software projects.

## File Name

Recommended:
- AI_RULES.txt
- AI_RULES.md

## Purpose

Define how AI assistants must behave when interacting with a project.

## Example Rules

- Do not scan the entire repository unless explicitly requested
- Analyze only files related to the current task
- Avoid assumptions and guessing
- Ask before making large or cross-module changes
- Preserve existing architecture and relationships
- Minimize unnecessary token usage
- Produce production-ready code
- Stop and ask when information is missing

## Usage

When starting work on a project, AI tools should be instructed:

> "Follow the rules defined in AI_RULES."

## Why This Matters

- Predictable AI behavior
- Lower token consumption
- Fewer destructive edits
- Safer large projects
- Better collaboration between humans and AI

This standard is intentionally simple.
Simplicity enables adoption.
