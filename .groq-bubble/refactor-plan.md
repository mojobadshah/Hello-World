# Groq Public Poly Auto-Fork Refactor Plan

- Source repo: `octocat/Hello-World`
- Target repo: `mojobadshah/Hello-World`
- Branch: `groq-poly-refactor-hello-world-2026-04-25t19-41-40-449z`
- Risk: `medium`
- Safe apply mode: `true`

## Important

AI-generated code changes are staged under `groq-bubble-safe-changes/` instead of being written directly to arbitrary repository paths.
This prevents GitHub 409 path conflicts and blocks unsafe writes like `.env`.

## Original Plan

{
  "summary": "Polyrepo refactor: Add demo and workflow changes",
  "risk": "low",
  "planMarkdown": "### Safe Polyrepo Refactor Plan
This refactor aims to add demo and workflow changes while preserving behavior and excluding secrets.

#### Changes:

1. **Create new file:** `docs/README.md`
   ```markdown
# Demo Documentation
This is a demo repository.
```
2. **Update existing file:** `docs/demo/index.js`
   ```javascript
// Add demo functionality
const demo = () => {
  console.log('Demo running');
};
demo();
```
3. **Create new file:** `demo/staging/index.html`
   ```html
<!DOCTYPE html>
<html>
<head>
  <title>Staging Demo</title>
</head>
<body>
  <h1>Staging Demo</h1>
</body>
</html>
```
4. **Create new file:** `docs/workflow/README.md`
   ```markdown
# Workflow Documentation
This is a workflow repository.
```
5. **Update existing file:** `static/css/styles.css`
   ```css
body {
  background-color: #f2f2f2;
}
```
6. **Update existing file:** `static/js/main.js`
   ```javascript
// Add minimal frontend staging demo
const demo = () => {
  document.getElementById('demo').innerHTML = 'Minimal Demo Running';
};
demo();
```
7. **Create new file:** `staging/index.js`
   ```javascript
// Minimal staging demo
const demo = () => {
  console.log('Minimal Demo running');
};
demo();
```
8. **Create new file:** `staging/server.js`
   ```javascript
// Set up a minimal server
const http = require('http');
http.createServer((req, res) => {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Minimal server running\n');
}).listen(3000, 'localhost');
``"
,
  "changes": [
    {
      "path": "docs/README.md",
      "action": "create",
      "reason": "Add documentation for the demo repository",
      "content": "# Demo Documentation\\nThis is a demo repository."
    },
    {
      "path": "docs/demo/index.js",
      "action": "update",
      "reason": "Add demo functionality",
      "content": "// Add demo functionality\\ncost demo = () => {\\n  console.log('Demo running

## Staged AI Changes

- No AI code changes staged.

