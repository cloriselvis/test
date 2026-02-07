---
name: review-code
description: Review code for bugs, style issues, and improvements
argument-hint: [file-or-directory]
---

Review the specified code (or the most recently changed files if none specified). For each file:

1. Check for bugs and logic errors
2. Check for security vulnerabilities
3. Evaluate readability and naming
4. Suggest concrete improvements

Output a summary grouped by severity: critical, warning, suggestion.
