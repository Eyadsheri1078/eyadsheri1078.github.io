# theverifier.github.io


# Complete CommonMark & GitHub Markdown Test

This document tests the core features of **CommonMark** and selected **GitHub Flavored Markdown (GFM)**.

---

# Heading 1

Paragraph under Heading 1.

## Heading 2

Paragraph under Heading 2.

### Heading 3

Paragraph under Heading 3.

#### Heading 4

Paragraph under Heading 4.

##### Heading 5

Paragraph under Heading 5.

###### Heading 6

Paragraph under Heading 6.

---

# Paragraphs

This is the first paragraph.

This is the second paragraph.

This paragraph contains multiple
lines that should render
as one paragraph.

This paragraph ends with two spaces.  
This line should appear below it.

---

# Emphasis

*Italic*

_Italic_

**Bold**

__Bold__

***Bold Italic***

___Bold Italic___

~~Strikethrough~~

**Bold with _italic_ inside**

*Italic with **bold** inside*

~~**Bold Strikethrough**~~

---

# Escaping Characters

\*Not italic\*

\# Not a heading

\`Not code\`

\\ Backslash

\> Not a blockquote

\_Not italic\_

\[\]

\(\)

\{\}

---

# Horizontal Rules

---

***

___

---

# Blockquotes

> Simple quote.

> Another quote
> continuing onto another line.

> Nested quote
>
>> Second level
>>
>>> Third level

> ## Quote with Heading
>
> - List item
> - Another item
>
> **Bold**
>
> `inline code`

---

# Lists

## Unordered

- Item 1
- Item 2
- Item 3

* Item A
* Item B
* Item C

+ Item X
+ Item Y
+ Item Z

---

## Nested Lists

- Parent
    - Child
        - Grandchild
            - Great Grandchild

---

## Ordered Lists

1. One
2. Two
3. Three

1. First
1. Second
1. Third

---

## Mixed Lists

1. Ordered
    - Unordered
        1. Ordered
            - Unordered

---

# Links

Inline link:

<https://github.com>

Named link:

[GitHub](https://github.com)

Reference link:

[GitHub Docs][docs]

[docs]: https://docs.github.com

Email:

<example@example.com>

---

# Images

Basic image

![Placeholder](https://via.placeholder.com/200)

Linked image

[![Placeholder](https://via.placeholder.com/100)](https://github.com)

Reference image

![Logo][logo]

[logo]: https://via.placeholder.com/150

---

# Automatic Links

<https://google.com>

<https://github.com>

<mailto:test@example.com>

---

# Inline Code

Use the `printf()` function.

Use `git status`.

Use `npm install`.

---

# Code Blocks

Indented:

    This is code.
    Still code.

Fenced:

```
Plain text
```

Language:

```python
print("Hello World")
```

```javascript
console.log("Hello");
```

```cpp
#include <iostream>

int main() {
    std::cout << "Hello";
}
```

```bash
git status
git add .
git commit -m "test"
```

```json
{
  "name": "markdown"
}
```

---

# Inline HTML

<b>Bold HTML</b>

<strong>Strong HTML</strong>

<i>Italic HTML</i>

<em>Emphasis HTML</em>

<u>Underline</u>

<mark>Highlighted</mark>

<small>Small text</small>

<big>Big text (deprecated HTML)</big>

<sub>Subscript</sub>

<sup>Superscript</sup>

<del>Deleted</del>

<ins>Inserted</ins>

<code>Inline code</code>

<kbd>Ctrl</kbd> + <kbd>C</kbd>

<samp>Output</samp>

<var>x</var>

<abbr title="HyperText Markup Language">HTML</abbr>

---

# HTML Paragraph

<p>
This paragraph uses raw HTML.
Markdown is ignored inside HTML blocks unless specifically supported.
</p>

---

# HTML Div

<div>

This content is inside a div.

**Markdown may not render here depending on parser.**

</div>

---

# HTML Span

<span style="color:red;">Red Text (style stripped on GitHub)</span>

<span>Plain Span</span>

---

# HTML Line Breaks

Line One<br>
Line Two<br>
Line Three

---

# HTML Horizontal Rule

<hr>

---

# HTML Tables

<table>
<tr>
<th>Name</th>
<th>Age</th>
</tr>

<tr>
<td>Alice</td>
<td>30</td>
</tr>

<tr>
<td>Bob</td>
<td>25</td>
</tr>
</table>

---

# HTML Lists

<ul>
<li>Apple</li>
<li>Banana</li>
<li>Cherry</li>
</ul>

<ol>
<li>One</li>
<li>Two</li>
<li>Three</li>
</ol>

---

# HTML Details

<details>

<summary>Click to expand</summary>

Hidden content.

More hidden content.

</details>

---

# HTML Images

<img
src="https://via.placeholder.com/300"
alt="Placeholder"
width="300">

---

# HTML Links

<a href="https://github.com">GitHub</a>

---

# HTML Quote

<blockquote>

This is an HTML blockquote.

</blockquote>

---

# HTML Preformatted

<pre>
Line 1
Line 2
Line 3
</pre>

---

# HTML Code

<pre><code>
function hello() {
    console.log("Hello");
}
</code></pre>

---

# HTML Comments

<!--
Invisible comment
-->

Visible text.

---

# Entity References

&amp;

&lt;

&gt;

&quot;

&apos;

&copy;

&trade;

&hearts;

---

# Mixed Markdown + HTML

<div>

# Markdown Heading

This may or may not render depending on parser.

**Bold**

</div>

---

# Edge Cases

******

___

- - -

***

> **Bold Quote**

> *Italic Quote*

> `Code Quote`

---

# Empty Elements

<br>

<hr>

---

# Unicode

😀 😁 😂 🤖 🚀 ❤️

こんにちは

Привет

مرحبا

שלום

नमस्ते

---

# End

If everything above renders correctly, your renderer supports nearly all core CommonMark syntax plus GitHub's supported inline HTML.
