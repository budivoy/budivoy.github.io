---
title: "Hugo Bear Blog Features Demo"
date: 2024-04-05
draft: false
tags: ["demo", "features", "markdown", "hugo"]
---

# Hugo Bear Blog Features Demo

This post demonstrates all the features supported by Hugo Bear Blog theme.

## Text Formatting

### Basic Text Styles
- **Bold text** using double asterisks
- *Italic text* using single asterisks
- ~~Strikethrough~~ using double tildes
- `inline code` using backticks

### Headers
# H1
## H2
### H3
#### H4
##### H5
###### H6

## Lists

### Ordered List
1. First item
2. Second item
3. Third item
   1. Nested item
   2. Another nested item

### Unordered List
- First item
- Second item
- Third item
  - Nested item
  - Another nested item

## Code Blocks

### Inline Code
This is an example of `inline code` in a sentence.

### Code Block with Syntax Highlighting
```python
def hello_world():
    print("Hello, World!")
    return True
```

### Code Block without Syntax Highlighting
```
This is a plain code block
with multiple lines
```

## Links and References

### Basic Links
- [GitHub](https://github.com)
- [External Link with Title](https://example.com "Example Website")

### Reference-style Links
This is [a reference link][1] and this is [another reference link][2].

[1]: https://example.com "Example Website"
[2]: https://github.com "GitHub"

## Blockquotes

> This is a blockquote. It can span multiple lines.
>
> > This is a nested blockquote.

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

## Horizontal Rule

---

## Images

### Basic Image
![Alt text for image](/images/example.jpg)

### Image with Title
![Alt text for image](/images/example.jpg "Image Title")

## Task Lists

- [x] Completed task
- [ ] Incomplete task
- [ ] Another task

## Footnotes

Here's a sentence with a footnote[^1].

[^1]: This is the footnote content.

## Math Equations (LaTeX)

Inline math: $E = mc^2$

Block math:
$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$

## Emoji Support

:smile: :heart: :rocket: :thumbsup:

## HTML Support

<div class="custom-class">
  This is a custom HTML block with a class.
</div>

## Metadata

This post was created on {{ .Date.Format "January 2, 2006" }}.

## Tags

This post is tagged with:
{{ range .Params.tags }}
- {{ . }}
{{ end }}

## Code Examples

TODO
