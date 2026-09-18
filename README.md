<div>
  <a href="http://www.w3.org/html/logo/">
    <img src="https://www.w3.org/html/logo/badge/html5-badge-h-semantics.png" width="133" height="64" align="left" alt="HTML5 Powered with Semantics" title="HTML5 Powered with Semantics">
  </a>
  <br>

  <h1 align="right">HTML Character Entities Cheat Sheet</h1>
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark-mode.png" alt="Repository banner dark color scheme" />
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light-mode.png" alt="Repository banner light color scheme" />
    <img src="assets/banner-light-mode.png" alt="Repository banner default theme" />
  </picture>
</div>

## 📑 About

**Character entities** allow you to display special characters and symbols within **HTML** documents that are not available in the **charset** encoding. These special characters must be replaced with **character entities** to prevent the browser from interpreting them as HTML code or rendering them incorrectly.

This comprehensive cheat sheet provides a quick reference to help you navigate this sea of characters, glyphs, and symbols. We'll be covering their usage, types, and best practices for creating well-formatted and accessible content.

🫶 **Contributions are welcome!** Feel free to:

- Correct grammatical errors and improve readability.
- Add new characters, glyphs, and symbols.
- Translate this project into your language.
- Improve explanations and address other ideas.

---

## 📋 Table of Contents

- [📑 About](#-about)
- [📎 Types of character entities](#-types-of-character-entities)
- [📓 Best practices and recommendations](#-best-practices-and-recommendations)
- [📜 List of HTML character entities](#-list-of-html-character-entities)
- [🤝 Contributing](#-contributing)
- [📄 Licenses and copyright](#-licenses-and-copyright)

---

## 📎 Types of Character Entities

HTML character entities are codes used to display reserved characters or special symbols—such as accented letters, diacritical marks, emojis, and characters not found on a standard keyboard—without interfering with HTML parsing.

There are three ways to represent them:

1. **Named Entities:** Represented by a standard and unique human-readable name, such as `&copy;` for the copyright symbol (&copy;) and `&gt;` for the greater-than sign (&gt;).
2. **Decimal Codes:** Represented by the character's Unicode decimal value preceded by `&#`, such as `&#169;` for the copyright symbol (&#169;) and `&#120506;` for the mathematical character sigma (&#120506;).
3. **Hexadecimal Codes:** Represented by the character's Unicode hexadecimal value preceded by `&#x`, such as `&#x00A9;` for the copyright symbol (&#x00A9;) and `&#x03A9;` for the Greek letter omega (&#x03A9;).

> [!TIP]
> Both decimal and hexadecimal formats are collectively known as **Numeric Entities**.

---

## 📓 Best Practices and Recommendations

- **Prefer Named Entities When Possible:** Use named entities for commonly used characters to enhance code readability. Named entities are easier to remember than numeric entities, making them simpler to read and maintain.

> [!NOTE]
> Entity names are case-sensitive. Always write entity names in lowercase.

- **Use Numeric Entities for Less Common Characters:** Many characters like `U+2691` (⚑) do not have a named equivalent. In these cases, use decimal or hexadecimal codes instead.

- **Prioritize Accessibility:** Ensure character entities remain accessible to screen readers and other assistive technologies by providing alternative text or context when necessary.

> [!TIP]
> Always specify UTF-8 character encoding (`<meta charset="UTF-8">`) at the beginning of every HTML document. UTF-8 natively supports almost all characters, ensuring browsers display content correctly and eliminating the need for character entities in most scenarios.

> [!WARNING]
> Web browsers can only render a character if the user's device has a font installed that supports it. If a character is missing from the available fonts, it will usually display as a box or placeholder symbol.

---

## 📜 List of HTML Character Entities

---

## 🤝 Contributing

**We welcome contributions!** You can:

- 🐛 Report bugs, typos, or grammar mistakes.
- ®️ Add new characters, glyphs, and symbols to the list.
- 🌐 Translate this project into other languages.
- 💡 Improve explanations and address other ideas.
- 📝 Enhance formatting and styling.

**(ദ്ദി ˙ᗜ˙ )** Thank you for taking the time to read and support this project.

---

## 📄 Licenses and Copyright

This project is licensed under the [MIT License](LICENSE), which is included in the root directory of this repository. Feel free to use, adapt, or copy any part of this project.

The [HTML5 logo](http://www.w3.org/html/logo/) is licensed under Creative Commons Attribution 3.0 — all are free to use and reimagine as they see fit.

---

<p align="center">
    <b>⭐ Star this repository if you found it helpful! - I appreciate it ദ്ദി( • ᴗ - ) ✧ ⭐</b>
</p>
