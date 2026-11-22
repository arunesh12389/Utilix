## 📁 Project Structure Guidelines

To keep the repository organized, please follow these basic conventions:

- Each developer tool should have its own folder inside `developer-tools/`.
- Each mini application should have its own folder inside `mini-apps/`.
- Include a `README.md` explaining what your contribution does.
- Keep source code and related assets inside your project's folder.
- Use clear, lowercase, hyphen-separated folder names.

Example: `json-formatter`, `habit-tracker`, `regex-tester`.

You are free to choose your preferred programming language and framework.

### Example 1: Developer Tool

A contributor adding a JSON Formatter should create:

```text
developer-tools/
└── json-formatter/
    ├── README.md
    ├── index.html
    ├── style.css
    └── script.js
```

### Example 2: Mini App

A contributor adding a Habit Tracker should create:

```text
mini-apps/
└── habit-tracker/
    ├── README.md
    ├── package.json
    ├── src/
    └── public/
```

These are suggested structures, not strict requirements. Contributors can organize their source files according to the technologies they use.