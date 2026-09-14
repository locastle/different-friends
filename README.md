# Different Friends — Unit 1 Clickable Textbook

A static clickable English textbook ("可点读课本") for PEP Grade 5, Unit 1 *Different Friends*.

🔗 Live site: https://locastle.github.io/different-friends/

## Project Structure

```
.
├── index.html                        ← home page (双栏: 课本原页 + 可点读)
├── Unit1_Different_friends_点读版.html ← textbook reader
└── images/                           ← textbook page scans (page_07.jpg ... page_18.jpg)
```

## Branch Workflow

| Branch  | Who can push       | How changes get in                |
|---------|--------------------|-----------------------------------|
| `main`  | only `locastle`    | Pull Request + 1 approval         |
| `develop` | any collaborator  | direct push                       |

### Standard flow for a contributor

```bash
git clone https://github.com/locastle/different-friends.git
cd different-friends
git checkout develop
git checkout -b feature/my-change

# edit files...
git add -A
git commit -m "describe what you changed"
git push origin feature/my-change

# then open a Pull Request on GitHub: feature/my-change -> main
# wait for review, then merge
```

### Direct push to `main` is blocked
Even the repo owner cannot force-push or delete `main`. Every change must go through a Pull Request with at least one approval.

## Hosting

Hosted via **GitHub Pages** (legacy build, HTTPS enforced). Any push to `main` triggers a rebuild (~30s).

## License

Personal project — not for redistribution without permission.
