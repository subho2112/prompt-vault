```markdown
# 🧰 Prompt Vault
A clean, organized collection of reusable prompts for writing, coding, chat personas, utilities, and experiments.  
Everything lives in one structured place so I can reuse, refine, and expand prompts easily.

```
***

**🗂️ Repository Overview**
```
prompt-vault/
├─ prompts/
│  ├─ writing/        # Fiction, poetry, Bengali prose, creative writing
│  ├─ coding/         # Debugging, code generation, boilerplates
│  ├─ chat/           # Personas, tone control, style prompts
│  ├─ tools/          # Summarizers, cleaners, extractors
│  └─ misc/           # Experiments or random prompts
├─ templates/         # Base templates (system, few-shot, structured output)
└─ index.md           # Manual list of all prompts
```

***

**🔧 YAML Metadata Example**
This is a standard metadata block for any prompt:
```yaml
id: writing/bengali-melancholy
title: Bengali Melancholic Prose
tags: [bengali, creative, dark, prose]
model: gpt-5.1
author: Subho
updated: 2025-11-24
````

Paste this at the top of any prompt `.md` file to get consistent structure.

***

**🎯 Purpose**

* Keep all prompts organized
* Reuse prompts across ChatGPT, Claude, VS Code, terminal tools
* Build a personal prompt library
* Track different writing/coding styles
* Experiment with consistent prompt formats
* Use templates to quickly make new prompts

---

**📝 Usage**
* Browse the `prompts/` folder
* Open any `.md` file and copy the prompt
* Create new prompt files using template examples
* Update `index.md` whenever new prompts are added
* Use `templates/` for starting a fresh prompt

***

**✨Categories**

 **Writing**
Fiction, creative prose, poetry, Bengali storytelling, styles, narrative structures.

 **Coding**
Debugging, refactoring, code generation, documentation helpers.

**Chat / Personas**
Assistant personalities, tone settings, communication modes, conversation styles.

**Tools**
```
Utilities:
* summarizers
* JSON cleaners
* extractors
* transformers
```
**Misc**
Uncategorized experiments, drafts, ideas.

***
**🧱 Templates**
Basic prompt templates inside `templates/`:
**system.md** → role/persona instructions
**few-shot.md** → examples for training
**structured-output.md** → JSON/table output constraints
Use these to keep prompts consistent.
***
