<!-- Headings -->
`INPUT: Headigs`
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
`OUTPUT:`
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

___

<!-- Italics -->
`INPUT: Italics`
```
*This text* is italic

\*This symbol\* is escaped

_This text_ is italic
```
`OUTPUT: `

*This text* is italic

\*This symbol\* is escaped

_This text_ is italic

***

<!-- Strong -->
`INPUT: Strong`
```
**This text** is strong

__This text__ is strong
```
`OUTPUT: `

**This text** is strong

__This text__ is strong

___

<!-- Strikethrough -->
`INPUT: Strikethrough`
```
~~This text~~ is strikethrough  
```

`OUTPUT: `

~~This text~~ is strikethrough
___
<!-- Horizontal rule  -->
`INPUT: Horizontal rule`
```
---
___
```

`OUTPUT: `

---
___

<!-- Blockquote -->
`INPUT: Blockquote`
```
> This is a quate
```

`OUTPUT: `

> This is a quate
___

<!-- Links -->
`INPUT: Links`
```
[NataDEV](http://natadev.nl)

[NataDEV](http://natadev.nl "Nata's website") 
```

`OUTPUT: `

[NataDEV](http://natadev.nl)

[NataDEV](http://natadev.nl "Nata's website")
___
<!-- UL -->
`INPUT: UL`
```
* Item 1 
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
```

`OUTPUT: `
* Item 1 
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
___
<!-- OL -->
`INPUT: OL`
```
1. Item 1
1. Item 2
1. Item 3
    1. Nested item 1
    1. Nested item 2
```
`OUTPUT: `
1. Item 1
1. Item 2
1. Item 3
    1. Nested item 1
    1. Nested item 2
---
<!-- Inline Code Block -->

`INPUT: Inline code block`
```
`<p>This is a paragraph</p>`
```

`OUTPUT: `
`<p>This is a paragraph</p>`

---
<!-- Images -->
`INPUT: Images`
```
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```
`OUTPUT: `
![Markdown Logo](https://markdown-here.com/img/icon256.png)

___
<!-- Github Markdown -->

<!-- Code Blocks -->
`INPUT: Code Blocks`
```
    ```bash
        npm install

        npm start
    ```
    ```javascript
        function add(num1, num2){
            return num1 + num2;
        }
    ```
    ```python
        def add(num1, num2) {
            return num1 + num2
        }
    ```
```

`OUTPUT: `
```bash
        npm install

        npm start
```
```javascript
        function add(num1, num2){
            return num1 + num2;
        }
```
```python
    def add(num1, num2) {
        return num1 + num2
    }
```
___
<!-- Tables -->
`INPUT: Tables`
```
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| John Doe | john@gmail.com |
```
`OUTPUT: `
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| John Doe | john@gmail.com |

---
<!-- Task Lists -->
`INPUT: Task Lists`

```
* [x] Task 1
* [x] Task 2
* [ ] Task 3
```

`OUTPUT: `
* [x] Task 1
* [x] Task 2
* [ ] Task 3