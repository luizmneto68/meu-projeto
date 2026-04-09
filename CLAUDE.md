# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Running the scripts

```bash
python HelloWorld.py
python mensagem.py
```

## Project structure

This is a beginner Python project with two standalone scripts:

- `HelloWorld.py` — prints "Olá, Mundo!" directly via `print`
- `mensagem.py` — stores the string in a variable before printing

No dependencies, no build step, no tests framework configured.

## Git workflow

Always ask the user for confirmation before committing. Do NOT ask for the commit message — generate it automatically based on the changes. After confirmation, commit and push to the remote in sequence.
