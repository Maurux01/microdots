# microdots

Personal [micro](https://github.com/micro-editor/micro) text editor configuration.

## Files

- `init.lua` — plugin setup (comments, filetype, lsp, emmet, autosave, nerdtree, fzf, markdown-preview, live-server)
- `settings.json` — editor settings (gruvbox theme, 2-space tabs, relative numbers, statusline, LSP languages, etc.)
- `colorschemes/gruvbox.micro` — gruvbox dark colorscheme

## Usage

Place the `micro/` directory in your micro config location:

- **Linux/macOS**: `~/.config/micro/`
- **Windows**: `%APPDATA%\micro\`

Then restart micro.

## Plugins

Fullstack-focused plugins:

- `comments`
- `filetype`
- `lsp`
- `emmet`
- `autosave`
- `nerdtree`
- `fzf`
- `markdown-preview` — Markdown visualizer
- `live-server` — live reload server

Supported LSP languages: JavaScript, TypeScript, Python, HTML, CSS, Go, Rust.

## Additional plugins

- **markdown-preview**: preview Markdown files in your browser
- **live-server**: live reload server for web development

## Settings

- Colorscheme: gruvbox
- Tab size: 2 spaces (soft tabs)
- Autoindent, ruler, cursorline, relative line numbers
- Statusline enabled, microui disabled
- Multicursor enabled
