# Markdown Cheatsheet

### Headings
```
    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6
```

=

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

### Escaping markup

\ is used to escape symbols from being interpreted as Markdown text ie. **BOLD** = \*\*BOLD\*\*

```
    To show this: **BOLD**
    You would type this: \*\*BOLD\*\*
```

### Italics
```
    *This Text* is italic
    _This Text_ is italic
```

=

*This Text* is italic

_This Text_ is italic

### Strong
```
    **This Text** is strong
    __This Text__ is strong
```

=

**This Text** is strong

__This Text__ is strong

### Combined emphasis
```
    **Combined _emphasis_**
```

=

**Combined _emphasis_**

### Strikethrough
```
    ~~This Text~~ is strikethough
```

=

~~This Text~~ is strikethough

### Horizontal rule
```
    ---
    ___
```

=

---
___

### Block quote
```
    > This is a quote
```

=

> This is a quote

### Links
```
    [I'm an inline-style link](https://google.co.uk)
```

=

[I'm an inline-style link](https://google.co.uk)

```
    [I'm an inline-style link with title](https://google.co.uk "Title")
```

=

[I'm an inline-style link with title](https://google.co.uk "Title")

### Ul
```
    * item 1
    * item 2
        * nested item 1
```

=

* item 1
* item 2
    * nested item 1

### ol
```
    1. item 1
    1. item 2
        1. nested item 1 
```

=

1. item 1
1. item 2
    1. nested item 1

### Inline code blocks
```
    `<p>This is a paragraph</p>`
```

=

`<p>This is a paragraph</p>`

### Images
```
    ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Title")
```

=

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Title")

## Github
### Code blocks
` ```bash`

      npm install
      npm start
` ``` `

=

```bash
    npm install
    npm start
```

` ```javascript`

      function add(num1, num2) {
          return num1 + num2;
      }
` ``` `

=

```javascript
    function add(num1, num2) {
        return num1 + num2;
    }
```

` ```python`

      def add(num1, num2)
          return num1 + num2
` ``` `

=

```python
    def add(num1, num2)
        return num1 + num2
```

### Tables
```
    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
```
=

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

### Task Lists
```
    * [x] task 1
    * [x] task 2
    * [ ] task 3
```

=

* [x] task 1
* [x] task 2
* [ ] task 3