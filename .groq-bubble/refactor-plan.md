# Groq Polyrepo Refactor Plan

- Model: `llama-3.1-8b-instant`
- Source: `octocat/Hello-World`
- Target fork: `mojobadshah/Hello-World`
- Base branch: `master`
- Review branch: `groq-poly-refactor-hello-world-2026-04-26t02-45-23-652z`
- Safe apply mode: `true`
- Risk: `low`

## Safe Refactor Plan

### Step 1: Authentication
 Authenticate GitHub using a secure credentials mechanism.

### Step 2: Find Best Writable Repo
Use an existing GitHub repository as the base for refactoring.

### Step 3: Accept Repo URLs
Enter or provide one or more GitHub repository URLs for refactoring.

### Step 4: Forking
Fork repositories into the configured owner when necessary.

### Step 5: Sample Text-File Scan
Scan a small, safe text-file sample from each repository.

### Step 6: Wait for Groq Token/Reset Window
Wait for the Groq token/reset window before planning each repository.

### Step 7: Refactor Plan Generation
Use the Groq API to create a strict JSON refactor plan.

### Step 8: Apply Refactor Changes
Safely apply generated changes into groq-bubble-safe-changes/*.

### Step 9: Minimal Frontend Demo
Always create a minimal frontend demo.

### Step 10: No Secret Commit
Never commit secrets or credentials.

## Safe apply behavior

Generated code/content proposals are written to `groq-bubble-safe-changes/*` so existing repository paths are not overwritten.