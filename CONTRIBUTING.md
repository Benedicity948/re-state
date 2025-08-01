# 🤝 Contributing to Awesome Homes

We're thrilled you're interested in making **Awesome Homes** even better! Whether you're fixing bugs, improving the UI, adding features, or helping with documentation, your contributions are **highly valued** and **greatly appreciated**.

This guide walks you through how to get started, submit changes, and collaborate with the team.

---

## 🌱 How to Contribute

### 1. Fork the Repository

Click the **"Fork"** button at the top-right of the [GitHub repository](https://github.com/Benedicity948/re-state.git) to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/Benedicity948/re-state.git
cd awesome-homes
```

### 3. Create a Feature Branch

Use a descriptive name for your branch:

```bash
git checkout -b feature/add-dark-mode-toggle
# or
git checkout -b bugfix/fix-image-loading-error
```

### 4. Make Your Changes

- Follow the existing code style.
- Write clear, concise commits.
- Test your changes thoroughly.

### 5. Commit Your Changes

Use meaningful commit messages:

```bash
git commit - "feat: add dark mode toggle in settings"
```

I will follow [Conventional_Commits] where possible:

- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documenting
- `style:` for formatting
- `refactor:` for code restructuring
- `test:` for adding tests
- `chore:` for maintenance

### 6. Push to Your Branch

```bash
git push origin feature/add-dark-mode-toggle
```

### 7. Open a Pull Request(PR)

- Go to the [Awesome_Homes_Github_page](https://github.com/Benedicity948/re-state.git).
- Click **"Compare & pull request"**.
- Fill out the PR template (see below)
- Submit and wait for review!
  > 💡 Please **link related issues** (e.g., `Closes #12`) in your PR description.

## 🐛 Reporting Bugs

Found a bug? We want to know!

1. **Check** if it’s already reported in [Issues](https://github.com/yourusername/awesome-homes/issues).
2. If not, open a new issue using the **"Bug Report"** template (if available).
3. Include the following details:
   - A **clear title** and **detailed description**
   - **Steps to reproduce** the issue
   - **Expected behavior** vs. **actual behavior**
   - **Screenshots or screen recordings** (if helpful)
   - Your **device model**, **OS version**, and **app version**

The more information you provide, the faster we can diagnose and fix the issue.

---

## 💡 Suggesting Features

Have an idea to improve the app? Share it!

1. Open a new issue using the **"Feature Request"** template.
2. Clearly describe:
   - **What** the feature is
   - **Why** it would benefit users
   - Any **design ideas** or **UX suggestions** (mockups welcome!)
3. We review all suggestions and tag them for future planning.

We may not implement every idea immediately, but we read and consider them all. Thank you for helping shape the future of Awesome Homes!

---

## 🧪 Testing

Before submitting a Pull Request (PR), please:

- Test your changes on **both iOS and Android** if possible.
- Ensure **no existing features are broken** (regression testing).
- Run the test suite:
  ```bash
  npm test
  ```
- **Add new unit or component tests** if you're introducing critical logic

We use [Jest] and [React_Native_Testing_Library] for testing.

## 📝 Code Style & Guidelines

To keep the codebase clean and consistent, please follow these practices:

- Use **ES6+ syntax** and modern React patterns (e.g., hooks, functional components).
- Follow **React Native best practices** for performance, accessibility, and responsiveness.
- Keep components **reusable**, **modular**, and **well-named**.
- Add **comments** for complex logic or non-obvious decisions.
- Avoid **hardcoded strings** — use localization-ready patterns (e.g., from a `strings.js` file or an i18n system).
- Respect the existing **file structure** and **naming conventions**.
- Code is formatted with **[Prettier](https://prettier.io)** and linted with **[ESLint](https://eslint.org)**.
  - Please run `npm run lint` before committing to catch formatting or syntax issues.

> 💡 **Consistency helps everyone collaborate more smoothly and reduces review time.**

---

## 🙌 Thank You!

Your time and effort help make **Awesome Homes** a better experience for everyone. 🏡  
We’ll do our best to review PRs quickly and provide clear, constructive feedback.

✨ _Together, we’re building the future of home discovery._ ✨
