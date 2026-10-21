# 2026_git_course

A deliberately imperfect analysis repo, for the **Version control in GitHub** session
of the ICR Reproducible Software Development course.

Fork it, break it, fix it. Your fork is yours to keep.

## What's in here

```
analysis/expression.py   a small differential-expression script, with problems
data/                    synthetic counts + clinical tables (not real data)
tests/                   one test, which currently fails
CHEATSHEET.md            every git command from the session
```

**Slides:** [slides URL] · **Cheat sheet:** [CHEATSHEET.md](CHEATSHEET.md)

## Getting started

```bash
git clone git@github.com:YOUR-USERNAME/2026_git_course.git
cd 2026_git_course
pip install -r requirements.txt
python analysis/expression.py
```

It will not work first time. **That is the point** — issue #1 is about exactly that.

## How to take part

1. Pick an issue from the [Issues tab](../../issues) and assign it to yourself.
   - New to git? Look for `good first issue`.
   - Comfortable already? Look for `stretch`.
2. Make a branch, fix it, push, open a pull request with `Closes #N` in the body.
3. Review your partner's pull request — at least one line comment and one
   suggested change.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the details.

## The rule

Never commit data or credentials. The files in `data/` are synthetic and exist only
so the script has something to read.
