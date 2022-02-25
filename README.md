# markdown-handbook

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code format.

## Heading

```
# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6
```

<details>
<summary>Click here for the example</summary>

<br>

# This is Header 1

## This is Header 2

### This is Header 3

#### This is Header 4

##### This is Header 5

###### This is Header 6

</details>

## Bold

Format of `**bold**` text. You have to enlist the part you want to make bold within `**` and `**` and then enclose it within `**` and `**`.

Example:

```markdown
This is **bold string** text.
```

## Italic
Format of **italic** text. You have to enlist the part yhou want to make italic within `*` and `*`.

Example:

```markdown
This is a *italic* text.
```

## Blockquote
According to [Wikipedia](https://en.wikipedia.org/wiki/Block_quotation)
> A block quotation (also known as a long quotation or extract) is a quotation in a written document that is set off from the main text as a paragraph, or block of text, and typically distinguished visually using indentation and a different typeface or smaller size font.

The below statement is in a blockquote

> This is a blockquote.

## Ordered List

You can use the following format to create an ordered list:

```    
    1. Item 1
    2. Item 2
    3. Item 3
```
Output in Markdown:

    1. Item 1
    2. Item 2
    3. Item 3

If you want to shuffle the items but also want markdown to assign the correct sequence by default, then you can use `1.` to all of them.

Example:

```
1. Item 1
1. Item 2
1. Item 3
```

It will provide the following output:

1. Item 1
1. Item 2
1. Item 3

Now, if you change any item, but want the markdown itself to assign the correct order, then it would work flawlessly! Now, I will replace the `Item 2` with `Item 3`, but the order would get corrected automatically.

```
1. Item 1
1. Item 3
1. Item 2
```

It will provide the following output:

1. Item 1
1. Item 3
1. Item 2




