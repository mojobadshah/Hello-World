/*
Model: llama-3.1-8b-instant
Original desired path: docs/README.md
Action: create
Reason: Initial README documentation
Safe apply mode: proposed content only; not written to original path.
*/

Octocat/Hello-World GitHub polyrepo refactor
==========================

This repository serves as a safe example for refactoring multiple GitHub repositories.

## Refactoring Flow

1. Authenticate GitHub.
2. Find the best writable repository.
3. Accept one or more GitHub repository URLs.
4. Fork repositories when necessary.
5. Scan a small text-file sample from each repository.
6. Wait for the Groq token/reset window.
7. Generate a strict JSON refactor plan using the Groq API.
8. Safely apply generated changes.
9. Create a minimal frontend demo.
10. Never commit secrets.