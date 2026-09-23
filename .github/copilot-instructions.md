## Code style
- Prefer named exports over default exports.
- Async functions only — never use `.then()` chains.
- One assertion per test.

## Pull request etiquette
- Title format: `<area>: <imperative summary>` (e.g., `auth: rotate session token on login`).
- PR body must include a "Why" section before any "What" section.
- Link an issue or skip linking entirely — don't fake-link.

## Tools to avoid
- Do not call external network APIs unless explicitly listed in `.github/mcp-allowlist.yml`.