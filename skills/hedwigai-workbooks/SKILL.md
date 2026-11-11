---
name: hedwigai-workbooks
description: Keep research, reports, lead lists and trackers in a hedwigai workbook so the work is saved with its sources and every version. Use when the user says "keep this in a hedwigai workbook", asks to save or reuse earlier work, or asks to find, read or update one of their workbooks.
---

# hedwigai workbooks

A workbook is one document your agent reads and writes. It keeps every version and the source of every line. Any assistant connected to the same account can open it later and carry on.

## When to use it

- The user says "keep this in a hedwigai workbook".
- The work should outlive the chat: a report, a lead list, a client tracker, a budget model.
- The user asks about earlier work. Search their workbooks first.

## How

1. Find the workbook: `search_workbooks` or `find_workbook`. Use `list_workbooks` to browse.
2. Read before you write: `read_workbook` (or `get_sections` for one part).
3. Write: `write_workbook` for your own edits, with `save_sources` for the pages you used.
4. New topic: `create_workbook`.
5. Ask hedwigai to research and keep it current: `update_workbook` starts a run. Runs are billed to the account, so say so first. `credits` shows the balance.

Reading, searching and writing are free.
