# Portfolio website: tasks and correction rules

Read this file first in any new conversation about the portfolio website.

## Where the website lives

- Live page: https://claude.ai/artifact/2phTBR9ywKqKADsGwHg7Dr (claude.ai Artifact, private until the owner shares it with the Share button).
- Source copy: `docs/portfolio/index.html` and `docs/portfolio/content.json` on branch `claude/portfolio-website-styling-vkiqqs`.
- The live page is the truth. The owner can change texts and photos on the page itself, so the repo copy can be older.

Files inside the artifact:

| File | What it holds |
|---|---|
| `index.html` | the page: design, all task texts, script |
| `content.json` | texts the owner saved in edit mode, `{"key": "text"}`; they replace the text of the element with the same `data-ed` key |
| `images/<key>.jpg` | photos the owner uploaded on the page |

Photo keys: `profile`, `teacher`, `group-work`, `quest-task1`, `q4`, `g1`, `g2`, `m1`, `l1`, `l2`, `c1`, `c2`, `c3`.

Editable text keys (`data-ed`): `about`, `intro`, `r1`–`r10` (reflections), `g1t`, `g2t`, `g3a`, `g3b`, `g3c`, `can1`, `can2`, `can3`.

## How to update the website

1. Read the live artifact first: `Artifact` with `action: "read"` and the URL above. Also read `content.json` from it (`path: "content.json"`).
2. Change `index.html` only. Publish with `url` set to the artifact URL, so the link stays the same.
3. Do not publish `content.json` or `images/*` unless the owner asks. They hold what she saved on the page, and overwriting them deletes her work.
4. If the text to fix is stored in `content.json`, `index.html` edits will not show. Either fix it in `content.json` (after reading it) or ask her to fix it in edit mode.
5. Keep the capabilities (`artifact`, `user`): they make the edit mode and photo upload work. Leave `capabilities` out of the publish call so they carry over.
6. After publishing, copy the new `index.html` to `docs/portfolio/` and commit it to the branch.

Edit mode, for the owner: the "Edit page" button at the bottom left (shown only to the owner and editors). It outlines editable texts, shows upload buttons on photos, and saves text with "Save text". Photos are resized to 1800 px JPEG on upload.

## The portfolio tasks

Fourth-year student of English Language Education, Akhmet Baitursynuly Regional University. Ten tasks, one page each, each ends with "My reflection":

1. Interview with a school English teacher on "Use of group work in education": 5 open questions, shown as a Telegram chat.
2. Rules for the group work: 10 short positive rules for an 11th grade class, plus a photo.
3. Quest on critical thinking: topic Travelling, grade 7, 5 online tasks from easiest to hardest.
4. Rubrics for assessment of 2 types of work: analytic rubric (essay, grade 11) and holistic rubric (monologue, grade 9).
5. Reading tasks for gifted and talented: a textbook task from okulyk.kz (screenshot, grade, book, page, task number) and her own harder version (analyse, evaluate, create).
6. Essay on underachievers: "The reasons of underachievement of pupils".
7. Memo on Lesson Study: what it is, origin (Japan, jugyō kenkyū; Stigler and Hiebert, The Teaching Gap, 1999), the cycle, why it helps, proposal.
8. Two tests for defining leaders: two ready-made online tests (woorise.com and knowledgejump.com), interactive on the page, with screenshot proof.
9. Questionnaire on "Inclusive education": Google Form https://forms.gle/DFtZfZKJfektWXP79, three chart screenshots, an analysis under each.
10. Short review, the result of the questionnaire: 150–180 words.

## Rules for correcting the website

- Keep her design: colours, fonts, one colour band per task, the layout. Change the design only when she asks.
- Keep her wording. Fix only clear mistakes: grammar, spelling, wrong facts, wrong numbers. Say in the reply what was changed.
- Word counts shown on the page ("≈ N words") must match a real count of the text.
- Never invent data: survey results, textbook details, the teacher's answers, test scores. If it is missing, ask her for it.
- Reflections stay in first person and in her voice.
- Do not remove a task or a section without asking.
- Check the page at phone width (about 390 px) as well as on a computer: no text cut off at the edge, no sideways scrolling.
- Leave the shared links (British Council, education.com, Wordwall, test sites, Google Form) as they are unless one is broken.

## Open problems (as of 2026-11-26)

- Task 10 retells the leadership tests (task 8) instead of the questionnaire results. Needs her survey answers (how many people answered, what most of them chose for each question) to rewrite.
- Placeholders not filled: "Grade: ___ · Book: ___ · Page: ___ · Task no.: ___", "Write the original textbook task here", the three chart analyses.
- No photos uploaded yet: profile, teacher, group work, quest task 1 and all screenshot slots.

## Change log

- 2026-11-26, version 1: page published from her HTML. Added photo upload and text editing for the owner, keyboard access to the test buttons, menu closes with Esc or a click outside, quest dark slide made visible, "a 11th" → "an 11th", word counts corrected (essay 174, review 153).
- 2026-11-26, version 2: Telegram chat appears in under 2 s instead of 7 s, hero title no longer cut off on phones, essay reflection sentence rewritten ("It is also a common problem that many pupils have to overcome."), edit button hidden for viewers in every case.
