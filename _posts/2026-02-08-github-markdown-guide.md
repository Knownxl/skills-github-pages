---

title: "What Markdowns YOU Can Use in GitHub"
date: 2026-02-08
----------------

# What Markdowns YOU Can Use in GitHub

GitHub uses **GitHub Flavored Markdown (GFM)**. This post lists the *actual, supported* Markdown features you can use in **README files, GitHub Pages (Jekyll), issues, pull requests, and comments**, with clean examples you can copy directly.

---

## 1. Headings

Use `#` symbols. GitHub supports up to six levels.

```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

---

## 2. Text Formatting

```md
**Bold**
*Italic*
~~Strikethrough~~
**_Bold and Italic_**
```

**Bold**
*Italic*
~~Strikethrough~~
***Bold and Italic***

---

## 3. Paragraphs & Line Breaks

```md
This is a paragraph.

This is another paragraph.
```

Line breaks require a blank line.
Single line breaks are ignored unless forced with `<br>`.

---

## 4. Blockquotes

```md
> This is a blockquote
>> Nested blockquote
```

> This is a blockquote
>
> > Nested blockquote

---

## 5. Lists

### Unordered List

```md
- Item one
- Item two
  - Sub item
```

* Item one
* Item two

  * Sub item

### Ordered List

```md
1. First
2. Second
3. Third
```

1. First
2. Second
3. Third

---

## 6. Task Lists (Checkboxes)

Supported in READMEs, issues, PRs, and comments.

```md
- [x] Completed task
- [ ] Incomplete task
```

* [x] Completed task
* [ ] Incomplete task

---

## 7. Links

```md
[GitHub](https://github.com)
```

[GitHub](https://github.com)

Automatic links also work:

```md
https://github.com
```

---

## 8. Images

Images are supported in Markdown and HTML.

```md
![Alt text](https://example.com/image.png)
```

You can also drag and drop images directly into GitHub, which uploads them and inserts the URL automatically.

![Image](https://cdn.bulldogjob.com/system/photos/files/000/003/440/original/readme.png)

![Image](https://m.media-amazon.com/images/I/618kgYkDpbL._AC_UF1000%2C1000_QL80_.jpg)

![Image](https://repository-images.githubusercontent.com/662720581/685b29bf-dbff-4533-82c0-c1be3bd4ee24)

---

## 9. Code Blocks

### Inline Code

```md
Use `git status` to check changes.
```

Use `git status` to check changes.

### Fenced Code Blocks

````md
```js
console.log("Hello GitHub");
```
````

```js
console.log("Hello GitHub");
```

GitHub supports syntax highlighting for many languages.

---

## 10. Tables

```md
| Name | Language | Stars |
|------|----------|-------|
| Repo A | JavaScript | ⭐ 120 |
| Repo B | Python | ⭐ 95 |
```

| Name   | Language   | Stars |
| ------ | ---------- | ----- |
| Repo A | JavaScript | ⭐ 120 |
| Repo B | Python     | ⭐ 95  |

---

## 11. Horizontal Rules

```md
---
```

---

## 12. Emojis

GitHub supports Unicode emojis and shortcode emojis.

```md
🚀 🎯 ✅
:rocket: :white_check_mark:
```

🚀 🎯 ✅

---

## 13. Mentions & References

```md
@username
#123
owner/repo#456
```

* Mentions users
* Links issues and pull requests
* Cross-references repositories

---

## 14. Collapsible Sections (Details / Summary)

Supported using HTML (allowed by GitHub).

```html
<details>
  <summary>Click to expand</summary>

  Hidden content here.
</details>
```

<details>
  <summary>Click to expand</summary>

Hidden content here.

</details>

---

## 15. HTML Support (Limited)

GitHub allows **safe HTML** inside Markdown.

Supported:

* `<br>`
* `<img>`
* `<details>`
* `<summary>`
* `<kbd>`
* `<sub>` / `<sup>`

Not supported:

* `<script>`
* Inline JavaScript
* External CSS files

Example:

```html
Press <kbd>Ctrl</kbd> + <kbd>C</kbd>
```

Press <kbd>Ctrl</kbd> + <kbd>C</kbd>

---

## 16. Alerts / Callouts (GitHub Specific)

```md
> [!NOTE]
> This is a note.

> [!WARNING]
> This is a warning.
```

> [!NOTE]
> This is a note.

> [!WARNING]
> This is a warning.

---

## 17. Footnotes

```md
This text has a footnote.[^1]

[^1]: Footnote text.
```

This text has a footnote.[^1]

[^1]: Footnote text.

---

## 18. Escaping Markdown

Use `\` to escape formatting.

```md
\*Not italic\*
```

*Not italic*

---

## 19. GitHub Pages (Jekyll) Front Matter

For blogs and pages:

```yaml
---
title: "Post Title"
date: 2026-02-08
layout: post
---
```

Required for GitHub Pages posts.

---

## Summary

GitHub Markdown supports:

* Text formatting
* Code highlighting
* Tables
* Images
* Task lists
* Alerts
* Limited HTML
* Jekyll front matter
