# Repository guide for AI agents

This is a **public** repository (mirrored to GitHub) holding a personal collection of prompts. It also contains local-only, proprietary material that must never be published.

## Never publish private content

The `private/` folder and any `*.private.*` file (`.md`, `.txt`, `.pdf`, `.docx`, `.xlsx`, `.pptx`) are gitignored on purpose — they hold proprietary content (e.g. market analysis) that must stay on the local machine only.

The only way content in `private/` could ever be committed is an explicit forced add (`git add -f`), which never happens by accident and which I won't do.

So: never use `git add -f` / `git add --force`, and never otherwise bypass `.gitignore`, for anything under `private/` or any `*.private.*` file. Normal staging (`git add <path>`, `git add -A`, `git add .`) is safe — it always respects `.gitignore`. If a commit would ever include private content, stop and flag it instead of proceeding.
