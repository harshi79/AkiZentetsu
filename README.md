# AkiZentetsu

A GitHub achievement coach concept: help people discover meaningful open-source contributions while working toward GitHub profile achievements.

## Idea

- Suggest issues that match a contributor's interests and experience.
- Help plan, implement, and review contributions as a co-author, with the contributor in control.
- Track contribution milestones without promising that GitHub will award an achievement.

The goal is useful contributions, not artificial activity or badge farming.

> This project is at the idea stage; these features are not implemented yet.

## Design notes

### Contributor experience

1. Let contributors select languages they want to practice.
2. Let contributors select topics they care about.
3. Allow contributors to set a weekly time budget.
4. Show why each suggested issue matches their preferences.
5. Distinguish a first contribution from a familiar-repository task.
6. Offer a way to save an issue for later.
7. Allow dismissing a suggestion without posting on GitHub.
8. Keep the contributor in control of all public interactions.
9. Make next steps understandable without achievement jargon.
10. Ask for feedback when a suggestion is not useful.

### Issue discovery

11. Prefer issues with a clear description and acceptance criteria.
12. Check whether the repository has contribution instructions.
13. Consider whether maintainers have responded recently.
14. Avoid recommending issues already assigned to someone else.
15. Flag issues with unclear scope rather than guessing.
16. Show the date when issue information was last refreshed.
17. Distinguish labels from verified issue difficulty.
18. Offer documentation tasks alongside code tasks.
19. Explain when a repository requires prior discussion.
20. Provide a direct link to the original issue.

### Planning

21. Summarize the requested change before suggesting an approach.
22. Identify open questions before proposing implementation.
23. Suggest a small first step for large tasks.
24. List likely files only after inspecting the repository.
25. Separate requirements from assumptions in a proposed plan.
26. Include expected checks in the plan.
27. Explain when a plan depends on maintainer input.
28. Let the contributor edit the plan before proceeding.
29. Record decisions made during a collaboration.
30. Keep plans short enough to review.

### Co-authoring

31. Ask before making changes to contributor-owned branches.
32. Prefer focused patches over unrelated refactors.
33. Explain the reason for each proposed change.
34. Preserve existing project style where practical.
35. Run relevant checks before suggesting a PR.
36. Report failed checks without hiding them.
37. Identify any code produced by the assistant.
38. Let the contributor review a diff before submission.
39. Never claim that a human wrote assistant-generated code.
40. Do not merge a contribution without explicit authorization.

### Review

41. Review changes against the original issue.
42. Point to specific lines when raising a concern.
43. Separate verified bugs from possible risks.
44. Prefer actionable suggestions over generic praise.
45. Check whether tests cover the changed behavior.
46. Acknowledge when a concern cannot be reproduced.
47. Avoid posting duplicate review comments.
48. Respect the repository’s review etiquette.
