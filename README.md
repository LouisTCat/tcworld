Sample Markdown

# Welcome to the ReadMe for this Project

This ReadMe was authored in Markdown, specifically GitHub Flavored Markdown, which includes syntax highlighting, task lists, tables, and @mentions. (@NickyBleiel, did I miss anything?) 

Emoji are also supported in Markdown! :thumbsup:
See the [Emoji Cheat Sheet](http:http://emoji-cheat-sheet.com) for the complete list.

You can learn more about Markdown here - and you can also create a link automatically like this - https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf 

## More about Markdown

First, the simple stuff: *This is Italic* **This is Bold**

You can also create unordered lists:

* Item 1
* Item 2
* Item 3
* Item 4
* Item 4b
* Item 5
* Item 6

And also ordered lists (of course): 
 
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

## Task Lists

Can be handy to keep track of things to do:

- [x] Task one is done
- [x] Task two is done
- [x] Task three is done
- [ ] This task is not yet done

## Code Blocks

Are easy; just open and close with three backticks.

```javascript
var first
    var name
    first = name = prompt("Enter new name, or OK to end")
    while (name != "" && name != null) {
    	if (name < first)
		first = name
    	name = prompt("Enter new name, or OK to end")
    }
    document.write("

 First name alphabetically = " + first)
