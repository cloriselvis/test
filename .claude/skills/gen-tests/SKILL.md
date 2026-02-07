---
name: gen-tests
description: Generate unit tests for the specified code
argument-hint: [file-or-function]
---

Generate unit tests for the specified file or function. Follow these guidelines:

1. Use the testing framework already configured in the project (fall back to common defaults for the language)
2. Cover happy path, edge cases, and error cases
3. Use descriptive test names that explain the expected behavior
4. Keep tests focused — one assertion per logical concept
