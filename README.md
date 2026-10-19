# TOK Exhibition Coach

A Claude skill that helps IB Theory of Knowledge students revise their own exhibition commentaries, written to work for any of the 35 IA prompts and to aim at the top mark band. It turns teacher feedback into specific edits, keeps the student's wording, and helps cut to the word limit without losing the TOK content.

It is an editing and coaching aid. It is not a ghostwriter, and it is not affiliated with or endorsed by the International Baccalaureate Organization.

## Academic integrity

The work you submit must be your own. Follow your school's and the IB's academic integrity policy, and **cite Claude** wherever you used it to revise your work. Harvard samples (in-text and bibliography) are below and in `references/citing-claude.md`.

**In-text:** (Anthropic, 2026)

**Bibliography:** Anthropic (2026) *Claude Sonnet 5.5* [Large language model]. Available at: https://claude.ai (Accessed: 19 October 2026).

Use your own model version, release year and access date, and check which referencing style your school requires.

## What it does

- Checks drafts against the four strands of the exhibition marking criterion (explicit real-world contexts, clear links to the prompt, a distinct contribution from each object, and evidence for every point) and avoids what the lower bands get wrong
- Adapts to the type of prompt you chose (criteria, extent, comparison, influence, ethical) so the commentary answers what it actually asks
- Reads your draft and your teacher's comments, then fixes the sentences the comments point at
- Finds the same mistakes your teacher didn't flag, using a list of recurring mistake types (`references/mistake-patterns.md`)
- Puts textbook theory at the start of a paragraph and links it to an example from your object
- Uses your IA prompt's exact wording in the intro and the link sentence
- Weaves in TOK concepts and cognitive tools where they change the argument
- Cuts for word count in a safe order, protecting theory, citations and the link
- Can review a draft too: adds its own short, teacher-style comments (labelled "Claude:") without changing your text
- Never invents quotes, page numbers or sources. It leaves a placeholder for you to fill from your own textbook

## Install

- **Claude.ai:** Settings, Capabilities, Skills, then upload the `.skill` file (or the zipped folder).
- **Claude Code:** copy the `tok-exhibition-coach` folder into `~/.claude/skills/`.

## Use

Share your IA prompt, theme, object details, draft, the teacher's comments, and any textbook lines you want used (with page numbers). Then ask, for example:

- "Fix Object 1 according to the comments, keeping as much of my wording as possible."
- "Tell me how to fix Object 2 based on the mistakes in Object 1."
- "Shorten this paragraph without removing any TOK theory."
- "Review my Object 3 and add comments like my teacher would."

## Contributing

Add lessons to the "Lessons log" in `SKILL.md`, or new mistake types to `references/mistake-patterns.md`. Please don't submit anyone's real exhibition text, teacher names, school names or textbook passages. Use invented examples.

## Files

- `SKILL.md`: the workflow, ground rules and structure of a strong commentary
- `references/mistake-patterns.md`: 22 recurring mistake types with fixes and invented examples
- `references/comment-style.md`: templates and rules for writing teacher-style review comments
- `references/assessment-criteria.md`: paraphrased top-band descriptors, what each lower band gets wrong, and per-object checklists
- `references/prompt-types.md`: the five prompt families and what each commentary needs
- `references/citing-claude.md`: Harvard sample for citing Claude, in-text and bibliography

The marking criteria are paraphrased, not quoted, and prompts are described by keyword. Check the official wording and prompt numbering in the current IB TOK subject guide.
