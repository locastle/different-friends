# Contributing

Thanks for helping improve this textbook.

## Ground Rules

1. **Never push directly to `main`.** Even the owner can't — branch protection enforces it.
2. All changes go through a Pull Request from `develop` (or a feature branch) to `main`.
3. PRs need **1 approval** before they can merge.
4. No force-pushes to `main`, ever.

## How to Contribute

```bash
git checkout develop
git pull
git checkout -b feature/<short-description>
# make your changes
git add -A && git commit -m "<what & why>"
git push origin feature/<short-description>
```

Then on GitHub: **Compare & pull request** → base: `main`, compare: `feature/<short-description>`.

## Things to avoid

- Pushing binary files (audio, video) larger than 5 MB without discussion
- Renaming `images/page_*.jpg` — these filenames are referenced from the HTML
- Changing the visible URL structure without coordinating with the README
