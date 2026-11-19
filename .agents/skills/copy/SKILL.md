---
name: copy
description: "Write and edit the words people read in a design: UI copy (buttons, labels, empty states, errors, onboarding), and the longer text around a design (an announcement, a doc, an email, a post). Use whenever a design needs words, when someone asks to rewrite or tighten a text, and as the last pass on every variant, prototype and walkthrough. Prioritizes truth, specificity, plain words and the product's own voice over polish."
---

# Copy

Every variant, prototype and walkthrough ends with a copy pass. Prototypes take their
existing words from the product's source code (`variants` skill); only the new words are
yours, and they follow this file.

## UI copy, before anything else

- **Use the product's own nouns.** Read the repo's existing labels and docs first and reuse
  their words. Never rename a thing the product already names.
- **Buttons say what happens:** a verb and its object ("Send invoice", "Delete 3 files"), never
  "OK", "Submit" or "Yes". A destructive button repeats the verb of the dialog's title.
- **Sentence case** for every label, title and button. No trailing period on a label or a
  button; a full sentence of helper text gets one.
- **An empty state says what will be here and the one action that fills it.** "No reports yet.
  Create one to share it with your team." — not "Nothing to see here!".
- **An error says what happened and what to do next**, in the user's terms, never a code alone.
- **Short beats complete.** If a label needs a tooltip to be understood, rewrite the label.
- **Numbers as digits, with units.** "3 files", "12 min", not "three files".

## Longer text

An announcement, a doc, an email or a post, or a request to rewrite or tighten a text:

1. **Know the one point.** Write it as one sentence before anything else. A text that has no
   such sentence is not ready to write.
2. **Say it first.** The point opens the text; background, if any, follows it.
3. **Write for one reader.** Name who reads it and what they do next, and leave out what that
   reader does not need.
4. **Be specific.** A name, a number, a date or an example instead of an adjective. A claim
   you cannot back with a source is cut, not softened.
5. **Use plain words and short sentences.** One idea per sentence, active voice, the reader as
   "you". No filler openings, no stacked qualifiers, no summary that repeats the text.
6. **Keep the writer's voice.** When editing someone's text, change what is unclear or untrue,
   not what is merely different from how you would say it.
7. **Check before you hand it over.** Read it as the reader: every sentence earns its place,
   every fact is true, every term is the product's own, and the next step is clear.

What Design Desk itself tells people is not this skill's: every text
[docs/desk.md](../../../docs/desk.md) → Writing on the Desk lists follows the
[`explain`](../explain/SKILL.md) skill alone, with no copy pass.
