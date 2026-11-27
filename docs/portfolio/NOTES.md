# Portfolio website: tasks and correction rules

Read this file first in any new conversation about the portfolio website.

## Where the website lives

- Live page: https://claude.ai/artifact/2phTBR9ywKqKADsGwHg7Dr (claude.ai Artifact, private until the owner shares it with the Share button).
- Source copy: `docs/portfolio/index.html` and `docs/portfolio/content.json` on branch `claude/portfolio-website-styling-vkiqqs`.
- The owner asked to remove the on-page edit mode (version 4). Do not add "Edit", "Upload photo" or "Add a photo" buttons or placeholders back.

Files inside the artifact:

| File | What it holds |
|---|---|
| `index.html` | the page: design, all task texts, script |
| `content.json` | optional text overrides, `{"key": "text"}`; each replaces the text of the element with the same `data-ed` key. Currently `{}` |
| `images/<key>.jpg` | photos; none published yet |

Photo keys: `profile`, `teacher`, `group-work`, `quest-task1`, `q4`, `g1`, `g2`, `m1`, `l1`, `l2`, `c1`, `c2`, `c3`. A photo box stays invisible until `images/<key>.jpg` exists. `profile` and `teacher` show a plain silhouette until then.

Text keys (`data-ed`): `about`, `intro`, `r1`–`r10` (reflections), `g1t`, `g2t`, `g3a`, `g3b`, `g3c`, `can1`, `can2`, `can3`.

## How to update the website

1. Read the live artifact first: `Artifact` with `action: "read"` and the URL above.
2. Change `index.html`. Publish with `url` set to the artifact URL, so the link stays the same.
3. To add a photo the owner sends as a file, publish it in `files` as `images/<key>.jpg`; the page shows it with no HTML change.
4. After publishing, copy the new `index.html` to `docs/portfolio/` and commit it to the branch.

## The portfolio tasks

Fourth-year student of English Language Education, Akhmet Baitursynuly Regional University. Ten tasks, one page each. No task has a reflection (she asked to remove all of them).

1. Interview with a school English teacher on "Use of group work in education": 5 open questions, shown as a Telegram chat.
2. Rules for the group work: 10 rules for an 11th grade class in three stages (before we start, while we work, at the end), each with a note on how it looks in a lesson; group roles (leader, timekeeper, speaker, secretary, rotating, as in the interview); useful phrases; a drawn illustration.
3. Quest on critical thinking: topic Travelling, grade 7, 5 tasks from easiest to hardest, drawn travel-map cover on the main card. The text of each task must match its link exactly: Task 1 own clues with Wikipedia links (Eiffel Tower, Colosseum, Baiterek, Mount Fuji); Task 2 LearnEnglish Teens video, speaker Sophia, plus transcript PDF; Task 3 the 10 statements of the Education.com worksheet "Travel the World: Fact or Opinion?" copied exactly; Task 4 own logic puzzle (same four cities); Task 5 the 15 Wordwall speaking cards "session 1" copied exactly.
4. Rubrics for assessment of 2 types of work: analytic rubric (essay, grade 11) and holistic rubric (monologue, grade 9).
5. Reading tasks for gifted and talented, grade 6: English Plus (Grade 6) Student's Book, Kazakhstan Edition (Wetz, Pye, OUP 2015), https://okulyk.kz/anglijskij-jazyk/963/, Unit 3, page 34, Reading "The red list", text "Danger! Humans!". Proof photo `images/g1.jpg` is page 34 rendered from the okulyk.kz PDF (books.okulyk.com/963/963.pdf). Slides: source, original exercises 1-4, four gifted tasks (analyse numbers, fact/opinion, evaluate, research and create a fact file), book vs mine.
6. Essay on underachievers: "The reasons of underachievement of pupils".
7. Memo on Lesson Study: what it is, origin (Japan, jugyō kenkyū; Stigler and Hiebert, The Teaching Gap, 1999), the cycle, why it helps, proposal.
8. Two tests for defining leaders: Test 1 for students, 4-H Leadership Survey (7th-12th Grade), Montana State University Extension 2019, 10 of 22 statements, scale 1-7. Test 2 for teachers, Teacher Leadership: Teacher Self-Assessment Tool, Center on Great Teachers and Leaders at AIR with REL Midwest, March 2017, 10 foundational indicators, scale Not Evident / Beginning / Developing / Advancing. Statements copied exactly; results show averages or counts only, no invented interpretation.
9. Making up a questionnaire on "Inclusive education": the questionnaire itself. Google Form https://forms.gle/DFtZfZKJfektWXP79 (edit link docs.google.com/forms/d/1GXj7jSCTwX5sJh8QABSHnn3ndUCnAqx8HXz1hV4Z02g), 10 multiple-choice questions, 5 options each. The page lists all questions and options.
10. Short review, the result of the questionnaire. Her instruction for the order: first the result screenshot of every question, then the analysis of each one, and only after all ten the overview (150–180 words).

Survey results (14 responses, counted from her screenshots of the Responses tab, 2026-11-26):

| Q | Answers (count of 14) |
|---|---|
| 1 | Absolutely essential 10, Moderately important 3, Highly important but not indispensable 1 |
| 2 | Genuinely promotes inclusion 8, Appearance without support 3, Both, depending on implementation 3 |
| 3 | Entirely accountable 8, Primarily, with government 3, Equally with families and society 3 |
| 4 | Teacher training 7, Social stigma 4, Financial resources 2, Policies 1, Infrastructure 0 |
| 5 | Strongly agree 6, Agree 6, Neutral 2 |
| 6 | Very great 5, Considerable 3, Moderate 6 |
| 7 | Government 6, All stakeholders equally 5, School administrations 2, Teachers 1, Parents 0 |
| 8 | Strongly agree 9, Agree 2, Neutral 3 |
| 9 | Teacher professional development 8, Accessible infrastructure 5, Collaboration 1 |
| 10 | Social cohesion 7, Equal opportunities 6, Difficult to predict 1 |

Chart images on the site: `images/res1.jpg` … `images/res10.jpg`, cropped from her phone screenshots.

## Rules for correcting the website

- Keep her design: colours, fonts, one colour band per task, the layout. Change the design only when she asks.
- Keep her wording. Fix only clear mistakes: grammar, spelling, wrong facts, wrong numbers. Say in the reply what was changed.
- Word counts shown on the page ("≈ N words") must match a real count of the text.
- Never invent data: survey results, textbook details, the teacher's answers, test scores. If it is missing, ask her for it.
- No reflections anywhere on the site (she asked to remove all of them). Do not add any back.
- Do not remove a task or a section without asking.
- Check the page at phone width (about 390 px) as well as on a computer: no text cut off at the edge, no sideways scrolling.
- Every link must lead to exactly the information written on the page. When the page quotes a source (worksheet, Wordwall cards, tests, textbook), copy its wording exactly and check it against the source.
- The assessment criteria below are a checklist for reviewing the site. Never put them on the website (she asked to remove them).
- Text on the page must not promise something the page does not have (photos, proof, reflections).

## Assessment criteria (use them to check the site, do not publish them)

Creating the e-Portfolio, 60%: logic of presented information 5, design (form) 5, aesthetic side 5, creativity 5, contents of the module tasks 40.
Defending the e-Portfolio, 40% (her oral defence, not the site): culture of presentation 10, coherence and cohesion of speech 20, argumentative answers to questions 10.

## Open problems (as of 2026-11-26)

- (fixed in version 12) Task 5 was incomplete (hurts "contents of tasks", 40%): "Grade: ___ · Book: ___ · Page: ___ · Task no.: ___", "Write the original textbook task here", no textbook screenshots. Needs the okulyk.kz textbook details from her.
- Photos on the site (version 13): `profile.jpg` (her, hero + interviewer), `teacher.jpg` (the interviewed teacher), `teacher-face.jpg` (Telegram avatar). Still hidden: group work photo (replaced by a drawing), memo photo, test screenshots.

## Change log

- 2026-11-26, version 1: page published from her HTML. Added photo upload and text editing for the owner, keyboard access to the test buttons, menu closes with Esc or a click outside, quest dark slide made visible, "a 11th" → "an 11th", word counts corrected (essay 174, review 153).
- 2026-11-26, version 2: Telegram chat appears in under 2 s instead of 7 s, hero title no longer cut off on phones, essay reflection sentence rewritten ("It is also a common problem that many pupils have to overcome."), edit button hidden for viewers in every case.
- 2026-11-26, version 3: quest Task 3 instruction fixed (it mixed "open the brackets" grammar with fact/opinion); first sentence is now "Thousands of tourists visit Astana every year."
- 2026-11-26, version 4: on-page edit mode removed at her request: no "Edit page", "Upload photo", "Change photo" buttons, no empty "📷" photo boxes. Empty photo spots are now invisible.
- 2026-11-26, version 5: task 9 now shows the full questionnaire (10 questions with options, read from the public form). Task 10 rewritten: result chart + analysis for each of the 10 questions, then an overview of 164 words. Reflections r9 and r10 rewritten to match. The old task 10 text about leadership tests was removed.
- 2026-11-26, version 6: "My reflection" removed from task 10 at her request.
- 2026-11-26, versions 7-9: added page "Criteria of assessment of portfolio" (#criteria) with her criteria table (Gained column left empty for the examiner), linked from the menu, the contents and task 10. The artifact is now shared as "Anyone with the link".
- 2026-11-26, version 10: criteria link removed from the Contents list on the home page at her request (still in the menu and after task 10). Do not add it back to Contents.
- 2026-11-26, version 11: criteria page removed completely at her request (she sent the criteria to check the site against, not to publish). Fixes from that check: quest Task 1 "Picture puzzle" had no pictures, now "Guess the place" with four text clues (Eiffel Tower, Colosseum, Baiterek, Mount Fuji, matching the four cities of Task 4) and an answer; task 8 lead no longer promises proof screenshots; home intro says tasks 1-9 have reflections (task 10 has none).
- 2026-11-26, version 12: all reflections removed; task 2 rebuilt (stages, notes, roles, phrases, illustration); task 3 got a drawn cover and verified links, Task 3 statements and Task 5 cards now copied exactly from Education.com and Wordwall, answers added for tasks 2 and 3; task 5 rebuilt on English Plus 6 page 34 with proof image; task 8 now has a students test (4-H) and a teachers test (AIR), statements copied exactly (the old page had paraphrased woorise statements). Photos IMG_3253 (profile + interviewer) and IMG_2948 (teacher) were mentioned but not attached.
- 2026-11-27, version 13: her selfie on the home page and as the interviewer, the teacher photo in the interview and as the Telegram avatar.
