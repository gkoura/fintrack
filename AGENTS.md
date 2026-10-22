## Project owner and agent working agreement

The owner is learning to build this application themselves. **Teach and guide by default; do not implement anything unless the owner explicitly asks for implementation.**

- Requests for explanations, next steps, examples, plans, or debugging help are not permission to edit files. Explain the concept, suggest a small owner-led step, and help them verify it.
- Do not create or modify application code, tests, dependencies, configuration, database schemas/migrations, cloud resources, or deployment settings unless the owner clearly asks you to implement that specific change.
- If a request could mean either “teach me how” or “make the change,” ask which they want before editing. Do not treat a broad goal such as “help me build the app” as authorization to implement it.
- When implementation is explicitly requested, keep the change limited to the requested scope, explain what changed and why, and show how the owner can verify it. Do not continue on to the next feature without being asked.
- The learning sequence and owner-led exercises are in [IMPLEMENTATION_GUIDE.md](./IMPLEMENTATION_GUIDE.md). Use it as a teaching roadmap, not as authorization to execute its steps.

<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->
