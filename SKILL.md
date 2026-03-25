# Review Code Tile

Review code for maintainability improvements and best practices.

## Usage

```
/review-code
```

Specify scope or reviews entire codebase.

## Scope Options

| Scope | Example |
|-------|---------|
| Recent changes | `git diff main`, specific PR |
| Directory | `src/services/` |
| File | Single file deep-dive |
| Pattern | "error handling", "duplication" |

## Process

1. Analyse scope for issues
2. Rate each finding by impact (1-10)
3. Output findings with recommendations
4. Skip findings rated below 4

## What It Looks For

- Simplification opportunities
- Code duplication
- Dead code
- Readability issues
- Complexity that could be reduced

## Example Invocations

- "Review code in src/auth/ for maintainability"
- "Review recent changes on this branch"
- "Review error handling patterns"
- "Deep review of utils.ts"

## Related

- `/review-naming` - Review naming clarity
- `/review-performance` - Review performance
- `/review-tests` - Review test coverage
