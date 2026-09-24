# 🤝 How to Contribute

First off, thank you so much for taking the time to contribute! 🎉

All contributions are welcome to help keep this resource accurate, simple, readable, and up to date.

---

## 📋 Guidelines & Recommendations

Please review these guidelines before contributing. Use your best judgment when applying them, and feel free to propose updates to this document by opening a pull request.

- **Conventional Commits:** Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification for clear and structured commit messages (e.g., `feat:`, `fix:`, `docs:`).

- **Coding Style:** To ensure consistent coding styles and formatting throughout the project, configure your editor to use the `.editorconfig` file located in the project root. For more information, visit the [EditorConfig Website](https://editorconfig.org/).

- **Emoji Usage:** To keep the code consistent, use standard Unicode emojis rather than GitHub's flavored markdown emojis unless strictly necessary.

- **Branch Naming:** Name your feature branch according to the conventions in the [Contribution Workflow](#-contribution-workflow).

- **Code of Conduct:** Adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md) to help us maintain a welcoming, healthy, and constructive community environment.

- **First-Time Contributors:** New to open source? Check out GitHub's guide [About Pull Requests](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) and the [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/) guide before getting started.

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

5. **Translate the README:** Create a copy of README.md inside the lang/ directory, naming the file using your language's [ISO code](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes). For example, let's add a French translation:

```bash
# Create a markdown file named "fr" based on the French ISO code
touch lang/fr.md

# Copy the contents from README.md to fr.md
cp --copy-contents README.md lang/fr.md

# That's it. Now you can start translating the cheat sheet to French!
```

6. **Add and Commit your Changes:**

```bash
git add .
git commit -m "feat(lang): add my amazing language translation, closes #<issue-number>"
```

7. **Push to the Branch:**

```bash
git push origin language/<issue-number>-your-language
```

7. **Open a Pull Request:** Submit a **PR** pointing to the `main` branch and link the **Issue** you created in Step 1. ***And that's it!*** It's easier than it looks, right?

> [!IMPORTANT]
> Once your pull request is successfully merged, your branch will be automatically deleted.

## 📄 License

Any contribution will be published under the same licensing terms as the project itself.
