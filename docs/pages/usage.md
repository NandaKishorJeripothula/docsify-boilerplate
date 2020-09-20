## Emphasis

_This text will be italic_

```md
_This text will be italic_
```

**This text will be bold**

```md
**This will also be bold**
```

_You **can** combine them_

```md
_You **can** combine them_
```

## Strikethrough

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

```md
~~this~~
```

## Lists

### Unordered

- Item 1
- Item 2
  - Item 2a
  - Item 2b

```md
- Item 1
- Item 2
  - Item 2a
  - Item 2b
```

### Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

```md
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

## Links

https://google.com - automatic!

[Google](https://google.com)

## Images

The following image is loaded with "Sample Image" as alternative text
![Sample Image](https://picsum.photos/200/300)

```md
![Alt Text](url)
```

## Quote

### Basic Quote

> This is basic quoted text

```md
> This is basic quoted text
```

### Docsify Specific Informative Quote

?>This is Docsify Specific Informative Quote text

```md
?>This is Docsify Specific Informative Quote text
```

### Docsify Specific Warning/Important Quote

!>This is Docsify Specific Warning/Important Quote text

```md
!>This is Docsify Specific Warning/Important Quote text
```

## Markdown in html tag

> Markdown supports some of the html tags combination.

You need to insert a space between the html and markdown content.
This is useful for rendering markdown content in the details element.

<details>
<summary>Summary View Collapsible(Click to expand)</summary>

- 123
- 456

</details>

```md
<details>
<summary>Summary View Collapsible(Click to expand)</summary>

- 123
- 456

</details>
```

Or markdown content can be wrapped in html tag.

<div style='color: red'>

- 123
- 456

</div>

```md
<div style='color: red'>

- 123
- 456

</div>
```
