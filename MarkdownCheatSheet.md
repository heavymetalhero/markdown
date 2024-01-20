# Markdown Cheat Sheet

This cheat sheet will demonstrate Markdown code followed by it's output.

## Contents
1. [Headings](#headings)
8. [Horizontal Rules](#horizontal-rules)
2. [Emphisis](#emphisis)
3. [Blockquotes](#blockquote)
4. [Lists](#lists)
    1. [Ordered List](#ordered-list)
    2. [Unordered List](#unoredered-list)
5. [Images](#images)
6. [Code Blocks](#code-blocks)
7. [Code](#code)
9. [Links](#links)

## Headings
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Horizontal Rules
```
 *** 
 ---
```
 *** 
 ---

## Emphisis
```
*italic*
**bold**
***bold and italic***
```
*italic*  
**bold**  
***bold and italic***

## Blockquote
```
> A man should always consider how much he has more than he wants.  
--Joseph Addison
```
> A man should always consider how much he has more than he wants.  
--Joseph Addison

## Lists
### Ordered List
The list should start with one but the order doesn't matter. Makes rearranging very easy.
```
1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
```
1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item

### Unoredered List
Unordered lists can start with a -, *, or +. Just be consistant.
```
- First item
- Second item
- Third item
    - First nested item
    - Second nested item
```
- First item
- Second item
- Third item
    - First nested item
    - Second nested item

### Images
```
You have never seen me before. This is what I look like.
![Picture of me](f857ba64b4dda6d7.png)
```
You have never seen me before. This is what I look like.  
![Picture of me](f857ba64b4dda6d7.png)

### Code
```
To update your repositories type `sudo apt update` and press Enter.
```
To update your repositories type `sudo apt update` and press Enter.

### Code Blocks
Surround your code with \`\`\`. Type your codes language right after the the beginning \`\`\`  to get proper highlighting.  
Input  
```
    ```python
    text = "Hello World!"
    print(text)
    ```
```

Output
```python
text = "Hello World!"
print(text)
```

## Links
```
My blog is [heavymetalhero.net](https://heavymetalhero.net).
```
My blog is [heavymetalhero.net](https://heavymetalhero.net).

You can also make a URl or email address into a link by enclosing it in angled brackets.  

```
<https://heavymetalhero.net>  
<notmyreal@emai.com>
```

<https://heavymetalhero.net>  
<notmyreal@emai.com>
