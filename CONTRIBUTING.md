# Contributing to grug-group420

Welcome! We're glad you want to contribute. Here's the grug way to do it.

## 🦴 The Grug Contribution Philosophy

1. **Keep it simple** - No over-engineering
2. **Small PRs** - One thing at a time
3. **Ship fast** - Don't overthink it
4. **Delete > Add** - Less code is better

## 🚀 Quick Start

```bash
# 1. Fork the repo
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME

# 3. Create a branch
git checkout -b feature/your-feature

# 4. Make changes (keep them small!)

# 5. Test locally
bun run serve  # for grugbot-server
# or just open index.html for portal

# 6. Commit
git add .
git commit -m "feat: add thing"

# 7. Push and PR
git push origin feature/your-feature
```

## 📝 Commit Messages

Keep them simple:

```
feat: add new command
fix: typo in wisdom
docs: update readme
style: fix spacing
```

## ✅ PR Checklist

Before submitting:

- [ ] Code is simple (grug can understand)
- [ ] No unnecessary dependencies added
- [ ] Works locally
- [ ] PR is small (< 200 lines ideal)

## 🎯 Good First Issues

Look for issues labeled `good first issue` or `help wanted`.

Ideas for contributions:
- Add new grugbot commands
- Improve portal design
- Fix typos in docs
- Add more grug wisdom

## 🤝 Code of Conduct

Be nice. Ship code. Don't add complexity.

## 📦 Project Structure

```
grug-group420/
├── .github/          # Org profile and templates
├── portal/           # Website (HTML/CSS/JS)
├── grugbot-server/   # Bun.js server + CLI
├── grug-cli/         # CLI tools
└── grug-templates/   # Starter templates
```

## ❓ Questions?

Open an issue. We'll help.

---

🦴 **Remember: Complexity is the enemy. Ship simple code.**
