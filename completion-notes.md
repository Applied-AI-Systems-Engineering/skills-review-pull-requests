# Review pull requests — verified course completion

This repository is an attributed copy of [GitHub Skills Review pull requests](https://github.com/skills/review-pull-requests). Instructor [MIT license](LICENSE) is preserved. The game and proposed changes are instructor-provided course practice, not an original showcase.

Completed 2026-10-13 using GitHub connectors for repository operations and the supervising agent using GitHub UI for actual suggestion application. No local files, new secrets, or accounts were used by the learner worker.

## Verified evidence

- [PR #2](https://github.com/Khemology/skills-review-pull-requests/pull/2) was created from instructor branch `update-game` into `main`, with the instructed title and description.
- Khemology was added as assignee; the teacher advanced after assignment. An assignee identifies responsibility and is distinct from a requested reviewer.
- The diff was inspected: four game-over wording changes in `index.html`.
- A COMMENT review was submitted at instructor head `4534f01ffeeb94268b382a8873922d42584f3995`, review ID `5507594357`. Its body explicitly states that the same Khemology account authored the PR and submitted the course review. It is not approval or independent peer review.
- A second COMMENT review, ID `5507603092`, posted the [actual inline suggestion](https://github.com/Khemology/skills-review-pull-requests/pull/2#discussion_r4261999977) on RIGHT line 51 of `index.html`.
- The supervising agent clicked GitHub UI Apply suggestion / Commit changes with the instructed commit title `Make the end game experience more friendly`. This was actual suggestion application, not an equivalent file update. The resulting commit is `d5927459cf8f6969c6df70f1588d62ee9b8746de`.
- The learner independently fetched `index.html` from `update-game` and verified line 51 exactly matches the instructor suggestion. The resulting file blob SHA was `389795f12fb0d6db0cea52d8989ca4f049199cfa`.
- The suggestion thread `PRRT_kwDOVHV9XM6r_FuT` was read back resolved and outdated after application.
- After the teacher posted Step 5, PR #2 merged using expected head `d5927459cf8f6969c6df70f1588d62ee9b8746de`. Merge commit: `2b005a11e888f1b1e708631ab65849ba7f1f28f6`.
- [Teaching issue #1](https://github.com/Khemology/skills-review-pull-requests/issues/1) is closed with reason completed. [Instructor finish comment](https://github.com/Khemology/skills-review-pull-requests/issues/1#issuecomment-6151560684) confirms exercise completion.

## Scope and limits

This proves PR creation, assignment, COMMENT review, inline suggested change, actual GitHub suggestion application, resolved-thread readback, and merge mechanics. No self-approval was attempted. Using one account for authoring and COMMENT reviews does not demonstrate independent human peer review or an approval gate.

Gameplay was not run. The static heading changed by the suggestion is overwritten by the existing endGame JavaScript messages during gameplay; no runtime user-experience improvement is claimed. No PR-triggered runtime workflows were returned for the suggestion commit. Instructor teaching workflow completion is separate from application validation. Existing automatic Codex reviews are separate from these course COMMENT reviews and no completed security-review claim is made.

Next suggested exercise: [Create and use reusable workflows](https://github.com/skills/reusable-workflows), in its own attributed training repository.
