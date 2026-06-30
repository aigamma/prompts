# prompts

A personal, version-controlled collection of prompts backed up here so every update is safe. The portable value here is a way to scaffold your own personal prompt library, which is what I am doing by dedicating Visual Studio Code to be a prompt library with this repository. I figure if someone might be able to get something out of these prompts that I may as well keep it open for them. And then of course .gitignore proprietary directories as you should too in your forks.

## Layout

Prompts are organized into folders by context:

- `general/` — prompts that apply anywhere, regardless of platform or project
- `.claude/` — prompts and concepts for Claude Code
- `ChatGPT/` — prompts for ChatGPT

Add new folders freely; the structure is just whatever's useful. Folders for other tools and projects (Codex, Cursor, and so on) are kept local, the same way private material is (see below).

## Keeping something private

This repo is **public**. Anything you don't want shared, keep it out of git one of two ways:

- put it in a `private/` folder, or
- name the file `*.private.md`

Both are already in [`.gitignore`](.gitignore), so they stay on your machine only.

## License

[MIT](LICENSE) © 2026 Eric Allione
