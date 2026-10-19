# Writing review comments in the style of a TOK teacher

Read this when the student asks Claude to review, comment on or "mark" a draft, or asks what a teacher would flag. The templates come from the shape of real teacher feedback on a TOK exhibition. The examples are invented.

Contents: 1 What teacher comments looked like · 2 Templates by type · 3 Rules · 4 Worked example · 5 Putting comments in a document

---

## 1. What teacher comments looked like

- **Short.** One line, usually a question or an instruction, often 3 to 15 words.
- **Placed right after the sentence they target**, in a different colour from the draft.
- **One issue each.** They point at the gap and rarely supply the fix.
- **Aimed at the same few things:** whether a label or claim is justified, whether a conclusion follows ("So?"), whether the prompt's exact wording is used, whether textbook theory supports the point, whether paragraphs flow and avoid repeating each other, and whether the commentary is the right length. The marking criteria add: is the real-world context explicit, is the link to the prompt clear, is each object's contribution justified, and is every point supported.
- **Fragment prompts** such as "as… (say why)" that invite the student to finish a sentence.
- **Object-wide notes** at the end of an object: word target, TOK concepts to add, cognitive tools to add.
- **Sometimes a model idea** to apply "if relevant", which the student rewrites in their own words.
- **Reference-list notes:** add all sources, include the textbook, order alphabetically by surname.

## 2. Templates by type

Fill the brackets with the student's own content.

| Type | Template |
|---|---|
| Label not justified | (Which label applies? Why? Justify it.) |
| Leap | So? Why does this mean [conclusion]? |
| Missing theory | Add TOK theory on [topic], then connect it to an example from your object. |
| Prompt wording | Use the exact wording of the prompt here. |
| Flow or repetition | Does this flow on from the paragraph above? You already said this in [where]. |
| Fragment | [Student's words] as… (say why). |
| Vague referent | "This" refers to what? |
| Blurred categories | What about the difference between [X] and [Y]? |
| Evidence | Better connect this to [the presence or lack of evidence]. |
| Justification thread | Reference justification throughout this paragraph. |
| Structure | PEEL: where is your Link back to the prompt? |
| Concepts and tools (end of object) | Add TOK concepts: [list]. Add links to cognitive tools: [list]. |
| Length (end of object) | Shorten so the whole object is around [N] words. |
| Context | What is this object's specific real-world context? State source, date and setting. |
| Unique contribution | What does this object add that the other two don't? |
| Description | What claim does this description support? Add it or cut it. |
| Weak link | Which part of the prompt does this answer, and how? Spell out the steps. |
| Cross-object repetition | This justification matches Object [n]. What is different here? |
| Limit or other side | What is the limit, or the opposing view, here? |
| Sources | Add all sources used, including the textbook, in alphabetical order by surname. |
| Idea to apply | Idea to try, in your own words: [one-line idea, not a full sentence to copy]. |
| Keep | Keep: [what works, so it survives cutting]. |

## 3. Rules

1. **Label every comment "Claude:"** so it is never mistaken for the teacher's. Don't claim to speak for the teacher, give or predict marks, or say what the teacher "wants". You may say which marking-criteria features a paragraph shows or lacks. Phrase comments as questions a reader would ask.
2. **One issue per comment, 20 words or fewer.** Put the comment immediately after the sentence it targets. Outside the text, anchor it to a short quoted phrase (six words or fewer).
3. **Comment, don't fix.** Point at the gap, give at most a hint, and let the student do the fixing. In reviewer mode, don't change the student's text. Offer to fix afterwards.
4. **Prioritise.** Order by importance: unsupported points and weak links to the prompt first, then vague context, then leaps, then repetition across objects, then structure and flow, then wording. Batch all grammar and punctuation into one comment at the end of the paragraph. Aim for about six comments per paragraph plus the object-wide notes.
5. **Mark taste as optional.** If a comment is style, not a gap, label it "optional".
6. **Add "Keep" comments** for strong theory, concepts and links, so the student protects them when cutting words.
7. **Use the student's own material.** Comments should refer to what's in the draft. Don't introduce new claims, sources or quotes.
8. **Scan the whole object**, not only the places the student asks about. Use the mistake types in `mistake-patterns.md` to find problems the teacher might not have reached yet.

## 4. Worked example (invented)

Draft:
> The sundial sits in a university courtyard, so it shows knowledge. Its markings are accurate. Some visitors call it beautiful.

Annotated:
> The sundial sits in a university courtyard, so it shows knowledge. **[Claude: So? Why does its location make its claims knowledge?]** Its markings are accurate. **[Claude: Accurate by what test? Name the evidence or method.]** Some visitors call it beautiful. **[Claude: Which category is this, and why? Use the prompt's wording.]**
>
> **[Claude, whole object: Add TOK theory to the first sentence. Add concepts and cognitive tools. Check the word target.]**

## 5. Putting comments in a document

- **In chat (the default):** return the student's text with each comment in bold square brackets straight after its sentence, as in the example above.
- **In an uploaded .docx:** follow the docx skill for mechanics. Use real Word comments if possible. Otherwise use coloured text in a colour that is different from the teacher's, always starting with "Claude:".
- **Tell the student** to delete the comments once they have addressed them. If they want the text fixed as well, switch back to the revision loop in `SKILL.md`.
