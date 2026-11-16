# Lantern Notes search checklist

This fixture is fictional. The text exercise lets you work out an expected result before checking a running application.

| Note title | Tag |
| --- | --- |
| Release notes | Work |
| Weekend plans | Personal |

## First check — a query with no matches

1. Use the title query `archive` with no tag filter selected.
2. Compare the query against both titles in the fixture. The expected result is zero matches.
3. In a running implementation, enter the same query. Expect the search view to display its empty-results state and leave the notes intact.
4. Record what you actually observed using the fields below.

```text
Check: Empty title search results
Scope: Fixture review or running application
Input: archive; no tag filter
Expected: Zero matches; application shows its empty-results state
Actual:
Evidence:
Follow-up:
```

## Remaining application checks

- [ ] Verify the empty-results state in a running application.
- [ ] Check combined title and tag filters once tag case sensitivity is decided.
- [ ] Check keyboard navigation through search results.

Use the [handoff](../HANDOFF.md) for the reason this check was chosen and the [status snapshot](../PROJECT_STATUS.md) for the current blocker and pending work.
