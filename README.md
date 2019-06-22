# Markdown CheatSheet

## Table of contents

<!-- Toc -->

1. [Headings](#h)
2. [Text Formatting](#tf)
3. [Blockquotes](#b)
4. [Links](#a)
4. [Lists](#l)
5. [Images](#i)
6. [Code](#c)
7. [Tables](#t)
8. [Task Lists](#tl)

___

<!-- Headings -->
## Headings<a name="h"/></a>

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

___

## Text Formatting<a name="tf"/></a>

<!-- Italics -->
*This text* is italic\
_This text_ is italic
___

<!-- Strong -->
**This text** is strong\
__This text__ is strong
___

<!-- Strong -->
***This text*** is strong and italic

___

<!-- Strikethrough -->
~~This text~~ is strikethrough

___

## Blockquotes<a name="b"/></a>

<!-- Blockquote -->
> This is a quote
___

## Links<a name="a"/></a>

<!-- Link -->
[raspberrypi](https://raspberrypi.onthewifi.com)\
[raspberrypiwithtooltip](https://raspberrypi.onthewifi.com "I am a tooltip")
___

## Lists<a name="l"/></a>

### Unordered List

<!-- UL -->
* Item 1
* Item 2
  * Nested Item 1
    * Nested Nested Item 1
  * Nested Item 2
___

### Ordered List

<!-- OL -->
1. Item 1
2. Item 2
   1. Nested Item 1
   2. Nested Item 2
___

## Images<a name="i"/></a>

<!-- Images -->
![Markdown Logo](https://markdown-here.com/img/icon256.png "Logo")
___

## Code<a name="c"/></a>

### Inline

<!-- Inline Code Block -->
`<p>This is a paragraph</p>`
___

### Blocks

<!-- Codeblocks -->

#### Regular

```
npm install

npm start
```

#### JavaScript

```javascript
function add(num1 + num2) {
  return (num1 + num2);
}
```

#### Python

```python
def add(num1 + num2):
  return num1 + num2
```

#### Difference

```diff
  theme: {
    type: "dark",
+   name: "darkmode",
-   name: "dark",
    usage: "popular",
    isDeprecated: false,
  }
```

___

## Tables<a name="t"/></a>

<!-- Tables -->
| Name............. | .........centered.......... | .............rigt-aligned |
| ----------------- | :-------------------------: | ------------------------: |
| John Snow         |       john@gmail.com        |            john@gmail.com |
| Arya Stark        |       arya@gmail.com        |            arya@gmail.com |
___

## Task Lists<a name="tl"/></a>

<!-- Task List -->
* [ ] Task 1
* [x] Task 2
* [x] Task 3
* [ ] Task 4
___
