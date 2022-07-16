---
id: o39p08y92teu1zgx1y4lx47
title: HTML
desc: ''
updated: 1657963976398
created: 1657957133184
---
# Main Points 
---
- Tags
    - Empty tags (self closing tags)
    
    It is denoted by not having a closing tag. or can be used as `<hr /> or <input />`  tags
    - Atrributes 
    
            Are the way to pass extra inforation to the browser that chages the way browser interpret the tag. 
            <input type="checkbbox" />

        ***Check the table section . where `<th scope="col">` is used to define the scope***
- Comments 

        `<!-- This is a comment -->`
            
- Whitespace 

    White spaces will be ignored. 

---

# A genric HTML File

```
1. <! DOCTYPE html>
2. <html>
3. <head>
4.<body>
```
---
# Semantic HTML - Element Grouping 
|Tag|Definitions|
|--|
|`<article>`|Self contained, independently distributable |
|`<section>`| is similar to article, - Thematic grouping of content. BUT NOT independently distributable
|`<header>`| Introductory content
|`<main>`| This contains the main content. ONLY ONE PER PAGE
|`<nav>`| Section of links 
|`< a side>`|INDirectly related NON vital content
|`<footer>`| Footer of document- like copy right 
---

# Essential Tags 
-   `<pre>` - Used for preformated text.
- `<br />` - Used for line breaks.
- `<emp> this is emphesised </emp>`

---
# Tables 
```html
    <table>
        <tr>
            <th scope="col"> Subheading </th>
            <th>First heading</th>
            <th>Second heading</th>
        </tr>
        <tr>
            <th> sub heading for row </th>
            <td>first column</td>
            <td> second column</td>
        </tr>
        <tr>
            <th> sub heading for row </th>
            <td> send row first column</td>
            <td> send row second column</td>
        </tr>
    </table>
```
---

# Forms

<form> 
    <label for ="username">User Name </label>
    <input id ="username" type ="text" />
</form>


```html
<form> 
    <label>User Name </label>
    <input type ="text" />
</form>

```