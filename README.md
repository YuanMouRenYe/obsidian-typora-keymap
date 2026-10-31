# Typora Keymap for Obsidian

Bring Typora's editing shortcuts to Obsidian — including the ones Obsidian can't do on its own.

Obsidian has commands like "Set heading 1", but pressing the same shortcut again does nothing. This plugin makes heading shortcuts **toggle** (press `Ctrl+1` on an H1 → back to paragraph), adds heading level up/down, and binds the rest of Typora's keymap for you.

## Install

### BRAT (recommended for now)

1. Install the [BRAT](https://github.com/TfTHacker/obsidian42-brat) plugin.
2. In BRAT: **Add Beta Plugin** → paste this repository's URL.
3. Enable **Typora Keymap** in Settings → Community plugins.

### Manual

1. Download `main.js` and `manifest.json` from the latest Release.
2. Put them in `<your vault>/.obsidian/plugins/typora-keymap/`.
3. Reload Obsidian and enable the plugin.

## What you get

### Built-in commands (work right after install)

| Hotkey | Command |
| --- | --- |
| `Ctrl+1` … `Ctrl+6` | Heading 1–6 · press again on the same level to go back to paragraph |
| `Ctrl+0` | Paragraph |
| `Ctrl+=` / `Ctrl+-` | Increase / decrease heading level |
| `Ctrl+U` | Underline |
| `Ctrl+Shift+\`` | Inline code |
| `Ctrl+Shift+C` | Comment (`%%…%%`) |
| `Ctrl+Shift+I` | Insert image |
| `Ctrl+Shift+M` | Math block |
| `Ctrl+Shift+H` | Horizontal rule |
| `Ctrl+Shift+X` | Task list |

### Core commands (one click in the plugin settings)

Settings → Typora Keymap → **Apply Typora keymap**. This is the same as changing them by hand in Settings → Hotkeys, so you can always reset them with the **Reset** button.

`Ctrl+B` bold · `Ctrl+I` italic · `Alt+Shift+5` strikethrough · `Ctrl+K` link · `Ctrl+T` table · `Ctrl+Shift+K` code block · `Ctrl+Shift+Q` quote · `Ctrl+Shift+[` / `]` ordered / bullet list · `Ctrl+]` / `Ctrl+[` indent / outdent · `Ctrl+\` clear formatting · `Ctrl+/` source mode · `Ctrl+Shift+L` toggle sidebar · `Ctrl+Shift+1` open outline · `Alt+1…6` switch tab · `Ctrl+N` new tab · `Ctrl+Shift+N` new note · `Ctrl+Alt+←/→` back / forward.

`Ctrl+/` is taken from Obsidian's default "toggle comment" — comments move to `Ctrl+Shift+C`.

## Not migrated

Typora actions with no Obsidian equivalent are listed in the plugin settings. The main ones: save / save as (Obsidian autosaves), select line / select word, table row/column operations, focus mode and typewriter mode.

## Notes

- Hotkeys are applied per vault. Your other vaults need the same one-click (or manual) setup.
- After updating the plugin, reload Obsidian once.
- Tested on Obsidian 1.14.x, Windows.

## 中文说明

把 Typora 的编辑快捷键搬到 Obsidian，包括 Obsidian 自己做不了的那部分：标题快捷键**再按一次退回正文**、标题升降级。

- **装完就能用**：`Ctrl+1~6`（标题，再按一次取消）、`Ctrl+0` 正文、`Ctrl+=` / `Ctrl+-` 升降级、`Ctrl+U` 下划线、`Ctrl+Shift+\`` 行内代码、`Ctrl+Shift+C` 注释、`Ctrl+Shift+I` 图片、`Ctrl+Shift+M` 公式、`Ctrl+Shift+H` 分割线、`Ctrl+Shift+X` 任务列表。
- **要点一下才生效**：设置 → Typora Keymap → 「套用」，把内置命令（加粗、表格、源码模式、大纲、侧边栏等）一次绑好。这和你在「设置 → 快捷键」里手动改是一回事，点「恢复」就能还原。
- `Ctrl+/` 原本是 Obsidian 的「注释」，这里让给源码模式，注释挪到 `Ctrl+Shift+C`。

## License

MIT
