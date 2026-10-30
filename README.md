# ai-study-prompts

81 field-specific AI study guides for 26 school tracks plus general college study. Each one gives
you a study workflow, a prompt to try, where answers in that field usually go wrong, and how to check what the AI
says. They are written for students who want AI to quiz them, not to do the work for them.

The method in one line: **answer first, let the AI challenge you, then check against your source.**

## Start with one complete example

[Try the first-session walkthrough](guides/first-session.md): fictional notes, a copyable quiz prompt, a worked answer and a source check. No installation required.

[Watch the 25-second Ace notes and flashcards demonstration](guides/ace-notes-review.md). The recording shows the product interface; the study exercise works in any assistant.

## Fields

| Field | Study areas | Subject guides |
| --- | --- | --- |
| [Medical school](fields/medical-school.md) | USMLE Step 1 and Step 2 CK | USMLE Step 1 AI tutor · USMLE Step 2 CK AI tutor |
| [Law school](fields/law-school.md) | bar exam, UBE and MPRE | AI for law case briefs · Bar exam AI study tutor |
| [Dental school](fields/dental-school.md) | INBDE | INBDE AI study tutor · Dental anatomy AI tutor |
| [Pharmacy school](fields/pharmacy-school.md) | NAPLEX and MPJE | NAPLEX AI study tutor · Pharmacology AI tutor |
| [Veterinary school](fields/veterinary-school.md) | NAVLE | NAVLE AI study tutor · Veterinary anatomy AI tutor |
| [Nursing school](fields/nursing-school.md) | NCLEX-RN and nursing exams | NCLEX AI study help · AI for nursing care plan study |
| [Physician assistant school](fields/physician-assistant-school.md) | PANCE and rotation exams | PANCE AI study tutor · AI for PA clinical rotations |
| [Optometry school](fields/optometry-school.md) | NBEO | NBEO AI study tutor · Optometry optics AI tutor |
| [Physical therapy school](fields/physical-therapy-school.md) | NPTE | NPTE AI study tutor · Physical therapy anatomy AI tutor |
| [Occupational therapy school](fields/occupational-therapy-school.md) | NBCOT | NBCOT AI study tutor · OT activity analysis AI tutor |
| [Podiatry school](fields/podiatry-school.md) | APMLE | APMLE AI study tutor · Podiatry biomechanics AI tutor |
| [Chiropractic school](fields/chiropractic-school.md) | NBCE | NBCE AI study tutor · Spinal anatomy AI tutor |
| [Public health school](fields/public-health-school.md) | CPH and comprehensive exams | Epidemiology AI tutor · Biostatistics AI tutor |
| [Speech and audiology school](fields/speech-and-audiology-school.md) | Praxis | Speech pathology AI tutor · Audiology AI tutor |
| [Business school](fields/business-school.md) | MBA coursework and GMAT preparation | AI for MBA case analysis · GMAT quantitative AI tutor |
| [Graduate school](fields/graduate-school.md) | qualifying exams and thesis defense | AI for reading research papers · AI for qualifying exam study |
| [Social work school](fields/social-work-school.md) | ASWB | ASWB AI study tutor · Social work ethics AI tutor |
| [Teacher education](fields/teacher-education.md) | Praxis and teaching exams | Praxis AI study tutor · AI for lesson plan study |
| [Psychology school](fields/psychology-school.md) | EPPP and counseling exams | EPPP AI study tutor · Counseling theory AI tutor |
| [Accounting school](fields/accounting-school.md) | CPA: FAR, AUD, REG and discipline sections | CPA exam AI study tutor · AI for accounting journal entries |
| [Architecture school](fields/architecture-school.md) | ARE | ARE AI study tutor · AI for architecture design critique |
| [Engineering school](fields/engineering-school.md) | FE and PE | FE exam AI study tutor · PE exam AI study tutor |
| [Divinity and seminary](fields/divinity-school.md) | ordination and comprehensive exams | Theology AI study tutor · AI for scripture study |
| [Post-baccalaureate study](fields/post-baccalaureate.md) | MCAT and DAT preparation | MCAT AI study tutor · DAT AI study tutor |
| [Trades and technical school](fields/trade-school.md) | licensing and technical exams | HVAC school AI study tutor · Electrical trade school AI tutor |
| [Medical residency](fields/medical-residency.md) | USMLE Step 3, in-training and board study | AI for medical board study · AI for clinical case presentations |
| [College study](fields/college-students.md) | course exams | AI for college lecture notes · AI for college exam study |

## How to use them

1. Open your own course material: an assigned reading, a lecture or a fictional teaching case.
2. Paste the prompt into the AI assistant you use, with that material.
3. Answer before you read any feedback, out loud or in writing.
4. Check the feedback against your source, and ask your instructor about what still disagrees.

We wrote these for the school tracks in [Ace](https://tryacee.com/?utm_source=github&utm_medium=ai-study-prompts), our AI
assistant. They work in any assistant.

## Ground rules

- Use material you are allowed to use, and follow your course's policy on AI.
- Never trust an AI citation you have not read. AI can invent or misstate sources.
- Keep real patient, client and student information out of prompts.
- These are original study prompts, not official exam questions. Exam names identify study areas only; nothing here is
  affiliated with or endorsed by any exam provider.

## Use it as an agent skill

The repo is also a skill, `study-coach`, for Claude Code and Codex: the agent quizzes you one question at a time from
your own material, using the method for your field.

```bash
git clone https://github.com/mthburnsbarber-web/ai-study-prompts ~/.claude/skills/study-coach   # Claude Code
git clone https://github.com/mthburnsbarber-web/ai-study-prompts ~/.codex/skills/study-coach    # Codex
```

Then ask: "Quiz me on these lecture notes for pharmacology."

## Machine-readable

`prompts.json` holds every guide as a record: `field`, `kind` (`field` or `subject`), `title`, `method`,
`prompt`, `note`, `question` and a link to the full guide.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Share and adapt with credit: "AI study prompts by Black Label
Tec (newaionline.com)". The full guides live at [newaionline.com/schools](https://newaionline.com/schools?utm_source=github&utm_medium=ai-study-prompts).
