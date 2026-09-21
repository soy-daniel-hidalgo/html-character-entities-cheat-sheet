# 🤝 How to Contribute

Thank you so much for taking the time to contribute to the **HTML Character Entities Cheat Sheet**! All contributions are welcome to help keep this resource accurate, simple, readable, and up to date.

---

## 📋 Guidelines

- **Conventional Commits:** Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification for commit messages (e.g., feat:, fix:, docs:, style:).

- **Formatting:** Keep the code formatting and Markdown style consistent throughout the project.

- **Code of Conduct:** We make an effort to maintain a healthy and constructive community environment by adopting and enforcing our [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## 💡 Ways to Contribute

You can help in many ways, including:

- 🐛 Reporting bugs, typos, or grammar mistakes in descriptions or entity codes.
- ➕ Adding and updating characters, glyphs, or symbols in the list.
- 🌐 Translating the cheat sheet into other languages.
- 🎨 Improving formatting, styling, accessibility, or readability.

---

## 🔄 Contribution Workflow

To keep things organized and avoid duplicated effort, please follow this process:

### Adding Features

1. **Open an Issue:** Before starting, check existing issues or [open a new Issue](https://github.com/soy-daniel-hidalgo/html-character-entities-cheatsheet/issues), use the issue template named **➕ Special Character Request** and briefly describe what you intend to work on.

2. **Fork the Repository:** Create your own copy of the repository by clicking the **Fork** button at the top right of the page.

3. **Create a Feature Branch:**

```bash
# Replace <issue-number> with your assigned issue number and brief description
git checkout -b feature/<issue-number>-your-awesome-feature
```

4. **Add and Commit your Changes:**

```bash
git add .
git commit -m 'feat: add some amazing feature, closes #<issue-number>'
```

5. **Push to the Branch:**

```bash
git push origin feature/<issue-number>-your-awesome-feature
```

6. **Open a Pull Request:** Submit a **PR** targeting to the `main` branch and link the **Issue** you created in Step 1. ***And that's it!*** It's easier than it looks, right?

### Translating Cheat Sheets

1. **Pick a Language:** Check open comments, discussions, or issues to see if someone is already working on your target language.
If no one has claimed it yet, claim it by [opening an issue](https://github.com/soy-daniel-hidalgo/html-character-entities-cheatsheet/issues) to avoid duplicate effort.

2. **Open an Issue:** To simplify the process, use the issue template named **🌐 Locale Request** and briefly describe what you intend to work on.

3. **Fork the Repository:** Create your own copy of the repository by clicking the **Fork** button at the top right of the page.

4. **Create a Language Branch:**

```bash
# Replace <issue-number> with your issue number and brief description
git checkout -b language/<issue-number>-your-language
```

5. **Translate the README:** Create a copy of README.md inside the lang/ directory, naming the file using your language's [ISO code](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes). For example, to add a French translation:

```bash
# Create a markdown file named "fr" based on the French ISO code
touch lang/fr.md

# Copy the contents from README.md to fr.md
cp --copy-contents README.md lang/fr.md
```

6. **Add and Commit your Changes:**

```bash
git add .
git commit -m "feat(lang): add <your-language> translation, closes #<issue-number>"
```

7. **Push to the Branch:**

```bash
git push origin language/<issue-number>-your-language
```

7. **Open a Pull Request:** Submit a **PR** pointing to the `main` branch and link the **Issue** you created in Step 1. ***And that's it!*** It's easier than it looks, right?

> [!IMPORTANT]
> Once your pull request is successfully merged, your branch will be automatically deleted.
