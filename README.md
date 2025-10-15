# ✍️ Commit Wizard — Raycast Extension

**Commit Wizard** is a Raycast extension that helps you craft clean, conventional Git commit messages quickly and with confidence.

## 🚀 Features

-   Enforces best practices for commit summaries:
    -   Imperative mood
    -   Capitalized
    -   Max 50 characters
    -   No trailing period
-   Optional body section with 72-character wrap guide
-   Requires at least one bullet point describing the change
-   Enforces `See #<issue-number>` format for referencing issues
-   Real-time preview of the final commit message
-   Copy to clipboard in one click

## 📦 Commit Format

```
<Capitalized imperative summary under 50 characters>

- Bullet point 1
- Bullet point 2

See #42
```

## 🛠 Tech Stack

-   [Raycast API](https://developers.raycast.com/)
-   React with TypeScript
-   Minimal dependencies

## 🧪 How to Use

1. Clone this repo:

    ```bash
    git clone https://github.com/juanmartinlopeze/commit-wizard.git
    cd commit-wizard
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run it locally in Raycast:
    ```bash
    ray run src/commit.tsx
    ```

## 📁 Project Structure

```
commit-wizard/
├── src/
│   └── commit.tsx        # The main command logic
|   └── pull-request.tsx
├── assets/               # Icons or visuals
├── raycast.json          # Raycast extension config
├── package.json          # Dependencies and scripts
├── tsconfig.json         # TypeScript config
└── README.md
```

## 📜 License

MIT — free to use, modify, or adapt.

## 🙌 Acknowledgments

Inspired by [A Note About Git Commit Messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) and the Raycast community.

---

Built by [Martín López](https://github.com/juanmartinlopeze) — contributions welcome!
