---
layout: page 
title: Typography 
description: Styles that you can use in your posts.
---

## Headers

```markdown
# H1 - Lorem ipsum

## H2 - Lorem ipsum

### H3 - Lorem ipsum

#### H4 - Lorem ipsum

##### H5 - Lorem ipsum

###### H6 - Lorem ipsum
```

# H1 - Lorem ipsum

## H2 - Lorem ipsum

### H3 - Lorem ipsum

#### H4 - Lorem ipsum

##### H5 - Lorem ipsum

###### H6 - Lorem ipsum

Lorem ipsum dolor sit amet faucibus purus nascetur elementum nullam.

---

## Emphasis

```markdown
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

---

## Lists

```markdown
1. First ordered list item
2. Another item
    * Unordered sub-list.
    * Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Another ordered sub-list item

* Unordered list can use asterisks

- Or minuses

+ Or pluses
```

1. First ordered list item
2. Another item
    * Unordered sub-list.
    * Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Another ordered sub-list item

* Unordered list can use asterisks

- Or minuses

+ Or pluses

---

## Links

There are two ways to create links.

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> and sometimes example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org

[1]: http://slashdot.org

[link text itself]: http://www.reddit.com

---

## Images

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

---

## Code and Syntax Highlighting

```js
// Comment
var s = "JavaScript syntax highlighting";
alert(s);
```

```html
<select id="custom-options">
    <option value="apple" data-color="red">Apple</option>
    <option value="samsung" data-color="blue" selected>Samsung</option>
    <option value="sony" data-color="#000">Sony</option>
    <option value="lg" data-color="#fff">LG</option>
</select>
```

---

## Tables

Colons can be used to align columns.

```markdown
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, and you don't need to
make the raw Markdown line up prettily. You can also use inline Markdown.

```markdown
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

---

## Blockquotes

```markdown
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.
```

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

```markdown
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 
