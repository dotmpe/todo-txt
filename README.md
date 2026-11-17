A more formalized set of rules for TODO.txt, with the intent to use similar
but completely different lists.

## Background

TODO.txt is a plain text, line based format.
It is a simple idea, using simple to read definitions (authoring rules).
But there is not a single provision for more flexible interpretations and
extended usage.

## Goals

- [+] Document a TODO.txt convention; with layers/levels and in more formal rules than github.com/todotxt/todo.txt
- [-] Provide an optimal form document for agentic or project derived instructions.
- [ ] Evolve the format into a separate, closely related syntax for tracking of
  other, non-task entities or records in plain-text, user editable files.
- [ ] Provide some guidance and centralized conventions for further tooling.

## Methods

The initial todo-txt worktree is produced by LLM. As different projects or
third-party usage reports their results it should progressively get a more
definite form.

There are no local running parts.
The source is plain text (markdown) for human and machine consumption.

## Definition

- [TODO.txt format rules and specifications](doc/FORMAT.md) — levels 0–4, five layers of compliance.

- [TODO.txt usage conventions](doc/CONVENTIONS+tasks.md) - the card to paste into agent or project instructions.

- [Generic project/baseline conventions](doc/CONVENTIONS+baseline.md) (copy).

## Status

The plan and dev/design notes are TODO.txt entries

- A separate parser in nice-plan has been set up; that project should identify
  how it supports TODO.txt by referring back here.

- For AI, also very simple models (~ 2.5B to even 500M params LLM), and as well
  as other/older styles of machine learning, like bayesian classification make
  interesting tools to mention here.
