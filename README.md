> **Portfolio showcase** — the complete implementation is kept private to protect intellectual property. This public repository intentionally contains documentation only. A live demo or private code review can be provided for a serious project discussion.

# AI Terminal Commander

Terminal-first coding agent that runs inside the real VS Code integrated terminal instead of a custom chat panel.

## Highlights
- OpenAI Responses API integration
- MCP tool execution
- prompt queue while an agent run is active
- /steer, /stop, /status and /new controls
- thin VS Code extension opening the CLI in the current workspace
- checkpointed tool-call flow
- automated tests for queueing and conversation state

## Stack
TypeScript, Node.js, OpenAI SDK, Model Context Protocol SDK, Zod, VS Code extension API.

## Development
1. Copy .env.example to .env.
2. Run npm install.
3. Run npm run build.
4. Run npm test.

Never commit API keys. .env is ignored by Git.

## Usage and licensing

This repository is source-available for portfolio evaluation. You may inspect the code and run an unmodified local copy for evaluation, but commercial use, redistribution, republishing and derivative distribution are not permitted without written permission. See [LICENSE.md](LICENSE.md).

