# This is a Blogpost

Welcome to this sample blog post! This post will showcase the various markup possibilities you can use in your Hugo blog. From headings to code snippets, you'll find everything you need to make your posts engaging and informative.

---

## Headings

You can create headings of different levels using the `#` symbol. The more `#`, the smaller the heading.

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

---

## Text Formatting

Markdown allows you to emphasize your text in several ways:

- **Bold text:** Use double asterisks (`**`) or double underscores (`__`) around your text.
  ```markdown
  **This is bold text**
  **This is also bold text**
  ```
- _Italic text:_ Use single asterisks (`*`) or single underscores (`_`).
  ```markdown
  _This is italic text_
  _This is also italic text_
  ```
- **_Bold and Italic combined:_**

  ```markdown
  **_This is bold and italic_**
  ```

- ~~Strikethrough:~~ Use double tildes (`~~`).
  ```markdown
  ~~This text is strikethrough~~
  ```

---

## Lists

### Unordered Lists

You can create bullet points with asterisks (`*`), plus signs (`+`), or hyphens (`-`).

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
- Item 3
```

### Ordered Lists

For numbered lists, simply use numbers followed by a period.

```markdown
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
3. Third item
```

---

## Links

You can easily create links using the following syntax:

```markdown
[OpenAI's GPT-4](https://openai.com)
```

Result: [OpenAI's GPT-4](https://openai.com)

---

## Images

Adding images is similar to adding links. Use an exclamation mark (`!`) followed by the alt text in square brackets and the image path in parentheses.

```markdown
![My Cool Image](/images/sample-image.png)
```

Here's an example image:

![Placeholder Image](https://via.placeholder.com/150)

---

## Blockquotes

To highlight quotes or important information, use the `>` symbol.

```markdown
> This is a blockquote. It's a great way to emphasize a particular section of your text.
```

Result:

> This is a blockquote. It's a great way to emphasize a particular section of your text.

---

## Code

You can showcase code snippets or inline code easily:

### Inline Code

```markdown
Use the `git status` command to check the state of your repository.
```

Result: Use the `git status` command to check the state of your repository.

### Code Blocks

For longer code blocks, use triple backticks (```) or indent with four spaces.

<pre>
```
def hello_world():
    print("Hello, World!")
```
</pre>

Result:

```python
def hello_world():
    print("Hello, World!")
```

### Syntax Highlighting

To specify the language for syntax highlighting, add the language name after the first set of backticks.

<pre>
```python
def add(a, b):
    return a + b
```
</pre>

Result:

```python
def add(a, b):
    return a + b
```

---

## Tables

Markdown also supports simple tables:

```markdown
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

Result:

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

---

## Horizontal Rules

You can create horizontal rules to break up sections using three or more asterisks (`***`), dashes (`---`), or underscores (`___`).

```markdown
---
```

Result:

---

## Embedding Media

You can also embed videos and other media using simple HTML tags.

```html
<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/dQw4w9WgXcQ"
  frameborder="0"
  allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen
></iframe>
```

Result:  
_(Embedding video example omitted in this Markdown preview.)_

---

## Conclusion

That's it for this sample blog post! You've seen how to use headings, lists, links, images, code snippets, and more in your blog posts. With these tools, you can create rich and engaging content for your readers. Happy blogging!
