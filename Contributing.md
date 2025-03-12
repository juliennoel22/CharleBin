# Contributing

Thank you for your interest in improving CharleBin! This guide will help you contribute effectively to the project.

---

## 📌 General Guidelines

- **Clean and clear code**: Use well-structured code in English and follow project conventions.
- **One PR = One change**: Avoid pull requests (PRs) that modify multiple features at once.
- **Test before submitting**: Ensure your changes work locally before opening a PR.
- **Relevant comments**: Only comment on non-obvious parts of the code.
- **No dead code or debug logs**.

---

## ❓ Asking Questions

Before asking a question:
1. Check the **documentation** and **existing issues**.
2. Search through **open and closed PRs**.
3. If no relevant answer is found, open a **clear and concise issue**.

---

## 📝 Opening an Issue

When opening an issue:
- **Clearly describe** the problem or requested feature.
- Provide **steps to reproduce** if it’s a bug.
- Suggest a **potential solution** if possible.

---

## 🚀 Pull Request (PR) Process

### 1️⃣ Preparation
- Ensure you are on the `main` branch:
  ```sh
  git checkout main
  ```

- Create a new branch for your feature:
  ```sh
  git switch -c feature-name
  ```
### 2️⃣ Development

Add your changes and commit with a clear message:
```sh
git add .
git commit -m "Short description of the change"
```

Push your branch:
```sh
git push -u origin feature-name
```

### 3️⃣ Creating the PR

On GitHub, open a Pull Request with:
- A clear title (e.g., "Add dynamic expiration option").
- A detailed description of the change.
- A link to a related issue if applicable.
- A screenshot or demo if relevant.

### ✅ PR Acceptance Criteria

- The code is functional and tested.
- There are no conflicts with `main`.
- The PR follows the project structure and does not contain unnecessary code.
- The changes are understandable and properly documented.

### 🔍 Code Review and Merge

- A team member will review the PR.
- Suggestions may be requested.
- Once approved, the PR will be merged into `main`.

---

> **Note**
> You can use [``PullRequest-Template.md``](./PullRequest-Template.md) as a template for your PRs.

Thank you for contributing! 🚀