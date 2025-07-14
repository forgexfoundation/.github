# 🤝 Contributing to ForgeX Foundation

Welcome, and thank you for considering contributing to **ForgeX Foundation**!  
We're a developer-first, non-profit initiative committed to open collaboration, innovation, and community empowerment through open-source software and events.

This guide will walk you through how to contribute effectively and respectfully to our projects.

---

## 🌟 How You Can Contribute

Whether you're technical or non-technical, there's a place for you.

### 🧑‍💻 Developers
- Bug fixes and improvements
- New features
- Refactoring and performance enhancements
- Writing or improving documentation

### 🎨 Designers
- UI/UX mockups
- Event graphics or social media assets
- Brand consistency suggestions

### 📚 Writers
- Blog posts and announcements
- Technical documentation
- Tutorials and how-to guides

### 📢 Community Members
- Event volunteering and planning
- Partnership introductions
- Outreach, social media help, or Discord moderation

---

## 🧭 Contribution Workflow

### 1. Fork the repository
Click the "Fork" button at the top of this repo to create your own copy.

### 2. Clone your fork locally
```bash
git clone https://github.com/your-username/forgex-foundation.git
cd forgex-foundation
```

### 3. Create a new branch
Use the following naming convention:
```bash
git checkout -b type/short-description
```
**Examples:**
- `fix/typo-in-readme`
- `feat/add-contribution-guide`
- `refactor/navbar-layout`

### 4. Make your changes
Edit the files or add new ones as needed. Be sure to follow the project’s structure and code style.

### 5. Commit your changes
Use clear and conventional commit messages:
```bash
git add .
git commit -m "feat: add community events section to homepage"
```

> ✅ We use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)  
> Example prefixes: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`

### 6. Push to your fork
```bash
git push origin your-branch-name
```

### 7. Open a Pull Request
- Go to the original ForgeX repository on GitHub
- Click "Compare & Pull Request"
- Fill out the PR template explaining **what**, **why**, and **how**
- Reference any related issue using `Closes #issue_number`

---

## 🌳 Branching Strategy

- `main` – Stable, production-ready code
- `dev` – Actively developed features and bug fixes
- `feature/xyz`, `fix/xyz` – Feature branches or fixes created off `dev`

> Please open your pull requests **against the `dev` branch**, not `main`.

---

## 📂 Project Structure (example)

```
forgex-foundation/
├── docs/                # Documentation and guides
├── src/                 # Core source code
├── public/              # Static assets
├── scripts/             # Dev/CI/CD scripts
├── events/              # Event resources
├── .github/             # PR templates, workflows
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── README.md
```

---

## 🧪 Testing (if applicable)

Before submitting, ensure:
- No linter or formatting errors (`npm run lint`, `pnpm format`)
- Tests (if present) pass: `npm test` or `pnpm test`

---

## 📋 Reporting Issues

Found a bug? Have an idea for improvement?  
Please check existing [issues](https://github.com/ForgeXFoundation/issues) first, then open a new one if needed.

Use the right labels:  
- `bug` – unexpected behavior  
- `feature` – feature requests  
- `question` – general questions  
- `good first issue` – beginner-friendly tasks

---

## 🛡 Code of Conduct

We’re committed to a safe and inclusive community. By participating, you agree to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## 🧵 Communication

- 🧑‍🚀 **Discord** – [Link here]  
- 🐦 **Twitter** – [@ForgeXFoundation](https://twitter.com/forgexorg)  
- 🌐 **Website** – [forgexfoundation](https://forgexfoundation.vercel.app/)

Join the conversation, ask questions, and get feedback.

---

## ❤️ Thank You

Your contribution matters. Every issue opened, line of code committed, or event supported helps us build a better developer-first future — together.

**Forge. Collaborate. Inspire.**  
– The ForgeX Foundation Team
