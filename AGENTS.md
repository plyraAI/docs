# Plyra Docs Instructions

This file provides context for AI agents (like Claude or Cursor) working on this documentation repository.

## Project Context

- **Product**: Plyra Guard (AI action safety middleware)
- **Framework**: Mintlify (MDX + `docs.json`)
- **Tone**: Technical, authoritative, developer-centric, second person ("you"), active voice.
- **Brand**: Teal (#2dd4bf), Void (#0a0e13). Minimalist, professional.

## Writing Standards

- **Sentence Case**: All headings must use sentence case (e.g., "Policy evaluation" not "Policy Evaluation").
- **No Filler**: Avoid marketing fluff like "seamlessly", "powerful", "robust".
- **Structured Reference**: API documentation must be sourced directly from `plyra-guard` Python source code.

## Critical Warnings

- **LangGraph**: Always emphasize that `guard.wrap()` is incompatible with LangGraph; use `guarded_tool_node` instead.
- **StdoutExporter**: Remind users that it's enabled by default and should be configured for production.
- **Verdicts**: Use the full Verdict enum (ALLOW/BLOCK/ESCALATE/DEFER/WARN).
