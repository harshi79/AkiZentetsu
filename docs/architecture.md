# Proposed architecture

This is a design sketch; no service is implemented yet.

- A GitHub integration would fetch authorized repository and contribution data.
- A recommendation component would rank candidate issues and preserve an explanation for each suggestion.
- A co-author component would prepare changes only after explicit approval.
- A user interface would show suggestions, evidence, and uncertain achievement estimates.

Keep GitHub write permissions separate from read-only discovery where possible.
