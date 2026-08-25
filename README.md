# MarkdownNote
Some notes about how to use markdown syntax.

[Official Website](https://www.markdownguide.org/basic-syntax/) 
[Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

**Backslash** \\: Escape Character.  
To show the reserved character up under the markdown mode.  
**Two Space and Enter**: Newline without an empty line.  
**Two Enter**: Newline with am empty line.

---
#### Navigator
<table>
   <tr>
      <td> [Tables](#Tables)</td>
      <td>[Size](#Size)</td>
      <td>[Font](#Font)</td>
   </tr>
   <tr>
      <td>[Format](#Format)</td>
      <td>[List](#List)</td>
      <td>[Code](#Code-Block)</td>
   </tr>
   <tr>
      <td>[Hyperlink](#Hyperlink)</td>
      <td>[Top](#MarkdownNote)</td>
      <td>[Bottom](Hyperlink)</td>
   </tr>
</table>

---
#### Tables
- Use **three or more hyphens (\---)** to distinct header and content.
- Use **pipes (|)** to seperate each column.
- Alignment inside the table
   - Align to the left :text
   - Align to the right :text:
   - Align to the middle text:
 
---
#### Size
- Heading \# (6 levels: smaller level, bigger size)

---
#### Font
1. *Italic* \*
2. **Bold** \**
3. ==Highlight== \==
4. ~Strikethrough~ \~ or \~~
5. Subscript (HTML) \<sub>T\</sub>
  H<sub>2</sub>O
7. Superscript X^2^ \^T\^

---
#### Format
1. Blockquote \>
> blockquote
2. Horizontal Rule \--- or \***

---
#### List
1. Numerical
  1. A
  2. B
  3. C
2. \-
   - D
   - E
   - F
3. Task List \- \[ \] 
   - [x] Add x between [] to select a checkbox.
   - [ ] Need space between brackets.

---
#### Code Block 
1. One line code \`  
`print("Hello World")`  
2. Multiple lines codes \``` or \~~~  
```python for loop
for i in range(3):
   print("This is line ", i)
```

---
#### Hyperlink
1. Link \[title](link)
[My GitHub Profile](https://github.com/shantinghsu)
2. Image \!\[alt text](image.jpg)
   > Have to upload the file first. Otherwise, should be a web image.
   [My favorite actress: Zhao Lusi](ZhaoLusi.jpg)
3. URLs and Email Addresses \<link or email address>
<https://github.com/shantinghsu>  
<shantinghsu0409@gmail.com>
4. Navigate to a Heading \[Name](#heading-ids)  
[Go back to the top](#MarkdownNote)
