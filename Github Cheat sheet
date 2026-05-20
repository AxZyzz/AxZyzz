# GitHub Cheat Sheet 2026

The Complete GitHub Productivity, Development & Automation Reference

> Build faster. Collaborate smarter. Automate everything.

---

## 1. Essential Keyboard Shortcuts (Web)

| Action              | Shortcut   |
| ------------------- | ---------- |
| Command Palette     | `Ctrl + K` |
| Go to Issues        | `g i`      |
| Go to Pull Requests | `g p`      |
| Go to Actions       | `g a`      |
| Go to Code          | `g c`      |
| Search Repository   | `/`        |
| Open File Finder    | `t`        |
| New Issue           | `c`        |
| Toggle File Tree    | `[`        |
| Copy Permalink      | `y`        |

Tip: Press `?` anywhere on GitHub to open the full shortcut list.

---

## 2. GitHub CLI (gh) — Must Know Commands

### Authentication

```bash
gh auth login
gh auth status
```

### Repository Commands

```bash
gh repo create
gh repo clone owner/repo
gh repo view
```

### Pull Requests

```bash
gh pr create
gh pr list
gh pr checkout 12
gh pr merge
```

### Issues

```bash
gh issue list
gh issue create
gh issue view 10
```

### Actions

```bash
gh workflow list
gh run list
gh run view
```

Install:

```bash
brew install gh
```

---

## 3. Git Workflow Essentials

### Daily Workflow

```bash
git status
git add .
git commit -m "message"
git push
git pull --rebase
```

### Branching

```bash
git switch -c feature/login
git switch main
git merge feature/login
```

### Undo & Restore

```bash
git restore .
git reset --hard HEAD~1
git revert <commit>
```

---

## 4. GitHub Actions (CI/CD)

### Example Workflow

```yaml
name: CI

on:
  push:
    branches: [ main ]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4

      - uses: actions/setup-node@v4
        with:
          node-version: 20

      - run: npm install
      - run: npm run build
```

### Useful Commands

```bash
gh workflow list
gh run list
gh run view
gh run rerun <id>
```

---

## 5. Pull Request Workflow

### Standard Flow

1. Create Branch
2. Commit Changes
3. Push Branch
4. Open Pull Request
5. Request Review
6. Merge

### Best Practices

* Small focused PRs
* Clear descriptions
* Link issues
* Use draft PRs
* Keep PRs updated
* Request reviews early

---

## 6. GitHub Projects & Organization

### GitHub Projects

* Table View
* Board View
* Roadmap
* Sprint Planning
* Automations
* Issue Tracking

### Organization Tools

* Teams & Permissions
* Repository Policies
* Security Insights
* Rulesets
* Branch Protection

---

## 7. GitHub Packages & Registry

### Package Registries

* Docker (GHCR)
* npm
* Maven
* NuGet
* RubyGems

### Docker Example

```bash
docker login ghcr.io

docker push ghcr.io/user/app:latest
```

---

## 8. GitHub Copilot & AI Tools

### Copilot Shortcuts

| Action              | Shortcut   |
| ------------------- | ---------- |
| Accept Suggestion   | `Tab`      |
| Dismiss Suggestion  | `Esc`      |
| Next Suggestion     | `Alt + ]`  |
| Previous Suggestion | `Alt + [`  |
| Open Copilot Chat   | `Ctrl + I` |

### AI Features

* Copilot Chat
* Copilot Edits
* AI Refactoring
* Test Generation
* Documentation Generation
* GitHub Models

---

## 9. Security & Dependabot

### Security Features

* Dependabot Alerts
* Secret Scanning
* Push Protection
* Branch Protection
* Code Scanning

### Useful Commands

```bash
gh secret list
gh secret set API_KEY
```

Best Practice:

* Enable 2FA
* Use branch protection
* Rotate secrets regularly

---

## 10. Useful Links & Resources

* GitHub Docs
  https://docs.github.com

* GitHub CLI Docs
  https://cli.github.com

* GitHub Actions Docs
  https://docs.github.com/actions

* GitHub Skills
  https://skills.github.com

* GitHub Status
  https://www.githubstatus.com

---

# Pro Tips

* Use Pull Requests for every major change
* Automate repetitive tasks with Actions
* Use GitHub Projects for planning
* Learn GitHub CLI for speed
* Use Copilot to accelerate development
* Keep repositories documented

---

# Follow Me on GitHub ⭐

If this helped you, star my README and follow my work:

https://github.com/AxZyzz

Repository:
AxZyzz/AxZyzz

---

Build better. Ship faster. 🚀

