## Engineering Journal — Week 3

*16–22 November 2026 · A3 Types & Data Modelling · Sprint 2*

**Learned**
  - The Monday port, with your "Coming from Java, I'd have…" lines, and Tuesday's typing line. I can't quote those exactly from here, so take them from what you wrote those days.
  - Protocol vs a Java interface, TypedDict, `--strict`.
  - Dataclass vs Pydantic: data your own code builds and trusts vs data that arrives from outside.

**Built**
- both models, the tests, the docstrings, the README section, `mypy --strict` clean, PR #2 merged, `v0.2.0`.

**Problem**
- Saturday's first `Book` commit was stopped by the `ruff-format` hook.

**Solution**
- `git diff` to see what ruff changed, `git add`, then the same commit again.

**Next week**
 - `@timed` decorator + tests.
 - Context manager for resource handling + tests.
 - Streaming Gutenberg parser against the three fixtures.
