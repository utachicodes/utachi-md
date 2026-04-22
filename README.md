# UTACHICODES.md Template

A ready-to-use instruction file for AI coding agents. Drop it in the root of any repository and the agent will know how to work: how to plan before building, what documents to produce at each phase, how to write and structure code, how to handle errors, how to test, how to commit, and when to stop and ask instead of guessing.

## What it covers

The file follows the Software Development Life Cycle from planning through maintenance. It includes rules for code standards, architecture, security, git workflow, CI/CD, and environment configuration. It also instructs the agent to produce formal project documentation unprompted — BRD, SRS, FRD, SDD, test plan, backlog, release notes, and postmortems — using the templates defined in the file.

## Usage

Copy `UTACHICODES.md` into the root of your repository. Compatible with Claude Code, Cursor, GitHub Copilot, Gemini CLI, and any agent that reads markdown context files at session start.

No configuration required.

## What the agent will do

- Read the file before starting any task
- Follow the SDLC phases in order for every piece of work
- Create a README if one does not exist
- Maintain a product backlog in `docs/backlog.md`
- Write formal specification documents at the appropriate project phase
- Ask before making decisions that are not covered by the file

## License

MIT
