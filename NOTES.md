# Notes

## What this workspace is

Pre-seeded **fallback case study** for the "Fundamental CS for AI Era" demo at BUILD Camp (4 July 2026). If the room votes its own topic, `/teach` starts a fresh workspace live and this one stays untouched. If the room is shy, open this workspace and continue from lesson 1.

## Demo plan

1. Show `MISSION.md` and `RESOURCES.md` briefly — the workspace anatomy from the slides.
2. Walk the room through `lessons/0001-count-steps-not-seconds.html` (open locally with `open lessons/0001-count-steps-not-seconds.html`).
3. Run the lesson-1 quiz out loud; grade answers per QUIZ-FEEDBACK rules (scatter correct positions, no key leaks).
4. Build **lesson 2 live** from the wrong answers. Planned direction: best/worst/average case (slides 24–26), then Θ vs O vs Ω (slides 28–35).
5. Write the session's first learning record live only if the room demonstrates understanding — `learning-records/` is intentionally absent until earned.

## Teaching preferences

- Audience: mixed developers/non-developers, Indonesian; lessons in English matching the talk, Indonesian terms (mangkus, operasi khas) kept where they help.
- Quizzes are answered by the room, not by Zain. Zain only types.
- Do not edit generated lessons/questions during the demo (ground rule on the agenda slide).

## Working notes

- Quiz answer key, lesson 1 (teacher-only): Q1 = B, Q2 = A, Q3 = C.
- Source-deck erratum to mention if Ω comes up: slide 34 says "lebih kecil" where a lower bound needs "lebih besar" — nice live example of why understanding beats copying, and it's in Zain's own deck (recorded in RESOURCES.md).
- Candidate live experiment if the room wants empirical proof: a tiny script timing an O(n) vs O(n²) loop as n grows (listed as a gap in RESOURCES.md).
