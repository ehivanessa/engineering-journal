## Engineering Journal — Week 2

*9–15 November 2026 · A2 Python Idioms for a Java Engineer · Sprint 1*

**Learned**
- the Python data model PEP8

**Built**
- README for asofar, merged through my first PR (feature branch, squash)
- LICENSE, PR template and a GitHub Actions workflow (ruff, mypy, pytest)
- a ruleset on main: PR required, the `check` required, no force pushes
- tagged v0.1.0

**Problem**
My first GitHub Actions run got stuck in Queued and could not be cancelled.

**Solution**
The workflow file passed actionlint and the Actions settings were fine. The next two runs (the PR and main) went green in about 15 seconds each. Run #1 is still stuck in Queued; it looks like a GitHub-side problem and it blocks nothing.

**Next week**
- Mon: the Java → Python port, literal then idiomatic (carried over: the Thursday exercise was too big and I was tired, so I cut it down)
- Tue/Thu: types: generics, Protocol, mypy --strict, Pydantic vs dataclass
- Sat/Sun: mypy --strict clean, then the Book and TextUnit models with a test for bad input
