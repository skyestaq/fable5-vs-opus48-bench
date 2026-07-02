## Notes

# Run Conditions — Fable 5 vs Opus 4.8 Benchmark

## Model Versions
- Run A (fable-run/): claude-fable-5 [confirm exact model string shown in Claude Code session]
- Run B (opus-run/): claude-opus-4-8 [confirm exact string]
- Claude Code version: [output of `claude --version`, must match in both panes]

## Thinking Mode
- Extended thinking: ON for both sessions
- Rationale: Fable's reasoning behavior is part of what we're evaluating; recordings capture how each model works, not just what it ships.

## Session Start Timestamps
- Run A prompt sent: [YYYY-MM-DD HH:MM:SS local]
- Run B prompt sent: [YYYY-MM-DD HH:MM:SS local]
- Target gap: under 30 seconds

## Global CLAUDE.md Contents (if any)
- Exists: [yes/no per setup verification]
- Contents: [paste verbatim, or "none"]
- Note: applies identically to both sessions, documented for reproducibility.

## MCP Servers Active
- [list from `/mcp` in each session, or "none"]
- Must be identical across both sessions. Recommended: none. Disconnect anything nonessential.

## Code Execution Allowed
- YES for both sessions
- Models may open/run their output to verify. Whether a model chooses to verify is itself a recorded observation.
- Permission prompts: approve file writes and local execution; deny anything network-bound.

## Prompt
- frozen-prompt.md v1.0, pasted verbatim, no edits after this file is committed to the run log.
- No follow-up messages permitted after the initial prompt. Model questions go unanswered.

## Completion Criteria
- Run ends when the model stops producing output.
- Deliverable saved untouched, committed in its own repo: "benchmark output, untouched"
- Token usage logged via /cost immediately at completion, before anything else.

## Environment
- Machine: [OS, e.g., macOS 15.x / Windows 11]
- Browser for judging: [Chrome version x]
- Recording tool: [name]
- Network: [normal / nothing unusual]

## Notes
- [anything unexpected during the runs]