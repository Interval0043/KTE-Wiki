This is only for people looking to write articles themselves on here. If you're not, then this page isn't for you.

## Text Editing

First up is the style of text.

* *italics* -> `*italics*`
* **bold** -> `**bold**`
* ***italic and bold*** -> `***italic and bold***`
* `codeblock` -> `` `codeblock` ``
# Header 1 -> `# Header 1`
## Header 2 -> `## Header 2`
### Header 3 -> `### Header 3`
#### Header 4 -> `#### Header 4`
##### Header 5 -> `##### Header 5`
###### Header 6 -> `###### Header 6`

- list -> `- list`

## Callouts

> [!note]
> These things.

```
> [!note]
> These things.
```

> [!info] different title
> You can even change the title!

```
> [!info] different title
> You can even change the title!
```

> [!question]
> You can even nest callouts!
> > [!example]
> > I'm a nest.

```
> [!question]
> You can even nest callouts!
> > [!example]
> > I'm a nest.
```

Available types: note, abstract, info, todo, tip, success, question, warning, failure, danger, bug, example, quote

## Links

[[index]] -> `[[index]]`
[link to google](https://google.com) -> `[link to google](https://google.com)`
[[index|Home]] -> `[[index|Home]]` (aliased link)

## Colored Text

- <span style="color:red">text</span> -> `<span style="color:red">text</span>`
- <span style="color:rgb(41, 128, 185)">text</span> -> `<span style="color:rgb(41, 128, 185)">text</span>`

## Properties

At the top of a page, just under the title, you can put properties.
```
---
  aliases:
    - example1
    - example 2
  tags:
    - example_1
    - example_2/example3
---
```

