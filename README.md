
# Chat Macro System

This repository contains a macro system configuration designed to streamline and enhance interactions with AI assistants like ChatGPT. It allows users to trigger specific response formats, styles, or helper actions using simple macro commands.

---

## 📄 Files

- `macro_setup_prompt.txt`: The full setup prompt that you can paste into a new chat to enable the macro system.

---

## 🚀 How to Use

1. **Copy the contents** of `macro_setup_prompt.txt`.
2. **Paste it into a new chat** with your AI assistant to initialize the macro system.
3. Start using macros immediately by prefixing commands with `;` (semicolon).

### Example:
```txt
=full
Please rewrite this code to be more efficient ;optimize ;comment
```

This would:
- Set the default macro to output full updated code.
- Optimize the given code.
- Add inline comments explaining changes.

---

## 🔧 Available Macros

See the [macro_setup_prompt.txt](macro_setup_prompt.txt) file for the full list. Categories include:
- Primary macros (`;full`, `;diff`, `;explain`, etc.)
- Code-focused macros (`;refactor`, `;optimize`, etc.)
- Writing and clarity macros (`;summarize`, `;define`, etc.)
- Workflow utilities (`;shell`, `;checklist`, etc.)
- Default modes (`=full`, `=diff`, `=null`)
- Uninstall: `;uninstall-macros` to clear the system

---

## 🧩 Extending the Macro System

You can add your own macros by appending to the setup prompt with this format:
```txt
;yourmacro – Description of what this macro should trigger or modify in behavior.
```

You can also define:
- Aliases for fast typing
- Custom grouped macro presets (e.g., `;debug-preset` for combining multiple macros)
- Mode-switching logic (e.g., switching to `;brief` after `;full`)

---

## 🧼 Uninstalling

To remove the macro system from a chat session:
```txt
;uninstall-macros
```

---

## 📢 Contributions

Feel free to fork and expand this macro system for your team, coding style, or project needs. PRs welcome!

