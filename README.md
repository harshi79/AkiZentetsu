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
49. Help respond to maintainer feedback constructively.
50. Keep the final decision with the human reviewer.

### Achievement information

51. Only GitHub can award GitHub profile achievements.
52. Display observed achievements separately from estimates.
53. Explain the evidence behind any progress estimate.
54. Allow for GitHub rules changing without notice.
55. Do not show a precise percentage when rules are unknown.
56. Avoid guaranteeing an achievement for a specific action.
57. Prefer contribution quality over badge speed.
58. Do not encourage self-interactions to inflate activity.
59. Identify which activity data is unavailable.
60. Show when achievement data was last checked.

### Trust and safety

61. Require consent before posting comments or opening PRs.
62. Use the least GitHub permissions needed for each feature.
63. Keep secrets out of logs and suggested patches.
64. Do not reveal private repository details in public output.
65. Offer a clear way to disconnect GitHub access.
66. Explain what data is retained and for how long.
67. Provide a path to delete stored account data.
68. Apply rate limits to automated GitHub actions.
69. Avoid unsolicited mentions of maintainers.
70. Respect repository rules about automated contributions.

### Accessibility

71. Use descriptive labels for controls.
72. Ensure keyboard access to the main workflow.
73. Do not communicate status using color alone.
74. Keep progress descriptions readable by screen readers.
75. Make external GitHub links recognizable.
76. Explain technical terms when first introduced.
77. Use concise error messages with recovery steps.
78. Allow users to pause notifications.
79. Keep recommendation reasons readable on small screens.
80. Test important flows without a mouse.

### Measurement

81. Measure whether recommendations are accepted or dismissed.
82. Track whether suggested issues remain available.
83. Collect feedback on recommendation quality.
84. Measure completed contributions without treating volume as quality.
85. Watch for accidental duplicate suggestions.
86. Review whether newcomers receive useful first tasks.
87. Check how often progress estimates are uncertain.
88. Monitor failed GitHub API calls.
89. Report aggregate metrics without exposing private activity.
90. Use feedback to revise ranking criteria.

### Delivery

91. Start with a read-only prototype.
92. Document required GitHub permissions before adding login.
93. Test recommendation ranking against sample issues.
94. Add integration tests before enabling write actions.
95. Provide a dry-run preview for proposed GitHub posts.
96. Make network failures recoverable.
97. Offer a changelog for user-visible behavior.
98. Document known limitations alongside each release.
